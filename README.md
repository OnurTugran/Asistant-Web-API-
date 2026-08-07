# 🤖 CTF & Pentest AI Asistanı

Bu proje, siber güvenlik eğitimleri, CTF (Capture The Flag) çözümleri ve laboratuvar pratikleri için tasarlanmış özel **prompt mühendisliğine** sahip bir yapay zeka sohbet asistanıdır. Google Gemini API altyapısını kullanır ve web arayüzü Flask ile geliştirilmiştir.

## 🚀 Özellikler

* **Özel Sistem Prompt'u (Eğitim Modu):** Standart AI filtrelerini eğitim ve laboratuvar senaryoları çerçevesinde esneterek, kullanıcıya doğrudan saldırı vektörleri, komut satırı çıktıları ve zafiyet istismar teknikleri sunacak şekilde (Kıdemli Pentest Eğitmeni rolünde) yapılandırılmıştır.
* **BYOK (Bring Your Own Key) Mimarisi:** Güvenlik amacıyla API anahtarı kaynak koduna gömülmemiştir. Açık kaynak güvenliği standartlarına uygun olarak, uygulama başlatıldığında kullanıcıdan terminal üzerinden kendi Gemini API anahtarını girmesi istenir.
* **Web Arayüzü:** Flask tabanlı, kullanımı kolay, sohbet geçmişi tutabilen ve istenildiğinde tek tıkla oturumu sıfırlayabilen pratik web arayüzü.

## 🧰 Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

## ⚙️ Kurulum ve Çalıştırma

**1. Repoyu bilgisayarınıza klonlayın:**
```bash
git clone [https://github.com/OnurTugran/Asistant-Web-API-.git](https://github.com/OnurTugran/Asistant-Web-API-.git)
cd Asistant-Web-API
```

**1. Repoyu bilgisayarınıza klonlayın:**
```bash
git clone [https://github.com/OnurTugran/Asistant-Web-API-.git](https://github.com/OnurTugran/Asistant-Web-API-.git)
cd Asistant-Web-API-
```

**2. Gerekli kütüphaneleri yükleyin:**
```bash
pip install flask google-generativeai
```

**3. Uygulamayı başlatın:**
```bash
python app.py
```

**4. API Anahtarınızı yapılandırın:**
Uygulama çalıştığında terminal ekranında Gemini API anahtarınız istenecektir. Kendi anahtarınızı yapıştırıp `Enter`'a bastıktan sonra yerel sunucu aktif hale gelecektir. Tarayıcınızdan `http://127.0.0.1:5000` adresine giderek asistanı kullanmaya başlayabilirsiniz.
