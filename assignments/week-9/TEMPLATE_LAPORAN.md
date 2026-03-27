# 📑 Laporan Praktikum Minggu 9: Convolutional Neural Networks (CNN)

**Informasi Mahasiswa:**
* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Analisis Arsitektur CNN
Berdasarkan hasil `model.summary()` di Blok 3:
1. **Penyusutan Dimensi:** Mengapa ukuran data berubah dari $32 \times 32$ di tahap Input menjadi $15 \times 15$ setelah lapisan *MaxPooling2D* pertama? Jelaskan mekanisme matematisnya.
2. **Parameter:** Lapisan mana yang menyumbang jumlah parameter (bobot) terbesar? Mengapa lapisan *Dense* (klasifikasi) seringkali memiliki parameter jauh lebih banyak daripada lapisan *Conv2D* (ekstraksi fitur)?

> **Jawaban:** (Tulis analisis arsitektur Anda di sini)

---

## 2. Eksplorasi Proses Belajar (W&B Tracking)
Buka *dashboard* W&B Anda dan analisis grafik **epoch/loss** serta **epoch/accuracy**.
1. **Identifikasi Overfitting:** Perhatikan jarak antara grafik `accuracy` (latih) dan `val_accuracy` (uji). Apakah terjadi celah (*gap*) yang lebar? Jika ya, jelaskan mengapa model CNN cenderung lebih mudah menghafal data gambar dibandingkan data tabel.
2. **Stabilitas Pelatihan:** Apakah grafik *loss* menurun secara halus atau bergejolak? Apa saran Anda jika grafik *validation loss* tiba-tiba naik kembali setelah epoch ke-5?

> **Jawaban:** (Tulis analisis kurva belajar di sini)

---

## 3. Eksperimen Mandiri: Modifikasi Arsitektur
Lakukan satu modifikasi pada model (misal: menambah lapisan `Dropout`, mengubah jumlah filter, atau menambah lapisan `Conv2D`) dan bandingkan hasilnya.

| Komponen | Model Baseline | Model Eksperimen |
| :--- | :--- | :--- |
| **Arsitektur Ringkas** | 2x Conv + 2x Pool | [Isi Modifikasi Anda] |
| **Akurasi Data Uji** | [Misal 0.6987] | ... |
| **Kondisi (Overfit?)** | ... | ... |

**Analisis:** Apakah penambahan lapisan membuat model lebih pintar atau justru memperparah *overfitting*? Mengapa teknik **Dropout** sangat disarankan dalam arsitektur CNN yang dalam?

---

## 4. Analisis Kritis: Kegagalan Prediksi (Error Analysis)
Gunakan kode tambahan atau inspeksi manual untuk mencari **satu gambar** yang salah ditebak oleh model (misal: Gambar Kucing ditebak Anjing).
1. Lampirkan gambar tersebut.
2. Analisis secara visual: Fitur apa yang menurut Anda membuat AI bingung? (Misal: latar belakang rumput yang dominan, posisi objek yang miring, atau resolusi $32 \times 32$ yang terlalu rendah).

> **Jawaban:** (Tulis analisis kesalahan di sini)

---

## 5. Dokumentasi Weights & Biases (W&B)
Tempelkan *screenshot* dari *dashboard* W&B Anda yang menampilkan grafik **Accuracy** dan **Loss** secara berdampingan.

> **[Tempel Screenshot W&B Anda di Sini]**

---

## 6. Kesimpulan & Refleksi
1. Apa perbedaan mendasar yang Anda rasakan antara model MLP (Minggu 7) dan CNN (Minggu 9) dalam menangani data gambar?
2. Jika Anda ingin meningkatkan akurasi hingga >90% pada dataset CIFAR-10 ini, strategi apa yang akan Anda terapkan pada pertemuan berikutnya? (Hint: Data Augmentation atau Transfer Learning).

---

### Instruksi Pengumpulan:
1. Isi laporan dengan analisis teknis yang mendalam (bukan sekadar narasi singkat).
2. Kumpulkan dalam format **Markdown** (`.md`) atau **PDF**.
3. Lampirkan link Pull Request dari GitHub Anda.

---
