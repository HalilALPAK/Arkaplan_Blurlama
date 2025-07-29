# ARKPLANA BLUR VE GÖRSEL EKLEME

Bu proje, bilgisayar kamerasından alınan görüntüde arka planı bulanıklaştırma veya bir görselle değiştirme işlemini gerçekleştirir. Python, OpenCV ve MediaPipe kullanılarak geliştirilmiştir.

## Özellikler

- Gerçek zamanlı arka plan bulanıklaştırma
- Arka planı seçilen bir görselle değiştirme
- Kolay kullanım ve hızlı sonuç

## Kurulum

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install opencv-python mediapipe numpy
   ```
2. `blur.ipynb` dosyasını açın ve çalıştırın.

## Kullanım

- Arka planı bulanıklaştırmak için:
  ```python
  live_background_replace(mode=0)
  ```
- Arka planı bir görselle değiştirmek için:
  ```python
  live_background_replace(mode=1, background_path="as.jpeg")
  ```

## Ekran Görüntüsü

Aşağıda uygulamanın çalışırken alınmış bir ekran görüntüsü örneği bulunmaktadır:

<img width="649" height="512" alt="Ekran1" src="https://github.com/user-attachments/assets/088761e0-6f99-42d5-bea8-3f508ebbaf96" />
<img width="642" height="512" alt="Ekran2" src="https://github.com/user-attachments/assets/8ce19ddf-328e-45a8-9796-02a0e6184aaa" />

## Çıkış

Uygulamadan çıkmak için `q` tuşuna basabilirsiniz.
