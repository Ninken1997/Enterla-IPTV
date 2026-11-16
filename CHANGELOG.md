# Sürüm notları

En yeni sürüm üsttedir. 1.0 öncesi notlar konuşma kaydı ve eldeki APK sürümlerinden geriye dönük derlenmiştir; eksiksiz bir değişiklik dökümü değildir.

## 1.0.12

- Ayarlarda ayrı Güncellemeler bölümü: sürüm durumu, son kontrol zamanı, yenilikler ve tek tuşla güncelleme.
- Yeni sürüm bildirimi, yenilikleri Güncelle / Sonra seçenekleriyle gösterir; yayın arka planda devam eder.
- Sonra denilen güncelleme unutulmaz: M3U ve Xtream önizlemelerinde kumandayla erişilen güncelleme işareti, uygulama yeniden açılsa da kalır. Yeni sürüm kurulunca kalkar.
- Hakkında yenilendi: Hitit görseli, Enterla IPTV kimliği, kısa oynatıcı açıklaması, geliştirici bilgisi ve kompakt Enterla / MemoriBox QR bağlantıları.
- Kullanılan AndroidX Media3, FFmpeg / io.put ve AndroidX Core için bileşen / lisans bilgileri ve tam metinlere erişim.

## 1.0.11

- Uygulama içinden güncelleme: yeni sürüm bildirimi, indirme ilerlemesi ve Android'in kullanıcı onaylı kurulum ekranı.
- Ayarlar → Hakkında üzerinden elle güncelleme kontrolü ve otomatik kontrolü açıp kapatma. Otomatik kontrol yalnızca uygulama açıkken, başarılı kontrolden sonra günde bir yapılır; ağ hataları yayına uyarı çıkarmaz.
- Standart / açılış yardımcılı APK seçimi korunur. Dosya boyutu, SHA-256, paket kimliği, sürüm, APK çeşidi ve kurulu uygulamanın imzası doğrulanır. Listeler ve tercihler silinmez.
- İlk prototipten bugüne sürüm geçmişi uygulamanın içinde çevrimdışı okunabilir.
- APK indirmeleri kaynak kod içermeyen ayrı, herkese açık dağıtım alanından sunulur.

## 1.0.10

- Önizlemeli açılışta kumanda odağı Ara yerine son izlenen kanalın satırına / kartına verilir. Uykudan önizlemeye dönüldüğünde de kanal listesi hazırdır; açık ayar veya ileti penceresine dokunulmaz.
- Tam ekran / yalnız liste açılışı ve kullanıcı sonradan Ara düğmesine geçtiğinde odağın korunması sürer.

## 1.0.9

- Mağazasız dağıtım için aynı uygulama sertifikasıyla imzalı, R8 ile küçültülmüş basic / assisted release APK'ları. Yerel derleme betiği imza, hata ayıklama ve 16 KB paket hizası kontrolleri yapar.

- Uygulamanın görünen adı Enterla IPTV oldu. Paket kimliği ve yerel veri alanı korunur.
- Ayarlarda ayrı Hakkında bölümü: Enterla / MemoriBox HTTPS bağlantıları, telefondan okutulabilen çevrimdışı QR kodlar ve ücretsiz oynatıcı açıklaması.
- Küçük E simgesi korundu; Android TV yatay başlatıcı görselinde Enterla IPTV adı kullanılır.

## 1.0.8

- Akıcılık ve Cihaz uyumu tek Performans bölümünde birleştirildi. Çalışma modu / tampon önde; kalite sınırı, decoder ve ekran ritmi gelişmiş bölümde.
- Çok satırlı seçenek kartlarında üst / alt kenar kayması ve kesilmesi düzeltildi; satırdaki kartlar aynı yükseklikte ölçülür.
- Daha sakin ince yüzey çizgileri, ortak köşe ölçüleri ve ferah seçenek aralıkları. Kumanda odağı ve seçili tercih ayrı görünmeye devam eder.
- Büyük yazıda başlık ve düğmeler gereken yüksekliğe açılır. Üst araç çubuğu yalnızca yer yetmediğinde ikinci satıra geçer; küçük önizlemede boş ekran açıklaması sadeleşir.
- M3U / Xtream satır ve kart yükseklikleri yazıya uyar. Resimsiz kartlarda gereksiz poster boşluğu ayrılmaz.

## 1.0.7

- Cihaz uyumu: Otomatik / Dengeli / Yüksek kalite; varsayılan Dengeli. Arayüz ve görüntü desteği ayrı değerlendirilir; mevcut yazı boyutu, kanal düzeni, tema ve açılış tercihleri korunur.
- Donanım çözücüsü ve bağlı TV destekliyorsa 4K / 8K dahil uygun kalite seçilebilir. Genel 1080p / 12 Mb/sn sınırı kaldırıldı; eski aquaman Mi Stick'in otomatik koruması korundu. Kalite seçimi tek kaynaklı videoyu dönüştürmez.
- Afiş ayrıntısı, renk derinliği, önbellek bütçesi ve yumuşak düğme geçişleri cihaz / mod seçimine uyar. Düşük bellek koruması her modda sürer; bellek baskısında afiş önbelleği temizlenir.
- İlk açılışta bir defalık, odağı almayan cihaz özeti. Ayarlarda mod değişince yayın durmadan kısa bir görsel geçiş ve seçilen modun özeti.

## 1.0.6

- Kumanda odağında daha belirgin dolgu ve üç birim kalınlığında çerçeve; üst düğmeler, boyut düğmesi ve ayarlar ortak stili kullanır.
- Liste / kartlarda gerçek kumanda odağı, odağın ayrıldığı eski satırdan ayrı gösterilir. M3U, Xtream ve tam ekran kanal paneli aynı davranır.
- Önizleme odaktayken açık / koyu görüntüde seçilebilen çift renkli kalın çerçeve ve OK ile tam ekran ipucu. Tam ekrana geçince odak süsleri gizlenir; dönüşte tekrar çalışır.
- Oynatma, tampon, çözücü ve açılış ayarları değiştirilmedi. Yeni animasyon veya görüntü filtresi eklenmedi.

## 1.0.5

- Görüntü uyumluluğu: Android 9 ve önceki aquaman / Amlogic Mi Stick'te kanal geçişlerinde eski çözücü durumu taşınmadan temiz oynatıcı açılır. M3U ve Xtream ortak davranır; ses yedeği ve ekran uyumu korunur.
- Ayarlar → Akıcılık altında Otomatik / Normal / Temiz başlangıç seçimi. Mevcut yayını kesmez; sonraki yayında uygulanır. Diğer cihazlarda otomatik seçim mevcut davranışı korur.
- Eski Mi Stick için asenkron görüntü kuyruklaması ve mevcut kullanıcı tercihlerini koruyan akıcılık düzenlemeleri.
- Teşhiste AVC başlığının düz kare / geçmeli tarama ayrımı ve uzun kare planlama aralıkları. Başlık işaretleri kesin görüntü kalitesi veya her karenin tarama biçimi olarak sunulmaz.
- Düz ve geçmeli sentetik yayınlar arasında gerçek ses / görüntü çözülerek kanal geçişi, normal moda dönüş ve Xtream'de aynı uyumluluk davranışı sınanır.
- Bu sürüm cihazın yeniden başlama nedeninin çözüldüğü veya her geçmeli yayının akıcılığının düzeldiği iddiasını taşımaz.

## 1.0.4

- Media3 1.11.1'e geçildi. Donanım ses çözücüsünün desteklemediği yaygın ses biçimlerinde kullanılan FFmpeg yedeği eklendi; MP2 sesli Beyaz TV gerçek Mi Stick'te doğrulandı.
- M3U / Xtream ortak oynatma yapılandırması ve belleği sınırlı üç tampon profili: Hızlı geçiş, Dengeli (varsayılan), Daha dayanıklı. Kesinti sonrası başlama rezervi artırıldı.
- Ekran hızı varsayılan olarak otomatik eşleştirilir. Desteklenen aynı çözünürlükteki ekran modları arasından uygun ritim seçilir; TV ayarını koruma ve elle seçim de vardır. Mi Stick'te 25 kare/sn ölçümüyle 50 Hz çıkış doğrulandı.
- Bilgi şeridinde gerçek çözülen görüntü boyutu ve varsa kare hızı; biçim bildirmiyorsa kare zamanlarından yaklaşık hız gösterilir.
- Ayarlar → Akıcılık: tampon, eski Android'ler için ek görüntü işleme seçeneği, ekran eşleştirme, canlı yayın teşhisi ve aynı yayını temiz bağlantıyla yeniden başlatma. Ses / altyazı ayarları ayrı bölümde kaldı.
- Teşhis ekranında tampon, veri hızı, ses biçimi / çözülmüş ses paketleri, görüntü çözücüsü, kare kaybı ve beklemeler görünür. Özel adresler / hesaplar teşhis çıktısına eklenmez.
- Desteklenmeyen yayın biçiminde açıklayıcı durum mesajı; kanal değiştirme açık kalır.
- Xtream yüklenirken önceki satıra ait sırada kalan tuşun yanlış içerik açması engellendi; ölçek değişimi yükleme ekranını korur.
- Film / dizi arayüzü yeniden çizilince duraklama durumu ve oynatma kontrolleri korunur.
- Açık kaynak lisansları ve kullanılan FFmpeg sürümüne ait kaynak / yeniden bağlantı bilgileri uygulamaya eklendi.

## 1.0.3

- Varsayılan arka plan #070F1C; hafif lacivert geçiş, daha sakin kartlar ve beyaz yazılı mavi odak / seçim durumları.
- Ayarlar → Renkler: altı hazır renk, özel #RRGGBB kodu ve varsayılana dönme. Yazılar ve yüzeyler otomatik uyarlanır; beyaz zeminde siyah yazılar kullanılır.
- Açık anahtarda belirgin renkli çerçeve ve dolu anahtar; kapalı durumda gri anahtar. Kumanda odağı ile seçili değer ayrılır.
- Xtream film / dizide OK durdurur veya devam ettirir; sağ / sol 10 saniye ileri / geri alır. Canlı kanal komutları ve yanlış liste uyarısı araya girmez.
- M3U ve Xtream canlı kategorisinde çok haneli kanal numarası girişi, sayısal klavye desteği ve geçersiz numarada mevcut kanalı koruma.
- Xtream canlı kanal numaraları kategori sırasını korur; filtre içinde satır / kart / bilgi paneli aynı numarayı gösterir.

## 1.0.2

- M3U ve Xtream için ortak ayar ekranı: solda bölümler, sağda aynı pencere içinde değişen seçenekler.
- Otomatik açılış ve kanal resimleri için yerinde aç/kapa anahtarları; seçili durumu belli radyo seçenekleri.
- Açılış, yazı / satır boyutu, ses / altyazı ve görüntü boyutunu seçerken ayarlar kapanıp yeniden açılmaz.
- “Sadece kanal listesi” yerine açıklamalı “Listeyi aç, yayını başlatma”; başlangıç görünümü ile tam ekran kanal panelinin farkı netleştirildi.
- Ses, altyazı ve görüntü ayarları yayını yeniden başlatmadan uygulanır. Yazı boyutu değişirken aynı ayar penceresi ve seçilen bölüm korunur.
- Tam ekran bilgi paneli yaklaşık yüzde 25 büyütüldü; yayın hazırken görünme süresi 4 saniyeden 7 saniyeye çıkarıldı. Önizleme panelinin boyutu korundu.
- Üst çubuktaki E TV yazısı kaldırıldı; simge büyütüldü. Ortak düğme konumları korundu.

## 1.0.1

- Liste okunurken logolu hazırlık ekranı; kayıtlı liste yüklenmeden yanlışlıkla "Henüz bir listen yok" gösterilmez.
- Hazırlık, gerçek liste / önbellek hazır olduğunda biter; yapay bekleme eklenmez. Boş hesap ve okuma hatası da hazırlıktan çıkar.
- M3U ↔ Xtream kaynak değişiminde ara kaynak ekranı ve kaydırma animasyonu kaldırıldı.
- Xtream ana sayfasında M3U'ya döndüren Geri düğmesi yok; iç bölümlerde Geri korunur. Ana sayfada kumandanın Geri tuşu TV ana ekranını açar.
- İki kaynakta ortak üst çubuk: Ara, ekran boyutu, Listeler, Ayarlar, ÇIKIŞ ve saat aynı yerlerde.
- Xtream görünüm / yenileme / iç bölüm Geri düğmeleri içerik alanına taşındı; açılış ayarları her iki kaynaktan aynı seçeneklerle açılır.

## 1.0.0

- M3U listeleri ve Xtream hesapları arasında doğrudan kaynak geçişi; ayrı kaynak alanları.
- M3U ve Xtream canlı kanalları için ortak liste / sağda önizleme ekranı.
- Sol kanal alanında isteğe bağlı iki sütun resimli kartlar; yalnızca kaynakta bulunan resimler.
- Tam ekranda kanal adı, yayın durumu ve gerçek indirme hızını gösteren bilgi paneli; yayın hazırken dört saniye sonra gizlenme.
- Yüklenemeyen kanalda kumandayla geçiş; eski bağlantı ve yeniden denemelerin yeni kanalı etkilemesini engelleme.
- Xtream son kanalının kategorisini koruma, eski eksik kategori bilgisini onarma ve son canlı kategori için özel önbellek.
- Tam ekran yayın, önizlemeli liste veya yalnızca listeyle açılma ve uyku dönüşü.
- Android 9 açılış desteği ve yeni Android TV için isteğe bağlı açılış yardımcısı.
- Büyük yazılar, bağımsız liste boyutu, tam ekran kanal paneli ve sayfalama, ses / altyazı tercihleri.
- Xtream film / dizi kategorileri, resimli görünümler, sezon ve bölüm seçimi.
- E TV marka simgesi / yatay TV kartı ve sistem ana ekranına ÇIKIŞ.

## 0.1.11 · Önizleme

- M3U ve Xtream canlı kanalları için ortak solda liste / sağda önizleme düzeni.
- Sol kanal alanında iki sütun resimli kartlar; resimler kaynakta varsa gösterilir.
- Kanal, yayın durumu ve indirme hızını gösteren bilgi paneli.
- Kaynak seçimi, son kanal / açılış görünümü ve Xtream canlı önbelleği.

## 0.1.10 · Önizleme

- Android 15 / 16 TV uyumluluğu ve yeni Android sürümleri için isteğe bağlı açılış yardımcısı üzerinde çalışmalar.
- Büyük yazı ve kumandayla kullanım düzenlemeleri.

## 0.1.9 · Önizleme

- Arayüz ve kanal listesi için ayrı boyut ayarları; hızlı boyut düğmesi.
- Küçükten büyüğe daha geniş yazı ve satır seçenekleri.

## 0.1.8 · Önizleme

- Liste ekleme sırasında görünür yükleme / hata geri bildirimi ve adres işlemleri.
- ÇIKIŞ ile TV ana ekranına dönüş; oynatma tercihleri.

## 0.1.7 · Önizleme

- E TV adı ve E / IPTV görseliyle ilk marka düzeni.
- Kurulum ve liste ekranlarında açıklamaların sadeleştirilmesi.

## 0.1.6 · Önizleme

- Yayın sürerken OK ile açılan kanal paneli; sağ / sol ile sayfa geçişi.
- Kanal logolarını kaynak sağlıyorsa isteğe bağlı gösterme.

## 0.1.5 · Önizleme

- Xtream için Canlı TV / Filmler / Diziler alanları, sağlayıcı kategorileri, sezon ve bölüm seçimi.
- Afiş / logo yükleme ve resimli görünümler.

## 0.1.4 · Önizleme

- Xtream sunucu, kullanıcı adı ve şifreyle giriş.
- İlk kurulumda M3U veya Xtream seçimi ve canlı kanal kumanda yönünün düzenlenmesi.

## 0.1.3 · Önizleme

- `.m3u` uzantılı canlı yayınların HLS içeriğiyle doğru hazırlanması.

## 0.1.2 · Önizleme

- Android 9 Mi Stick için cihaz açılışında otomatik başlatma iyileştirmeleri.

## 0.1.1 · Önizleme

- İlk APK kurulum ve Mi Stick uyumluluk düzenlemeleri.

## 0.1.0 · İlk prototip

- Ev TV adıyla Türkçe Android TV oynatıcısı.
- Dosyadan / internet adresinden M3U ekleme, kanal listesi, önizleme ve tam ekran izleme.
- Büyük yazı, basit kumanda kullanımı ve son kanala devam etme odaklı ilk sürüm.
