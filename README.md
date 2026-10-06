<div align="center">

## LAPORAN [WEBSITE DAN SISTEM MOBILE]

![Logo PNL](/img/logo-pnl.png)

### Disusun Oleh:  
Nama               : [Riatunnisa]  
NIM                : [2024903430051]  
Kelas              : [TRKJ 3D]


### Program Studi Teknologi Rekayasa Komputer Jaringan
### Jurusan Teknologi Informasi dan Komputer
### Politeknik Negeri Lhokseumawe
### 2026


---


## Lembar Pengesahan


| No. Praktikum     | : | [03] |
|------------------:|:-:|:--------------|
| Judul Praktikum   | : | [Membuat Restful API CRUD Mahasiswa] |
| Tanggal Praktikum | : | [25  September 2026] |
| Tanggal Penyerahan| : | [1 Oktober 2026] |
| Nama Praktikan    | : | [Riatunnisa] |
| NIM/Kelas Praktikan| : | [2024903430051] / [TRKJ 3D] |
| Nilai Praktikum   | : | .......................... |
| Dosen Pengampu    | : | Muhammad Davi, S.Kom., M.Cs. |

Mengetahui,  
Dosen Pengampu
<br><br><br><br><br>

Muhammad Davi, S.Kom., M.Cs.
</div>


## Daftar Isi
- [Lembar Pengesahan](#lembar-pengesahan)
- [Daftar Isi](#daftar-isi)
- [Tujuan Praktikum](#tujuan-praktikum)
- [Dasar Teori](#dasar-teori)
- [Alat dan Bahan](#alat-dan-bahan)
- [Langkah Kerja](#langkah-kerja)
- [Hasil dan Pembahasan](#hasil-dan-pembahasan)
- [Kesimpulan](#kesimpulan)
- [Referensi](#referensi)
---

## A. Tujuan Praktikum
Tujuan dari praktikum ini adalah:

Praktikum ini bertujuan untuk:

1. Membuat RESTful API menggunakan framework Laravel.
2. Membuat database untuk menyimpan data mahasiswa.
3. Membuat fitur CRUD (Create, Read, Update, Delete) data mahasiswa.
4. Membuat hubungan antara tabel mahasiswa dengan tabel program studi.
5. Menggunakan Resource Laravel untuk mengatur format response API.
6. Melakukan pengujian API menggunakan Postman.
   
## B. Dasar Teori
1. RESTful API

RESTful API adalah sebuah sistem yang memungkinkan aplikasi saling berkomunikasi menggunakan protokol HTTP. Dalam RESTful API terdapat beberapa metode yang umum digunakan, yaitu:

GET → mengambil data.
POST → menambahkan data.
PUT/PATCH → mengubah data.
DELETE → menghapus data.
2. CRUD

CRUD merupakan singkatan dari:

Create → membuat/menambahkan data.
Read → membaca atau menampilkan data.
Update → mengubah data.
Delete → menghapus data.

Pada praktikum ini CRUD digunakan untuk mengelola data mahasiswa.

3. Laravel Resource

MahasiswaResource digunakan untuk mengatur bentuk data yang dikembalikan oleh API sehingga response menjadi lebih terstruktur, misalnya memiliki bagian status, message, dan data.

Materi praktikum menggunakan Laravel dan Laradock sebagai lingkungan kerja.

## C. Alat dan Bahan
Alat dan bahan yang digunakan dalam praktikum ini adalah:
1. Laptop atau komputer.
2. Sistem operasi Windows/Linux/macOS.
3. Laravel.
4. Composer.
5. Docker/Laradock sebagai lingkungan kerja.
6. Git dan GitHub.
7. Postman.
8. Package tymon/jwt-auth.

## D. Langkah Kerja

1. Membuat Model dan Migration Program Studi

Buka Git Bash/Terminal pada folder project Laravel, kemudian jalankan:

php artisan make:model ProgramStudi -m

Perintah tersebut membuat:

Model ProgramStudi
File migration program_studis_table

Materi menggunakan perintah yang sama untuk membuat model dan migration Program Studi.

## F. Kesimpulan
Berdasarkan praktikum yang telah dilakukan, dapat disimpulkan bahwa Restful API Login menggunakan Laravel dan JWT berhasil dibuat dan diuji menggunakan Postman. JWT digunakan sebagai autentikasi untuk menghasilkan token setelah pengguna berhasil melakukan login.

Praktikum ini juga memberikan pemahaman mengenai konfigurasi JWT, model User, AuthController, serta route API untuk proses login, refresh token, dan logout.

## G. Referensi
[1] Politeknik Negeri Lhokseumawe, Modul Praktikum TIK-6555 Website dan Sistem Mobile, 2025–2026 Ganjil.

[2] Laravel, Laravel Documentation. [Online]. Available: Laravel Documentation.

[3] JSON Web Token, JWT (JSON Web Token). [Online].
