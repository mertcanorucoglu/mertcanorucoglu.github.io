# Mert Can Oruçoğlu — Kişisel Web Sitesi

Tek sayfalık, mobil uyumlu kişisel portföy sitesi. HTML, CSS ve vanilla JavaScript kullanır; Node, paket yöneticisi veya derleme adımı gerektirmez.

## İçerik

- Hakkımda ve profesyonel profil özeti
- Halbuqi Trend — Genel Müdür (Nisan 2022 – Eylül 2025)
- Asset Global Logistic Integration — İhracat Müşteri İlişkileri (Nisan 2021 – Nisan 2022)
- İstanbul Arel Üniversitesi — Dış Ticaret (LinkedIn eğitim kaydında 2018–2020)
- Facebook, Instagram, YouTube ve iki ayrı LinkedIn profil bağlantısı

Eğitim tarihi, sağlanan LinkedIn eğitim kaydındaki 2018–2020 aralığına göre gösterilmiştir. Facebook Hakkında alanında eğitim başlangıcı 2018 ve durum “Halen” olarak yer aldığından, iki kayıtta görünen tarih farklılığı ayrıca doğrulanabilir.

## GitHub Pages'te yayınlama

1. GitHub'da `mertcanorucoglu/mertcanorucoglu.github.io` deposunu aç.
2. ZIP içeriğini (ZIP dosyasının kendisini değil) deponun kök dizinine yükle. `index.html` kökte olmalı.
3. Değişiklikleri `main` dalına commit et.
4. Repository → **Settings → Pages** bölümünü aç.
5. **Build and deployment → Source** altında `Deploy from a branch` seç.
6. Branch olarak `main`, klasör olarak `/(root)` seçip **Save**'e bas.
7. Yayınlandıktan sonra site: <https://mertcanorucoglu.github.io/>

## Profil fotoğrafı

Site, erişilebilen GitHub avatarını `https://avatars.githubusercontent.com/u/350177168?v=4` adresinden gösterir. Fotoğraf erişilemezse “MC” yedek görseli görünür. Sağlanan LinkedIn içeriklerinde şirket ve üniversite logoları bulunuyor; kişisel profil fotoğrafı bulunmadığından bu logolar kişi fotoğrafı gibi kullanılmadı.

## Kişiselleştirme

- Metinler ve sosyal medya adresleri `index.html` içinde bulunur.
- Tema renkleri CSS'in en üstündeki `:root` bölümünden değiştirilebilir.
- Harici yazı tipi veya JavaScript kütüphanesi kullanılmaz.
- SEO için title, description, canonical, Open Graph ve `Person` yapılandırılmış verisi eklenmiştir.

## Fotoğraf ve video galerisi

- Fotoğraf galerisi, depodaki `images/` klasöründeki görselleri otomatik olmayan, doğrudan dosya yollarıyla gösterir. Yeni görsel eklerken HTML içindeki `photoNames` listesine dosya adını da eklemek gerekir.
- YouTube video galerisi 7 uzun video ve 5 Shorts bağlantısı içerir.
- Video kartları küçük resimleri YouTube görsel sunucusundan alır ve tıklanınca ilgili YouTube videosunu yeni sekmede açar.
- Fotoğraf ve video bölümleri `index.html` içinde düzenlenir.
