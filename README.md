# Teknolojik Yemekler — Responsive Pizza Landing Page

Workintech HTML/CSS challenge kapsamında geliştirilen bu proje, verilen tasarım dili temel alınarak hazırlanmış statik bir yemek sipariş deneyimidir. Tasarım; semantic HTML, erişilebilir form yapısı, responsive yerleşim ve kontrollü CSS mikro etkileşimleriyle özelleştirilmiştir.

## Bağlantılar

- [GitHub Repository](https://github.com/MelisaOzgur/pizza-landing-page)
- [Uyarlanmış Final Figma](https://www.figma.com/design/FPMtzbKHVAoxZgMvoKpnLv/Teknolojik-Yemekler---Pizza-Landing-Page?node-id=39703-2)

## Öne Çıkan Özellikler

- Semantic HTML5 yapısı
- Mobile-first responsive tasarım
- CSS Grid ve Flexbox kullanımı
- CSS custom properties ile oluşturulan tasarım sistemi
- Klavye erişilebilirliği ve görünür focus stilleri
- `label`, `fieldset`, `legend` ve anlamlı alternatif metin kullanımı
- Özelleştirilmiş checkbox ve radio kontrolleri
- Hover, active ve giriş mikro etkileşimleri
- `prefers-reduced-motion` desteği
- Native form doğrulaması
- Statik sipariş başarı ve durum ekranı
- Masaüstü, tablet ve mobil kırılımlar

## Kullanılan Teknolojiler

- HTML5
- CSS3
- Vite
- npm

## Sayfalar

- `index.html`: Hero alanını, kategori ve kampanya bölümlerini, ürün kartlarını ve statik sipariş formunu içeren ana landing page.
- `success.html`: Belirli bir ürün veya dinamik sipariş verisi göstermeyen, statik sipariş onay ve durum ekranı.

## Kurulum ve Çalıştırma

Projeyi yerel ortamınıza klonlayın:

```bash
git clone https://github.com/MelisaOzgur/pizza-landing-page.git
cd pizza-landing-page
npm install
npm run dev
```

Üretim build'i oluşturmak için:

```bash
npm run build
```

## Proje Yapısı

```text
pizza-landing-page/
├── README.md          # Proje dokümantasyonu
├── index.html         # Landing page ve sipariş formu
├── success.html       # Statik sipariş onay ekranı
├── style.css          # Tasarım sistemi ve responsive stiller
├── vite.config.js     # Çok sayfalı üretim build yapılandırması
└── public/
    └── assets/        # Logo, ikon ve yemek görselleri
```

## Teknik Yaklaşım

Stiller mobile-first yaklaşımla oluşturulmuştur. Temel kurallar küçük ekranları hedefler; yaklaşık `768px` tablet ve `1024px` masaüstü breakpoint'leriyle çok sütunlu düzenlere geçilir.

CSS Grid; kampanya yerleşiminde, ürün kartlarında, form seçeneklerinde, footer bölümlerinde ve sipariş durum göstergesinde kullanılır. Flexbox ise hero içeriği, kategori navigasyonu, kart içi hizalamalar ve form kontrolleri gibi tek boyutlu düzenleri yönetir.

Renkler, tipografi, spacing değerleri, radius ölçüleri, gölgeler ve container genişlikleri `:root` altında CSS değişkenleriyle tanımlanır. Form elemanları semantic HTML yapısını ve klavye kullanımını korurken görünür `focus-visible` stilleriyle desteklenir. Hareket azaltma tercihi bulunan kullanıcılar için animasyon ve geçişler `prefers-reduced-motion` medya sorgusuyla etkisiz hale getirilir.

Vite, `index.html` ve `success.html` dosyalarını ayrı girişler olarak işleyen çok sayfalı bir production build oluşturacak şekilde yapılandırılmıştır.

## Statik Kapsam

Uygulama JavaScript mantığı içermez. Adet artırma ve azaltma butonları ile sipariş durum göstergesi, ödev kapsamına uygun olarak yalnızca görseldir. Form, tarayıcının native doğrulaması tamamlandıktan sonra `GET` yöntemiyle `success.html` sayfasına yönlenir. `vite.config.js` yalnızca build yapılandırmasıdır; uygulama davranışı eklemez.

## Tasarım ve Kaynaklar

Workintech tarafından sağlanan tasarımlar referans alınmış; final ekranlar projenin tamamlanan HTML/CSS uygulamasıyla uyumlu olacak şekilde uyarlanmıştır.

- [Workintech başlangıç deposu](https://github.com/Workintech/fsweb-s4-bonus-challenge-html-pizza)
- [Orijinal S6 Figma](https://www.figma.com/design/B6rGWNjWqVyvuB9htLyIMR/S6-Challange-v2.1)
- [S8 Pizza React Challenge referansı](https://www.figma.com/design/q0xPW5uCel3rdzFgpjR9lt/S8-Pizza-React-Challange-v2.1)
- [Uyarlanmış Final Figma](https://www.figma.com/design/FPMtzbKHVAoxZgMvoKpnLv/Teknolojik-Yemekler---Pizza-Landing-Page?node-id=39703-2)

## Geliştirici

Melisa Özgür

GitHub: [github.com/MelisaOzgur](https://github.com/MelisaOzgur)
