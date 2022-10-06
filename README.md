# Laporan Proyek Machine Learning - Firda Sa'baniyah

## Domain Proyek

Sistem rekomendasi telah menjadi lazim dalam beberapa tahun terakhir karena menangani masalah kelebihan informasi dengan menyarankan pengguna produk yang paling relevan dari sejumlah besar data. Untuk produk media, rekomendasi film kolaboratif online berupaya membantu pengguna mengakses film pilihan mereka dengan menangkap tetangga yang persis sama di antara pengguna atau film dari peringkat umum historis mereka. Namun, karena data yang jarang, pemilihan tetangga menjadi lebih sulit dengan meningkatnya film dan pengguna dengan cepat. 
Sistem rekomendasi movie merupakan sistem yang merekomendasikan movie kepada penonton atau pengguna lainnya, rekomendasi ini contohnya diterapkan pada situs seperti netflix, iqiyi, dan wetv. Dalam proyek ini, diusulkan sistem rekomendasi film berbasis model collaborative filtering dan based filtering.  Sistem rekomendasi yang saya buat ini didasarkan pada peferensi kesukaan pengguna dimasa lalu, serta rating dari movie tersebut.
Hasil eksperimen pada dataset recommendation movie menunjukkan bahwa pendekatan yang diusulkan dapat memberikan kinerja tinggi dalam hal akurasi, dan menghasilkan rekomendasi film yang lebih andal dan personal jika dibandingkan dengan metode yang ada.


- Film adalah salah satu media hiburan yang populer di masyarakat. Banyaknya judul-judul yang telah rilis membuat masyarakat kesulitan untuk menemukan film mana yang mereka ingin tonton. Karena hal tersebut masalah ini perlu untuk diatasi. Sehingga informasi mengenai film akan memudahkan masyarakat untuk menemukan film yang cocok dengan preferensi user, oleh sebab itu user perlu sebuah sistem yang dapat memberikan rekomendasi film.  
- Sistem rekomendasi adalah sistem yang mampu memberikan rekomendasi item-item yang mungkin disukai oleh pengguna. Metode Collaborative Filtering merupakan salah satu metode pada sistem rekomendasi. Metode ini memanfaatkan penilaian pengguna lain berupa rating atau umpan balik lain untuk memprediksi item yang mungkin diminati. Collaborative filtering (CF) yang digunakan adalah metode User Based Collaborative Filtering. Penerapan dilakukan pada website merekomendasikan film-film untuk user menonton.
- Collaborative filtering merupakan sebuah metode dalam membuat prediksi dengan cara menyaring informasi
item dari opini pengguna lain. Ide utama dalam sistem rekomendasi collaborative filtering adalah untuk
memanfaatkan riwayat opini pengguna aktif lain untuk memprediksi item yang mungkin akan disukai/diminati
oleh seorang pengguna. Implementasi yang paling sederhana dari pendekatan ini adalah membuat rekomendasi
kepada pengguna aktif berdasarkan item yang disukai pengguna lain dengan riwayat selera yang serupa (Ricci,
Rokach, & Shapira, 2011). 

sumber : Nugraha, D., Purboyo, T. W., & Nugrahaeni, R. A. (2021). Sistem Rekomendasi Film Menggunakan Metode User Based Collaborative Filtering. eProceedings of Engineering, https://openlibrarypublications.telkomuniversity.ac.id/index.php/engineering/article/view/16513.


  
  Format Referensi: [Judul Referensi](https://scholar.google.com/) 

## Business Understanding

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Pernyataan Masalah 1
- Pernyataan Masalah 2
- Pernyataan Masalah n

### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
