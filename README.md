# Turkish-sign-language-translator-extension

Kameradan Türk İşaret Dili hareketlerini algılayıp çeviren proje. Chrome extension ile tarayıcıda gösteriyor.

## Nasıl çalışıyor

Webcam görüntüsü Roboflow modeline gönderiliyor, tanınan işaret tarayıcıda gösteriliyor.

## Kurulum

```bash
pip install -r requirements.txt
python serve_inference.py
```

Sonra `extension/` klasörünü Chrome'e yükle (geliştirici modu açık olmalı).

Roboflow API anahtarı için `.env` dosyası oluştur.
