# Analisis Sentimen Biaya Pendidikan

## 📌 Deskripsi
Proyek ini bertujuan untuk melakukan **analisis sentimen terhadap opini mengenai biaya pendidikan** menggunakan pendekatan **Natural Language Processing (NLP)** dan *machine learning*.

Notebook utama yang digunakan:
`AnalisisSentimen-BiayaPendidikan.ipynb`

## 🎯 Tujuan
- Mengidentifikasi sentimen opini terkait biaya pendidikan.
- Melakukan pembersihan dan preprocessing data teks.
- Mengubah teks menjadi fitur numerik.
- Melakukan klasifikasi sentimen.
- Mengevaluasi performa model.

## 🔄 Tahapan Analisis
1. **Import Library**  
   Mengimpor library untuk pengolahan data, visualisasi, NLP, dan machine learning.

2. **Memuat Dataset**  
   Membaca dataset dan memahami struktur serta isi data.

3. **Data Preprocessing**  
   Membersihkan data teks melalui beberapa tahap seperti:
   - Case Folding
   - Cleaning
   - Tokenizing
   - Stopword Removal
   - Stemming

4. **Exploratory Data Analysis (EDA)**  
   Menganalisis distribusi data dan sentimen melalui statistik dan visualisasi.

5. **Feature Extraction**  
   Mengubah teks menjadi fitur numerik menggunakan **TF-IDF**.

6. **Pembagian Dataset**  
   Membagi data menjadi data *training* dan *testing*.

7. **Klasifikasi Sentimen**  
   Melatih model *machine learning* untuk mengklasifikasikan sentimen.

8. **Evaluasi Model**  
   Performa model dievaluasi menggunakan:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

## 🛠️ Teknologi
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Natural Language Processing (NLP)
- Jupyter Notebook / Google Colab

## 📂 Struktur Proyek
```text
.
├── AnalisisSentimen-BiayaPendidikan.ipynb
├── dataset/
│   └── dataset.csv
└── README.md
