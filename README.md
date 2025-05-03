<div id="top"></div>

<div align="center">
  <a href="https://github.com/username/proyek-anda">
    <img src="public/LOGO_ORIGINAL.png" alt="Logo" width="300">
  </a>
  <h3 align="center">PRU (Peminjaman Ruangan UNTIRTA)</h3>
  <p align="center">
    Web Peminjaman Ruangan UNTIRTA
</div>

## Sekilas Web dan Pedoman Penggunaan

**PRU (Peminjaman Ruangan UNTIRTA)** adalah aplikasi berbasis web yang dikembangkan untuk memfasilitasi proses peminjaman ruangan di lingkungan Fakultas Teknik, Universitas Sultan Ageng Tirtayasa (UNTIRTA). Aplikasi ini dapat digunakan oleh dosen dan mahasiswa untuk mengakses informasi terkait ketersediaan ruangan dan melakukan peminjaman di Fakultas Teknik UNTIRTA.


PRU memiliki beberapa fitur utama di dalamnya:

**User**
1. Halaman Login dan Registrasi
    Halaman ini berisi validasi apakah Anda pengguna baru atau pengguna lama. Jika pengguna lama, maka dapat log-in secara langsung tanpa registrasi terlebih dahulu dengan memasukkan email dan password yag telah dibuat oleh pengguna. Jika pengguna belum pernah masuk ke web ini, maka Anda dapat melakukan registrasi dengan memasukkan nama Lengkap, NIM untuk mahasiswa dan NIDN untuk dosen, email (@untirta.ac.id), password sesuai keinginan Anda dan konfirmasi password yang telah dimasukkan. Setelah registrasi, maka akan kembali ke halaman log-in untuk memasukkan akun dan password yang telah dibuat dan akan masuk ke halaman daftar ruangan setelah melakukan log-in dengan benar

    Berikut struktur halaman secara singkat:
    - Validasi email institusi (@untirta.ac.id)
    - Form registrasi dengan:
      - Nama lengkap
      - NIM/NIDN
      - Email dan password
      - Konfirmasi password
    - Redirect otomatis ke halaman utama setelah login


2. Halaman Daftar Ruangan
   Di halaman ini terdapat daftar ruangan yang bisa dapat Anda kunjungi untuk melakukan peminjaman ruangan yang tersedia pada halaman ini. Untuk melihat profil ruangan dan daftar ruangan yang mengajukan peminjaman pada suatu ruang, Anda dapat mengklik nama ruangan dan akan terlihat profil ruangan dan daftar ruangan yang mengajukan peminjaman pada ruangan yang Anda klik. Pada halaman profil dan daftar ruangan yang mengajukan peminjaman, Anda dapat mengajukan peminjaman ruangan baik pada ruangan yang Anda klik maupun tempat lainnya.

   Berikut struktur halaman secara singkat:
    - Tabel daftar ruangan dengan:
        - Nama ruangan (clickable untuk detail)
        - Kode ruangan
      - Fitur detail ruangan:
        - Profil lengkap ruangan
        - Jadwal peminjaman
        - Form pengajuan peminjaman
      - Sistem booking online:
        - Pilih tanggal dan waktu
        - Input tujuan peminjaman
        - Konfirmasi "Pending" untuk sementara yang akan melakukan
          keputusan konfirmasi yang dipastikan oleh admin




3. Halaman Daftar Ruangan yang terpinjam  
    Selanjutnya pada halaman ini Anda akan melihat daftar ruangan yang terpinjam secara keseluruhan dari semua ruangan yang diajukan pengguna sehingga Anda dapat memantau secara real-time apakah statusnya diterima atau tidak. Jika tidak, maka statusnya tidak diterima dengan keterangan misalnya "sedang dipakai", "ruangan sedang maintenance", dan keterangan", "Siap dipakai" dan keterangan lainnya yang menyatakan diterima sesuai kondisi ruangan.

    Berikut struktur halaman secara singkat:
    Monitoring real-time status peminjaman:
     - Diterima ("Siap dipakai, diterima,dan lain-lain")
     - Pending
     - Ditolak ("Ruangan tidak tersedia, ruangan sedang maintenance
       sedang dipakai, dll")
   - Filter pencarian berdasarkan:
     - Tanggal
     - Status
     - Ruangan


   **Admin**
  1. Halaman Login dan Registrasi
      Halaman ini berisi validasi untuk admin yang akan mengelola pengajuan user supaya dapat melanjutkan administrasi yang diperlukan setelah memberi respon kepada user.
  2. Daftar User
      Halaman ini dapat menampilkan daftar seluruh user yang terdaftar dalam sistem. Di mana admin dapat mengelola  user baik lingkup user itu sendiri maupun admin sekalipun. Halaman ini dapat mengubah nama, nonor induk, password, dan e-mail 
  3. Pengajuan Peminjaman
      Pada halaman ini dapat menampilkan daftar pengajuan peminjaman ruangan yang membutuhkan persetujuan admin. Sebagai admin dapat memilih  salah satu dari dua tanda yang tersedia yaitu tanda centang dan silang
  4. Daftar Peminjaman
      Pada halaman ini admin dapat melihat riwayat daftar peminjaman ruangan baik sedang berlangsung maupun sudah selesai peminjamannya. Admin dapat menghapus riwayatnya dengan klik logo hapus.
  5. Daftar Ruangan
      Pada halaman ini admin dapat melihat daftar ruangan dan mengubah formulir ruangan sesuai kebutuhan



   **SuperAdmin**
  1. Halaman Login dan Registrasi
      Halaman ini berisi validasi untuk admin yang akan mengelola pengajuan user supaya dapat melanjutkan administrasi yang diperlukan setelah memberi respon kepada user dan juga dapat mengelola ruangan yang tersedia, karena di bagian ini tidak seperti admin pada umumnya
  2. Daftar Admin
      Halaman ini dapat melihat daftar admin yang terdaftar. Di halaman ini superadmin dapat mengubah atau menghapus admin yang terdaftar bila ada perubahan yang terjadi.
  3. Daftar User
      Halaman ini dapat melihat semua pengguna yang terdaftar di database. Di sini superadmin dapat mengubah role dari pengguna yang tersedia seperti ketua kelompok bisa diubah role-nya menjadi mahasiswa, bisa juga menjadi admin sesuai kebutuhan. Ini juga dapat menghapus user yang tersedia di halaman ini
  4. Pengajuan Peminjaman
      Halaman ini dapat  melihat user yang mengajukan peminjaman dari beberapa user. SuperAdmin dapat memberi keputusan apakah menerima atau todak dengan memilih salah satu dari dua kotak centang atau silang 
  5. Daftar Peminjaman
      Pada halaman ini superadmin dapat melihat riwayat daftar peminjaman ruangan baik sedang berlangsung maupun sudah selesai peminjamannya. SuperAdmin dapat menghapus riwayatnya dengan klik logo hapus.
  6. Daftar Ruangan
      Pada halaman ini dapat melihat daftar ruangan dan mengubah formulir ruangan sesuai kebutuhan. Bedanya dengan halaman admin, superadmin dapat menghapus ruangannya jika ada perubahan yang terjadi.
    
### Pedoman Penggunaan

Untuk pedoman penggunaan aplikasi ini, Anda dapat mengunduh atau melihatnya melalui Google Docs di [tautan berikut](https://docs.google.com/document/d/18QqgSzpuvflK2MkCZf7CT4sEr_yamIXu/edit?usp=drive_link&ouid=102321657428421809136&rtpof=true&sd=true).

### Dibangun Dengan

Proyek ini dibangun menggunakan teknologi berikut:

* [Laravel](https://laravel.com)
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [XAMPP](https://www.apachefriends.org/download.html)

## Cara Memulai

Berikut adalah langkah-langkah untuk menjalankan aplikasi secara lokal di komputer Anda.

### Prasyarat dan Instalasi

Berikut adalah petunjuk untuk memulai proyek ini:

1. **Install Composer** di komputer Anda.
   - Jika Anda belum memiliki Composer, Anda bisa mengunduhnya dari [Composer](https://getcomposer.org/).

2. **Clone repository** ke komputer Anda:
   ```bash
   git clone https://github.com/username/proyek-anda.git
   
