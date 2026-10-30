# Yangi O'zbek Alifbosi

> Yangi o'zbek lotin alifbosi harflarini tezkor nusxalash va matnlarni ikki tomonlama o'girish uchun yengil, bepul web-tool.

[![Live demo](https://img.shields.io/badge/Live%20demo-hexjasur.github.io-4f46e5?style=for-the-badge&logo=googlechrome&logoColor=white)](https://hexjasur.github.io/ozbek-yangi-alifbosi/)
[![GitHub stars](https://img.shields.io/github/stars/hexjasur/ozbek-yangi-alifbosi?style=for-the-badge&logo=github)](https://github.com/hexjasur/ozbek-yangi-alifbosi/stargazers)

## Nima qiladi?

Yangi alifbodagi maxsus belgilarni bir bosishda clipboard’ga nusxalaydi va eski yozuvni yangi yozuvga, shuningdek yangi yozuvni eski yozuvga avtomatik konvertatsiya qiladi:

- `O' o'` → `Ö ö`
- `G' g'` → `Ğ ğ`
- `Ch ch` → `Ç ç`
- `Sh sh` → `Ş ş`

## Imkoniyatlar

- Responsive, dark-first interfeys — telefon, planshet va desktop uchun.
- Katta-kichik harflar uchun tezkor copy tugmalari.
- Jonli qidiruvga ega to'liq alifbo grid’i.
- Ikki tomonlama konvertor, namuna matnlar va character count.
- Native Share API, GitHub repository CTA va real-time star count.
- Open Graph banner, Twitter Card, canonical URL, favicon va Schema.org JSON-LD.
- Hech qanday build step yoki framework talab qilmaydi: sof HTML, Tailwind CDN va JavaScript.

## Ishga tushirish

Repo’ni clone qiling va `index.html` faylini static server orqali oching:

```bash
git clone https://github.com/hexjasur/ozbek-yangi-alifbosi.git
cd ozbek-yangi-alifbosi
python3 -m http.server 8080
```

Keyin `http://localhost:8080` manziliga o'ting. `file://` orqali ham ochiladi, ammo clipboard API va GitHub star count uchun localhost yoki HTTPS tavsiya qilinadi.

## Tuzilishi

```text
.
├── assets/
│   ├── brand-mark.png   # favicon, app icon va header logotipi
│   ├── hero-banner.png  # landing page hero background
│   └── og-banner.png    # social sharing preview
├── index.html
├── robots.txt
└── sitemap.xml
```

## Litsenziya

Ochiq manbali loyiha. Taklif va pull request’lar mamnuniyat bilan qabul qilinadi.
