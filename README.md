# 💸 AI Influencer Otopilotu (v2026)
## "Görünmez İmparatorluk Kurucusu"

> **"Sen bir içerik üreticisi değilsin. Sen bir MEDYA PATRONUSUN."**

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6D5A?style=for-the-badge&logo=n8n)
![OpenAI](https://img.shields.io/badge/Beyin-GPT--4o-412991?style=for-the-badge&logo=openai)
![Durum](https://img.shields.io/badge/Durum-Production%20Ready-success?style=for-the-badge)

---

## 🚨 Bu Nedir?

Bu **SADECE** bir n8n iş akışı değildir. Bu, tek bir JSON dosyasına sıkıştırılmış **tam otonom bir medya şirketidir.**

Çoğu "otomasyon gurusu" size metin kopyalayıp yapıştıran basit botlar satar. **Bu sistem farklıdır.** Instagram Algoritmasını **Tersine Mühendislik** ile çözmek için tasarlanmıştır. Viral videoları izler, neden viral olduklarını anlar (Görsel + Ses + Bağlam) ve bunları sizin **Sanal AI Influencer'ınız** (Aitana veya Lil Miquela gibi) için yeniden yazar.

### 💀 Felsefe
Sosyal medya bir dikkat savaşıdır. Verileri milisaniyeler içinde işleyen algoritmalara karşı savaşıyorsunuz.
*   **Eski Yol:** "İlham" gelmesini beklemek ve tükenmek.
*   **Yeni Yol:** Bu sistemi kullanarak "Doğrulanmış Viral Verileri" madenlemek ve bunu haksız bir rekabet avantajına dönüştürmek.

---

## ⚡ Temel Özellikler

### 1. 👁️ Hibrit Vizyon Mantığı ("Göz")
Sadece metni okuyan basit kazıyıcıların aksine, bu sistem **Görsel Bağlamı** analiz eder.
*   **Girdi:** Kapak Resmi (Thumbnail) + Açıklama + Transkript.
*   **Süreç:** GPT-4o sahneyi analiz eder (örneğin, "Spor salonu ortamı", "Araba vlogu").
*   **Çıktı:** *Bağlam farkındalığına sahip* oyunculuk notlarıyla başlayan bir senaryo (örneğin, `[Alnındaki teri siler] "Arkadaşlar, bacak günü fena geçti..."`).

### 2. 🛡️ Kırılmaz Mimari ("Kalkan")
*   **Yeniden Deneme Mantığı (Retry Logic):** Bir API başarısız olursa sistem çökmez. Bekler ve 3 kez yeniden dener.
*   **Girdi Korkulukları:** Eksik açıklamaları veya bozuk görselleri döngüyü bozmadan zarifçe yönetir.
*   **Toplu İşleme:** Maksimum verimlilik için videoları 5'li partiler halinde işler.

### 3. 🧠 Kişilik Enjeksiyonu ("Ruh")
Sadece özetlemez. **Oyunculuk Yönetimi** yapar.
*   "Üçüncü Şahıs" anlatımlarını **"Birinci Şahıs" (POV)** influencer deneyimlerine dönüştürür.
*   Duygusal ipuçları ekler: `[Güler]`, `[İç çeker]`, `[Ekrana işaret eder]`.

---

## 🛠️ Kurulum & Ayarlar

### Gereksinimler
*   [n8n](https://n8n.io/) (Kendi sunucunuzda veya Bulutta)
*   **Apify Hesabı** (Instagram Kazıyıcı için)
*   **OpenAI API Anahtarı** (GPT-4o erişimi için)
*   **Google Hesabı** (Sheets & Gmail için)

### Adım 1: Canavarı İçe Aktar
1.  Bu repodan `n8n.json` dosyasını indirin.
2.  n8n panelinizi açın.
3.  **"Import from File"** (Dosyadan İçe Aktar) seçeneğine tıklayın ve `n8n.json` dosyasını seçin.

### Adım 2: Kimlik Bilgilerini Yapılandırın
n8n içinde aşağıdaki kimlik bilgilerini (Credentials) ayarlamanız gerekir:
*   `Apify API Key` -> **Scrape Hashtag** & **Transcribe Video** düğümleri için.
*   `OpenAI API` -> **AI Agent** düğümü için.
*   `Google Sheets OAuth2` -> Veritabanı kaydı için.
*   `Gmail OAuth2` (Opsiyonel) -> Günlük raporlar için.

### Adım 3: "Altın Madeni"ni Hazırla (Google Sheet)
Yeni bir Google Sheet oluşturun ve 1. Satıra aşağıdaki başlıkları ekleyin:
| A | B | C | D | E | F | G | H |
|---|---|---|---|---|---|---|---|
| **url** | **caption** | **thumbnail** | **Transcript** | **AI Generated Inspired Script** | **likesCount** | **ownerUsername** | **timestamp** |

*(Not: Sistem verileri otomatik olarak bu sütunlara eşleyecektir.)*

---

## 🚀 Kullanım

1.  İş akışını açın.
2.  **"Test Workflow"** (veya üretim için "Active") butonuna tıklayın.
3.  **Form Girişi:** Bir hashtag (örneğin, `#yapayzeka`) ve analiz edilecek reel sayısını (örneğin, `20`) girin.
4.  **Arkana Yaslan:** Sistemin verileri madenlemesini, analiz etmesini ve Google Sheet dosyanızı çekime hazır senaryolarla doldurmasını izleyin.

---

## 📂 Proje Yapısı

```
.
├── n8n.json       # Çekirdek Motor (Bunu içe aktarın!)
└── README.md      # Şu an bunu okuyorsunuz.
```

---

## ⚠️ Yasal Uyarı

**Bu araç önemli bir rekabet avantajı sağlar.**
*   Sorumlu kullanın.
*   Spam yapmayın.
*   Platformların Hizmet Koşullarına saygı gösterin.

**Piyasa adil değil. Ama artık şans sizden yana.**

---

**Geliştirici:**
### 👻 XCodeWraith DEV.
*Dijital Mimar | Sistem Kurucu*
