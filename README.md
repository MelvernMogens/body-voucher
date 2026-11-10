# Body Voucher

**Website interaktif: tap bagian tubuh karakter untuk membuka voucher hadiah.** Dibuat untuk merayakan selesainya UAS 💕.

Satu halaman HTML, tanpa backend — karakter mengambang dengan beberapa hotspot (kepala, wajah, tangan, perut, badan); setiap hotspot membuka kartu voucher dengan judul, deskripsi dan kode unik yang bisa disalin.

## Fitur
- 5 hotspot interaktif pada gambar karakter (`character.png`), masing-masing dengan warna, judul dan deskripsi sendiri.
- Kartu voucher animasi dengan kode voucher yang bisa di-copy (tombol "Copy").
- Latar belakang animasi di `<canvas>`.
- Didesain untuk layar HP (karakter mengambang, hint bar di bawah).

## Cara buka
Buka `index.html` langsung di browser, atau jalankan server statis:
```bash
python3 -m http.server 8000
```
lalu kunjungi `http://localhost:8000`.

## Deploy
GitHub Actions (`.github/workflows/static.yml`) men-deploy repo ini ke GitHub Pages setiap push ke `master`.

## Status
Proyek hadiah pribadi, selesai dan sudah di-deploy. Tidak ada rencana pengembangan lanjutan.

Dibuat oleh [Melvern Mogens](https://github.com/MelvernMogens).
