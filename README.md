# Klasifikasi Gambar Batu-Kertas-Gunting

## Tinjauan Umum
Proyek ini menunjukkan model klasifikasi gambar sederhana menggunakan TensorFlow dan Keras untuk mengklasifikasikan gambar tangan yang menunjukkan bentuk batu, kertas, atau gunting. Dataset yang digunakan untuk pelatihan dan validasi berasal dari dataset Batu-Kertas-Gunting yang disediakan oleh Dicoding Academy.

## Struktur File
- `rock_paper_scissors_classification.ipynb`: Notebook Jupyter yang berisi kode untuk persiapan data, pelatihan model, evaluasi, dan prediksi.
- `rockpaperscissors.zip`: File zip dataset yang berisi gambar batu, kertas, dan gunting.

## Cara Menggunakan
1. **Unduh Dataset**: Dataset disertakan dalam file `rockpaperscissors.zip`. Jika Anda perlu memperbarui dataset atau memulai dari awal, Anda dapat mengunduhnya dari sini.
2. **Jalankan Notebook Jupyter**: Buka dan jalankan notebook `rock_paper_scissors_classification.ipynb` Jupyter. Pastikan untuk memiliki pustaka dan dependensi yang diperlukan terpasang.
3. **Ikuti Langkah-langkah Notebook**:
   - Notebook dimulai dengan mengunduh dan mengekstrak dataset.
   - Kemudian mengorganisir data menjadi set pelatihan dan validasi.
   - Arsitektur model didefinisikan dan dilatih menggunakan set pelatihan.
   - Kinerja model dievaluasi pada set validasi.
   - Notebook juga mencakup bagian untuk memprediksi gambar baru.
4. **Sesuaikan Hyperparameter (Opsional)**: Jika diinginkan, Anda dapat bereksperimen dengan hyperparameter yang berbeda, seperti learning rate atau jumlah epoch, untuk berpotensi meningkatkan kinerja model.
5. **Evaluasi Kinerja Model**: Notebook menampilkan akurasi/loss pelatihan dan validasi sepanjang epoch dan memberikan evaluasi akhir pada set tes.
6. **Prediksi Gambar Baru**: Anda dapat mengunggah gambar baru di akhir notebook untuk melihat seberapa baik model yang telah dilatih memprediksinya.

## Dependensi
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Numpy
- Scikit-learn

## Credits
Dicoding Academy for providing the Rock-Paper-Scissors dataset.
