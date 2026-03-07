# 📑 Laporan Praktikum Minggu 5: Decision Tree & Random Forest

**Informasi Mahasiswa:**

* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]
* **Link Pull Request GitHub:** [Paste Link PR Tugas Anda]

---

## 1. Pendahuluan & Konsep Dasar

Jelaskan dengan ringkas pemahaman Anda mengenai:

1. Apa itu **Gini Impurity** dan bagaimana algoritma menggunakannya untuk membelah data?
2. Mengapa **Random Forest** sering kali lebih akurat dan lebih stabil (tidak mudah *overfitting*) dibandingkan satu pohon keputusan tunggal?

> **Jawaban:** (Tulis penjelasan Anda di sini)

---

## 2. Analisis Visual Decision Tree (Dataset Wine)

Berdasarkan hasil `plot_tree` pada Blok 3 di Notebook Anda:

1. **Root Node:** Fitur apa yang digunakan untuk pembelahan pertama kali? Mengapa fitur tersebut dipilih sebagai "akar"?
2. **Kedalaman Pohon:** Sebutkan fitur yang muncul di kedalaman ke-2.
3. **Purity:** Temukan satu kotak "Leaf Node" (ujung pohon). Berapa nilai Gini-nya? Jelaskan apa arti nilai Gini tersebut.

> **Jawaban:** (Tulis analisis visual Anda di sini)

---

## 3. Perbandingan Model: Tree vs Forest

Isi tabel perbandingan akurasi berdasarkan eksperimen pada dataset Wine:

| Model | Accuracy Score | Kelebihan/Kekurangan |
| --- | --- | --- |
| **Decision Tree (Single)** | ... | ... |
| **Random Forest (Ensemble)** | ... | ... |

**Analisis:** Mengapa terdapat perbedaan akurasi di antara keduanya? Manakah yang lebih Anda percayai untuk digunakan pada data baru?

---

## 4. Tugas Inti: Random Forest vs Titanic (Kritis)

Berdasarkan tugas implementasi pada dataset Titanic:

**A. Hyperparameter Tuning:**
Tuliskan hasil akurasi saat Anda mengubah jumlah pohon (`n_estimators`):

* `n_estimators = 10`  : [Isi Akurasi]
* `n_estimators = 50`  : [Isi Akurasi]
* `n_estimators = 200` : [Isi Akurasi]
* **Analisis:** Apakah menambah jumlah pohon selalu meningkatkan akurasi secara signifikan?

**B. Feature Importance (Wajib):**
Lihat grafik tingkat kepentingan fitur yang Anda hasilkan.

1. Sebutkan 3 fitur paling penting menurut model Random Forest Anda!
2. **Analisis Kritis:** Pada Minggu 4 (Logistic Regression), fitur `Sex` mungkin terlihat sangat dominan. Di Random Forest Minggu 5 ini, apakah fitur seperti `Fare` (Harga Tiket) atau `Age` (Umur) naik tingkat kepentingannya? Mengapa model berbasis pohon bisa melihat hubungan yang tidak tertangkap oleh model linear?

> **Jawaban:** (Tulis analisis kritis fitur di sini)

---

## 5. Perbandingan dengan Minggu 4

Bandingkan performa **Logistic Regression (Minggu 4)** dan **Random Forest (Minggu 5)** untuk kasus Titanic.

* Model mana yang memberikan akurasi lebih tinggi?
* Berdasarkan pemahaman Anda, mengapa dataset Titanic mungkin lebih cocok diselesaikan dengan algoritma berbasis "pohon" daripada "garis linear"?

> **Jawaban:** (Tulis refleksi perbandingan di sini)

---

## 6. Dokumentasi Weights & Biases (W&B)

Lampirkan *screenshot* dashboard W&B Anda yang menunjukkan perbandingan metrik antara Decision Tree dan Random Forest.

> **[Tempel Screenshot W&B Anda di Sini]**

---

## 7. Kesimpulan & Refleksi

Apa hal paling menarik yang Anda pelajari tentang cara "berpikir" sebuah pohon keputusan? Apa kendala teknis yang Anda temui selama praktikum ini?

---

### Instruksi Pengumpulan:

1. Lengkapi laporan ini dengan analisis mendalam.
2. Simpan sebagai **PDF** atau **Markdown** (`.md`).
3. Pastikan folder tugas Anda rapi: `assignments/week-5/NIM_NAMA/` berisi file `.ipynb` dan laporan ini.
4. Lakukan **Pull Request** ke repositori utama.

---
