# Tutorial Penggunaan Mataplot

**MATAPLOT** adalah aplikasi web untuk menggambar **plot tata cahaya** (lighting plot) pertunjukan langsung di browser. Kamu meletakkan lampu di denah panggung, mengatur ukuran panggung dan tampilan, mengisi blok judul, lalu mengekspor gambar sebagai PNG, PDF, atau SVG.

- Alamat aplikasi: <https://mataxmedia.github.io/mataplot/>
- Pembuat: Mataxmedia (dibuat dengan bantuan Claude)
- Versi: v.0.1

> **Catatan:** Tutorial ini disusun dari struktur dan label yang tampil di halaman aplikasi. Nama persis beberapa tombol atau jenis lampu bisa sedikit berbeda karena aplikasi masih berkembang. Bagian yang bersifat dugaan diberi tanda *(cek di aplikasi)*.

---

## Daftar Isi

1. [Gambaran Antarmuka](#1-gambaran-antarmuka)
2. [Memulai: Contoh atau Proyek Baru](#2-memulai-contoh-atau-proyek-baru)
3. [Mengatur Panggung](#3-mengatur-panggung)
4. [Menempatkan Lampu](#4-menempatkan-lampu)
5. [Mengedit Lampu (Properti)](#5-mengedit-lampu-properti)
6. [Pengaturan Tampilan](#6-pengaturan-tampilan)
7. [Tulisan Belakang dan Tepi Panggung](#7-tulisan-belakang-dan-tepi-panggung)
8. [Lembar Gambar (Blok Judul)](#8-lembar-gambar-blok-judul)
9. [Menyimpan dan Membuka Proyek](#9-menyimpan-dan-membuka-proyek)
10. [Ekspor: PNG, PDF, SVG](#10-ekspor-png-pdf-svg)
11. [Alur Kerja yang Disarankan](#11-alur-kerja-yang-disarankan)
12. [Tips dan Pemecahan Masalah](#12-tips-dan-pemecahan-masalah)
13. [Ringkasan Cepat](#13-ringkasan-cepat)

---

## 1. Gambaran Antarmuka

Antarmuka terdiri dari beberapa area:

| Area | Fungsi |
|---|---|
| **Bilah atas** | Tombol *Urungkan*, *Ulangi*, *Baru*, *Contoh*, *Simpan proyek*, *Buka proyek* |
| **Alat** | Alat untuk memilih dan memanipulasi objek di kanvas |
| **Lampu** | Daftar jenis lampu yang bisa diletakkan, plus kolom kustom nama jenis lampu |
| **Panggung** | Ukuran panggung, penguncian grid, serta opsi tampilan |
| **Kanvas** | Denah panggung tempat lampu diletakkan |
| **Bilah status** | Tombol zoom (`+`, `−`, `▣`) dan info *Posisi*, *Lampu*, *Bottom* |
| **Properti** | Pengaturan objek/lampu yang sedang dipilih |
| **Lembar gambar** | Isi blok judul: judul pertunjukan, tempat, penata cahaya, tanggal, nomor gambar |
| **Ekspor** | Resolusi, ukuran kertas, dan tombol unduh |

---

## 2. Memulai: Contoh atau Proyek Baru

Ada dua cara memulai.

### a. Mencoba lewat Contoh
1. Klik **Contoh** di bilah atas.
2. Aplikasi memuat denah contoh lengkap dengan lampu.
3. Pelajari cara lampu ditata, lalu ubah sesuai kebutuhan.

Ini cara tercepat untuk memahami hasil akhir yang bisa dibuat.

### b. Membuat dari nol
1. Klik **Baru** untuk mengosongkan kanvas.
2. Atur ukuran panggung ([bagian 3](#3-mengatur-panggung)).
3. Mulai meletakkan lampu ([bagian 4](#4-menempatkan-lampu)).

### Urungkan dan Ulangi
- **Urungkan**: membatalkan aksi terakhir (misalnya salah menaruh lampu).
- **Ulangi**: mengembalikan aksi yang baru saja diurungkan.

---

## 3. Mengatur Panggung

Buka bagian **Panggung** untuk menyesuaikan denah dengan panggung aslimu.

| Pengaturan | Penjelasan |
|---|---|
| **Lebar (m)** | Lebar panggung dalam meter |
| **Kedalaman (m)** | Kedalaman panggung (dari depan ke belakang) dalam meter |
| **Kunci ke grid** | Membuat posisi lampu "menempel" ke titik grid. Pilihan: **Mati**, **0,1 m**, **0,25 m**, **0,5 m**, **1 m** |
| **Ukuran grid (m)** | Jarak antar garis grid yang ditampilkan |
| **Ukuran ikon (semua lampu)** | Memperbesar atau memperkecil ikon semua lampu sekaligus |

### Cara memilih kunci grid
- **Mati**: lampu bisa diletakkan bebas di mana saja.
- **1 m / 0,5 m**: cocok untuk denah kasar dan rapi.
- **0,25 m / 0,1 m**: cocok bila perlu penempatan presisi.

> **Tip:** Sesuaikan *Ukuran grid* dengan skala panggung. Panggung 12 × 8 m nyaman dengan grid 1 m, sedangkan panggung kecil lebih enak dengan 0,5 m.

---

## 4. Menempatkan Lampu

Petunjuk di aplikasi: *"Klik jenis lampu lalu klik di kanvas, atau seret ikonnya ke kanvas."*

### Cara 1: Klik lalu klik
1. Di bagian **Lampu**, klik jenis lampu yang diinginkan.
2. Klik titik di kanvas tempat lampu diletakkan.
3. Ulangi untuk lampu berikutnya.

### Cara 2: Seret dan lepas (drag & drop)
1. Tekan dan tahan ikon jenis lampu.
2. Seret ke kanvas.
3. Lepaskan di posisi yang diinginkan.

### Menempel otomatis ke bottom
Lampu yang diletakkan **dekat garis bottom** akan **otomatis menempel** ke garis tersebut. Berguna untuk menata lampu pada *bottom* (batang gantung lampu) tanpa harus mengejar posisi yang presisi.

### Kustom nama jenis lampu
Ada kolom **Kustom nama jenis lampu** *(cek di aplikasi untuk letak dan perilakunya)*. Gunakan untuk memberi nama jenis lampu sesuai inventaris, misalnya "Par LED 54", "Fresnel 1K", atau "Moving Head Spot".

### Memindahkan dan mengatur lampu
- Pilih lampu di kanvas, lalu seret untuk memindahkannya.
- Atur detailnya (arah, kanal, dan lain-lain) lewat panel **Properti** ([bagian 5](#5-mengedit-lampu-properti)).
- Bila salah, gunakan **Urungkan**.

---

## 5. Mengedit Lampu (Properti)

Panel **Properti** menampilkan pengaturan untuk objek yang sedang dipilih. Dari opsi tampilan yang tersedia, properti lampu mencakup:

- **Arah sorot**: ke mana lampu mengarah. Garis arah muncul bila *Tampilkan arah sorot* aktif.
- **Nomor kanal**: kanal kontrol/dimmer lampu. Tampil di gambar bila *Tampilkan nomor kanal* aktif.
- **Bottom**: lampu yang menempel pada bottom tertentu memakai nama bottom tersebut *(cek di aplikasi)*.

Langkah umum:
1. Klik lampu di kanvas sampai terpilih.
2. Lihat panel **Properti**.
3. Ubah nilai yang diperlukan. Hasilnya langsung terlihat di kanvas.

---

## 6. Pengaturan Tampilan

Pengaturan ini ada di bagian **Panggung** dan berupa kotak centang:

| Opsi | Efek |
|---|---|
| **Tampilkan grid** | Menampilkan atau menyembunyikan garis grid |
| **Tampilkan arah sorot** | Menampilkan garis arah sorot tiap lampu |
| **Tampilkan nomor kanal** | Menampilkan nomor kanal di dekat ikon lampu |
| **Tampilkan nama bottom di gambar** | Menampilkan nama bottom pada gambar hasil |

> **Tip:** Matikan grid dan arah sorot saat mengekspor bila ingin gambar yang bersih. Nyalakan nomor kanal bila gambar dipakai operator lampu.

### Zoom dan navigasi kanvas
Di bilah status tersedia tiga tombol:
- **`+`**: perbesar tampilan
- **`−`**: perkecil tampilan
- **`▣`**: pas ke layar (menampilkan seluruh panggung)

Di sebelahnya ada info ringkas: **Posisi** (koordinat kursor), jumlah **Lampu**, dan jumlah **Bottom**.

---

## 7. Tulisan Belakang dan Tepi Panggung

Kamu bisa menambah teks pada denah, misalnya "BACKSTAGE", "KIRI PANGGUNG", "KANAN PANGGUNG", atau "AUDIENCE".

### Tulisan belakang panggung
1. Isi kolom **Tulisan belakang panggung**.
2. Centang **Tampilkan tulisan belakang panggung**.
3. Atur **Ukuran tulisan belakang panggung** sesuai selera.

### Tulisan tepi panggung
1. Isi kolom **Tulisan tepi panggung**.
2. Centang **Tampilkan tulisan tepi panggung**.
3. Atur **Ukuran tulisan tepi panggung**.

---

## 8. Lembar Gambar (Blok Judul)

Bagian **Lembar gambar** mengisi blok judul di hasil ekspor, seperti gambar teknik pada umumnya.

| Kolom | Isi |
|---|---|
| **Judul pertunjukan** | Nama acara atau pertunjukan |
| **Font judul (ekspor)** | Jenis huruf untuk judul pada hasil ekspor |
| **Ukuran judul** | Ukuran huruf judul |
| **Tempat** | Lokasi atau venue |
| **Font tempat (ekspor)** | Jenis huruf untuk tempat |
| **Ukuran tempat** | Ukuran huruf tempat |
| **Penata cahaya** | Nama penata cahaya |
| **Tanggal** | Tanggal pertunjukan atau tanggal gambar |
| **Nomor gambar** | Nomor lembar gambar, misalnya `LP-01` |

### Aturan ukuran huruf
Dari keterangan di aplikasi:
- **Ukuran 0 = otomatis.**
- Teks panjang **turun ke baris berikutnya**, rata tengah di dalam kotak.
- Ukuran huruf **mengecil sendiri** bila teks tidak muat.

Jadi kamu cukup menulis judul panjang tanpa khawatir terpotong. Isi ukuran manual hanya bila ingin kontrol penuh.

---

## 9. Menyimpan dan Membuka Proyek

Pekerjaan bisa disimpan agar dilanjutkan nanti.

### Menyimpan
1. Klik **Simpan proyek** di bilah atas.
2. File proyek akan diunduh ke perangkatmu.
3. Simpan di tempat yang aman (cloud, flashdisk, folder kerja).

### Membuka
1. Klik **Buka proyek**.
2. Pilih file proyek yang tersimpan.
3. Denah dan pengaturan kembali seperti saat disimpan.

> **Penting:** Aplikasi berjalan di browser. Simpan proyek secara berkala dan jangan hanya mengandalkan tab yang terbuka, karena menutup atau me-refresh halaman bisa menghilangkan pekerjaan yang belum disimpan.

---

## 10. Ekspor: PNG, PDF, SVG

Bagian **Ekspor** menghasilkan gambar akhir.

### Pengaturan ekspor
| Pengaturan | Pilihan |
|---|---|
| **Resolusi PNG (sisi lebar)** | **HD** (1920 px), **2K** (2560 px), **4K** (3840 px) |
| **Kertas PDF (lanskap)** | **A3**, **A4** |
| **Sertakan legenda dan blok judul** | Centang untuk menambahkan legenda lampu dan blok judul pada hasil |

### Tombol unduh
- **Unduh PNG**: gambar raster, cocok untuk dibagikan lewat chat atau dimasukkan ke dokumen.
- **Unduh PDF**: dokumen lanskap A3 atau A4, cocok untuk dicetak.
- **Unduh SVG (vektor)**: gambar vektor yang bisa diperbesar tanpa pecah dan diedit di Inkscape, Illustrator, atau Figma.

### Memilih format
| Kebutuhan | Format |
|---|---|
| Kirim cepat ke kru | PNG (HD) |
| Cetak untuk dokumen produksi | PDF A3 atau A4 |
| Cetak besar atau poster | PNG 4K atau SVG |
| Diedit lanjut di software desain | SVG |

> **Tip:** Untuk plot yang akan dicetak, pilih **A3** dan centang **Sertakan legenda dan blok judul** agar tulisan tetap terbaca jelas.

---

## 11. Alur Kerja yang Disarankan

1. **Klik Contoh** sekali untuk melihat bentuk hasil akhir. Lalu klik **Baru**.
2. **Atur panggung**: isi lebar dan kedalaman, pilih kunci grid (misalnya 0,5 m).
3. **Tulis teks panggung**: belakang dan tepi panggung (kiri, kanan, penonton).
4. **Letakkan lampu**: mulai dari bottom atau posisi utama, lalu lampu lainnya.
5. **Rapikan lampu**: atur arah sorot dan nomor kanal lewat **Properti**.
6. **Atur tampilan**: nyalakan atau matikan grid, arah sorot, nomor kanal, nama bottom.
7. **Isi lembar gambar**: judul, tempat, penata cahaya, tanggal, nomor gambar.
8. **Simpan proyek** agar bisa diedit lagi.
9. **Ekspor** sebagai PDF atau PNG, dan SVG bila perlu.

---

## 12. Tips dan Pemecahan Masalah

**Lampu sulit diletakkan tepat di bottom**
Dekatkan saja ke garis bottom. Fitur tempel otomatis akan menyambungkannya.

**Ikon lampu terlalu kecil atau besar**
Ubah **Ukuran ikon (semua lampu)** di bagian Panggung.

**Posisi lampu tidak rapi**
Aktifkan **Kunci ke grid** (misalnya 0,5 m atau 0,25 m).

**Teks judul terpotong atau terlalu kecil**
Biarkan ukuran **0** (otomatis), atau perbesar manual bila teks pendek.

**Gambar ekspor terlalu ramai**
Matikan grid dan arah sorot sebelum mengunduh.

**Pekerjaan hilang setelah tab ditutup**
Biasakan klik **Simpan proyek** secara berkala, terutama sebelum menutup browser.

**Tampilan tidak pas di layar**
Klik tombol **`▣`** untuk menyesuaikan tampilan, atau gunakan **`+`/`−`** untuk zoom manual.

**Aplikasi tidak muncul sempurna di ponsel**
Gunakan layar yang lebih lebar (laptop, tablet, atau ponsel mode lanskap) agar panel dan kanvas nyaman dipakai.

---

## 13. Ringkasan Cepat

| Aksi | Cara |
|---|---|
| Lihat contoh | **Contoh** |
| Mulai kosong | **Baru** |
| Batalkan / ulangi | **Urungkan** / **Ulangi** |
| Atur ukuran panggung | Panggung → **Lebar** dan **Kedalaman** |
| Letakkan lampu | Klik jenis lampu lalu klik kanvas, atau seret ikon |
| Tempel ke bottom | Letakkan lampu dekat garis bottom |
| Posisi presisi | **Kunci ke grid** |
| Tampilkan nomor kanal / arah sorot | Centang opsi terkait di Panggung |
| Isi blok judul | **Lembar gambar** |
| Simpan / buka | **Simpan proyek** / **Buka proyek** |
| Ekspor | **Unduh PNG / PDF / SVG** |

---

*Tutorial ini dibuat berdasarkan halaman MATAPLOT per 4 November 2026. Aplikasi masih dikembangkan, jadi fitur dan label bisa berubah.*
