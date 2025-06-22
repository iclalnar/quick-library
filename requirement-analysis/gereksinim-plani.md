**Quick-library v1.0 - Proje Gereksinim Planı**

---

### 🔖 1. Projenin Amacı ve Hedef Kitlesi

**Amaç:**
Quick-library, kullanıcıların anonim olarak fikir ve öneri paylaşabileceği, yapay zeka destekli öneriler alabileceği ve sosyal dayanışmayla motive olabileceği bir dijital kültür paylaşım platformudur.

**Hedef Kitle:**
Gençler, öğrenciler ve motivasyon arayan bireyler. Sosyal medyanın toksik yanlarından uzak, anonim ve pozitif bir ortam isteyen kullanıcılar.

**Fark Yaratan Noktalar:**
- Anonim, isimden bağımsız paylaşım yapılması
- Yapay zeka ile kişisel öneri motoru
- Kültürel ve duygusal paylaşım odaklı yapı

---

### 🔀 2. Temel Özellikler ve Fonksiyonlar

**İçerik Paylaşımı:**
- Motive edici söz, kitap, film, deneyim, hikaye, günün önerisi
- Metin, bağlantı veya görsel olarak paylaşım

**Yapay Zeka Öneri Motoru:**
- Kullanıcının ruh haline göre öneri verir
- Günlük motive edici mesajlar
- Paylaşım yapmaya yönlendiren destekleyici çıktılar

**Etkileşim Biçimleri:**
- Puanlama
- Fikir geliştirme ("Ben şunu da eklerdim")
- Sohbet başlatma

**Sosyal İçerik Özellikleri:**
- Anket, oylama, fikir kutusu
- Kulüp oluşturma ve yönetme
- Etkinlik planlama

**Arama ve Keşfetme:**
- Hashtag destekli arama
- Ruh hali, tür, kategoriye göre filtreleme

**Bildirimler:**
- "Bugün bir öneri paylaşmak ister misin?"
- AI tabanlı kişisel bildirimler

**Topluluk Kuralları:**
- Toksik içeriği filtreleyen otomatik sistem
- Topluluk şartlarına uygunluk kontrolleri

---

### ⚖️ 3. Teknik Gereksinimler

**Teknoloji Yığını:**
- Frontend: React.js
- Backend: Node.js + Express.js
- Veritabanı: MongoDB

**Sunucu & Dağıtım:**
- Test ortamı: Vercel / Netlify / Railway
- Canlı ortam: Bulut sunucu + lokal MongoDB (DigitalOcean / AWS / Hetzner)

**Giriş Sistemi:**
- Email-şifre veya nickname-şifre ile kimlik doğrulama
- JWT tabanlı oturum yönetimi

**Mobil Uyumluluk:**
- Web responsive tasarım (mobil uyumlu)
- Gelecekte mobil uygulama planlanmakta

**PWA:**
- Gerekli değil (ilk aşamada)

---

### 🤖 4. Yapay Zeka Özellikleri

**Strateji:**
- Model eğitimi yok
- Kullanılacak servisler: OpenAI / Gemini / Claude / Perplexity Labs API

**Uygulama Biçimi:**
- Ruh haline dayalı prompt oluşturma
- Prompt engineering takımı ve API kullanım katmanı
- Prompt/cevap logları, veri gizliliğiyle uyumlu şekilde yönetilir

**AI Özellikleri:**
- Günlük öneri
- Ruh haline özel öneriler
- Paylaşım yaratmaya teşvik eden cümleler

---

### 📊 5. Yönetim ve Topluluk Denetimi

**Admin Paneli:**
- İçerik denetimi (kaldırma/gizleme)
- Kullanıcı yönetimi (susturma/silme)
- Kulüp ve etkinlik kontrolü
- Rapor taleplerini görüntüleme

**Roller:**
- Admin
- Moderatör
- Kulüp Yöneticisi
- Standart Kullanıcı

**Topluluk Analitiği:**
- En aktif içerikler
- Paylaşım sıklığı ve kullanıcı davranışı
- AI öneri dönüş oranları

---

### ✅ Son Söz
Quick-library projesi, motivasyonel içeriği, sosyal paylaşımı ve yapay zeka desteğini modern ve etik bir yaklaşımla birleştirerek özgün bir deneyim sunmayı amaçlamaktadır. Bu belge, geliştirme sürecinde bir yol haritası olarak kullanılmak üzere hazırlanmıştır.

