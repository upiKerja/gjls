# Utama 

```text
                    ┌──────────────────────┐
                    │   Pengunjung Masuk   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Lihat Katalog Produk │
                    └──────────┬───────────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
                ▼                             ▼
        Cari / Filter                  Detail Produk
                │                             │
                └──────────────┬──────────────┘
                               ▼
                     Tambah ke Keranjang
                               │
                               ▼
                    Lanjut Belanja?
                 ┌─────────┴─────────┐
                 │                   │
                Ya                 Tidak
                 │                   │
                 └───────┐      Checkout
                         │          │
                         ▼          ▼
                  Kembali Katalog  Login?
                                    │
                       ┌────────────┴────────────┐
                       │                         │
                     Belum                      Sudah
                       │                         │
                Login / Register                │
                       └────────────┬────────────┘
                                    ▼
                          Isi Alamat Pengiriman
                                    │
                                    ▼
                         Pilih Kurir & Layanan
                                    │
                                    ▼
                         Pilih Metode Pembayaran
                                    │
                                    ▼
                         Konfirmasi Pesanan
                                    │
                                    ▼
                       Menunggu Pembayaran
                                    │
                    ┌───────────────┴───────────────┐
                    │                               │
                 Gagal                          Berhasil
                    │                               │
                Pesanan Batal                 Verifikasi Admin
                                                    │
                                                    ▼
                                           Pesanan Diproses
                                                    │
                                                    ▼
                                            Packing Barang
                                                    │
                                                    ▼
                                            Dikirim Kurir
                                                    │
                                                    ▼
                                         Pesanan Diterima
                                                    │
                                                    ▼
                                            Beri Review
                                                    │
                                                    ▼
                                                  Selesai
```

# Admin

```text
              Pesanan Baru
                    │
                    ▼
         Verifikasi Pembayaran
                    │
          ┌─────────┴─────────┐
          │                   │
        Valid             Tidak Valid
          │                   │
          ▼                   ▼
   Kurangi Stok         Tolak Pesanan
          │
          ▼
   Cetak Invoice
          │
          ▼
   Packing Barang
          │
          ▼
 Input Nomor Resi
          │
          ▼
 Status → Dikirim
          │
          ▼
 Status → Selesai
```

# Manajemen Produk

```text
Admin
  │
  ▼
Tambah Produk
  │
  ▼
Input Nama Produk
  │
  ▼
Input Harga
  │
  ▼
Input Stok
  │
  ▼
Pilih Kategori
  │
  ▼
Upload Gambar
  │
  ▼
Publish
  │
  ▼
Produk Muncul di Website
```

# Arsitektur Logic

```text
        Customer
            │
            ▼
      Frontend Website
            │
            ▼
        REST API Server
            │
  ┌─────────┼───────────┐
  ▼         ▼           ▼
Auth     Product     Order
Service   Service    Service
  │         │           │
  └─────────┼───────────┘
            ▼
       PostgreSQL
            │
            ▼
     Storage Gambar
```
