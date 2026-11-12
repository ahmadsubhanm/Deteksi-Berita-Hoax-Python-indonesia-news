# 🤖 Deteksi Berita Hoaks Menggunakan Metode Naive Bayes

Repository ini berisi proyek *Machine Learning* untuk mendeteksi dan mengklasifikasikan berita hoaks (palsu) maupun valid menggunakan algoritma **Naive Bayes** dalam bahasa pemrograman **Python**. Proyek ini diimplementasikan menggunakan Jupyter Notebook dan memanfaatkan dataset teks berita.

---

## 📂 Struktur Repository

* **`klasifikasi berita hoax.ipynb`** : Berkas Jupyter Notebook utama yang mencakup tahapan *data preprocessing*, ekstraksi fitur (*TF-IDF*), pelatihan model (*training*), hingga evaluasi akurasi menggunakan *Naive Bayes*.
* **`dataset_news.csv`** : Dataset teks berita yang digunakan sebagai sumber data latih dan data uji dalam model klasifikasi.

---

## 🛠️ Pustaka / Library yang Digunakan

Pastikan Anda telah menginstal beberapa pustaka Python berikut sebelum menjalankan kodenya:
* `pandas` (untuk manipulasi data)
* `numpy` (untuk komputasi numerik)
* `scikit-learn` (untuk algoritma Naive Bayes, TF-IDF Vectorizer, dan evaluasi model)
* `matplotlib` / `seaborn` (opsional, untuk visualisasi data)

Anda dapat menginstalnya melalui terminal menggunakan perintah:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
