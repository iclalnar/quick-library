# 🚀 Quick-library – MVP (Minimum Viable Product) Planı

## 📌 MVP Nedir?

**MVP (Minimum Viable Product)**, bir ürünün pazara sunulabilecek en temel ve işlevsel versiyonudur. Amaç, temel işlevselliği hızlıca geliştirip kullanıcı geri bildirimi alarak ürünü aşamalı olarak büyütmektir.

---

## 🧩 1. Temel Özellikler (MVP Kapsamı)

| Özellik | Durum |
|--------|-------|
| ✅ Kullanıcı kayıt/giriş sistemi (nickname + şifre) | Dahil |
| ✅ Ruh hali seçimi | Dahil |
| ✅ İçerik paylaşımı (söz, kitap, film) | Dahil |
| ✅ AI'dan içerik önerisi alma | Dahil |
| ✅ İçerik listeleme / filtreleme (ruh hali ve etiket bazlı) | Dahil |
| ✅ İçeriği beğenme / yorum yapma | Dahil |
| ❌ Kulüp oluşturma / etkinlik düzenleme | *MVP dışı* |
| ❌ Sosyal medya ile giriş | *MVP dışı* |
| ❌ Bildirim sistemi | *MVP dışı* |
| ❌ İçerik moderasyon paneli | *Kısıtlı (manuel yapılabilir)* |

---

## ⚙️ 2. Teknik Yapı (MVP)

| Katman | Teknoloji | Açıklama |
|--------|-----------|----------|
| **Frontend** | React.js | Responsive kullanıcı arayüzü |
| **Backend** | Node.js + Express.js | REST API, kullanıcı, içerik, AI |
| **Veritabanı** | MongoDB | Kullanıcı, içerik, etkileşim verileri |
| **Yapay Zeka** | OpenAI GPT-4 API | Öneri üretimi |
| **Kimlik Doğrulama** | JWT | Token tabanlı oturum |
| **Dağıtım** | Vercel (Frontend), Railway/Render (Backend) | MVP aşaması için bulut tabanlı dağıtım |

---

## 🔄 3. MVP Kullanıcı Akışı

1. Kullanıcı kayıt olur veya giriş yapar.
2. Ruh halini seçer.
3. Ana sayfada önerileri ve içerikleri görür.
4. Yapay zekadan içerik önerisi alır.
5. Kendisi de içerik paylaşabilir.
6. Diğer içeriklere beğeni ve yorum ekleyebilir.

---

## 📦 4. Sprint Planı (MVP İçin)

| Sprint | Kapsam | Tahmini Süre |
|--------|--------|--------------|
| **Sprint 1** | Kullanıcı kayıt/giriş sistemi + profil yapısı | 1 hafta |
| **Sprint 2** | İçerik paylaşımı ve görüntüleme modülü | 1 hafta |
| **Sprint 3** | AI öneri motoru entegrasyonu | 1 hafta |
| **Sprint 4** | Etkileşim (beğeni, yorum) + test & bug fix | 1 hafta |

> **Toplam süre:** 4 hafta

---

## 🎯 5. MVP Başarı Kriterleri

- ✅ En az 10 farklı kullanıcıdan içerik paylaşımı alınması
- ✅ AI önerilerinin %50'sinin kullanıcı tarafından paylaşılabilir bulunması
- ✅ İçerik etkileşimi (beğeni, yorum) oranının %20'den yüksek olması
- ✅ İlk kullanıcı geri bildirimlerine göre V2 için analiz yapılması

---

## 📎 Ekstra Not

MVP aşaması tamamlandığında şu geliştirmeler planlanabilir:
- Kulüp sistemi
- Etkinlik modülü
- Bildirim ve hatırlatıcılar
- Sosyal medya ile giriş
- Gelişmiş moderasyon ve AI içerik analizi

