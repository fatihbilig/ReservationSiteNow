# 🏨 OTEL REZERVASYON SİSTEMİ

Bu proje, staj süresi boyunca yazılım geliştirme adımları takip edilerek uygulamalı bir şekilde öğrenmeyi amaçlamaktadır.
Otellerin online rezervasyon yapabilmesini, kullanıcıların oda seçimi, müsaitlik kontrolü ve ödeme simülasyonu yapabildiği web tabanlı bir sistemdir.
Kullanıcı dostu bir arayüze sahip olarak temel rezervasyon ihtiyaçlarının kolaylıkla karşılanabileceği bir sistem olmayı hedefler.

---

## ⚙️ Kullanılacak Teknolojiler

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **Veri Tabanı:** PostgreSQL

---

## 👥 Kullanıcı Rolleri ve Senaryoları

### 1️⃣ Müşteri
- Siteye kayıt olur / giriş yapar.
- Belirli kriterlere göre (tarih, kişi sayısı) oda araması yapar, müsait odaları görüntüler.
- Oda rezervasyonu yapar ve ödeme simülasyonu yapar.

### 2️⃣ Otel Yöneticisi
- Sisteme giriş yapar.
- Oda ekler, siler, düzenler.
- Müsaitlik durumunu kontrol eder.
- Fiyat düzenlemesi yapar.
- Rezervasyonları görüntüler.

### 3️⃣ Admin
- Genel sistemi yönetir, denetler.

---

## 📊 Use Case Diyagram

_Burada diyagram görseli yer alacak._

---

## ✅ İşlevsel Gereksinimler

- Kullanıcı kayıt olabilir ve sisteme giriş yapabilir.
- Kullanıcı, tarih ve kişi sayısına göre oda araması yapabilir.
- Kullanıcı, oda araması sonucunda müsait odaları görüntüleyebilir.
- Kullanıcı, oda rezervasyonu yapabilir ve ödeme simülasyonu yapabilir.
- Yönetici, oda ekleyebilir, silebilir, düzenleyebilir, fiyat güncellemesi yapabilir.
- Yönetici, rezervasyonları görüntüleyebilir.
- Admin, sistemi yönetebilir ve denetleyebilir.

---

## 🚫 İşlevsel Olmayan Gereksinimler

- Sistem responsive tasarıma sahip olmalıdır.
- Kullanıcı bilgileri güvenli bir şekilde saklanmalıdır.
- Arayüz, kullanıcı dostu ve sade olmalıdır.
- Gerçek ödeme entegrasyonu değil, simülasyon yapılmalıdır.
- Sadece web üzerinde kullanılmalıdır.
- Node.js ve PostgreSQL ile geliştirilmelidir.

---

## 🔍 SWOT ANALİZİ

| Güçlü Yönler (Strengths) | Zayıf Yönler (Weaknesses) |
|--------------------------|---------------------------|
| Modern web teknolojileri kullanıldı. | Gerçek ödeme sistemi yoktur. |
| Basit ve kullanıcı dostu arayüze sahiptir. | Yalnızca tek bir otel yönetilebiliyor. |

| Fırsatlar (Opportunities) | Tehditler (Threats) |
|---------------------------|---------------------|
| Gerçek projeye dönüşebilir. | Güvenlik açıkları olabilir. |
| Mobil uygulama olarak genişletilebilir. | Artan teknik borç ve bakım maliyeti artabilir. |

---

## 🗂️ Veri Tabanı Tasarımı

Tablolar ve Temel Alanlar:

_(Buraya ER Diyagramı veya tablo yapısı eklenebilir)_

---

## 📝 Lisans

Bu proje staj sürecinde eğitim amaçlı hazırlanmıştır.
