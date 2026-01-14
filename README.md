# BlazeOS.com.tr
# 🔥 BlazeOS

**BlazeOS**, performans, sadelik ve kontrolü merkeze alan, Debian tabanlı bir Linux dağıtımıdır.  
Gereksiz şişkinlik yok, kullanıcıyı aptal yerine koyan varsayılanlar yok.

> Hedef: Hızlı, kararlı ve geliştirici dostu bir sistem.

🌐 Resmi Kurulum Sayfası:  
👉 https://github.com/DarkMorpheus-pc/BlazeOS.com.tr

---

## 🚀 Özellikler

- ⚡ Hafif ve hızlı masaüstü ortamı
- 🧠 Gereksiz servisler ve bloatware **yok**
- 🛠 Geliştiriciler için optimize edilmiş yapı
- 🔒 Güvenlik ve kararlılık öncelikli
- 🎯 Günlük kullanım + ileri seviye kullanıcılar için uygun

---

## 📦 Sistem Gereksinimleri

**Minimum**
- 1 GB RAM
- 1 çekirdekli işlemci
- 20 GB disk alanı HDD  veya SD

**Önerilen**
- 3 GB RAM ve üzeri
- SSD
- UEFI destekli sistem

---

## 💿 Kurulum

### 1️⃣ ISO Dosyasını İndir
ISO dosyasını **resmi GitHub Pages kurulum sayfasından** indir:

👉 https://github.com/DarkMorpheus-pc/BlazeOS.com.tr

> ⚠️ ISO dosyasını üçüncü parti sitelerden indirme. Güvenlik senin sorumluluğun.

---

### 2️⃣ Boot Edilebilir USB Oluştur

Önerilen araçlar:
- **Ventoy** (şiddetle tavsiye edilir)
- Rufus
- Balena Etcher

ISO’yu USB’ye yaz ve sistemi USB’den başlat.

---

### 3️⃣ Kurulum

- “Install BlazeOS” seçeneğini seç
- Disk bölümleme ekranında dikkatli ol  
  (Yanlış disk → veriler **uçtu**, geri dönüş yok)
- Kurulumu tamamla ve sistemi yeniden başlat

---

## 🧩 Masaüstü Ortamı

BlazeOS varsayılan olarak **hafif ve performans odaklı** bir masaüstüyle gelir.  
Alternatif masaüstü ortamları daha sonra yüklenebilir.

---

## 🔄 Güncelleme

```bash
sudo apt update && sudo apt upgrade

