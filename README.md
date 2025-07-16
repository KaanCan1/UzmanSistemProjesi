# Uzman Sistem Projesi

Bu proje, PHP ve Python kullanılarak geliştirilmiş bir uzman sistem öneri platformudur. Kullanıcıların web üzerinden cevapladığı sorular, arka planda bir Python betiğine gönderilerek değerlendirilir. Sistem, kullanıcı cevaplarına göre veritabanındaki önerileri analiz eder ve en uygun tavsiyeyi sunar.

Özellikler:
Web Arayüzü: index.php üzerinden kullanıcıdan veri alır.
Python Karar Motoru: uzman_sistem.py, kullanıcı yanıtlarını değerlendirerek veritabanı üzerinden öneri üretir.
MySQL Veritabanı: Öneri ve soru-cevap eşleşmelerini saklar.
JSON ile Veri İletişimi: PHP'den Python'a veri JSON formatında iletilir.

Kullanım Alanları:
Psikolojik danışmanlık sistemleri
Kişiselleştirilmiş öneri motorları
Karar destek sistemleri
