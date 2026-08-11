<center>

# LEMBAR KERJA PESERTA DIDIK

**JOB SHEET PRAKTIKUM PEMROGRAMAN WEB**<br>
**PERTEMUAN 2: DESIGN & DATA PLANNING**

</center>


**NAMA KELOMPOK** : SPEED <br>
**NAMA APLIKASI** : SPEED BICYCLE STORE <br>
**SEKTOR PRODUK** : [ ] Fashion/Thrifting  [ ] Kuliner  [ ] Gadget  [✓] Lainnya

**ANGGOTA TIM** :
1. Luthfi Malik Muayat (Project Manager)
2. Fiqri Abdullah & Alif Ferdiansyah (Front End)
3. Hans Muhamad & Yanuar Firdaus (Back End)

---

## TUGAS 1: PERANCANGAN USER FLOW (TUGAS BERSAMA TIM)

Gambarkan diagram alur kerja sistem kalian dari Buka Web hingga Transaksi Selesai. Pastikan memenuhi ketentuan berikut:

- [x] Menggunakan notasi baku *Flowchart* (Terminator, Process, Decision, Data).
- [x] Memiliki penanganan kondisi stok habis atau transaksi gagal (*Edge Cases*).
- [x] Alur bersifat efisien (tidak memaksa pembeli mengisi data yang tidak penting).

*(Lampirkan Foto/Link Diagram pada Kolom di Bawah)*

**Link / Dokumen User Flow:** https://cdn.jsdelivr.net/gh/upiKerja/gjls@main/tempalte-workflow.drawio

## TUGAS 2: SPEC DETAIL BASIS DATA (TUGAS BACKEND DEVELOPER)

<center>
<img src="https://cdn.jsdelivr.net/gh/upiKerja/gjls@main/Screenshot%202026-08-11%20113029.png"/>
</center>

## TUGAS 3: LOW-FIDELITY WIREFRAME (TUGAS UI/UX DESIGNER)

Selesaikan perancangan kerangka halaman pada platform Figma. Pastikan memenuhi kriteria *checklist* berikut:

- [x] Dibuat pada Frame Desktop (1440 × 1024 px) atau Mobile (390 × 844 px).
- [x] **TIDAK MENGGUNAKAN WARNA BRAND** (Hanya Hitam, Putih, dan Abu-abu).
- [x] Halaman Katalog memiliki Search Bar dan Filter Kategori/Harga.
- [x] Halaman Detail Produk memiliki penjelas fitur spesifik toko kalian.
- [x] Halaman Checkout memiliki rincian komponen biaya yang transparan.

## TUGAS 4: MATRIKS VERIFIKASI DOKUMEN (TUGAS PROJECT MANAGER)

Lakukan pengecekan kesesuaian antara Tampilan UI dan Kolom Basis Data Backend:

| Komponen di Layar UI/UX | Kolom Database di Backend (Tabel.Kolom) | Status (Sesuai / Belum) |
|---|---|---|
| Contoh: Tombol Beli / Harga Produk | `products.price` | Sesuai |
| 1. Input Alamat Pengiriman | `addresses` | Belum |
| 2. Pilihan Kurir Pengiriman | `shipments` | Belum|
| 3. Fitur Khusus Produk Toko | `products` | Sesuai |
| 4. Total Biaya Akhir | `carts`, `products.price` | Sesuai |
