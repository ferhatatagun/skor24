# SKOR24

24 aylık kredi skoru simülasyon oyunu — eğitim amaçlı, tek dosyalık bir web deneyimi.

**[🎮 Oyunu oyna → ferhatatagun.github.io/skor24](https://ferhatatagun.github.io/skor24/)**

Yazan: [Ferhat Atagün](https://ferhatatagun.com)

Oyuncu her ay bir finansal karar verir (ekstre ödemesi, kredi başvurusu, limit artışı, kefillik vb.) ve bu kararlar FICO'nun kamuya açık faktör ağırlıklarına (ödeme geçmişi %35, kullanım oranı %30, kredi geçmişi uzunluğu %15, yeni sorgular %10, kredi çeşitliliği %10) göre skoru etkiler. Skor, Türkiye'deki Findeks/KKB ölçeğine (0–1900) eşlenir.

Oyun kasıtlı olarak yalnızca **kredibiliteyi iyileştirmeyi** oyunlaştırır; borçlanmayı veya kredi kullanımını teşvik eden hiçbir mekanik içermez.

## Çalıştırma

Bağımlılık yok — tek `index.html` dosyası, saf HTML/CSS/JS.

```bash
python3 -m http.server 8000
```

sonra `http://localhost:8000/index.html` adresini açın.

## Kapsam dışı

Bu bir finansal danışmanlık aracı değildir. Gerçek KKB/Findeks skor hesaplama mantığını birebir yansıtmaz; skor faktör ağırlıkları eğitim amaçlı basitleştirilmiştir.
