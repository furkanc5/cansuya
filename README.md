# Cansu'ya ✨

Tek sayfalık, kişisel bir zaman akışı ve anı sunumu.

## Çalıştırma

`index.html` dosyasını modern bir tarayıcıda açın. Ses ve medya dosyaları göreli yollarla `assets/` klasöründen yüklenir. Tarayıcı yerel dosyalarda medya kısıtı çıkarırsa klasörü basit bir statik sunucuyla çalıştırın.

## Proje Yapısı

- `index.html`: Uygulamanın tüm arayüz, animasyon ve akış mantığı.
- `assets/images/`: Güzellik seviyelerinde sırayla gösterilen `1.png`-`5.png`.
- `assets/videos/`: Reels oynatıcısında sırayla kullanılan 6 video.
- `assets/audio/`: Oynat düğmesiyle düşük sesten başlayıp yükselen `olur-ya.mp3`.
- `docs/versions/`: Git sürümlerinin ve geliştirme aşamalarının raporları.

## Kullanım Akışı

1. Fotoğraflar yüklenene kadar `Oynat` düğmesi pasif kalır.
2. Oynat düğmesi grafik akışını ve `olur-ya.mp3` müziğini başlatır.
3. Grafik tamamlanınca kenar turu başlar; çizgi hızlanır, kalınlaşır ve ekran pembeye döner.
4. Final mesajları sırayla görünür.
5. Reels ekranında videolar sessiz oynatılır; tüm videolar görüntülendikten sonra playlist geçişi açılır.
6. Playlist ekranındaki bağlantı Spotify'a yönlendirir.

## Sürüm Raporları

Ayrıntılı tarihçe için [`docs/versions`](docs/versions) klasörüne bakın.
