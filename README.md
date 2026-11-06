# Tugas UAS NLP: Advanced Natural Language Processing Portfolio

> Repositori komprehensif yang berisi serangkaian eksperimen dan implementasi model *Deep Learning* serta *Natural Language Processing* (NLP) tingkat lanjut, mulai dari teknik *Word Embedding*, arsitektur *Sequence-to-Sequence*, hingga model berbasis *Transformer* dan *Attention Mechanism*.

## 📌 Tentang Repositori
Repositori ini dikembangkan sebagai bagian dari eksplorasi dan penyelesaian studi kasus NLP tingkat lanjut. Proyek ini mendemonstrasikan pemahaman mendalam mengenai manipulasi teks, representasi vektor kata, pembangunan arsitektur *Neural Networks* dari awal (*from scratch*), hingga evaluasi performa model menggunakan Python dan TensorFlow/PyTorch.

---

## 🚀 Modul & Proyek Utama

### 1. Transformer Model (`Transformer.ipynb`)
* **Deskripsi:** Implementasi arsitektur *Transformer* berbasis *Multi-Head Attention* untuk pemodelan teks dan regresi, serta melakukan *benchmarking* performa langsung terhadap model *Encoder-Decoder* (LSTM).
* **Fitur & Alur Kerja:**
  * Preprocessing dan normalisasi data komprehensif (penanganan nilai kosong, *StandardScaler*, dan *Label Encoding*).
  * Pembangunan blok *Transformer* menggunakan layer `MultiHeadAttention`, *Layer Normalization*, dan *Dropout*.
  * Pelatihan model regresi dan evaluasi menggunakan metrik *Mean Absolute Error* (MAE).
* **Teknologi:** Python, TensorFlow / Keras, Scikit-Learn.

### 2. Word2Vec Embedding & Visualisasi (`Word2Vec.ipynb`)
* **Deskripsi:** Eksplorasi pembuatan representasi vektor kata (*word embedding*) menggunakan library `Gensim` pada korpus teks ulasan/komentar berbahasa Indonesia.
* **Fitur & Alur Kerja:**
  * Pembersihan korpus teks (*text cleaning*) dan tokenisasi menggunakan NLTK & Pandas.
  * Pelatihan model `Word2Vec` (*Continuous Bag of Words / Skip-gram*), penyimpanan model (*save/load*), serta *continue training*.
  * *Sanity check* untuk mencari kemiripan kata (*similar words*).
  * Reduksi dimensi vektor tingkat lanjut menggunakan **UMAP** dan visualisasi interaktif dengan **Plotly**.
* **Teknologi:** Python, Gensim, NLTK, UMAP, Plotly, Pandas.

### 3. Sequence-to-Sequence (Seq2Seq) NMT (`text_seq2seq.ipynb`)
* **Deskripsi:** Implementasi model *Neural Machine Translation* (NMT) menggunakan arsitektur *Encoder-Decoder* berbasis LSTM untuk tugas penerjemahan bahasa.
* **Fitur & Alur Kerja:**
  * Pembersihan teks lanjutan, normalisasi Unicode, tokenisasi, dan *padding sequences*.
  * Pembangunan arsitektur LSTM berkapasitas tinggi untuk pemetaan urutan teks (*sequence mapping*).
  * Proses pelatihan stabil dan pengujian inferensi untuk penerjemahan kalimat secara akurat.
* **Teknologi:** Python, TensorFlow / Keras, NLTK.

---

## 🛠️ Tech Stack & Libraries
* **Bahasa Pemrograman:** Python
* **Deep Learning Frameworks:** TensorFlow, Keras, PyTorch
* **NLP & Utilities:** NLTK, Gensim, Scikit-Learn, Pandas, NumPy
* **Visualisasi & Reduksi Dimensi:** UMAP, Plotly, Matplotlib
* **Environment:** Google Colab

## ⚙️ Cara Menjalankan Proyek
1. Clone repositori ini ke perangkat lokal Anda:
   ```bash
   git clone [https://github.com/wiwindaaulia/Tugas_UAS_NLP.git](https://github.com/wiwindaaulia/Tugas_UAS_NLP.git)
