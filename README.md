# LATIHAN7DPBO2023

## Deskripsi Soal
Modifikasi kode yang sudah diberikan, dengan ketentuan sebagai berikut:
Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
Skor hanya bertambah jika pemain berbelok. Detail:
Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.
Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).
Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.
Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.


## Penjelasan Program
Skor akan bertambah 1 jika player bergerak ke kanan, kiri, atas, atau bawah.
Saya menambahkan atribut baru yaitu tempKey pada kelas Controller, fungsinya untuk menyimpan nilai key sebelumnya.
Apabila nilai key tidak sama dengan tempKey, maka akan menambah 1 score game dan update nilai tempKey

## Dokumentasi
<p align="center">
  <img src="https://github.com/Azzahrasth/LATIHAN7DPBO2023/blob/main/dokumentasi.gif" alt="gif format testing"/>
</p>

