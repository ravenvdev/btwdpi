<div align="center">

# BTWDPI

**Türkiye'den Discord ve Roblox'a sorunsuz erişim.**

DPI ve DNS engellemesini yalnızca ihtiyaç duyduğun servisler için aşan, tek dosyalık, hafif bir Windows uygulaması.

`VPN yok · Proxy yok · Hesap yok · Reklam yok · Kurulum derdi yok`

</div>

---

## BTWDPI nedir?

Türkiye'de Discord ve zaman zaman Roblox'un bazı bölümleri (oyun görselleri, avatarlar, profil resimleri) **DNS zehirlenmesi** ve **DPI (Derin Paket İncelemesi)** ile engelleniyor. Bu yüzden:

- Discord hiç açılmıyor ya da "bağlanılıyor" ekranında kalıyor.
- Roblox ana sayfası açılıyor ama **oyunların ve avatarların görselleri boş/gri geliyor**.

Çoğu kişi bunun için VPN kullanıyor. Ama VPN **tüm internet trafiğini** yavaşlatır, oyunlarda ping'i yükseltir, ücretlidir ve bazen güvenlik riski taşır.

**BTWDPI farklı çalışır:** VPN kurmaz, trafiğini başka bir sunucuya yönlendirmez. Sadece Discord/Roblox'a giden paketleri, engellemeyi aşacak şekilde düzenleyip **doğrudan** gönderir. Geri kalan internet trafiğine **hiç dokunmaz** — ne yavaşlama, ne ping artışı, ne gizlilik riski.

---

## Neden BTWDPI? (Artıları)

| | BTWDPI | VPN | Diğer DPI araçları |
|---|:---:|:---:|:---:|
| Ping / hız kaybı yok | ✅ | ❌ | ⚠️ |
| Sadece Discord/Roblox'a dokunur | ✅ | ❌ | ❌ (tüm trafik) |
| Diğer siteler normal kalır | ✅ | ❌ | ❌ |
| Ücretsiz | ✅ | ⚠️ | ✅ |
| Hesap / giriş gerektirmez | ✅ | ❌ | ✅ |
| Tek dosya, kurulum yok | ✅ | ❌ | ⚠️ |
| Açılışta otomatik başlar | ✅ | ⚠️ | ⚠️ |
| Sistem tepsisinde sessiz çalışır | ✅ | ⚠️ | ❌ |

### Öne çıkan avantajlar

- **🎯 Cerrahi hassasiyet.** Yalnızca açtığın servislerin (Discord ve/veya Roblox) trafiğine müdahale eder. YouTube, Twitch, oyunların, bankan — hepsi tamamen normal, hiç dokunulmadan çalışır.
- **⚡ Sıfır hız kaybı.** VPN gibi trafiğini uzak bir sunucudan geçirmez. Paketler doğrudan Discord/Roblox sunucularına gider. Ping aynı kalır, indirme hızın düşmez.
- **🪶 Tüy gibi hafif.** Tek bir `.exe` dosyası, ~7 MB. Arka planda neredeyse hiç kaynak kullanmaz.
- **🔌 Kur-unut.** Bir kere çalıştır, açılışta otomatik başlasın diye ayarla, bir daha uğraşma. Sistem tepsisinde sessizce bekler.
- **🧩 Modüler koruma.** Discord ve Roblox için ayrı açma/kapama anahtarları. Sadece Discord istiyorsan Roblox'u kapalı tut.
- **🔒 Gizlilik.** Hiçbir veri toplamaz, hiçbir sunucuya bir şey göndermez, hesap istemez. DNS sorgularını şifreli (DoH) yapar, böylece operatörün ne sorduğunu bile göremez.

---

## Özellikler

- ✅ **Discord koruması** — discord.com, CDN, gateway, medya ve güncelleyici dahil.
- ✅ **Roblox koruması** — rbxcdn görselleri, avatarlar, oyun küçük resimleri, thumbnail'lar.
- ✅ **DoH (DNS-over-HTTPS)** — operatörün kirli DNS'ini bypass ederek gerçek sunucu adreslerini bulur.
- ✅ **Akıllı paket motoru** — yalnızca hedef trafiğe fake-TTL + paket bölme tekniği uygular.
- ✅ **Otomatik IP güncelleme** — sunucu adresleri değişirse kendini 15 dakikada bir yeniler.
- ✅ **Sistem tepsisi** — küçültünce görev çubuğundan kaybolur, tepside sessizce bekler.
- ✅ **Windows ile başlat** — açılışta otomatik, arka planda, tek tıkla aç/kapat.
- ✅ **Canlı durum paneli** — anlık trafik grafiği, bypass sayacı, çalışma süresi.
- ✅ **Modern arayüz** — koyu tema, macOS tarzı başlık çubuğu, akıcı animasyonlar.

---

## Kurulum

1. [**Releases**](../../releases) sayfasından en güncel `BTWDPI.exe` dosyasını indir.
2. İndirdiğin dosyaya **çift tıkla**.
3. Windows yönetici izni isteyecek → **Evet** de. *(Gerekli, çünkü ağ sürücüsünü yüklemesi gerekiyor.)*
4. Uygulama açılır, gerekli bileşeni kendisi indirir ve çalışmaya başlar.
5. Discord'u / Roblox'u aç — artık çalışıyor olmalı. 🎉

> Bir sonraki bilgisayar açılışında uygulama **kendiliğinden** arka planda başlar (istersen bu özelliği Ayarlar'dan kapatabilirsin).

---

## Kullanım

- **Ana ekrandaki büyük düğme** korumayı başlatır/durdurur.
- **Korumalar** kartından Discord ve Roblox'u ayrı ayrı aç/kapat.
- **Sarı küçült düğmesi** → uygulamayı sistem tepsisine alır (görev çubuğunda görünmez).
- **Tepsi simgesine tıkla** → geri getirir. **Sağ tık** → hızlı menü (Göster / Başlat-Durdur / Çıkış).
- **Ayarlar** → Windows ile başlatmayı aç/kapat, sürücüyü yönet, dosya konumlarını gör.

---

## ⚠️ Antivirüs uyarısı (önemli)

Windows Defender veya başka bir antivirüs, BTWDPI'ı **yanlışlıkla** "tehlikeli" olarak işaretleyebilir (örn. `Trojan:Win32/Bearfoos`).

**Bu bir virüs değildir — yanlış alarmdır (false positive).**

Sebebi: BTWDPI'ın engellemeyi aşmak için yaptığı işler (ağ sürücüsü yükleme, paketleri düzenleme, yönetici yetkisiyle çalışma) teknik olarak zararlı yazılımların da yaptığı işlere benzer. Antivirüs bunu ayırt edemeyip tedbir amaçlı işaretler. Aynı durum bu türden **tüm** DPI araçları (GoodbyeDPI dahil) için geçerlidir.

### Çözüm

Windows Defender'a istisna ekle:

1. **Windows Güvenliği**'ni aç.
2. **Virüs ve tehdit koruması** → **Ayarları yönet**.
3. **Dışlamalar** → **Dışlama ekle veya kaldır**.
4. **Klasör ekle** → `C:\Program Files\BTWDPI` klasörünü seç.

Bu kadar. Artık engellemez.

---

## Sıkça Sorulan Sorular

**VPN mi bu?**
Hayır. VPN trafiğini şifreleyip uzak bir sunucudan geçirir; BTWDPI trafiğini hiçbir yere yönlendirmez, sadece engellenen paketleri geçecek şekilde düzenler. Bu yüzden hız kaybı olmaz.

**İnternetimi yavaşlatır mı?**
Hayır. Yalnızca Discord/Roblox paketlerine dokunur, onlar da doğrudan gider. Diğer her şey (oyunlar, video, indirmeler) tamamen etkilenmez.

**Başka siteleri de açar mı?**
Hayır, bilinçli olarak. Sadece Discord ve Roblox için çalışır. Amacı genel bir sansür aracı olmak değil, bu iki servisi düzeltmek.

**Güvenli mi, veri topluyor mu?**
Hiçbir veri toplamaz, hiçbir sunucuya bir şey göndermez, hesap/giriş istemez. DNS sorgularını bile şifreli yapar.

**Discord sesli görüşme çalışır mı?**
Evet. Ses genelde zaten engellenmiyor; BTWDPI açıkken sorunsuz çalışır.

**Roblox'ta görseller hâlâ gelmiyor?**
Ana ekrandan **Roblox** korumasının açık olduğundan emin ol, sonra Roblox'u (veya tarayıcı sekmesini) tamamen kapatıp yeniden aç.

**Kapatınca ne oluyor?**
Uygulamadan tamamen çıkarsan koruma durur ve sistem eski haline döner. Arka planda çalışmasını istersen tepsiye küçült, kapatma.

**Nasıl kaldırırım?**
Ayarlar'dan "WinDivert servisini kaldır" de, sonra `C:\Program Files\BTWDPI` klasörünü sil. Windows ile başlatma görevini de kaldırmak için uygulamayı bir kez açıp Ayarlar'dan kapatman yeterli.

---

## Sistem gereksinimleri

- **Windows 10** (1803+) veya **Windows 11**, 64-bit.
- **Microsoft Edge WebView2 Runtime** (modern Windows'ta zaten yüklü; değilse ilk açılışta uyarı verir ve indirme bağlantısı gösterir).
- **Yönetici yetkisi** (ağ sürücüsü için gerekli).

---

<div align="center">

**BTWDPI** — küçük bir araç, büyük bir rahatlık.

*Bu yazılım yalnızca Türkiye'deki yasal erişim engellerini kişisel kullanım için aşmaya yöneliktir. Sorumlu kullanın.*

</div>
