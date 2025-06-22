# 📘 Quick-library – Use Case Ayrıntıları ve AI Prompt Önerileri

---

## 👤 Kullanıcı

### 🎯 Giriş Yap / Kayıt Ol

**Adımlar:**
1. Kullanıcı ana sayfaya gelir.
2. Giriş yap veya kayıt ol seçeneğini seçer.
3. Nickname + şifre veya email + şifre girer.
4. Başarılı giriş sonrası ruh hali seçimine yönlendirilir.

**AI Prompt Önerisi:**
> “Kullanıcının sisteme ilk girişinden sonra motivasyonunu artıracak, platformu keşfetmesini teşvik eden kısa bir hoş geldin mesajı üret.”

---

### 🎯 Profilini Oluştur / Güncelle

**Adımlar:**
1. Kullanıcı profil sayfasına girer.
2. Nickname ve avatar seçer.
3. (İsteğe bağlı) "Ben kimim?" alanına kendini tanıtan metin girer.
4. Değişiklikleri kaydeder.

**AI Prompt Önerisi:**
> “Kullanıcının seçeceği avatara göre kısa bir kişilik yorumu yaz ve profil tanım önerisi sun.”

---

### 🎯 Ruh Haline Göre İçerik Gör

**Adımlar:**
1. Kullanıcı ruh halini seçer (örneğin: huzursuz, yalnız, ilham arıyorum).
2. Sistem bu seçime göre içerikleri filtreler.
3. Kullanıcı ilgili içerik akışını görür.

**AI Prompt Önerisi:**
> “Kullanıcının ruh hali şu: ‘{ruh hali}’. Bu ruh haline uygun 3 farklı türde içerik önerisi (kitap, film, söz) üret.”

---

### 🎯 AI’dan Öneri Al

**Adımlar:**
1. Kullanıcı "AI önerisi al" butonuna tıklar.
2. Ruh hali + içerik türü seçer.
3. Sistem prompt’u oluşturur ve API’ye gönderir.
4. Cevap kullanıcıya sunulur.
5. Kullanıcı “paylaş”, “kaydet” veya “yeni öneri al” seçeneklerinden birini seçer.

**AI Prompt Önerisi:**
> “Kullanıcı {ruh hali} içinde. Ona {tür} kategorisinde yaratıcı ve motive edici bir öneri ver. Öneri kısa ama etkileyici olsun.”

---

### 🎯 İçerik Paylaş (Kitap, Film, Söz vb.)

**Adımlar:**
1. Kullanıcı “+ Paylaş” butonuna basar.
2. İçerik türünü seçer.
3. Başlık ve açıklamayı girer.
4. Hashtag ve ruh hali etiketi ekler.
5. (İsteğe bağlı) AI ile içerik oluşturur.
6. “Paylaş” ile gönderiyi yayınlar.

**AI Prompt Önerisi:**
> “Kullanıcının paylaşmak istediği tür: {tür}. Ona bu türde paylaşabileceği ilham verici bir metin önerisi yap.”

---

### 🎯 İçeriği Görüntüle

**Adımlar:**
1. Kullanıcı ana sayfa veya kulüpten içerik akışına ulaşır.
2. İlgi duyduğu içeriğe tıklar.
3. İçeriği detaylı görür: metin, görsel, tarih, yazar.

**AI Prompt Önerisi:**
> “Şu içeriği açıklayıcı ve etkileyici şekilde yeniden yaz: ‘{içerik}’. Hedef: daha çok etkileşim almak.”

---

### 🎯 İçeriği Puanla / Fikir Geliştir / Yorum Yap

**Adımlar:**
1. Kullanıcı içerik detayındadır.
2. Beğen, yorum, fikir geliştir gibi butonlardan birini seçer.
3. Etkileşim verisi sisteme işlenir.
4. Yorum veya ek fikir görünür hale gelir.

**AI Prompt Önerisi:**
> “Kullanıcının gördüğü içerik şu: ‘{içerik}’. Bu içeriğe olumlu, yapıcı bir fikir geliştirici yorum yaz.”

---

### 🎯 Kulübe Katıl / Kulüp Oluştur

**Adımlar:**
1. Kullanıcı kulüp listesine girer.
2. İlgisini çeken kulübe katılır veya yeni bir kulüp oluşturur.
3. Kulüp adı, açıklama, avatar, ilgi alanı girilir.
4. Kulüp yayına alınır, içerik paylaşımı başlar.

**AI Prompt Önerisi:**
> “Kullanıcının ilgi alanı: {ilgi alanı}. Ona buna uygun, samimi ve ilham verici bir kulüp adı ve açıklama öner.”

---

### 🎯 Etkinlik Oluştur / Katıl

**Adımlar:**
1. Kulüp içinden veya genel sayfadan “Etkinlik Oluştur” seçilir.
2. Etkinlik adı, tarih, açıklama girilir.
3. Etkinlik yayınlanır, diğer kullanıcılar katılabilir.
4. Hatırlatma sistemi devreye girer.

**AI Prompt Önerisi:**
> “Etkinlik konusu: {konu}. Bu etkinlik için yaratıcı ve motive edici bir başlık + açıklama öner.”

---

### 🎯 İçerik Raporla

**Adımlar:**
1. Kullanıcı içerik detayında “raporla” butonuna tıklar.
2. Rapor sebebi seçer (uygunsuz dil, spam, vs).
3. Rapor moderatöre iletilir.
4. Gerekirse sistem içeriği geçici olarak gizler.

**AI Prompt Önerisi:**
> “Şu içerik şüpheli bulunuyor: ‘{içerik}’. Bu içerik topluluk kurallarına aykırı mı? Hızlı bir ön değerlendirme yap.”

---
# ⚙️ Quick-library – Admin & Moderatör Use Case Ayrıntıları ve AI Prompt Önerileri

---

## 🛠️ Admin

### 🎯 Tüm Kullanıcıları Yönet

**Adımlar:**
1. Admin paneline giriş yapılır.
2. Kullanıcılar listelenir (arama, filtreleme imkanı ile).
3. Her kullanıcı için şu işlemler yapılabilir:
   - Profili görüntüle
   - Sustur
   - Kalıcı olarak sil
   - Yetki değiştir (moderatör yap, geri al)

**AI Prompt Önerisi:**
> “Kullanıcı profili: {nickname}, son 30 gün içindeki davranış geçmişi: {aktivite}. Bu kullanıcıyı değerlendirerek sistem içi bir öneri sun (örnek: susturmalı mı, moderatör olabilir mi?).”

---

### 🎯 Tüm İçerikleri Kaldır / Denetle

**Adımlar:**
1. Tüm içerikler listelenir (tarihe, kullanıcıya, şikayet sayısına göre sıralanabilir).
2. İçerik detayına girilir.
3. Şu işlemler yapılabilir:
   - Yayından kaldır
   - İçeriği düzenle (admin notu eklenebilir)
   - Kullanıcıyı uyar

**AI Prompt Önerisi:**
> “İçerik: ‘{içerik metni}’. Bu içerik Quick-library top

