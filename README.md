# TP2DPBO2023
Saya Muhammad Fadlan Ghafur NIM 2106923 mengerjakan LP7 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Deskripsi Tugas

Modifikasi kode yang sudah diberikan, dengan ketentuan sebagai berikut:
Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
Skor hanya bertambah jika pemain berbelok, bukan bergerak berurutan. Detail:
Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.
Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).
Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.
Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.

## Design Program
Program ini memiliki beberapa kelas diantaranya:

kelas Controller, kelas ini memiliki dua atribut game dan handler. method yang terdapat dalam kelas ini adalah keyPressed() dan keyReleased(). fungsinya untuk mengontrol objek.
kelas controller = terdapat dua atribut yaitu game dan handler dimana juga ada method keypressed dan keyrealesd untuk mengatur tata letak objek

kelas display = kelas ini mempunyai dua method open dan close untuk memunculkan objek dalam frame

kelas game = kelas ini mempunyai method start stop render dan loop dimana ini berkaitan dengan fungsi game itu sendiri

kelas game object = dimana class ini befungsi untuk membuat suatu object di dalam game dengan tipe masing masing

kelas handler = kelas ini mengatur dan mengelola objek dalam game dimana nanti mengumpulkan object beripe arraylist

kelas sychronization = kelas ini yang new kan game dan menjalankan nya


## Alur Program
User dapat menekan tombol WASD/panah key pada keyboard untuk menggerakkan object, setiap kali user menekan tombol WASD/panah maka skor akan bertambah 1,akan tetapi skor tidak bertambah apabila user menakan tombol yang sama dalam urutan misalkan setelah W user menekan W lagi maka skor tidak akan bertambah. skor akan bertambah jika tombol dilepaskan. jika tombol hanya ditekan skor belum bertambah, tapi ketika di lepas skor akan bertambah 1. lal

## dokumentasi program
![Synchronization Tutorial 2023-04-25 12-45-07](https://user-images.githubusercontent.com/100921271/234185406-cc7b1a10-3dfd-4932-8b70-531d5874385f.gif)


