# NYCA — Menu Digital (Food & Beverages)

Menu digital modern untuk **NYCA**, dibangun sebagai satu halaman web statis (tanpa build tools).

## ✨ Fitur

- **11 kategori** — 59 hidangan & 50 minuman
- **32 foto hidangan** dengan latar transparan, diekstrak langsung dari menu PDF resmi
- **Navigasi sticky + scrollspy** untuk menjelajah antar kategori
- **Tab filter minuman** — Kopi Susu, White, Black, Non Kopi, Refreshing Tea, Mocktail, Additional
- **Responsif** — nyaman dibuka di HP, tablet, hingga layar display/TV
- **Siap cetak** — `Ctrl+P` menghasilkan versi cetak yang rapi
- **Tanpa dependensi** — cukup buka `index.html` di browser

## 📁 Struktur

```
nyca-menu/
├── index.html        # Halaman menu (HTML + CSS + JS dalam satu file)
└── assets/           # 32 foto hidangan (WebP, latar transparan)
```

## ▶️ Menjalankan

Buka `index.html` langsung dengan double-click, atau jalankan server lokal:

```bash
python -m http.server 8000
# lalu buka http://localhost:8000
```

> Font (Fraunces & Plus Jakarta Sans) dimuat dari Google Fonts.
> Saat offline, font cadangan sistem akan digunakan dan tampilan tetap rapi.

## 📝 Catatan

- Foto & data menu bersumber dari **"NYCA Food Menu.pdf"** (menu resmi NYCA).
- Harga ditampilkan dalam format `K` (ribuan Rupiah), mengikuti menu asli.
- Beberapa ejaan dirapikan: *Cappuccino*, *Beef Black Pepper*.
