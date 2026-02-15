# CheckPoint-1-Data-Gathering-Business-Understanding

## Judul : Analisis Faktor-Faktor yang Mempengaruhi Harga Laptop di Pasar

## Import Library
https://colab.research.google.com/drive/1WBSl2lSK452JmKQantK1AXTsmYOn17rZ#scrollTo=xKIGbzaOEItv

## Memuat Dataset
https://www.kaggle.com/datasets/muhammetvarl/laptop-price

## Business Understanding

1. Business Objective
### Tujuan Bisnisnya : ###
adalah memahami variabel apa saja yang paling signifikan dalam menentukan harga sebuah laptop.

### Masalah utamanya : ###
Perbedaan harga laptop sangat bervariasi meskipun spesifikasinya terlihat mirip.
Konsumen sulit menentukan laptop terbaik sesuai budget.
Penjual belum tentu mengetahui faktor spesifikasi mana yang paling mempengaruhi harga.

3. Assess Situation
Kondisi Dataset :
Data memiliki campuran tipe data kuantitatif (harga, berat, RAM) dan kualitatif (merk, sistem operasi, tipe layar)
Dataset memiliki 1303 baris.
Beberapa kolom seperti RAM dan Storage masih mengandung satuan (GB/TB).
Tantangan Dataset :
Perlu cleaning data seperti menghapus simbol mata uang, satuan GB, dll.
Banyak fitur kategorikal (Brand, GPU, CPU) perlu encoding.
Potensi adanya outlier pada laptop kategori high-end atau gaming yang harganya jauh di atas rata-rata.
Resiko : Data tidak lengkap atau tidak konsisten.

4. Analytic Goals
Menganalisis distribusi harga laptop.
Membandingkan rata-rata harga berdasarkan brand.
Menganalisis hubungan antara (RAM dan Harga, Storage dan Harga, Berat dan Harga).
Mengidentifikasi spesifikasi yang paling berpengaruh terhadap harga.
Membuat model prediksi harga laptop.

5. Project Plan
Mengeksplorasi struktur data (baris dan kolom) serta tipe data setiap variabel.
Melakukan pembersihan data (cleaning) dari nilai yang hilang.
Membuat visualisasi awal seperti Scatter Plot untuk melihat hubungan spesifikasi dengan harga.
Membangun Dashboard interaktif menggunakan tools seperti Tableau.
