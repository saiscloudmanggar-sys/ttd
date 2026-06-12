# TTD PDF V3.2

Aplikasi berbasis HTML untuk menambahkan tanda tangan digital ke dokumen PDF secara offline melalui browser tanpa instalasi software tambahan.

## Fitur

* Membuat tanda tangan langsung di browser
* Pilihan warna tinta:
  * Hitam
  * Biru Tua 1
  * Biru Tua 2
  * Emas
  * Emas Tua
  * Putih
  * Putih Abu
  * 
* Pilihan gaya pena:
  * Pulpen
  * Tinta
    
* Crop otomatis area tanda tangan
* Tempel tanda tangan ke PDF
* Geser dan ubah ukuran tanda tangan
* Multi halaman PDF
* Login pengguna menggunakan PIN
* Verifikasi identitas penandatangan
* Simpan hasil PDF dengan format:
  `nama_file_asli_ttd.pdf`

## Cara Penggunaan

### 1. Login

Masukkan PIN yang telah terdaftar.

Setelah login berhasil, identitas penandatangan akan otomatis dimuat dari database Google Sheet.

### 2. Buat Tanda Tangan

* Pilih warna tinta.
* Pilih jenis pena.
* Buat tanda tangan pada area yang tersedia.
* Klik **Buat PNG TTD**.

### 3. Buka PDF

* Klik **Pilih File PDF**.
* Pilih dokumen PDF yang akan ditandatangani.

### 4. Tempel Tanda Tangan

* Klik dua kali pada posisi yang diinginkan di halaman PDF.
* Geser untuk memindahkan tanda tangan.
* Tarik sudut kanan bawah untuk mengubah ukuran.

### 5. Simpan PDF

Klik **Simpan PDF**.

File hasil akan otomatis diunduh dengan nama:

`nama_file_asli_ttd.pdf`

## Informasi Penandatangan

Setiap dokumen yang ditandatangani akan menyimpan informasi:

* User ID
* Nama
* Instansi
* Jabatan
* Nomor Pegawai
* Tanggal dan waktu penandatanganan

## Verifikasi Dokumen

Klik tombol **Verifikasi Penandatangan** untuk memeriksa data identitas yang tersimpan pada PDF.

## Teknologi yang Digunakan

* HTML5
* JavaScript
* PDF.js
* PDF-Lib
* Google Apps Script
* Google Sheets

## Catatan

Aplikasi ini berjalan sepenuhnya di browser dan tidak memerlukan instalasi software tambahan.

Disarankan menggunakan:

* Google Chrome
* Microsoft Edge
* Safari (iPhone/iPad)

## Versi

TTD PDF V3.2
