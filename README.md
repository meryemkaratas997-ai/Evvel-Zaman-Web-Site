# Evvel-Zaman-Web-Site
## Proje Hakkında (Ne Yapar?)
Bu proje, **Programlamaya Giriş** dersi vize ödevi kapsamında geliştirilmiş etkileşimli bir Türk masalları web platformudur. 

Kullanıcıların geleneksel Türk masallarını dijital ortamda keşfetmesini sağlar. Sayfa üzerinde masalları inceleme, kişisel okuma listesi oluşturup yönetme, masallardan alıntı kaydetme ve kullanıcı yorum/değerlendirmeleri ekleme gibi etkileşimli özellikler sunar.

## Nasıl Çalıştırılır?
Projeyi çalıştırmak için herhangi bir ek kurulum veya sunucu gerekmez:

1. Depodaki dosyaları bilgisayarınıza indirin.
2. İndirdiğiniz klasördeki `.html` dosyasına çift tıklayarak herhangi bir modern web tarayıcısında (Safari, Chrome vb.) doğrudan açabilirsiniz.
### Dosya Yapısı ve Harici Yapılandırma

Önceki tek sayfalık HTML yapısı, modülerlik ve okunabilirlik amacıyla üç temel dosyaya ve dokümantasyon dosyasına ayrılmıştır. Projede sayfa iskeletini, başlık ve filtre alanını, okuma ve profil görünümlerini barındıran **index.html** dosyası bulunurken, açık ve gece modu tema değişkenleri, tipografi, grid yerleşimi ve mobil uyum kurallarını içeren harici stil dosyası **style.css** üzerinden bağlanmıştır. Tüm masal verileri, arama ve kategori filtreleme işlemleri, okuma durumu takibi, seçerek alıntı kaydetme, puanlama ve inceleme sistemi, beğeni sayacı, kullanıcı profili ve `localStorage` kalıcılık yönetimi ise harici betik dosyası olan **script.js** içinde toplanmıştır. Bunlara ek olarak proje tanıtımını, kullanım adımlarını ve teknik notları içeren **README.md** dosyası da depo yapısında yer almaktadır.
