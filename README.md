## Restaurant Order Management System (Java)

Bu proje Java programlama dili kullanılarak geliştirilmiş konsol tabanlı bir restoran sipariş yönetim sistemidir. Uygulama, nesne yönelimli programlama (OOP) prensipleri kullanılarak gerçek bir restoran iş akışını modellemek amacıyla tasarlanmıştır.

Sistem; müşteri, garson, ürün ve sipariş kavramlarını sınıflar aracılığıyla ilişkilendirerek sipariş oluşturma ve fiş çıktısı üretme süreçlerini simüle eder.

## Proje Amacı

Bu projenin amacı:

Java ile nesne yönelimli programlama pratiği yapmak

Gerçek dünya senaryosunu sınıf yapılarıyla modellemek

Sınıflar arası ilişki ve sorumluluk dağılımını göstermek

Dosya işlemleri ile sipariş çıktısı oluşturmak

## Kullanılan Teknolojiler ve Kavramlar

Java

OOP (Object Oriented Programming)

Sınıf ve nesne yapısı

Kapsülleme (Encapsulation)

Kalıtım (Inheritance)

Metot organizasyonu

ArrayList koleksiyonu

Rastgele veri üretimi (Random)

Dosya yazma işlemleri (FileWriter, PrintWriter)

Exception handling (try-catch)

## Sistem Yapısı

Sistem aşağıdaki temel sınıflardan oluşmaktadır:

Kisi.java
Temel kişi özelliklerini tanımlar.

Musteri.java
Müşteri davranışlarını temsil eder.

Garson.java
Garson işlemlerini modelleyen sınıf.

Urun.java
Temel ürün sınıfı.

Yemek.java
Yemek türündeki ürünleri temsil eder.

Icecek.java
İçecek türündeki ürünleri temsil eder.

Siparis.java
Sipariş bilgilerini tutar (ürün, müşteri, garson, tarih, sipariş numarası).

Restoran.java
Menü, müşteri ve garson yönetimini sağlar ve sipariş oluşturma işlemini gerçekleştirir.

Test.java
Programın başlangıç noktasıdır (main metodu).

## Program Akışı

Restoran sistemi oluşturulur.

Menüye ürünler eklenir.

Garson ve müşteri listeleri oluşturulur.

Rastgele müşteri ve garson seçilerek sipariş oluşturulur.

Sipariş bilgileri ekrana yazdırılır.

Sipariş bilgisi otomatik olarak "Siparisler" klasörüne metin dosyası olarak kaydedilir.

## Derleme ve Çalıştırma

Proje klasöründe aşağıdaki komutları çalıştırın.

Derleme:

javac *.java

Çalıştırma:

java Test

Siparişler otomatik olarak "Siparisler" klasörü altında oluşturulan .txt dosyalarına yazılır.

## Teknik Detaylar

Menü, müşteri ve garson verileri ArrayList yapısı ile tutulmaktadır.

Sipariş oluşturma işlemi Random sınıfı ile dinamik hale getirilmiştir.

Her sipariş için ayrı bir dosya oluşturularak çıktı alınmaktadır.

Dosya işlemleri sırasında hata yönetimi için try-catch mekanizması kullanılmıştır.

Sınıflar arası ilişki, gerçek restoran senaryosuna uygun şekilde modellenmiştir.

Geliştirme Önerileri

Sipariş numarasının merkezi bir sayaç ile yönetilmesi

Sipariş geçmişi listeleme özelliği

Stok kontrol sistemi

Dosyadan veri okuma (kalıcı veri yönetimi)

Grafiksel kullanıcı arayüzü (Swing / JavaFX)

Katmanlı mimariye geçiş (Service ve Repository yapısı)




## Geliştirici

Tuğba Çevik
