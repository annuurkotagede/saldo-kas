# Saldo Kas Takmir Masjid An-Nuur Kotagede

Halaman statis untuk menampilkan informasi saldo kas takmir.

## Struktur folder

```
saldo-kas/
├── index.html
├── css/
│   └── style.css
└── assets/
    ├── logo.svg     ← logo masjid
    └── wallet.svg   ← ikon kas
```

## Cara mengubah angka saldo atau tanggal update

Buka `index.html`, cari baris berikut lalu ubah isinya:

```html
<p class="balance-amount">Rp 18.690.208</p>
<p class="balance-updated">Diperbarui 26 September 2026</p>
```

## Cara upload ke GitHub & tayangkan lewat GitHub Pages

1. Buat repository baru di GitHub (public).
2. Upload seluruh isi folder ini (`index.html`, `css/`, `assets/`) lewat
   "Add file → Upload files", atau lewat git:
   ```bash
   git init
   git add .
   git commit -m "Saldo kas takmir"
   git branch -M main
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git push -u origin main
   ```
3. Buka **Settings → Pages**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Situs akan tayang di `https://USERNAME.github.io/NAMA-REPO/`.
