# Bank-Term-Deposite-ML-Process

## Backround
Sebuah Lembaga perbankan di Portugis ingin melakukan kampanye pemasaran langsung yaitu melalui panggilan telepon untuk mempromosikan produknya yaitu Term Deposite (Deposito Berjangka). Untuk menghemat cost dalam project kampanye Term Deposite ini, tentu pihak bank tidak mungkin menghubingi semua nasabah yang terdaftar. Bank memerlukan suatu cara yang efektif untuk menyeleksi nasabahnasabah yang berpotensi untuk berlangganan Term Deposite.

## Objective
Masalah yang harus diselesaikan di sini adalah bagaimana caranya agar Bank dapat memprediksi dengan benar nasabah-nasabah mana saja yang nantinya akan berlangganan Term Deposite. Untuk menyelesaikan masalah ini, dapat dilakukan pemodelan klasifikasi dengan machine learning dengan tujuan memprediksi apakah nasabah akan berlangganan Term Deposite. Pemodelan ini dilakukan dengan memanfaatkan data nasabah sebagai input, yaitu seperti job, marital, education, default, housing, loan, contact, month, dll, dengan output berupa variabel yang menjelaskan status langganan Term Deposite nasabah.

Kemudian, ada beberapa pemodelan machine learning yang bisa dimanfaatkan untuk penyelesaian masalah ini. Diantaranya adalah pemodelan Logistric Regression dan pemodelan dengan Random Forest.

Akan dilakukan klasifikasi menggunakan dua metode ini. Kemudian dibandingkan hasilnya dan diambil metode yang terbaik untuk kemudian digunakan pada proses deployment.

## Dataset
Dataset yang digunakan merupakan data nasabah dari sebuah Lembaga di Potugis. Data memiliki total 4521 baris dengan 17 variabel. Berikut diberikan penjelasan mengenai masing-masing variabel atau fitur.

1 — age (numerik): usia\\
2 — job (kategorikal): jenis pekerjaan
3 — marital (kategorikal): status pernikahan
4 — education (kategorikal): pendidikan
5 — default (kategorikal): status kepemilikan kredit macet
6 — balance (numerik): saldo rekening
7 — housing (kategorikal): status kepemilikan housing loan
8 — loan (kategorikal): status kepemilikan personal loan
9 — contact (kategorikal): jenis kontak untuk komunikasi (cellular/telephone)
10 — month (kategorikal): bulan kontak terakhir
11 — day_of_week (kategorikal): hari kontak terakhir
12 — duration (numerik): durasi kontak terakhir [Catatan penting: variabel ini sangat memengaruhi target output (misalnya, jika durasi=0 maka y=’tidak’) karena durasi diperoleh ketika nasabah sudah dihubungi.
13 — kampanye (numerik): jumlah kontak yang dilakukan dalam kampanye ini untuk nasabah ini
14 — pdays (numerik): jumlah hari berlalu sejak nasabah dihubungi dari kampanye sebelumnya (999 berarti nasabah belum dikontak sebelumnya)
15 — previous (numerik): jumlah kontak yang dilakukan sebelum kampanye ini untuk nasabah ini
16 — poutcome (kategorikal): hasil dari marketing kampanye sebelumnya
