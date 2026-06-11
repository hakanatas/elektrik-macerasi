# ⚡ Elektrik Macerası — Volta Şehri'ni Aydınlat

6. Sınıf Fen Bilimleri • Ünite 6: **Elektriğin İletimi ve Direnç** için oyunlaştırılmış,
MakeyMakey destekli ders paketi. ("Kraliçeyi Kurtarmak" tarzı macera-harita yapısında.)

## Kullanım

- **`index.html`** dosyasını çift tıklayıp tarayıcıda açın — kurulum gerektirmez, çevrim dışı çalışır.
- GitHub Pages'te yayınlamak için klasörü olduğu gibi bir depoya yükleyin.

## Yapı

| Dosya | İçerik |
|---|---|
| `index.html` | Tek sayfalık macera uygulaması: giriş → Volta Şehri haritası → 5 istasyon → sertifika |
| `calisma-kagitlari/ck1-…3.html` | Yazdırılabilir 3 çalışma kağıdı (cevap anahtarlı) |
| `ogretmen/ders-plani.html` | 8 ders saatlik 5E planı (Fen × BT işbirliği) |
| `ogretmen/makey-makey.html` | 3 MakeyMakey görev kartı, Scratch tarifleri, rubrik, sorun giderme |
| `css/print.css` | Yazdırılabilir sayfaların ortak stili |

## İstasyonlar ve tamamlama koşulları

1. 🏹 **İletken Avı** — 60 sn'de sınıflandırma; ≥120 puan
2. 🔬 **Devre Laboratuvarı** — 12 maddenin tamamını test et
3. 🧲 **Direnç Laboratuvarı** — 3 mühendislik görevi
4. 🎚️ **Reosta Vadisi** — simülasyon + 3/3 soru
5. 🏆 **Büyük Yarışma** — 16 soruluk buzzer yarışması (tek kişide ≥160 puan)

Her istasyon şehre %20 enerji kazandırır; %100'de sertifika ekranı açılır.
İlerleme tarayıcıda (localStorage) saklanır. Haritadaki **"Öğretmen modu"**
bağlantısı tüm istasyonların kilidini açar (sınıfta istenen istasyona atlamak için).

## MakeyMakey tuş eşleşmeleri

- **İletken Avı:** ◀ = İletken, ▶ = Yalıtkan
- **Büyük Yarışma buzzer'ları:** Takım 1 = ◀, Takım 2 = ▶, Takım 3 = ▲, Takım 4 = ▼

Aynı tuşlar klavyeden de çalışır; MakeyMakey yoksa hiçbir şey kaybolmaz.
