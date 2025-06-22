# 🔁 Quick-library – Karma Sequence Diagram: AI'dan Öneri Al + İçerik Paylaş

## 🎯 Senaryo Açıklaması

Kullanıcı, motivasyon ihtiyacı doğrultusunda AI'dan içerik önerisi ister. AI, kullanıcının ruh hali ve içerik türü seçimine göre öneride bulunur. Kullanıcı, bu öneriyi sistem üzerinden düzenleyip doğrudan paylaşır.

**Akışın Adımları:**
1. Kullanıcı AI öneri modülünü açar.
2. Ruh halini ve içerik türünü seçer.
3. Sistem bu bilgilere göre bir prompt oluşturur.
4. Prompt AI API’sine gönderilir.
5. AI yanıtı alınır ve kullanıcıya gösterilir.
6. Kullanıcı bu öneriyi içerik paylaşım modülüne aktarır.
7. Kullanıcı içerik metni üzerinde düzenleme yapar.
8. İçerik veritabanına kaydedilir ve ana akışta yayınlanır.

---

## 📐 Sequence Diagram (Mermaid Formatı)

```mermaid
sequenceDiagram
    participant User
    participant UI
    participant AIController
    participant AIService
    participant ContentService
    participant Database

    User ->> UI: AI öneri modülünü aç
    UI ->> User: Ruh hali + içerik türü seçimi
    UI ->> AIController: createPrompt(mood, type)
    AIController ->> AIService: sendPrompt(prompt)
    AIService ->> AI API: POST /generate
    AI API -->> AIService: response (öneri)
    AIService -->> AIController: öneri metni
    AIController -->> UI: öneriyi göster

    User ->> UI: "Paylaş" butonuna tıkla
    UI ->> ContentService: prepareContent(öneri)
    ContentService ->> Database: save(content)
    Database -->> ContentService: OK
    ContentService -->> UI: Paylaşım başarılı
    UI -->> User: İçerik yayınlandı 🎉
