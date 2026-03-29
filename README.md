# 🌌 Cosmic Guide: Gerçekçi Gece Gökyüzü Simülasyonu ve Tarihe Dayalı Güneş Sistemi

Bu proje, kullanıcının gerçek zamanlı konum ve zaman verilerini kullanarak, bulundukları noktadan gökyüzünün nasıl göründüğünü simüle eden etkileşimli bir web uygulamasıdır. Sadece yıldızları göstermekle kalmaz; mitoloji, bilimsel veriler ve **Gemini AI**'ı harmanlayarak eşsiz bir keşif deneyimi sunar.

---

## ✨ Öne Çıkan Özellikler

* **Gerçek Zamanlı Astronomik Hizalama:** Geolocation API ve özel algoritmalar sayesinde yıldızlar, gezegenler ve Güneş; koordinatlarınıza ve o anki zamana göre doğru konumlandırılır.
* **Gemini AI Entegrasyonu:** Herhangi bir gök cismine tıklandığında, **Gemini 2.5 Flash** modeli üzerinden nesneye özel bilimsel açıklamalar ve derin mitolojik hikayeler anlık olarak üretilir.
* **Sesli Anlatım (TTS):** Yapay zeka tarafından oluşturulan bilgiler, entegre Text-to-Speech servisi kullanılarak sesli bir şekilde dinlenebilir.
* **Bilimkurgu Hikaye Üreticisi:** Seçilen yıldız veya gezegen temalı, edebi dili güçlü, 3 cümlelik kısa bilimkurgu hikayeleri oluşturma özelliği.
* **Dinamik Atmosfer ve Hava Durumu:** **Open-Meteo API** entegrasyonu ile bölgedeki bulutluluk ve sıcaklık verileri çekilerek gözlem şartları analiz edilir. Gerçekçi bir gündüz/gece döngüsü mevcuttur.
* **Mitolojik Takımyıldız Görselleri:** Belirli bir yakınlaştırma seviyesinden sonra Orion, Büyük Ayı, Akrep gibi takımyıldızların mitolojik figürleri silüet olarak belirir.
* **Çift Kontrol Modu:** İster fare/dokunmatik (OrbitControls) ile isterseniz mobil cihazınızın jiroskop sensörlerini kullanarak gökyüzünde özgürce gezinebilirsiniz.

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Kullanım Alanı |
| :--- | :--- |
| **Three.js** | 3D evrenin oluşturulması ve render edilmesi. |
| **Gemini AI API** | İçerik üretimi ve seslendirme servisleri. |
| **Open-Meteo API** | Canlı hava durumu ve atmosferik veriler. |
| **HTML5 & CSS3** | Modern, cam efektli (glassmorphism) ve duyarlı arayüz. |

---

## 🚀 Başlangıç

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları takip edin:

### 1. API Anahtarı Tanımlama
Uygulamanın zekasını kullanabilmek için kendi API anahtarınızı eklemelisiniz:
* `fetchGeminiAI` ve `fetchGeminiTTS` fonksiyonlarındaki `apiKey` değişkenlerine [Google AI Studio](https://aistudio.google.com/)'dan aldığınız anahtarı tanımlayın.

### 2. Çalıştırma
* Dosyayı bir yerel sunucu (örneğin VS Code **Live Server** eklentisi) üzerinden açın.
* Tarayıcının **konum** ve (mobil cihazdaysanız) **sensör/jiroskop** erişim izinlerini onaylayın.

---

## 📖 Kullanım ve Veri Seti

* **Keşfe Başla:** Simülasyonu başlatır ve anlık konumunuza göre gökyüzünü yükler.
* **Tıkla/Dokun:** Bir yıldıza veya gezegene dokunarak detaylı bilgi panelini açabilirsiniz.
* **Zoom:** Fare tekerleği ile takımyıldız çizgilerini ve figürlerini ortaya çıkarın.
* **Şeffaf Dünya:** Dünya yüzeyi yarı saydamdır, böylece "ayaklarınızın altındaki" yıldızları bile görebilirsiniz.

**Kapsam:** Uygulama; 8000'den fazla yıldız, tüm ana gezegenler ve aralarında Orion, Büyük Ayı, Kraliçe, Akrep ve Zodyak kuşağının da bulunduğu 20'den fazla takımyıldızının detaylı verisini içerir.

---

⭐ **Keyifli gözlemler!**
