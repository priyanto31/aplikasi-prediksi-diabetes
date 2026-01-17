# Pembelajaran Mesin

Selamat datang di repositori Pembelajaran Mesin! Repositori ini berisi koleksi notebook Google Colab yang mendokumentasikan perjalanan dalam mempelajari berbagai konsep dan algoritma Pembelajaran Mesin.

## Daftar Isi

- [Pendahuluan](#pendahuluan)
- [Struktur Repositori](#struktur-repositori)
- [Persyaratan Sistem](#persyaratan-sistem)
- [Cara Menggunakan](#cara-menggunakan)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

## Pendahuluan

Ini adalah bagian mengenai praktik Pembelajaran Mesin dari materi perkuliahan. Tujuan utama repositori ini adalah untuk menyimpan dan berbagi kode, analisis, serta eksperimen yang lakukan selama proses belajar. Setiap notebook dirancang untuk fokus pada topik atau algoritma tertentu, mulai dari dasar-dasar pembersihan data hingga implementasi model-model canggih.

## Struktur Repositori

Setiap folder dalam repositori ini mewakili sebuah pertemuan (pertemuan) atau topik utama, dan di dalamnya terdapat notebook-notebook (`.ipynb`) yang relevan.

- `Pertemuan 2 - Mengambil Data dari Kaggle.ipynb`: Contoh penggunaan API Kaggle untuk mengunduh dataset dan persiapan data awal.
- `Pertemuan 3 - Data Cleaning dan Feature Selection.ipynb`: Pembahasan tentang teknik pembersihan data dan pemilihan fitur menggunakan Pearson Correlation, Chi Square, RFE, dan Embedded methods.
- `Pertemuan 4 - Algoritma Supervised Learning (Klasifikasi) : Naïve Bayes dan Decision Tree.ipynb`: Implementasi dan evaluasi model klasifikasi Naïve Bayes dan Decision Tree.
- `Pertemuan 5 - Algoritma Supervised Learning: Logistic Regression, SVM dan k-NN.ipynb`: Implementasi dan evaluasi model klasifikasi Logistic Regression, Support Vector Machine (SVM), dan k-Nearest Neighbors (k-NN).
- `Pertemuan 6 - Algoritma Supervised Learning (Regresi).ipynb`: Eksplorasi berbagai algoritma regresi seperti Simple Linear Regression, Multiple Linear Regression, Lasso Regression, Random Forest Regressor, dan SVR.
- `Pertemuan 7 - Unsupervised Learning (Clustering).ipynb`: Implementasi algoritma clustering seperti K-Means, Hierarchical Clustering, dan DBSCAN.
- `Pertemuan 9 - Algortima Neural Network (ANN).ipynb`: Pengenalan dan implementasi dasar Artificial Neural Network menggunakan scikit-learn dan TensorFlow/Keras.
- `Pertemuan 11 - Deployment.ipynb`: Contoh deployment model Pembelajaran Mesin menggunakan Flask dan Gradio.

## Persyaratan Sistem

Untuk menjalankan notebook-notebook ini, Kita memerlukan Python environment dengan library berikut:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow` (untuk ANN)
- `keras` (untuk ANN)
- `gradio` (untuk deployment)
- `flask` (untuk deployment)

Anda dapat menginstal semua library tersebut menggunakan `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras gradio flask
```

Alternatifnya, karena sebagian besar notebook ini dirancang untuk Google Colab, Kalian cukup membukanya di lingkungan Colab, dan semua dependensi biasanya sudah tersedia atau dapat diinstal dengan mudah.

## Cara Menggunakan

1.  **Clone Repositori**: Salin repositori ini ke mesin lokal Anda.
    ```bash
    git clone https://github.com/bayhaqy/Pembelajaran_Mesin.git
    ```

2.  **Buka di Google Colab**: Cara termudah adalah membuka file `.ipynb` langsung di Google Colab. Klik pada file notebook di GitHub, lalu klik tombol "Open in Colab" (jika tersedia) atau unduh dan unggah secara manual ke Colab.

3.  **Jalankan Secara Lokal**: Jika Anda ingin menjalankan secara lokal, pastikan Anda telah menginstal semua [Persyaratan Sistem](#persyaratan-sistem), lalu gunakan Jupyter Notebook atau JupyterLab:
    ```bash
    jupyter notebook
    ```
    Kemudian navigasikan ke folder repositori dan buka notebook yang diinginkan.

## Kontribusi

Saran dan kontribusi sangat diterima! Jika Kalian memiliki ide untuk perbaikan, penambahan topik, atau menemukan _bug_, jangan ragu untuk membuat _issue_ atau mengirimkan _pull request_.

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
# aplikasi-prediksi-diabetes
Tujuan dari proyek ini adalah untuk mengembangkan model machine learning yang mampu memprediksi kemungkinan terjadinya diabetes
