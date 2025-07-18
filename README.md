# 🌿 Analisis Kesehatan Tumbuhan (Fuzzy Mamdani & Sugeno)

[![Lisensi: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Sebuah sistem cerdas untuk menganalisis tingkat kesehatan tumbuhan berdasarkan parameter lingkungan menggunakan logika fuzzy. Proyek ini mengimplementasikan dan membandingkan metode inferensi **Mamdani** dan **Sugeno**.

![Demo Aplikasi](URL_KE_SCREENSHOT_ATAU_GIF_DEMO_ANDA.gif)

## 🌟 Tentang Proyek

Proyek ini dibuat sebagai Tugas Besar untuk mata kuliah **Dasar Kecerdasan Artifisial**. Tujuannya adalah membangun model yang mampu mengolah data lingkungan yang tidak pasti (seperti kelembapan dan intensitas cahaya) untuk menghasilkan diagnosis kesehatan tanaman yang akurat.

### 🛠️ Dibangun Menggunakan

* **Python**: Bahasa utama yang digunakan.
* **Pandas**: Untuk manipulasi dan pra-pemrosesan data.
* **Numpy**: Untuk operasi numerik.
* **Scikit-fuzzy**: Library untuk implementasi logika fuzzy.

## ✨ Fitur Utama

* **Seleksi Data**: Memilih parameter input yang relevan seperti Kelembapan Tanah, Intensitas Cahaya, dan Kandungan Klorofil.
* **Implementasi Mamdani**: Model dengan output linguistik yang intuitif.
* **Implementasi Sugeno**: Model yang efisien secara komputasi.
* **Evaluasi Model**: Membandingkan akurasi dan kinerja kedua model menggunakan metrik seperti *precision*, *recall*, dan *confusion matrix* .

## 🚀 Cara Menjalankan Proyek

1.  **Clone repositori ini**
    ```sh
    git clone https://github.com/username/nama-repositori.git
    ```
2.  **Masuk ke direktori proyek**
    ```sh
    cd nama-repositori
    ```
3.  **Install dependensi yang dibutuhkan**
    ```sh
    pip install -r requirements.txt
    ```
4.  **Jalankan file notebook utama**
    Buka dan jalankan `nama_file.ipynb` menggunakan Jupyter Notebook atau Google Colab.

## 📈 Hasil

Berdasarkan evaluasi terhadap 1200 data, kedua model menunjukkan performa yang mirip dengan **akurasi 75%**. Namun, model Mamdani terbukti sedikit lebih andal dan konsisten di semua kelas pengujian.

| Model   | Akurasi | Rata-rata F1-Score |
|---------|---------|--------------------|
| Mamdani | 75%     | 0.74               |
| Sugeno  | 75%     | 0.74               |

## 🧑‍🤝‍🧑 Tim Penyusun
| Nama Anggota                 | Username Github |
|------------------------------|-----------------|
| Sitti Fadhillah Nur Ahsan    | [@dicodella](https://github.com/dicodella)      |
| Aisya Zahra                  | [@isaffectionate](https://github.com/isaffectionate) |
| Ameta Noveolyn               | @               |

## 🤝 Kontribusi

Kontribusi sangat kami hargai! Jika Anda memiliki saran untuk membuat proyek ini lebih baik, silakan lakukan *fork* repositori dan buat *pull request*. Jangan lupa untuk memberikan bintang jika proyek ini membantu Anda! ⭐

## 📝 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file `LICENSE` untuk detailnya.
