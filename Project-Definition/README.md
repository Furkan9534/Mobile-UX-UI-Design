# YAPAY ZEKA DESTEKLİ MONTAJ & KABLOLAMA HATA TESPİT SİSTEMİ
## Teknik ve Ticari Teklif
### Proje 
Montaj hattında kablo ve parça montaj hatalarının görüntü işleme ve yapay zeka ile tespiti
### Hedef
Fabrika montaj hattı – mobil , tablet & AVR Gözlük Entegrasyon Destekli Operatör Arayüzü

### Projenin Amacı
Bu projenin amacı; montaj hattında gerçekleştirilen kablo montajlarının, bağlantı noktalarının ve parça yerleşimlerinin yapay zeka destekli görüntü işleme yöntemleri ile analiz edilerek;

yanlış kablolama,

eksik bağlantı,

yanlış parça veya yanlış yön montajı

gibi kalite hatalarının gerçek zamanlı veya yarı gerçek zamanlı olarak tespit edilmesidir.

### Proje Kapsamı

Sistem aşağıdaki fonksiyonları kapsayacaktır:

Kablo montaj doğruluğu kontrolü

Yanlış kablo / yanlış soket tespiti

Eksik bağlantı ve eksik parça tespiti

Yanlış yön / yanlış yerleşim tespiti

Kamera üzerinden görüntü alma ve analiz

Tablet ve mobil cihazlar için operatör arayüzü

Hata bildirimi ve kayıt altyapısı

Basit yönetim ve izleme ekranı

### Sistem Mimarisi – Genel Yaklaşım

Çözüm aşağıdaki ana bileşenlerden oluşacaktır:

Endüstriyel kamera veya mevcut kamera altyapısı

Görüntü işleme ve yapay zeka servisleri

Model eğitim ve doğrulama altyapısı

Mobil / tablet uygulaması

Merkezi servis ve API katmanı

AVR Gözlük ile Uygulama Entegrasyonu

AVR Gözlüğe Mobil ve Tablet Uygulamasının Entegresyanu



### Proof of Concept (PoC) Aşaması

Bu proje için klasik anlamda bir “demo” yerine Proof of Concept (PoC) çalışması önerilmektedir.

PoC’nin amacı

Sistemin gerçek üretim hattı koşullarında teknik olarak çalışabilirliğini ve başarı oranını doğrulamaktır.

PoC kapsamı

PoC çalışması aşağıdaki sınırlı kapsam ile yürütülecektir:

Seçilecek tek bir montaj istasyonu

Sınırlı parça ve kablo tipi

Sınırlı hata senaryosu

Tek kamera veya sınırlı kamera kurulumu

Sadece doğrulama amaçlı yapay zeka modeli

Tablet / mobil üzerinden temel operatör ekranı

Önemli not

PoC çalışması ticari ürün değildir.
Fizibilite ve teknik doğrulama amaçlı mühendislik çalışmasıdır.

PoC çalışması; saha verisi toplanması, görüntülerin etiketlenmesi, model eğitimi ve test faaliyetlerini içeren bir mühendislik sürecidir ve ücretsiz demo kapsamında değerlendirilemez.

### PoC Çıktıları

PoC sonunda aşağıdaki çıktılar sunulacaktır:

Seçilen istasyon için çalışan yapay zeka modeli

Temel mobil / tablet arayüzü

Tespit edilen hata senaryoları için doğruluk raporu

Sistem mimarisi ve teknik değerlendirme dokümanı

### PoC Sonrası Ürünleştirme Aşaması

PoC’nin başarılı olması durumunda;

model genişletme,

yeni istasyonların eklenmesi,

daha fazla parça ve kablo tipi,

merkezi yönetim paneli,

entegrasyon ihtiyaçları

ürünleştirme fazında hayata geçirilecektir.

PoC kapsamında geliştirilen yazılım, altyapı ve modeller ana ürün geliştirme sürecine doğrudan entegre edilir.

### Saha Koşulları ve Performans Etkileri

Aşağıdaki faktörlerin sistem performansını doğrudan etkilediği taraflarca kabul edilir:

Kamera konumu ve çözünürlüğü

Ortam ışığı ve gölge koşulları

Operatör hareketleri

Üretim temposu

Ürün varyasyonları

Model doğruluk oranları bu değişkenlere bağlı olarak farklılık gösterebilir.

## Proje Fazları
### Faz 1 – PoC Çalışması

Kamera montaj hata ve montajlama için test

Veri toplama

Görüntü etiketleme

Yapay zeka model eğitimi

Mobil / tablet temel arayüz

Saha testleri

### Faz 2 – Ürün Geliştirme

Yeni istasyonların eklenmesi

Genişletilmiş hata senaryoları

Performans iyileştirme

Yönetim paneli

Entegrasyonlar

### Faz 3 – Ürün Geliştirme1

AVR Gözlük ile uygulama  entegrasyonu

Servis Modülü Entegrasyonu

### Genel Değerlendirme

Bu proje;

klasik bir yazılım geliştirme projesi değil,

gerçek saha verisine,

üretim hattı koşullarına,

görüntü kalitesine ve ortam değişkenlerine

bağımlı, yüksek mühendislik içeren bir yapay zeka uygulamasıdır.

Bu nedenle sürecin PoC temelli ve kontrollü şekilde ilerlemesi önerilmektedir.

### Mobil, Tablet ve AR (AVR) Gözlük Tabanlı Operatör Arayüzü
Bu proje kapsamında, montaj hattında çalışan operatörlerin doğrudan kullanacağı;

| Cihazlar  |  
| ------------- |  
| endüstriyel tabletler  |  
| Gözlük Teknolojisine Entegre Etme  |  

üzerinden çalışan çoklu istemci mimarisi tasarlanacaktır. Tüm istemci uygulamaları, merkezi yapay zeka servisleri ile API tabanlı haberleşme üzerinden çalışacaktır.

### Mobil ve Tablet Uygulamaları


UX/UI