# Atlas Rota — HTML & CSS Hata Avı Projesi

Bu proje, HTML ve CSS temellerini pekiştirmek amacıyla hazırlanmış bir **butik seyahat stüdyosu tanıtım sitesidir.**

Site, ilk bakışta tamamlanmış ve profesyonel bir web sitesi görünümündedir. Ancak kaynak kodlarına bilerek çeşitli HTML ve CSS hataları eklenmiştir. Projenin amacı, bu hataları tespit etmek, nedenlerini anlamak ve doğru şekilde düzelterek web geliştirme becerilerini geliştirmektir.

---

## 🎬 Proje Tanıtım Videosu

Aşağıdaki videodan Atlas Rota web sitesinin genel görünümünü ve sayfa içerisindeki bölümleri inceleyebilirsin.

https://github.com/user-attachments/assets/b65e0efd-b7bc-4919-b6e5-d8ae3e25fdbe

[![Atlas Rota - Proje Tanıtım Videosu](https://img.shields.io/badge/▶_Projeyi_İzle-Video-red?style=for-the-badge)](VIDEO_LINKINI_BURAYA_EKLE)

---

## 1. Kullanılan Teknolojiler

| Teknoloji | Kullanım Amacı |
|---|---|
| **HTML5** | Sayfanın yapısını ve içeriğini oluşturmak için kullanıldı. `header`, `section`, `article` ve `footer` gibi semantik etiketlerle erişilebilir ve anlamlı bir HTML yapısı oluşturuldu. |
| **CSS3** | Renk, tipografi, sayfa düzeni ve responsive tasarım özelliklerini oluşturmak için kullanıldı. Grid ve Flexbox ile sayfa yerleşimi sağlandı. |
| **Google Fonts** | Fraunces, Work Sans ve JetBrains Mono fontları kullanılarak tipografik hiyerarşi oluşturuldu. Fraunces başlıklarda, Work Sans gövde metinlerinde, JetBrains Mono ise küçük etiketlerde ve rota kodlarında tercih edildi. |
| **Unsplash** | Profesyonel ve yüksek çözünürlüklü seyahat fotoğrafları kullanmak amacıyla görseller doğrudan URL üzerinden projeye dahil edildi. |

**Not:** Projede Bootstrap veya Tailwind gibi herhangi bir CSS framework'ü kullanılmadı. Amaç, saf HTML ve CSS kullanarak web geliştirme becerilerini pekiştirmektir.

---

## 2. Proje Klasör Yapısı

Proje, sade ve anlaşılır bir dosya yapısıyla oluşturulmuştur.

```text
atlas-rota/
├── index.html          # Sayfanın HTML yapısı ve içeriği
├── css/
│   └── style.css       # Tüm CSS stilleri
└── README.md           # Proje açıklamaları ve kullanım rehberi
```

Proje tek sayfalı (single-page) bir web sitesi olarak tasarlanmıştır. Sayfadaki bölümler `index.html` dosyası içerisinde ayrı `id` değerleriyle tanımlanmıştır:

- `#anasayfa`
- `#hakkimizda`
- `#rotalar`
- `#yorumlar`
- `#iletisim`

Navigasyon menüsündeki bağlantılar, ilgili bölümlere yönlendirme yapar.

CSS kodları tek bir dosyada (`style.css`) tutulmuş ve okunabilirliği artırmak amacıyla bölümlere ayrılmıştır:

- NAVBAR
- HERO
- ABOUT
- ROTALAR
- YORUMLAR
- İLETİŞİM
- FOOTER

Ayrıca dosyanın en üstünde `:root` seçicisi içerisinde renk ve font değişkenleri (CSS Custom Properties) tanımlanmıştır. Böylece proje genelindeki renk ve font değerleri tek bir noktadan kolayca yönetilebilir.

---

## 3. Nasıl Başlanır? — Adım Adım

Projeyi çalıştırmak ve hata avına başlamak için aşağıdaki adımları takip edebilirsin:

1. **Projeyi indir:** GitHub deposundan `Code → Download ZIP` seçeneğiyle projeyi indir veya `git clone` komutuyla bilgisayarına klonla.
2. **Projeyi aç:** İndirdiğin klasörü Visual Studio Code gibi bir kod editöründe aç.
3. **HTML dosyasını çalıştır:** `index.html` dosyasını tarayıcıda aç. VS Code kullanıyorsan Live Server eklentisinden yararlanabilirsin.
4. **Sayfayı incele:** Sayfada bazı bölümlerin yerleşiminin bozulduğunu, bazı buton ve etiketlerin stillerinin kaybolduğunu veya navigasyon menüsünün alt alta sıralandığını görebilirsin. Bunlar projeye bilerek eklenmiş hatalardır.
5. **Geliştirici araçlarını kullan:** Tarayıcıda sağ tıklayıp `İncele` seçeneğini kullanabilir veya `F12` tuşuna basabilirsin. Özellikle **Elements** ve **Console** sekmeleri, hataları tespit etmene yardımcı olacaktır.
6. **Hataları düzelt:** Tespit ettiğin hataları HTML ve CSS dosyalarında tek tek düzelt. Her değişiklikten sonra sayfayı yenileyerek sonucu kontrol et.
7. **Hataları belgele:** Bulduğun her hatayı, bulunduğu yeri ve nasıl düzelttiğini kısa notlar hâlinde kaydet. Bu listeyi `HATALAR.md` dosyasında paylaş.

### Hataları Ararken Nelere Dikkat Etmelisin?

**HTML Hataları**
- Kapatılmamış etiketler
- Yanlış veya eksik öznitelikler (`alt`, `name` vb.)
- Hatalı iç içe geçmiş HTML etiketleri
- Eksik tırnak işaretleri
- Yanlış kullanılan HTML etiketleri

**CSS Hataları**
- Yanlış yazılmış CSS özellikleri
- Eksik değer birimleri (`px`, `%`, `rem` vb.)
- Eksik noktalı virgüller
- Geçersiz renk kodları
- Kapatılmamış süslü parantezler (`{ }`)
- Yanlış seçiciler ve hatalı özellik değerleri

**Önemli:** Bazen tek bir CSS hatası, sayfanın büyük bir bölümünün görünümünü etkileyebilir. Bu nedenle her düzeltmeden sonra yalnızca ilgili bölümü değil, sayfanın tamamını kontrol etmen önerilir.

---

## 4. Teslim ve GitHub Paylaşımı

Hata düzeltme çalışmasını tamamladıktan sonra aşağıdaki dosyaları kendi GitHub deponda paylaş:

- `index.html` — Düzeltilmiş HTML dosyası
- `css/style.css` — Düzeltilmiş CSS dosyası
- `HATALAR.md` — Tespit edilen ve düzeltilen hataların listesi

`HATALAR.md` dosyasında her hata için aşağıdaki bilgileri belirtmen yeterlidir:

- **Hata:** Karşılaşılan problemin açıklaması.
- **Konum:** Hatanın bulunduğu dosya ve bölüm.
- **Çözüm:** Yapılan düzeltme ve kısa açıklaması.

---

**Kolay gelsin, iyi avlar! 🧭**
