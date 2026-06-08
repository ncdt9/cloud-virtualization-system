Bu proje, perakende sektöründe faaliyet gösteren ŞOK Marketler zincirinin bilişim altyapısının modernizasyonu için Sistem Geliştirme Yaşam Döngüsü (SDLC) prensiplerine uygun olarak tasarlanmış, uçtan uca sanal bir ağ altyapısı simülasyonudur.
📝 Proje Özeti

Proje kapsamında, kurumsal bir yapının ihtiyaç duyabileceği bulut bilişim, sanallaştırma ve merkezi yönetim mimarileri üzerine çalışılmıştır. Sistem analizi, fizibilite çalışmaları ve risk değerlendirmeleri yapılarak tasarlanan altyapı, sanal bir ortamda hayata geçirilmiş ve test edilmiştir. Proje, kurumsal sistem yönetimi ve ağ otomasyonu konularında pratik bir uygulama niteliği taşımaktadır.
🛠️ Kullanılan Teknolojiler ve Araçlar

    Sanallaştırma: Oracle VM VirtualBox

    İşletim Sistemleri: Windows Server 2019, Windows 10 (İstemci)

    Sistem Yönetimi: Active Directory (AD), Group Policy Object (GPO)

    Otomasyon: PowerShell

    Ağ Simülasyonu: Cisco Packet Tracer

✨ Temel Özellikler (Features)

    Ağ Topolojisi Modellemesi: Cisco Packet Tracer kullanılarak kurum içi ağ mimarisinin mantıksal ve fiziksel tasarımı.

    Merkezi Sunucu Kurulumu: VirtualBox üzerinde Windows Server 2019 ayağa kaldırılarak domain controller yapılandırmasının gerçekleştirilmesi.

    Kullanıcı ve Yetki Yönetimi: Active Directory entegrasyonu ile departmanlara ve rollere göre Windows 10 istemcilerinin (client) yetkilendirilmesi.

    Güvenlik ve Politika Yönetimi: GPO (Group Policy Object) kullanılarak kurumsal güvenlik politikalarının uç noktalara dağıtılması.

    Sistem Otomasyonu: Rutin ağ yönetimi ve sistem süreçlerinin PowerShell betikleri (script) yazılarak optimize edilmesi ve hızlandırılması.

📂 Proje Çıktıları

Bu depo (repository) projenin kod ve yapılandırma kısımlarını içermektedir. Proje kapsamında ayrıca aşağıdaki dokümantasyonlar üretilmiştir:

    SDLC Dokümantasyonu: Sistem analizi, risk ve fizibilite değerlendirmeleri.

    Yapılandırma Dosyaları ve Betikler: PowerShell otomasyon kodları ve Packet Tracer (.pkt) dosyaları.

    Kanıt (Proof of Concept) Belgeleri: Active Directory ve GPO yapılandırma adımlarının ekran görüntüleri.

🚀 Kurulum ve Çalıştırma

Not: Bu projeyi kendi ortamınızda simüle etmek için VirtualBox ve Cisco Packet Tracer kurulu olmalıdır.

    Bu depoyu klonlayın: git clone https://github.com/kullaniciadiniz/sok-market-altyapi-projesi.git

    Network-Topology klasöründeki .pkt dosyasını Cisco Packet Tracer ile açarak ağ mimarisini inceleyin.

    Scripts klasöründeki PowerShell betiklerini Windows Server ortamında Administrator yetkisiyle çalıştırarak otomasyon süreçlerini test edebilirsiniz.
