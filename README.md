👥 Personel Kayıt ve Yönetim Sistemi
Bu proje, işletmelerin personel verilerini dijital ortamda güvenli ve düzenli bir şekilde tutmalarını sağlamak amacıyla geliştirilmiş bir masaüstü uygulamasıdır. Python'ın esnekliği ile Qt (PySide6)'in görsel gücünü birleştirerek modern bir kullanıcı deneyimi sunar.

🚀 Öne Çıkan Teknik Özellikler
Modern GUI Mimarisi: PySide6 kütüphanesi ve .ui dosyası entegrasyonu ile geliştirilmiş esnek arayüz.

Gelişmiş Veri Doğrulama (Validation): QRegularExpressionValidator kullanılarak TC Kimlik Numarası (11 hane) ve Telefon Numarası gibi alanlarda hatalı girişi engelleyen gerçek zamanlı kontrol mekanizması.

Hata Yönetimi (Error Handling): try-except blokları ve QMessageBox bildirimleri ile desteklenmiş, kullanıcıyı yönlendiren güvenli çalışma yapısı.

Veri Saklama: Veriler personel.csv dosyasında yapılandırılmış şekilde saklanır; bu sayede harici bir veritabanı kurulumuna gerek kalmadan taşınabilir bir yapı sunar.

CRUD Operasyonları: Personel ekleme, verileri tablo üzerinde anlık listeleme ve form temizleme özelliklerini içerir.

🛠️ Kullanılan Teknolojiler
Dil: Python 3.x

Arayüz: PySide6 (Qt for Python)

Veri Formatı: CSV (Semicolon Delimited)
