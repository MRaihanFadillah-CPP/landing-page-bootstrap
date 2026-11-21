CATATAN TUGAS PRAKTIKUM BOOTSTRAP

Nama : Muhammad Raihan Fadillah
NIM  : 2511102441045

==================================================
TIGA PERUBAHAN DARI CONTOH MODUL:
==================================================
1. Tampilan Header/Hero:
   Mengubah header standar modul menjadi hero section modern dengan efek linear-gradient, foto profil melingkar (rounded-circle) dengan border transparan, dan dua tombol aksi (Lihat Keahlian & Hubungi).

2. Tiga Card Keahlian Berisi Gambar dan Badge:
   Mengganti format card sederhana di modul menjadi 3 card interaktif yang dilengkapi gambar ilustrasi (card-img-top), icon lingkaran gradasi, teks deskripsi keahlian, badges teknologi terkait, serta efek animasi hover (card-keahlian:hover).

3. Navigasi Sticky dengan Desain Gelap:
   Menambahkan navbar responsif dengan class sticky-top agar menu tetap terlihat saat halaman digulir (scroll), lengkap dengan tombol toggle (hamburger menu) untuk layar mobile/kecil.

==================================================
SATU KENDALA DAN CARA MENGATASINYA:
==================================================
- Kendala:
  Tampilan card keahlian tingginya tidak sama rata saat dibuka di layar tablet (breakpoint md) karena panjang deskripsi teks berbeda.

- Solusi:
  Menambahkan class utility Bootstrap `h-100` pada elemen card dan membungkus kolom dalam `row g-4` sehingga semua card otomatis memiliki tinggi yang sama (equal height) di setiap breakpoint layar.
