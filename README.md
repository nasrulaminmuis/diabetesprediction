<div align="center">

# 🩺 Diabetes Prediction App

**Aplikasi prediksi diabetes berbasis Machine Learning menggunakan K-Nearest Neighbors (KNN)**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Tentang Proyek

Aplikasi ini memprediksi kemungkinan seorang pasien menderita **diabetes** berdasarkan data medis klinis. Dibangun menggunakan algoritma **K-Nearest Neighbors (KNN)** dan dideploy sebagai web app interaktif dengan **Streamlit**.

Model dilatih menggunakan dataset **Pima Indians Diabetes** yang merupakan dataset standar dalam penelitian prediksi diabetes.

---

## ✨ Fitur Utama

- 🔍 **Prediksi Real-Time** – Masukkan data medis dan dapatkan hasil prediksi instan
- 🎯 **Model KNN** – Algoritma K-Nearest Neighbors yang terlatih dan siap pakai
- 📊 **8 Indikator Medis** – Analisis berdasarkan parameter klinis yang komprehensif
- 🖥️ **Antarmuka Intuitif** – UI yang bersih dan mudah digunakan dengan Streamlit
- ✅ **Hasil Visual** – Tampilan hasil yang jelas dengan warna merah (positif) dan hijau (negatif)

---

## 🧪 Parameter Input

| No. | Parameter | Deskripsi | Rentang |
|-----|-----------|-----------|---------|
| 1 | **Pregnancies** | Jumlah kehamilan | 0 – 20 |
| 2 | **Glucose** | Kadar glukosa darah | 0 – 200 |
| 3 | **Blood Pressure** | Tekanan darah (mm Hg) | 0 – 150 |
| 4 | **Skin Thickness** | Ketebalan kulit (mm) | 0 – 100 |
| 5 | **Insulin** | Kadar insulin (mu U/ml) | 0 – 1000 |
| 6 | **BMI** | Indeks Massa Tubuh | 0.0 – 70.0 |
| 7 | **DPF** | Diabetes Pedigree Function | 0.0 – 2.5 |
| 8 | **Age** | Usia (tahun) | 1 – 120 |

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|-----------|----------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Bahasa pemrograman utama |
| ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?logo=streamlit&logoColor=white) | Framework web app interaktif |
| ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&logoColor=white) | Library machine learning |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white) | Komputasi numerik |
| ![joblib](https://img.shields.io/badge/-joblib-lightgrey) | Serialisasi model ML |

---

## 🚀 Cara Menjalankan

### Prasyarat

Pastikan Python 3.8+ sudah terinstal di sistem Anda.

### 1. Clone Repository

```bash
git clone https://github.com/nasrulaminmuis/diabetesprediction.git
cd diabetesprediction
```

### 2. Install Dependensi

```bash
pip install -r requirements.txt
```

### 3. Jalankan Aplikasi

```bash
streamlit run app.py
```

### 4. Buka di Browser

Aplikasi akan terbuka secara otomatis di browser, atau akses manual di:

```
http://localhost:8501
```

---

## 📁 Struktur Proyek

```
diabetesprediction/
├── app.py                  # Aplikasi Streamlit utama
├── diabetes_model.pkl      # Model KNN yang sudah dilatih
├── requirements.txt        # Daftar dependensi Python
└── README.md               # Dokumentasi proyek
```

---

## ⚙️ Cara Kerja Aplikasi

```
┌─────────────────┐     ┌──────────────────┐     ┌─────────────────┐
│  Input Data      │ --> │  Model KNN        │ --> │  Hasil Prediksi │
│  Medis Pasien    │     │  (diabetes_model  │     │  ✅ Tidak Diabetes│
│  (8 parameter)   │     │   .pkl)           │     │  ❌ Positif Diabetes│
└─────────────────┘     └──────────────────┘     └─────────────────┘
```

1. **Input** – Pengguna memasukkan 8 parameter medis melalui form
2. **Proses** – Data diformat sebagai array NumPy dan diproses oleh model KNN
3. **Output** – Aplikasi menampilkan hasil prediksi dengan indikator visual berwarna

---

## 📊 Tentang Model

- **Algoritma:** K-Nearest Neighbors (KNN)
- **Parameter:** `k = 2` neighbors
- **Tipe:** Binary Classification
- **Dataset:** Pima Indians Diabetes Dataset
- **Output:** `0` = Tidak Diabetes | `1` = Positif Diabetes

---

## 👤 Author

**Nasrul Amin Muis**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nasrulaminmuis)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<div align="center">

⭐ **Jika proyek ini bermanfaat, berikan bintang di GitHub!** ⭐

</div>
