# Virtual Tour Masjid 99 Kubah Makassar

## Deskripsi Proyek

Proyek ini merupakan website virtual tour Masjid 99 Kubah Makassar yang memungkinkan pengguna menjelajahi beberapa sudut lokasi melalui tampilan panorama interaktif.

Website dibuat menggunakan HTML, CSS, dan JavaScript dengan bantuan pustaka Pannellum 2.5.7 untuk menampilkan panorama serta menyediakan navigasi antar lokasi.

## Fitur Website

- Menampilkan delapan titik atau sudut lokasi masjid.
- Navigasi antar lokasi melalui menu dan hotspot.
- Mengatur arah pandang panorama dengan mouse.
- Memperbesar dan memperkecil tampilan.
- Menampilkan kontrol navigasi dan layar penuh.
- Dapat diakses melalui browser setelah website dipublikasikan.

## Fitur Website

- Menampilkan delapan lokasi Masjid 99 Kubah Makassar.
- Menyediakan hotspot informasi yang menampilkan penjelasan setiap lokasi.
- Menyediakan hotspot navigasi untuk berpindah ke lokasi sebelumnya atau berikutnya.
- Menyediakan tombol pilihan lokasi.
- Mendukung kontrol arah pandang, zoom, dan layar penuh.
- Menampilkan informasi lokasi yang sedang dikunjungi.
- Menggunakan Pannellum 2.5.7 untuk menampilkan panorama interaktif.

## Teknologi yang Digunakan

- HTML untuk struktur halaman.
- CSS untuk desain dan tata letak.
- JavaScript untuk interaksi, informasi lokasi, dan navigasi.
- Pannellum 2.5.7 untuk penampil panorama.
- Git dan GitHub untuk pengelolaan kode.
- GitHub Pages untuk publikasi website.

## Struktur Proyek

```text
masjid_99_kubah_vtour/
├── index.html
├── README.md
├── .nojekyll
└── images/
    ├── titik tengah.jpeg
    ├── teras kiri.jpeg
    ├── teras kanan.jpeg
    ├── teras depan.jpeg
    ├── samping kanan.jpeg
    ├── pintu samping.jpeg
    ├── pintu depan.jpeg
    └── bagian depan.jpeg
```

## Teknologi yang Digunakan

- HTML untuk struktur halaman website.
- CSS untuk desain dan tata letak.
- JavaScript untuk pengaturan navigasi dan interaksi.
- Pannellum 2.5.7 untuk menampilkan panorama 360 derajat.
- Git dan GitHub untuk pengelolaan kode serta publikasi website.
- GitHub Pages untuk hosting website.

## Cara Menjalankan Website Secara Lokal

Pastikan Python sudah terpasang dan terminal berada di folder proyek.

Jalankan perintah berikut:

```bash
python -m http.server 8000
```

Jika menggunakan `python3`, jalankan:

```bash
python3 -m http.server 8000
```

Buka alamat berikut di browser:

http://localhost:8000/

Untuk menghentikan server, tekan `Ctrl + C` pada terminal.

## Memperbarui Website di GitHub

Setelah melakukan perubahan pada file proyek, jalankan:

```bash
git add .
git commit -m "Update virtual tour Masjid 99 Kubah"
git push
```

Tunggu proses deployment GitHub Pages selesai, kemudian muat ulang website di browser.

## Catatan

Nama file gambar pada folder `images/` harus sama persis dengan nama file yang digunakan dalam konfigurasi `panorama` pada `index.html`. Perhatikan spasi, huruf kapital, dan ekstensi file.

Untuk tampilan panorama 360 derajat yang benar, gambar perlu berupa panorama equirectangular 360 × 180 derajat, umumnya dengan rasio lebar dan tinggi 2:1. Foto biasa tidak otomatis menjadi panorama 360 derajat hanya karena ditampilkan menggunakan Pannellum.

## Referensi

- Pannellum Documentation: https://pannellum.org/documentation/reference/
- GitHub Pages Documentation: https://docs.github.com/en/pages
- Git Documentation: https://git-scm.com/doc
