## Data Preparation


tahap proyek saat memutuskan data yang akan digunakan untuk analisis. Kriteria yang dapat digunakan untuk membuat keputusan ini meliputi relevansi data dengan tujuan penggalian data, kualitas data, dan juga kendala teknis seperti batasan volume data atau jenis data.


1. Memilih Data:
    Buat daftar data yang akan disertakan/dikecualikan dan alasan di balik keputusan tersebut.


2. Pembersihan Data:
    Menjelaskan keputusan dan tindakan apa yang diambil untuk mengatasi masalah kualitas data. Pertimbangkan transformasi data apa pun yang dilakukan untuk tujuan pembersihan dan kemungkinan dampaknya terhadap hasil analisis.


3. Build data yang dibutuhkan:

    - Atribut turunan: atribut baru yang dibuat dari satu atau beberapa atribut yang sudah ada dalam rekaman yang sama, misalnya menggunakan variabel panjang dan lebar untuk menghitung variabel luas yang baru.
    - Catatan yang dihasilkan: Menjelaskan pembuatan catatan yang benar-benar baru. Misalnya, mungkin perlu membuat catatan untuk pelanggan yang tidak melakukan pembelian selama setahun terakhir. Tidak ada alasan untuk memiliki catatan tersebut dalam data mentah, tetapi untuk tujuan pemodelan, mungkin masuk akal untuk secara eksplisit menunjukkan fakta bahwa pelanggan tertentu tidak melakukan pembelian sama sekali.

4. Integrasikan data:

    - Data gabungan: Menggabungkan tabel mengacu pada penggabungan dua atau lebih tabel yang memiliki informasi berbeda tentang objek yang sama. Misalnya, jaringan ritel mungkin memiliki satu tabel dengan informasi tentang karakteristik umum setiap toko (misalnya, luas lantai, jenis mal), tabel lain dengan data penjualan yang diringkas (misalnya, laba, persentase perubahan penjualan dari tahun sebelumnya), dan tabel lain dengan informasi tentang demografi daerah sekitarnya. Setiap tabel ini berisi satu catatan untuk setiap toko. Tabel-tabel ini dapat digabungkan menjadi tabel baru dengan satu catatan untuk setiap toko, menggabungkan bidang-bidang dari tabel sumber.
    
    - Agregasi: Agregasi mengacu pada operasi di mana nilai baru dihitung dengan meringkas informasi dari beberapa catatan dan/atau tabel. Misalnya, mengonversi tabel pembelian pelanggan di mana terdapat satu catatan untuk setiap pembelian menjadi tabel baru di mana terdapat satu catatan untuk setiap pelanggan, dengan bidang seperti jumlah pembelian, jumlah pembelian rata-rata, persentase pesanan yang dibebankan ke kartu kredit, persentase item yang sedang dalam promosi, dll.