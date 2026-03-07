# Minggu 5: Decision Tree & Random Forest 🌲

## Tujuan Pembelajaran
1. Memahami konsep *Node*, *Branch*, dan *Leaf* pada Decision Tree.
2. Memahami metrik **Gini Impurity** atau **Entropy** sebagai dasar pembelahan data.
3. Mengenal fenomena *Overfitting* pada pohon yang terlalu dalam.
4. Memahami konsep **Ensemble Learning (Bagging)** melalui Random Forest.
5. Mengekstrak dan menganalisis **Feature Importance** (Tingkat Kepentingan Fitur).

## 1. Decision Tree (Pohon Keputusan)
Model ini bekerja seperti permainan "Tebak Siapa/Tebak Kata" dengan 20 pertanyaan. Algoritma akan mencari fitur yang paling baik dalam memisahkan kelas menggunakan **Gini Impurity**. Semakin rendah nilai Gini (mendekati 0), semakin murni kelas di simpul (*node*) tersebut.
Rumus Gini:
$$Gini = 1 - \sum_{i=1}^{c} (p_i)^2$$

## 2. Mengapa Random Forest?
Decision Tree sangat mudah terkena *Overfitting* (menghafal data latih tapi gagal di data baru). **Random Forest** memecahkan masalah ini dengan cara membuat ratusan "Pohon Keputusan" secara acak, lalu mengambil suara terbanyak (*Majority Voting*) dari pohon-pohon tersebut untuk menentukan hasil akhir.
