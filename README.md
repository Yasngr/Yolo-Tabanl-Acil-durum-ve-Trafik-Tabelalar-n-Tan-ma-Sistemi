# Yolo-Tabanl-Acil-durum-ve-Trafik-Tabelalar-n-Tan-ma-Sistemi
# YOLO Tabanlı Acil Durum ve Trafik Tabelalarının Tanınma Sistemi

Bu proje, görüntü işleme ve derin öğrenme teknikleri kullanılarak acil durum işaretleri ve trafik tabelalarının otomatik olarak tespit edilmesini ve sınıflandırılmasını amaçlamaktadır. Çalışmada, gerçek dünya koşullarına uygun olarak oluşturulmuş ve manuel olarak etiketlenmiş özel bir veri seti kullanılmıştır.

Proje kapsamında, YOLO (You Only Look Once) tabanlı nesne tespit algoritmaları kullanılarak trafik tabelalarının gerçek zamanlı olarak algılanması hedeflenmiştir. Model, farklı trafik tabelası türlerini yüksek doğruluk oranı ile tanıyabilecek şekilde eğitilmiş ve doğrulanmıştır. Bu sayede sürüş güvenliğini artırmaya yönelik akıllı ulaşım sistemlerine katkı sağlanması amaçlanmaktadır.

## Veri Seti Bilgileri
- Veri seti: Özel oluşturulmuş ve etiketlenmiş görüntüler
- Toplam görüntü sayısı: 1261
- Eğitim (Train): 1008 görüntü
- Doğrulama (Validation): 126 görüntü
- Toplam sınıf sayısı: 4

## Model ve Eğitim Detayları
- Kullanılan model: YOLO11n
- Epoch sayısı: 50
- Görüntü boyutu: 640x640
- Batch size: 16
- Optimizasyon algoritması: AdamW
- Donanım: NVIDIA RTX 5050 Laptop GPU

## Projenin Amacı
Bu çalışmanın temel amacı, trafik tabelalarının otomatik olarak tanınmasını sağlayarak sürücü destek sistemleri, otonom araçlar ve akıllı ulaşım uygulamaları için ölçeklenebilir bir çözüm sunmaktır. Geliştirilen sistem, gerçek zamanlı çalışmaya uygun olacak şekilde tasarlanmıştır.

## Notlar
- Veri setinin tamamı ve eğitilmiş model ağırlıkları dosya boyutu nedeniyle GitHub reposuna eklenmemiştir.
- İlgili dosyalar talep edilmesi halinde paylaşılabilir.

