# Panduan Praktis ERPNext

**Akuntansi Manufaktur dari Instalasi hingga Laporan Keuangan**
Studi Kasus PT Kopi Merapi Nusantara

| | |
|---|---|
| Penulis Pertama | Theresya Chesilya (NIM 12030122130157) |
| Penulis Kedua | Dr. Totok Dewayanto, S.E., M.Si., Akt., CA. |
| Mata Kuliah | Enterprise Resource Planning |
| Institusi | Program Studi Akuntansi, Fakultas Ekonomika dan Bisnis, Universitas Diponegoro |
| Tahun | 2026 |

## Unduh E-book

📘 **[Panduan Praktis ERPNext_Theresya Chesilya.pdf](Panduan%20Praktis%20ERPNext_Theresya%20Chesilya.pdf)** (48 halaman)

Versi web: folder [`ebook/`](ebook/index.html).

## Isi Buku

1. Mengenal ERP dan ERPNext
2. Instalasi ERPNext dengan Docker
3. Pengaturan Awal Perusahaan
4. Chart of Accounts Manufaktur
5. Entry Data Master
6. Studi Kasus PT Kopi Merapi Nusantara
7. Petunjuk Pengerjaan Soal
8. Memeriksa Hasil Pengerjaan
9. Skema Pelaksanaan Pengerjaan
10. Pemecahan Masalah

## Ringkasan Studi Kasus

PT Kopi Merapi Nusantara mengolah biji kopi hijau arabika menjadi kopi bubuk kemasan 250 g. Empat belas transaksi September 2026 (modal, pembelian bahan, produksi 500 bungkus dengan Work Order, penjualan 300 bungkus, pembayaran, beban, dan penyusutan) dikerjakan di ERPNext v16.

| Hasil | Nilai |
|---|---|
| Total mutasi Trial Balance (debit = kredit) | Rp512.700.000 |
| Laba bersih September 2026 | Rp5.700.000 |
| Total aset 30 September 2026 | Rp315.700.000 |
| Nilai persediaan akhir | Rp15.100.000 |

## Berkas Pendukung

- `COA_PT Kopi Merapi Nusantara.xlsx`: Chart of Accounts manufaktur (32 akun) siap diimpor lewat **Chart of Accounts Importer**.

## Lingkungan

ERPNext v16.50.0 dijalankan dengan Docker melalui repositori resmi [frappe_docker](https://github.com/frappe/frappe_docker) (`pwd.yml`).
