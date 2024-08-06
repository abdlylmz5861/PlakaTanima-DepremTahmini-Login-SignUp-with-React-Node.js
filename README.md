
# Plaka Tanıma ve Deprem Tahmini Sistemi

Bu proje, plakaları tanıyan, deprem tahminleri yapan ve kullanıcı giriş/çıkış işlemlerini yöneten bir sistemdir. React, Node.js ve Python kullanılarak geliştirilmiştir.

## İçindekiler

- [Özellikler](#özellikler)
- [Gereksinimler](#gereksinimler)
- [Kurulum](#kurulum)
  - [Backend Kurulumu](#backend-kurulumu)
  - [Frontend Kurulumu](#frontend-kurulumu)
  - [Python Servis Kurulumu](#python-servis-kurulumu)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)

## Özellikler

- **Plaka Tanıma**: Görüntülerdeki plakaları tanıyarak veri tabanına kaydeder.
- **Deprem Tahmini**: Deprem verilerini analiz ederek tahminlerde bulunur.
- **Kullanıcı Giriş/Çıkış**: Kullanıcıların kayıt olmasını ve giriş yapmasını sağlar.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki yazılımlara ihtiyacınız olacak:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [MongoDB](https://www.mongodb.com/)
- [PytesseractOCR](https://github.com/UB-Mannheim/tesseract/wiki)

## Kurulum

Projeyi yerel makinenize klonladıktan sonra aşağıdaki adımları izleyerek kurabilirsiniz.

### Backend Kurulumu

1. Proje dizinine gidin ve gerekli paketleri yükleyin:

    ```sh
    cd server
    npm install
    ```

2. Server'ı başlatın:

    ```sh
    npm start
    ```

### Frontend Kurulumu

1. Proje dizinine gidin ve gerekli paketleri yükleyin:

    ```sh
    cd client
    npm install
    ```

2. Uygulamayı başlatın:

    ```sh
    npm run dev
    ```

### Python Servis Kurulumu

1. Gerekli paketleri yükleyin:

    ```sh
    pip install opencv-python-headless
    pip install numpy
    pip install scipy
    pip install pytesseract
    pip install pandas
    pip install scikit-learn
    pip install lightgbm
    pip install joblib
    ```

## Kullanım

1. **Plaka Tanıma**: Uygulamanın arayüzünden plaka tanıma özelliğini kullanarak araç plakalarını tanıyabilirsiniz.
2. **Deprem Tahmini**: Deprem tahmini bölümünden, güncel deprem verilerini analiz edip tahminlerde bulunabilirsiniz.
3. **Kullanıcı Giriş/Çıkış**: Giriş yaparak veya kayıt olarak uygulamanın kullanıcı yönetim sistemini kullanabilirsiniz.

## Proje Yapısı

```plaintext
.
├── server
│   ├── src
│   ├── package.json
│   └── ...
├── client
│   ├── src
│   ├── public
│   ├── package.json
│   └── ...
├── python_service
│   ├── main.py
│   ├── requirements.txt
│   └── ...
└── README.md
```

