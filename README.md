# 3D Anatomi Pro - İnteraktif Medikal Atlas 🩺

Bu proje, Three.js kütüphanesi kullanılarak geliştirilmiş, web tabanlı bir **3D İnteraktif Anatomi Atlası** uygulamasıdır. Kullanıcıların insan organlarını yüksek çözünürlüklü 3D modeller üzerinden detaylı bir şekilde incelemesine olanak tanır.

---

## 🌐 Canlı Önizleme (Live Demo)

Projeyi tarayıcınızda anlık olarak deneyimlemek için aşağıdaki bağlantıya tıklayabilirsiniz:
👉 **[samehmet00.github.io/3d_organlar](https://samehmet00.github.io/3d_organlar/)**

---

## 📸 Proje Görünümü

<img width="1512" height="950" alt="Ekran Resmi" src="https://github.com/user-attachments/assets/fde54302-8595-4c87-b56a-074fd0e42be4" />

---

## ✨ Özellikler

* **Geniş Organ Kütüphanesi:** Kalp, Akciğer, Karaciğer, Böbrek, Göz ve Kulak modelleri.
* **İnteraktif Kontroller:** Fare ile 360 derece döndürme, yakınlaştırma (Zoom) ve kaydırma.
* **X-Ray Modu:** Tek tuşla organları şeffaflaştırarak iç yapıları inceleme imkanı.
* **Dinamik Etiketleme:** Fare ile organ parçalarının üzerine gelindiğinde otomatik isimlendirme.
* **Gerçekçi Animasyonlar:** Kalp modeli için biyometrik ritme uygun atış animasyonu.
* **Akıllı Arama:** Menü üzerinden hızlı organ arama ve filtreleme.
* **Responsive Tasarım:** Modern, karanlık tema (Dark Mode) destekli ve her ekran boyutuna uygun arayüz.

---

## 🛠 Kullanılan Teknolojiler

* **Three.js:** 3D grafiklerin WebGL üzerinden render edilmesi.
* **JavaScript (ES6+):** Uygulama mantığı ve interaktif özellikler.
* **HTML5 & CSS3:** Modern arayüz tasarımı ve Glassmorphism efektleri.
* **GLTF/GLB:** Optimize edilmiş 3D model formatları.

---

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınızda çalıştırmak için şu adımları izleyin:

1.  Bu depoyu klonlayın:
    ```bash
    git clone [https://github.com/samehmet00/3d_organlar.git](https://github.com/samehmet00/3d_organlar.git)
    ```
2.  Proje klasörüne gidin:
    ```bash
    cd 3d_organlar
    ```
3.  3D modellerin (GLB) tarayıcıda düzgün yüklenmesi için bir yerel sunucu kullanmanız gerekir. 
    * **VS Code** kullanıyorsanız, `Live Server` eklentisini kurun ve `index.html` dosyasını "Go Live" ile açın.

---

## 📖 Kullanım Klavuzu

1.  **Organ Seçimi:** Sol menüden incelemek istediğiniz organa tıklayın.
2.  **İnceleme:** Sol tık ile döndürün, tekerlek ile yakınlaşın.
3.  **Bilgi:** Fare imlecini organın farklı kısımları üzerinde gezdirerek bölge isimlerini görün.
4.  **X-Ray:** Alt bardaki butonu kullanarak katmanlar arası geçiş yapın.

---


**Geliştiren:** [samehmet00](https://github.com/samehmet00)
