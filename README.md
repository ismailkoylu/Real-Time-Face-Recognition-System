# Real-Time Face Recognition and Biometric Analysis

Bu proje, bilgisayar kamerası üzerinden alınan canlı görüntü akışında yüz tespiti ve tanıma işlemlerini gerçekleştiren yapay zeka tabanlı bir uygulamadır.

## 👁️ Temel Özellikler
- **Gerçek Zamanlı Yüz Tespiti:** Kamera akışındaki insan yüzlerini anlık olarak belirleme.
- **Yüz Tanıma (Face Recognition):** Kayıtlı yüzleri yüksek doğrulukla eşleştirme ve tanımlama.
- **API Entegrasyonu:** `face_api.py` modülü üzerinden modüler ve genişletilebilir bir tanıma yapısı.
- **Canlı Görüntü İşleme:** OpenCV kullanarak düşük gecikmeli görüntü işleme süreçleri.

## 🛠️ Teknik Altyapı
- **Dil:** Python
- **Kütüphaneler:** OpenCV (cv2), Face Recognition (dlib tabanlı), NumPy
- **Mimari:** Modüler API yapısı (`face_api.py`) ve merkezi kontrol birimi (`main.py`)

## 🚀 Kurulum
1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install opencv-python face-recognition numpy
   Uygulamayı çalıştırın:
   python main.py
