Cisco Packet Tracer ile Akıllı Otel Ağ Tasarımı

Bu proje, modern bir otel işletmesinin ihtiyaç duyduğu karmaşık ağ altyapısını, Cisco Packet Tracer üzerinde uçtan uca simüle eder. Proje; ağ hiyerarşisi, IoT entegrasyonu ve dış dünya bağlantısı (WAN) gibi temel ağ prensiplerini uygulamalı olarak sunmaktadır.

🛠 Teknik Mimari ve Özellikler
1. Ağ Segmentasyonu (VLAN Yapılandırması)
Ağ performansı ve güvenliğini optimize etmek amacıyla sistem mantıksal katmanlara ayrılmıştır:  


VLAN 10 (Misafir Ağı): Müşterilerin internet erişimi için izole edilmiş katman.  


VLAN 30 (Personel Ağı): Resepsiyon, mutfak ve temizlik birimleri arasındaki dahili haberleşme.  


VLAN 40 (Otopark/IoT Ağı): Sensörlerin ve akıllı ekranların trafiğini ana ağdan ayıran özel segment.  

2. Sunucu ve Yönetim Hizmetleri
Sistemin verimliliğini artırmak için merkezi bir sunucu üzerinden şu servisler aktifleştirilmiştir:  


DHCP: Tüm laptop ve IoT cihazlarına otomatik IP ataması.  


DNS: Alan adlarını (örneğin: grandmarmaraotel.com) IP adreslerine çözümleme.  


HTTP: Otel içi bilgilendirme ve servisler için özel tasarlanmış web arayüzü.  

3. IoT ve Donanım Otomasyonu
Otel içindeki fiziksel süreçler dijitalleştirilmiştir:  


Akıllı Otopark: MCU ve hareket sensörleri kullanılarak araç giriş-çıkış takibi ve LCD ekran üzerinden anlık boş yer bildirimi.  


Dijital Hizmet Bildirimi: Odalardaki akıllı butonlar aracılığıyla personelin merkezi ekranlarına (IoT Monitor) anlık talep iletimi.  

4. Güvenlik (ACL & WAN)

WAN Simülasyonu: Otel ağının dış dünya (Ev ağı) ile olan bağlantısı simüle edilmiştir.  


Erişim Kontrol Listesi (ACL): Core Switch üzerinde yapılandırılan firewall kuralları ile dış ağdan gelen yetkisiz erişimler (personel ve otopark ağına sızma) engellenmiştir.  

🚀 Sonuç
Bu simülasyon; VLAN yönetimi, IP yönlendirme kuralları, servis yapılandırmaları ve donanım kodlamasının (Python/MCU) bir ağ mimarisinde nasıl entegre çalıştığını kanıtlayan bütünleşik bir çalışmadır.  

👥 Hazırlayanlar
Naz Altınbaş   

Fatma Tanrıverdi   

İlknur Güner   


Bu proje 2025-2026 Eğitim Öğretim Yılı Bahar Dönemi "Bilgisayar Ağlarına Giriş" dersi final ödevi olarak hazırlanmıştır.
