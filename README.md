# 🦇 Batak: Bir Dönüş Hikayesi

![Unity](https://img.shields.io/badge/Unity-2022.3+-black?logo=unity)
![C#](https://img.shields.io/badge/C%23-7.3-blue?logo=c-sharp)
![Platform](https://img.shields.io/badge/Platform-Mobile-green)
![Status](https://img.shields.io/badge/Status-In--Development-yellow)

**Batak**, retro pixel art estetiğiyle modern hikaye anlatıcılığını birleştiren, 2D hikaye odaklı bir mobil aksiyon-macera oyunudur. Eski bir askerin, dostunu kurtarmak için suçun kalbine yaptığı yolculuğu konu alır.

---

## 📖 Hikaye

**Bekir**, savaşın travmalarını beyaz önlüğünün altına gizlemeye çalışan eski bir askeri doktordur. Sıradan bir nöbet gecesinde, eski silah arkadaşı **Yavuz**'un kanlar içinde acile gelmesiyle hayatı altüst olur. Yavuz, mafya tarafından kaçırılıp polisin bile giremediği, her katında farklı bir suçun işlendiği **"Batak"** adlı binaya götürülür.

Bekir için bu sadece bir kurtarma operasyonu değil; geçmişteki çaresizlikleriyle yüzleşme ve bir kefaret yolculuğudur.

> "Eğer oraya polis giremiyorsa, ben girerim!"

---

## 🛠️ Teknik Özellikler & Mimari

Bu proje, ölçeklenebilir ve sürdürülebilir bir oyun geliştirme süreci için **Modüler Kod Mimarisi** üzerine inşa edilmiştir.

* **Universal Cutscene Player:** Tek bir sahne ve script üzerinden yönetilen, çok dilli (Localization-Ready) ara sahne sistemi.
* **Global State Management:** `GameManager` üzerinden yönetilen, sahneler arası veri taşıyan merkezi durum yönetimi.
* **Localization Support:** Gelecekteki dil seçeneklerine uygun, anahtar tabanlı (Key-based) metin sistemi.
* **Combat & Investigation:** Çatışma modu ve olay yeri inceleme modu arasında dinamik geçişler sağlayan durum makineleri.
* **Persistence:** JSON tabanlı, ilerlemeyi ve dünya durumunu kaydeden `SaveManager` sistemi.

---

## 🎮 Oynanış Mekanikleri

* **Sinematik Geçişler:** Yumuşak kararma (Fade-in/out) efektleriyle desteklenen hikaye anlatımı.
* **Stratejik Çatışma:** Sınırlı kaynaklar ve askeri disiplinle harmanlanmış aksiyon sahneleri.
* **Katmanlı Bölüm Tasarımı:** Her katın kendine has bir atmosferi, suçu ve zorluğu olduğu dikey ilerleme.

---


## 🎨 Görsel Stil

Oyunun görselleri **Pixel Studio** kullanılarak, karanlık ve "Noir" bir atmosfer yaratmak amacıyla 2D Pixel Art tarzında hazırlanmıştır.

---

## 👨‍💻 Geliştirici

**Yusuf Büyüktaş** *Yazılım Mühendisliği Öğrencisi @ Sakarya Üniversitesi* *Technical Artist & Game Developer*
**Umut Arda Ekiz** *Yazılım Mühendisliği Öğrencisi @ Sakarya Üniversitesi* *Game Developer*
---

## 📜 Lisans

Bu proje kişisel bir portfolyo çalışmasıdır. Tüm hakları saklıdır.
