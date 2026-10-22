# Cash Moon ☾

Cash Moon adalah aplikasi pencatatan keuangan pribadi sederhana berbasis HTML, CSS, dan JavaScript. Aplikasi ini bisa dipublikasikan menggunakan GitHub Pages.

## Fitur

- Ringkasan saldo keseluruhan
- Pencatatan pemasukan melalui **Deposit**
- Pencatatan pengeluaran melalui **Withdraw**
- Pencatatan transfer beserta tujuan transfer
- Riwayat transaksi yang dapat difilter berdasarkan jenis dan bulan
- Grafik perbandingan pemasukan dan pengeluaran
- Penyimpanan lokal menggunakan `localStorage`
- Tampilan responsif untuk HP dan desktop

## Cara menjalankan secara lokal

1. Unduh atau ekstrak repository ini.
2. Buka `index.html` di browser modern.
3. Tambahkan transaksi melalui tombol Deposit, Withdraw, atau Transfer.

Tidak memerlukan instalasi paket atau build tools.

## Cara menerbitkan dengan GitHub Pages

1. Buat repository baru di GitHub.
2. Unggah `index.html` dan `README.md` ke **root** repository.
3. Buka **Settings → Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai. URL situs biasanya berbentuk `https://USERNAME.github.io/NAMA-REPOSITORY/`.

## Catatan penting

- Ini adalah aplikasi pencatatan keuangan **simulasi**, bukan layanan perbankan.
- Deposit, withdraw, dan transfer hanya mencatat transaksi; aplikasi tidak memindahkan uang sungguhan.
- Data disimpan di browser perangkat yang digunakan dengan `localStorage`. Data tidak otomatis tersinkronisasi antarperangkat.
- Menghapus data situs/browser dapat menghapus transaksi yang tersimpan. Buat cadangan sendiri bila diperlukan.
- Jangan masukkan kata sandi, nomor rekening, atau informasi finansial sensitif.

## Struktur file

```text
cash-moon/
├── index.html
└── README.md
```
