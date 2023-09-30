# Lab1web
| [Praktikum](#praktikum-) | [Pertanyaan](#pertanyaan-dan-jawaban-)  | 
| :---| :------- | 
# <p align="center">Praktikum </p>
## 1. Membuat Paragraf
![Screenshot 2023-09-30 201957](https://github.com/hafizalkariem/Lab1web/assets/115614957/96354da3-0f91-469d-935b-6cceb33210d3)

![Screenshot 2023-09-27 203217](https://github.com/hafizalkariem/Lab1web/assets/115614957/5ce8e759-7626-4d73-bb3b-e171db29d16a)

## 2. Menambahkan Judul

![Screenshot 2023-09-30 202637](https://github.com/hafizalkariem/Lab1web/assets/115614957/f67b920d-7759-405d-89a8-a2f91f05be0b)

![Screenshot 2023-09-27 203552](https://github.com/hafizalkariem/Lab1web/assets/115614957/a673f0b4-fb57-4b29-bed9-6711e0a72830)

## 3. Memformat teks

![Screenshot 2023-09-30 203111](https://github.com/hafizalkariem/Lab1web/assets/115614957/49e404f8-19dd-41db-9f90-4816bc1fcf52)
![Screenshot 2023-09-30 203345](https://github.com/hafizalkariem/Lab1web/assets/115614957/e492f20b-1922-4dfb-a1e0-d2eb7aada050)

## 4. Menyisipkan Gambar
![Screenshot 2023-09-30 203622](https://github.com/hafizalkariem/Lab1web/assets/115614957/02965d1b-1274-45ac-80f7-12a7f42391ed)
![Screenshot 2023-09-30 204131](https://github.com/hafizalkariem/Lab1web/assets/115614957/dad3e724-1e46-4674-9891-5a6938444ff9)

## 5. Menambahkan Hyperlink
![Screenshot 2023-09-30 204610](https://github.com/hafizalkariem/Lab1web/assets/115614957/dd3706b9-382a-4fc5-ae94-0639f19afe04)
![Screenshot 2023-09-30 205446](https://github.com/hafizalkariem/Lab1web/assets/115614957/41f61934-a95b-4c66-af73-daf6c5256236)

# <p align="center">Pertanyaan dan jawaban </p> 
![Screenshot 2023-09-29 193256](https://github.com/hafizalkariem/Praktikum1_Pemrograman_Web/assets/115614957/6c294912-9c3b-4b5e-bf84-d1da811e8d0c)
Berikut adalah jawaban beserta beberapa langkah penyesuaian terhadap soal praktikum diatas.
## Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya apakah ada error ketika terjadi kesalahan penulisan tag
Untuk error sendiri,selama kita tidak salah dalam penulisan tagar tagar html,  kemungkinan tidak akan terjadi error. tapi terkadang ketika kita salah menulis tagar, pasti ada kemungkinan error yang dampaknya adalah tag yang kita maksud tidak berfungsi seperti misalnya menggunakan tag ``p align="center"`` karena kesalahan penulisan tag akhirnya paragraf yang harusnya terpusat dari tengah malah hanya menjadi paragraf biasa.
## Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
Tag `<p>` dan tag `<br>` adalah dua tag HTML yang digunakan untuk mengatur tampilan dan pemformatan teks dalam halaman web. Berikut adalah perbedaan antara keduanya:

`<p>` (Paragraph Tag):

Penjelasan: Tag `<p>` digunakan untuk mengelompokkan teks menjadi paragraf atau blok teks. Ini digunakan untuk membuat paragraf baru di halaman web.

`<br>` (Line Break Tag):

Penjelasan: Tag `<br>` digunakan untuk membuat perubahan baris baru (line break) di tengah teks atau di dalam elemen lain seperti tabel atau deskripsi singkat. Ini tidak mengelompokkan teks menjadi paragraf, tetapi hanya menggeser teks ke baris berikutnya.

## Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!

Atribut title dan alt pada tag <img> adalah dua atribut yang digunakan untuk memberikan informasi tambahan tentang gambar pada halaman web. Namun, keduanya memiliki tujuan yang berbeda:

<b>Atribut alt (Alternative Text):</b>

Tujuan: Atribut alt digunakan untuk memberikan teks alternatif atau deskripsi singkat dari gambar. Ini adalah teks yang akan ditampilkan jika gambar tidak dapat dimuat atau jika pengguna menggunakan perangkat bantu seperti pembaca layar.


<b> Atribut title  : </b>

Tujuan: Atribut title digunakan untuk memberikan informasi tambahan tentang gambar saat pengguna mengarahkan kursor mouse ke gambar tersebut. Ini adalah teks tooltip yang muncul saat pengguna menghover mouse di atas gambar.

Jadi, perbedaan utama antara kedua atribut tersebut adalah bahwa alt digunakan untuk memberikan deskripsi alternatif untuk gambar yang bermanfaat jika gambar tidak dapat ditampilkan atau untuk aksesibilitas, sementara title digunakan untuk memberikan informasi tambahan yang muncul sebagai tooltip saat mouse diarahkan ke gambar. Kedua atribut ini dapat digunakan bersama-sama dalam tag <img> untuk memberikan informasi yang lebih kaya tentang gambar.

## Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

Untuk mengatur ukuran gambar dalam HTML, Anda dapat menggunakan atribut width (lebar) dan height (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi salah satu atribut ini, yaitu atribut width atau atribut height, dan biarkan yang satunya kosong. Ini akan memungkinkan browser untuk menghitung nilai yang sesuai untuk atribut yang tidak diisi berdasarkan perbandingan aspek gambar (rasio lebar-tinggi) yang diberikan.

Dengan mengisi hanya satu atribut (width atau height) dan membiarkan yang satunya kosong, gambar akan tetap proporsional dan browser akan menghitung nilai yang sesuai berdasarkan aspek gambar yang ada. Jika Anda mengisi kedua atribut width dan height dengan nilai yang spesifik, maka gambar mungkin akan terlihat terdistorsi jika rasio lebar-tinggi tidak sesuai dengan gambar asli. Oleh karena itu, sebaiknya gunakan salah satu atribut untuk mengatur ukuran gambar dan biarkan yang satunya kosong agar gambar tetap proporsional.

## Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

Atribut target digunakan dalam tag `<a>` (link) untuk mengendalikan bagaimana halaman yang terhubung akan dibuka atau ditargetkan ketika pengguna mengklik tautan. Berikut penjelasan tentang nilai atribut target yang bervariasi:

<b>_blank:</B>

Saat Anda menggunakan target="_blank", tautan akan membuka halaman yang terhubung dalam jendela atau tab browser yang baru. Ini akan mengakibatkan halaman yang saat ini sedang dilihat tetap terbuka.
Contoh: `<a href="https://www.example.com" target="_blank">Kunjungi Contoh</a>`

<b>_self:</b>

Ini adalah perilaku default ketika target tidak diatur. Jika Anda mengatur target="_self", tautan akan membuka halaman yang terhubung di jendela atau tab yang sama di mana tautan itu sendiri berada.
Contoh: `<a href="https://www.example.com" target="_self">Kunjungi Contoh</a>`

<b>_top:</b>

Saat Anda menggunakan target="_top", tautan akan membuka halaman yang terhubung di jendela atau tab yang sama seperti _self, tetapi jika tautan tersebut terletak dalam iframe atau frame dalam halaman web, maka tautan tersebut akan membuka halaman di jendela atau tab paling atas (top-level window/tab) dan menggantikan keseluruhan halaman tersebut.
Contoh: `<a href="https://www.example.com" target="_top">Kunjungi Contoh</a>`

<b>_parent:</b>

Ketika Anda menggunakan target="_parent", tautan akan membuka halaman yang terhubung di jendela atau tab yang sama seperti _self, tetapi jika tautan tersebut terletak dalam iframe atau frame dalam halaman web yang lebih kompleks, maka tautan tersebut akan membuka halaman di dalam frame yang lebih tinggi (parent frame) dan menggantikan konten frame tersebut.
Contoh: `<a href="https://www.example.com" target="_parent">Kunjungi Contoh</a>`
Pemahaman tentang penggunaan nilai-nilai target ini dapat membantu Anda mengendalikan perilaku tautan dan navigasi dalam halaman web Anda, tergantung pada kebutuhan dan tujuan spesifik Anda.

## <p align="center"> TERIMAKASIH </p>
