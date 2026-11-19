# Evvel-Zaman-Web-Site
## Proje Hakkında (Ne Yapar?)
Bu proje, **Programlamaya Giriş** dersi vize ödevi kapsamında geliştirilmiş etkileşimli bir Türk masalları web platformudur. 

Kullanıcıların geleneksel Türk masallarını dijital ortamda keşfetmesini sağlar. Sayfa üzerinde masalları inceleme, kişisel okuma listesi oluşturup yönetme, masallardan alıntı kaydetme ve kullanıcı yorum/değerlendirmeleri ekleme gibi etkileşimli özellikler sunar.

## Nasıl Çalıştırılır?
Projeyi çalıştırmak için herhangi bir ek kurulum veya sunucu gerekmez:

1. Depodaki dosyaları bilgisayarınıza indirin.
2. İndirdiğiniz klasördeki `.html` dosyasına çift tıklayarak herhangi bir modern web tarayıcısında (Safari, Chrome vb.) doğrudan açabilirsiniz.
Dosya Yapısı ve Harici Yapılandırma

Önceki tek sayfalık HTML yapısı, modülerlik ve okunabilirlik amacıyla üç temel dosyaya (ve dokümantasyon dosyasına) ayrılmıştır:

Evvel-Zaman-Web-Site/
├── index.html      # Sayfa iskeleti, başlık/filtre alanı, okuma ve profil görünümleri
├── style.css       # Harici stil dosyası (tema değişkenleri, tipografi, grid ve mobil düzen)
├── script.js       # Harici betik dosyası (masal verileri, filtreleme, alıntı, inceleme ve LocalStorage)
