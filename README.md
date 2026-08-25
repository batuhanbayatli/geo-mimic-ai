# 🧬 GeoMimic AI // Evrimsel Görsel Rekonstrüksiyon Motoru
> **bGroup // bAI × DATEX Tasarım**  
> *Genetik Algoritmalar ve Stokastik Optimizasyon Kullanan İstemci Tabanlı (Client-Side) Evrimsel Sanat Motoru*

<p align="left">
  <a href="https://geo-mimic-ai.vercel.app/"><img src="https://img.shields.io/badge/Canlı%20Demo-Vercel-2563eb?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Canlı Demo"></a>
  <img src="https://img.shields.io/badge/Ecosystem-bGroup-0f172a?style=for-the-badge" alt="bGroup">
  <img src="https://img.shields.io/badge/Partners-bAI%20%C3%97%20DATEX%20Tasar%C4%B1m-7c3aed?style=for-the-badge" alt="Marka İş Birliği">
  <img src="https://img.shields.io/badge/Core-Genetic%20Algorithm-059669?style=for-the-badge" alt="Core Engine">
  <img src="https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge" alt="License">
</p>

---

## 📌 Proje Özeti

**GeoMimic AI**, herhangi bir kaynak hedef görüntüyü; **Genetik Algoritmalar (Genetic Algorithms)** ve **Stokastik Optimizasyon** ilkeleriyle, rastgele üretilen geometrik formlardan (poligonlar, daireler, dikdörtgenler, çizgiler) sıfırdan yeniden inşa eden tarayıcı tabanlı bir yapay zeka motorudur.

Klasik sinir ağlarının (Neural Network) aksine kapalı bir "Kara Kutu" (Black Box) sunmaz; mutasyon, doğal seçilim ve uygunluk (Fitness) fonksiyonunun kaostan düzene geçiş adımlarını canlı olarak görselleştirir.

---

## 🧠 Nasıl Çalışır? (Evrimsel Hesaplama)

1. **Popülasyon & Genom Başlatma:** Sistem rastgele koordinat, renk ve şeffaflığa sahip bir DNA (şekiller dizisi) üretir.
2. **Mutasyon:** Her iterasyonda bir şeklin rengi, saydamlığı veya köşe koordinatları rastgele değiştirilir.
3. **Fitness (Uygunluk) Testi:** Yeni çizim ile kaynak görsel arasındaki piksel farkı (Loss) $O(1)$ örnekleme ile hesaplanır.
4. **Doğal Seçilim:** Mutasyon hedef görsele daha çok benziyorsa (daha düşük kayıp) genom güncellenir; benzemiyorsa elenir.
5. **Döngü:** Bu süreç saniyede binlerce kez tekrarlanarak kaotik geometriden anlamlı bir sanat eseri türetilir.

---

## ✨ Öne Çıkan Özellikler

* 🎨 **Çoklu Sanat Stili:**
  * 🔺 **Low-Poly (Üçgenler):** Modern köşeli poligon sanatı.
  * ⚫ **Pointillism (Noktacılık):** Dairelerle estetik empresyonizm.
  * 🟥 **Kübizm (Dikdörtgenler):** Soyut geometrik kompozisyon.
  * ✏️ **Eskiz (Çizgiler):** Karakalem hissi veren çizgisel çizim.
* ⚡ **Turbo Donanım Optimizasyonu:** Web tarayıcısının gücünü kullanan çoklu mutasyon döngüsü.
* 🔒 **%100 İstemci Tabanlı (Client-Side):** Sıfır sunucu ve API maliyeti. Yüklenen görseller kullanıcının cihazından asla dışarı çıkmaz.
* 💾 **Yüksek Çözünürlüklü Dışa Aktarım:** Oluşturulan evrimsel eseri anında PNG olarak indirme desteği.

---

## 🛠️ Teknoloji Yığını

* **Arayüz / Tasarım:** Semantic HTML5, Tailwind CSS (Clean Light SaaS Design System)
* **Hesaplama & Çizim:** HTML5 Canvas API (willReadFrequently & Fast Pixel Sampling)
* **İkonografi:** Lucide Icons CDN
* **Algoritmik Motor:** Vanilla ES6+ JavaScript (Sıfır harici kütüphane bağımlılığı)
* **Dağıtım / CI-CD:** Vercel Edge Network

---

## 🚀 Yerel Kurulum ve Çalıştırma

```bash
# Repoyu klonlayın
git clone [https://github.com/batuhanbayatli/geo-mimic-ai.git](https://github.com/batuhanbayatli/geo-mimic-ai.git)

# Proje dizinine geçin
cd geo-mimic-ai

# index.html dosyasını tarayıcınızda açın veya canlı demoyu ziyaret edin:
# [https://geo-mimic-ai.vercel.app/](https://geo-mimic-ai.vercel.app/)
