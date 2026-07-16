# 📊 Analisis Sentimen Ulasan Produk

## 📌 Tentang Proyek

Proyek ini merupakan implementasi analisis sentimen terhadap ulasan produk pada sebuah perusahaan e-commerce. Proyek ini bertujuan untuk mengolah data ulasan pelanggan, memberikan label sentimen menggunakan pendekatan rule-based sentiment analysis, menganalisis pola sentimen pelanggan, serta menghasilkan insight yang mendukung evaluasi kepuasan pelanggan dan pengambilan keputusan bisnis.

---

## 🎯 Tujuan Proyek

- Membersihkan dataset agar siap dianalisis.
- Memberikan label sentimen pada setiap ulasan pelanggan.
- Menganalisis pola sentimen pelanggan.
- Mengidentifikasi produk dengan jumlah ulasan negatif tertinggi.
- Menyajikan insight melalui visualisasi data.
- Memberikan rekomendasi bisnis berdasarkan hasil analisis.

---

## 📂 Dataset

Dataset berisi data ulasan pelanggan pada sebuah platform e-commerce.

Dataset terdiri dari beberapa atribut, antara lain:

- Review ID
- User ID
- Product ID
- Review Text
- Rating
- Review Date

Pada tahap data understanding ditemukan:

- 105 data
- 6 atribut
- 12 missing value
- 5 data duplikat

Seluruh data dibersihkan sebelum dilakukan analisis lebih lanjut.

---

## 🔒 Privasi Data

Dataset yang digunakan merupakan dataset untuk keperluan pembelajaran dan uji kompetensi. Tidak terdapat informasi pribadi pelanggan yang dapat digunakan untuk mengidentifikasi individu.

---

## 🛠️ Tools yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Microsoft PowerPoint

---

## 📚 Library Python

- pandas
- numpy
- matplotlib.pyplot

---

## 🔍 Tahapan Analisis

### 1. Data Understanding

- Memahami struktur dataset.
- Mengidentifikasi missing value.
- Mengidentifikasi data duplikat.
- Melakukan statistik deskriptif.

### 2. Data Cleaning

- Menghapus data duplikat.
- Menangani missing value.
- Mengubah format tanggal menjadi YYYY-MM-DD.

### 3. Rule-Based Sentiment Labeling

Pelabelan sentimen dilakukan menggunakan pendekatan berbasis kata kunci (Rule-Based Sentiment Analysis).

Kategori sentimen:

- Positif
- Negatif
- Netral

### 4. Exploratory Data Analysis (EDA)

Analisis dilakukan untuk mengetahui:

- Distribusi label sentimen.
- Tren review berdasarkan waktu.
- Distribusi rating.
- Hubungan antara rating dan label sentimen.
- Produk dengan jumlah ulasan negatif terbanyak.

### 5. Data Visualization

Visualisasi yang dibuat meliputi:

- Tren review per bulan.
- Distribusi label sentimen.
- Distribusi rating berdasarkan sentimen.
- Top 5 produk dengan ulasan negatif terbanyak.

---

## 📊 Dashboard / Visualisasi

Tambahkan screenshot visualisasi pada folder:

```text
images/
```

Contoh:

```
images/
├── trend_review.png
├── distribusi_sentimen.png
├── distribusi_rating.png
└── top_produk_negatif.png
```

---

## 💡 Insight Utama

- Dataset awal terdiri dari 105 data dengan 12 missing value dan 5 data duplikat sehingga diperlukan proses data cleaning sebelum analisis.
- Sentimen negatif memiliki jumlah sedikit lebih banyak dibandingkan sentimen positif.
- Rating tidak selalu mencerminkan isi ulasan, karena ditemukan beberapa review dengan rating tinggi tetapi memiliki sentimen negatif.
- Produk P15 dan P11 menjadi produk dengan jumlah ulasan negatif terbanyak sehingga menjadi prioritas evaluasi.

---

## 🚀 Business Recommendation

- Memprioritaskan evaluasi terhadap produk P15 dan P11.
- Melakukan investigasi terhadap ketidaksesuaian antara rating dan isi ulasan.
- Tidak hanya menggunakan rating sebagai indikator kepuasan pelanggan, tetapi juga mempertimbangkan isi review.
- Memantau tren ulasan pelanggan secara berkala untuk mendeteksi potensi penurunan kepuasan pelanggan.

---

## 🔗 File Proyek

### 📄 Notebook Python

Notebook yang berisi proses data cleaning, pelabelan sentimen menggunakan pendekatan rule-based, exploratory data analysis (EDA), serta visualisasi data dapat diakses melalui tautan berikut:

👉 **[Lihat Notebook Python](https://github.com/septabagass/analisis-sentimen-ulasan-produk/blob/main/notebook/Analisis_Sentimen_Ulasan_Produk.ipynb)**

### 📊 Presentasi

Presentasi yang berisi ringkasan proses analisis, visualisasi, insight, dan business recommendation dapat diakses melalui tautan berikut:

👉 **[Lihat Presentasi Analisis](https://github.com/septabagass/analisis-sentimen-ulasan-produk/blob/main/Analisis_Sentimen_Ulasan_Produk_BNSP.pdf)**

---

## 📁 Struktur Repository

```text
├── notebook/
│   └── Analisis_Sentimen_Ulasan.ipynb
│
├── dataset/
│   └── dataset_review.csv
│
├── Analisis_Sentimen_Ulasan_Produk.pdf
├── README.md
```

---

## 👨‍💻 Author

**Septa Bagas Setyawan**

- LinkedIn: https://www.linkedin.com/in/septabagass/
- GitHub: https://github.com/septabagass

---

⭐ Proyek ini dibuat sebagai bagian dari portofolio Data Scientist untuk menunjukkan kemampuan dalam data cleaning, sentiment analysis, exploratory data analysis (EDA), data visualization, serta penyusunan rekomendasi bisnis menggunakan Python.
