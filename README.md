# 🖥️ JET File Transfer (Veri Aktarım Aracı)

## JET File Transfer, yerel ağ (Wi-Fi/Ethernet) üzerindeki akıllı telefonlar ve bilgisayarlar arasında, özellikle Pardus ve Windows işletim sistemlerinde, küçük ve büyük boyutlu dosyaların hızlı, güvenli ve kablosuz olarak aktarılmasını sağlayan Qt tabanlı bir masaüstü sunucu uygulamasıdır.

Ek olarak proje kapsamında geliştirilen mobil uygulama ve msaüstü uygulamaları sayesinde Milli Eğitim Bakanlığına bağlı Pardus işletim sistemi yüklü tüm tahtalarda öğretmenlerin kolaylıkla cep telefonlarından akıllı tahtaya dosyalar ve metinleri aktararak öğrencilere sunmaları hedeflenmektedir.

------
## JET File Transfer'in Android istemcisi ile aynı yerel ağ üzerindeki dosyaları mobil cihazınızdan PARDUS işetim sistemine güvenli olarak gönderebilirsiniz.
## Öncelikle  PLAY STORE üzerinden (https://play.google.com/store/apps/details?id=com.gksyazilim.parduslansharemobile) JET File Transfer isimli mobil uygulamayı Android cihazınıza kurmalısınız

## Mobil uygulamayı kurduktan sonra bu linkte yer alan deb paketini indirerek Pardus işletim sisteminize kurabilir ve cep telefonunuz üzerinden aynı ağda yer alan pardus işetim sisteminize dosya transferini yapabilirsiniz.

### 📥 Uygulama İndirme Linkleri

* 🐧 **Pardus / Linux İşletim Sistemi İçin (.deb):**  
  [🔗 JET File Transfer İndir](http://www.gksyazilim.org/debs/pardus-lan-share-pkgv2.deb)

* 🪟 **Windows İşletim Sistemi İçin Kurulum Dosyası (Setup):**  
  [🔗 JET File Transfer Windows Kurulumu İndir](https://github.com/gucluyurekler0/Pardus-LAN-Share/raw/main/PardusLanShare_Setup.exe)

------

## 📱 Android İstemcisi

---------------------------------------------------------------------------------------------------------------------------------------------------------
 **JET File Transfer Mobile:**  
Github : https://github.com/gucluyurekler0/PardusLanShareMobile <br>
Uygulama Dosyası : (https://play.google.com/store/apps/details?id=com.gksyazilim.parduslansharemobile)
## 📷 Android Mobil Uygulama Ekran Görüntüleri

<p align="center">
  <img src="https://raw.githubusercontent.com/gucluyurekler0/Pardus-LAN-Share/main/screenshots/scr1.jpg" alt="Ana Ekran 1" width="300"/>

  
</p>

---


# 📱 Kullanım

1. Uygulamayı Pardus üzerinde çalıştırın.
2. **Sunucu IP Adresi** bölümünde görünen QR kodu mobil uygulama üzerinden taratın veya ekranda görüne IP numarası ve parola ile uygulamaya giriniz. (Örn: `192.168.1.50`)
3. Aynı Wi-Fi ağına bağlı telefonunuzdaki istemci uygulamasından bu IP adresine bağlanın.
4. Metin gönderdiğinizde düzenleme alanında görüntülenir.
5. **Değişiklikleri Panoya Kopyala** butonuyla bilgisayar panosuna aktarabilirsiniz.
6. Dosya gönderildiğinde sistem günlüğünün en üstünde görünür.
7. Dosyaya çift tıklayarak doğrudan açabilirsiniz.
8. Dosyalarınız İndirilenler dizini altında PardusLanShare dizini altında kaydedilmektedir.

---


# ✨ Özellikler

- **Gelişmiş Metin Editörü (`QTextEdit`)**
  - Telefondan gelen pano (clipboard) içeriklerini kırpılmadan tam haliyle görebilir, düzenleyebilir ve tek butonla bilgisayar panosuna aktarabilirsiniz.

- **Akıllı Dosya Yöneticisi**
  - Gelen dosyalar tamamlandığında sistem günlüklerinin en üstünde görünür.
  - Dosyaya çift tıklayarak varsayılan uygulama ile açabilirsiniz.

- **Sanal Ağ Filtreleme**
  - VirtualBox, VMware ve WSL gibi sanal adaptörleri otomatik filtreler.
  - Gerçek yerel IP adresini gösterir.

- **Anlık İlerleme Çubuğu**
  - Dosya aktarım yüzdesini canlı olarak gösterir.



# 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|-----------|----------|
| **Dil** | C++17 |
| **Arayüz** | Qt 6 (QtWidgets, QtNetwork) |
| **Derleme Sistemi** | CMake |

---

# 📸 Ekran Görüntüsü



![JET File Transfer](https://raw.githubusercontent.com/gucluyurekler0/Pardus-LAN-Share/main/screenshots/scr2.jpg)

![JET File Transfer](https://raw.githubusercontent.com/gucluyurekler0/Pardus-LAN-Share/main/screenshots/parduslansharescr1.png)

![JET File Transfer](https://raw.githubusercontent.com/gucluyurekler0/Pardus-LAN-Share/main/screenshots/parduslansharescr2.png)
---

# 📄 Lisans

Bu proje açık kaynak olarak geliştirilmektedir.
