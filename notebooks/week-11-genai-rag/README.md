# Minggu 11: Generative AI & Retrieval-Augmented Generation (RAG) 🤖📚

## Tujuan Pembelajaran
1. Memahami konsep dasar **Large Language Models (LLM)**.
2. Memahami masalah **Hallucination** pada AI dan cara mengatasinya.
3. Mengimplementasikan arsitektur **RAG** untuk memberi "ingatan" baru pada AI.
4. Mengenal **Vector Databases** dan **Embeddings**.

## 1. Apa itu Generative AI?
Generative AI (seperti Gemini atau GPT) adalah model yang dilatih untuk memprediksi kata berikutnya dalam sebuah urutan. Model ini menggunakan arsitektur **Transformer** yang memiliki mekanisme *Attention* untuk memahami konteks kalimat yang panjang.



## 2. Retrieval-Augmented Generation (RAG)
LLM memiliki pengetahuan yang terbatas pada tanggal terakhir mereka dilatih (Knowledge Cut-off). **RAG** adalah teknik untuk memberikan dokumen eksternal (PDF, Database, Website) kepada AI sebelum ia menjawab, sehingga jawabannya lebih akurat dan faktual.

### Alur Kerja RAG:
1. **Load:** Mengambil dokumen (PDF/Teks).
2. **Split:** Memecah dokumen menjadi potongan kecil (Chunks).
3. **Embed:** Mengubah teks menjadi koordinat angka (Vectors).
4. **Store:** Menyimpan di Vector Database.
5. **Retrieve:** Mencari potongan teks paling relevan dengan pertanyaan user.
6. **Augment:** Mengirim teks tersebut ke LLM sebagai referensi jawaban.
