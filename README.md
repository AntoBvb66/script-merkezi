# 🏰 TW Script Center / TW Script Merkezi

🌍 **[English](#english)** | 🇹🇷 **[Türkçe](#türkçe)**

---

<a id="english"></a>
## 🌍 English

**TW Script Center** is an advanced, React-based web application designed to provide powerful analysis and visualization tools for Tribal Wars (Klanlar) players. 

> **⚠️ Disclaimer:** This project is developed strictly for **informational and analytical purposes**. It is an independent tool and is not officially affiliated with InnoGames. 
> 
> **🛑 Server Friendly (1-Hour Cache):** To respect the game's servers and prevent unnecessary load, this application utilizes a strict **1-hour local caching mechanism**. When world data (`village.txt`, `player.txt`, `ally.txt`) is fetched, it is stored in your browser. Any subsequent requests within the next hour will load instantly from the cache without pinging the game servers.

### ✨ Features

* **⏱️ Building Times Calculator:** * Calculate exact building completion times based on World Speed and HQ Level.
  * Features an interactive, drag-and-drop table column system to customize your view.
* **📍 Teleport & Continent Analysis:**
  * Tracks player movements and detects exact "Teleportation" events by comparing old and new coordinates.
  * Groups teleports by target continents and visually draws the movement paths on a dynamic canvas map.
  * Includes a manual data entry and archiving system for historical comparisons.
* **🗺️ Advanced Map Generator:**
  * A highly customizable map rendering engine similar to TWStats.
  * Automatically assigns visually distinct (Golden Angle HSL) colors to tribes situated close to each other.
  * Calculates the **Center of Mass** for tribes/players to place highly readable tags (with dark stroke/shadows) exactly where their village density is highest.
  * Features smart autocomplete for player searches and automatic point-based sorting for tribes.

### 🛠️ Technical Stack
* **Frontend:** React.js, React Router (HashRouter for static hosting)
* **Storage:** Browser LocalStorage for settings, archives, and 1-hour data caching.

---

<a id="türkçe"></a>
## 🇹🇷 Türkçe

**TW Script Merkezi**, Klanlar (Tribal Wars) oyuncuları için güçlü analiz ve görselleştirme araçları sunmak amacıyla tasarlanmış, React tabanlı gelişmiş bir web uygulamasıdır.

> **⚠️ Yasal Uyarı:** Bu proje tamamen **bilgi vermek ve istatistiksel analiz yapmak** amacıyla geliştirilmiştir. Bağımsız bir araçtır ve InnoGames ile resmi bir bağlantısı yoktur.
>
> **🛑 Sunucu Dostu (1 Saatlik Önbellek):** Oyun sunucularını yormamak ve gereksiz trafik yaratmamak adına bu uygulama katı bir **1 saatlik önbellek (cache) sistemi** kullanır. Dünya verileri (`village.txt`, `player.txt`, `ally.txt`) çekildiğinde tarayıcınıza kaydedilir. Sonraki 1 saat içindeki tüm işlemleriniz, oyun sunucularına istek atmadan doğrudan tarayıcınızın hafızasından şimşek hızında gerçekleşir.

### ✨ Özellikler

* **⏱️ Bina Süreleri Hesaplayıcı:** * Dünya Hızı ve Ana Bina seviyesine göre kesin inşaat sürelerini hesaplar.
  * Sütunların yerini sürükle-bırak (drag & drop) yöntemiyle değiştirebileceğiniz interaktif bir tabloya sahiptir.
* **📍 Işınlanma ve Kıta Analizi:**
  * Oyuncu hareketlerini takip eder ve eski/yeni koordinatları karşılaştırarak "Işınlanma" (Teleport) olaylarını tam olarak tespit eder.
  * Işınlanmaları hedef kıtalara göre gruplar ve harita üzerinde hareket yönlerini çizgilerle çizer.
  * Geçmiş verileri saklamak ve karşılaştırmak için manuel giriş ve arşivleme sistemi içerir.
* **🗺️ Gelişmiş Harita Oluşturucu:**
  * TWStats benzeri, tamamen özelleştirilebilir bir harita çizim motoru.
  * Yan yana olan klanların haritada birbirine karışmaması için zıt renkleri (Altın Açı HSL algoritması) otomatik olarak atar.
  * Klanların ve oyuncuların **Ağırlık Merkezini (Center of Mass)** hesaplayarak, klan isimlerini (okunabilir dış gölge ile birlikte) tam olarak yoğunluğun en yüksek olduğu noktaya basar.
  * Oyuncu aramaları için akıllı otomatik tamamlama (autocomplete) ve klanlar için puana göre otomatik sıralama özellikleri sunar.

### 🛠️ Kullanılan Teknolojiler
* **Arayüz:** React.js, React Router (Statik yayın için HashRouter)
* **Veri Saklama:** Ayarlar, arşivler ve 1 saatlik veri önbelleği (cache) için Browser LocalStorage.
