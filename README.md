
# Java Dili Projesi – Restoran Sipariş Sistemi

Bu proje, **Java** programlama dili kullanılarak geliştirilmiş küçük ölçekli bir **restoran sipariş uygulamasıdır**.  
Uygulama, nesne yönelimli programlama (OOP) konseptlerini kullanarak konsol üzerinde sipariş alıp işleyen temel bir sistemdir.

---

## 📌 Projenin Amacı

Bu projenin amacı:

- Nesne yönelimli programlamayı uygulamalı olarak öğrenmek  
- Sınıf, kalıtım ve nesne ilişkilerini Java dilinde kurmak  
- Müşteri → Sipariş → Garson → Restoran akışını modellemek  
- Basit bir konsol uygulaması yazmaktır.

Projeyi kendi yazdım ve Java'nın temel kavramlarını öğrendikten sonra geliştirdim.

---

## 📂 Proje Dosyaları ve Sınıflar

### 👤 **Kisi.java**
Ortak kişi özelliklerini tutan temel sınıftır.  
Bu sınıf üzerinden kalıtım alan müşteri ve garson sınıfları türetilir.

---

### 🧑‍🍳 **Garson.java**
Müşteriden sipariş alma, siparişi işleme gibi görevleri temsil eden sınıftır.

---

### 🧍‍♂️ **Musteri.java**
Restoran ortamında sipariş verebilen kullanıcıyı temsil eder.

---

### 🍽️ **Urun.java**
Tüm ürünlerin ortak özelliklerini tutan temel sınıftır.  
Bundan türeyen ürünlerde farklı türde ürünler tutulur.

---

### 🍕 **yemek.java**
Urun sınıfından türeyen yemek türündeki ürünleri temsil eder.

---

### 🥤 **Icecek.java**
Urun sınıfından türeyen içecek türündeki ürünleri temsil eder.

---

### 🧾 **Siparis.java**
Bir müşterinin verdiği siparişi, içerisinde hangi ürünlerin olduğu ve toplam tutarı tutar.

---

### 🏪 **Restoran.java**
Sistemi kontrol eden sınıftır.  
Garson, müşteri ve sipariş nesnelerini bu sınıf içinde yönetir.

---

### ▶️ **Test.java**
Programın başlangıç noktasıdır (`main` metodu burada yer alır).  
Buradan tüm sistem çalıştırılır ve konsol üzerinden kullanıcı ile etkileşim sağlanır.

---

## 🔄 Program Akışı

1. `Test.java` çalıştırılır.
2. Restoran nesnesi oluşturulur.
3. Garson ve müşteri nesneleri tanımlanır.
4. Menüdeki yemek ve içecek ürünleri oluşturulur.
5. Müşteri bir sipariş verir.
6. Garson siparişi alır ve restoran aracılığıyla işlenir.
7. Sipariş özeti ve toplam tutar ekrana yazdırılır.

---

## 🧠 Kullanılan OOP Kavramları

Projede aşağıdaki nesne yönelimli programlama kavramları kullanılmıştır:

- **Class (Sınıf)**
- **Object (Nesne)**
- **Inheritance (Kalıtım)**
- **Encapsulation (Kapsülleme)**
- **Polymorphism (Çok Biçimlilik)**

---

## 🛠️ Derleme ve Çalıştırma

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 📌 Java dosyaları mevcutsa:

```bash
javac *.java
java Test
