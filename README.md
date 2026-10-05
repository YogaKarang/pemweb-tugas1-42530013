# ValoMarket - Responsive Landing Page

Tugas 1 (T-01) Pemrograman Web: Rancang Bangun Responsive Landing Page Berbasis Dokumen Semantik HTML5 dan Tata Letak CSS Modern.

- **Tema:** B - Katalog Produk Digital
- **NIM:** 42530013
- **Live preview:** https://YogaKarang.github.io/pemweb-tugas1-42530013/
- **Repositori:** https://github.com/YogaKarang/pemweb-tugas1-42530013

## Deskripsi

ValoMarket adalah landing page fiktif marketplace akun Valorant. Halaman ini dibuat untuk keperluan tugas kuliah dan tidak berafiliasi dengan Riot Games.

## Fitur

- Header dengan navigasi internal (Fitur, Katalog, Testimoni, Kontak)
- Hero berisi proposisi nilai dan tombol CTA
- Fitur unggulan: pengiriman instan, garansi anti-hackback, full data access
- Katalog 3 paket akun (Smurf, Skin Starter, Sultan) dengan tombol "Beli Sekarang"
- Aside fakta penjualan, 2 testimoni pembeli, dan footer kontak

## Teknis

- HTML5 semantik tanpa div: `header`, `nav`, `main`, 4 `section` tematik, `article`, `aside`, `footer`
- Hierarki heading runtut (h1, h2, h3), `alt` deskriptif pada semua gambar, `aria-label="Navigasi Utama"` pada navigasi dan `aria-label` pada tautan
- CSS murni tanpa framework: reset `box-sizing`, variabel CSS di `:root`, Flexbox (navigasi, tombol, ikon), CSS Grid `repeat(auto-fit, minmax(280px, 1fr))` (kartu)
- Bebas scrollbar horizontal di 320px - 1920px (diuji; `body` juga diberi `overflow-x: hidden` sebagai jaring pengaman)
- Mobile-first dengan breakpoint `min-width: 768px` (tablet) dan `min-width: 1024px` (desktop, `max-width` + `margin auto`)

## Struktur Direktori

```
pemweb-tugas1-42530013/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   │   └── hero-valomarket.jpg
│   └── icons/
│       ├── icon-email.svg
│       ├── icon-shield.svg
│       └── icon-key.svg
└── README.md
```

## Menjalankan

Buka `index.html` di browser, atau aktifkan GitHub Pages lewat Settings → Pages.
