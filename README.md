# 🏞️ Deep Learning Place Classification

Model Deep Learning untuk mengklasifikasikan gambar pemandangan berdasarkan kategori tempat menggunakan TensorFlow dan Convolutional Neural Network (CNN).

## 📖 Tentang Proyek

Proyek ini dikembangkan untuk mengenali dan mengklasifikasikan gambar ke dalam beberapa kategori tempat secara otomatis menggunakan teknologi Deep Learning.

Model dilatih menggunakan Intel Image Classification Dataset yang berisi ribuan gambar pemandangan dari berbagai kategori lingkungan.

## 🎯 Tujuan

- Membangun model klasifikasi gambar berbasis CNN
- Menerapkan proses preprocessing dan data augmentation
- Mengevaluasi performa model pada data validasi dan pengujian
- Mengekspor model ke berbagai format deployment

## 🗂️ Dataset

Dataset yang digunakan:

Intel Image Classification Dataset

Kategori gambar:

| No | Kelas |
|----|--------|
| 1 | Buildings |
| 2 | Forest |
| 3 | Glacier |
| 4 | Mountain |
| 5 | Sea |
| 6 | Street |

Sumber Dataset:
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

---

## 🛠️ Teknologi yang Digunakan

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-Learn

---

## 📁 Struktur Repository

```text
submission_Shava/
│
├── Proyek_Klasifikasi_Gambar_Intel_Image_Classification.ipynb
├── requirements.txt
├── saved_model/
├── tflite/
└── README.md
```

### Keterangan

| File / Folder | Deskripsi |
|---------------|-----------|
| Notebook | Berisi seluruh proses pengembangan model |
| requirements.txt | Daftar library yang digunakan |
| saved_model | Model hasil training dalam format TensorFlow SavedModel |
| tflite | Model TensorFlow Lite untuk deployment mobile |

---

## 🔄 Tahapan Pengembangan

1. Data Loading
2. Data Preprocessing
3. Data Augmentation
4. Data Splitting
5. Model Development
6. Model Training
7. Model Evaluation
8. Model Export

---

## 🚀 Cara Menjalankan Proyek

### Clone Repository

```bash
git clone https://github.com/shavel28/deep-learning-place-classification.git
```

### Install Dependency

```bash
pip install -r requirements.txt
```

### Jalankan Notebook

```bash
jupyter notebook
```

Kemudian buka file:

```text
Proyek_Klasifikasi_Gambar_Intel_Image_Classification.ipynb
```

---

## 📊 Hasil

Model berhasil dilatih untuk melakukan klasifikasi gambar ke dalam 6 kategori tempat menggunakan pendekatan Convolutional Neural Network (CNN).

Model telah diekspor ke format:

- TensorFlow SavedModel
- TensorFlow Lite (TFLite)

---

## 👩‍💻 Author

**Shava Selvia Ramadhani S**

Mahasiswa Teknik Informatika  
Politeknik Negeri Jember

GitHub:
https://github.com/shavel28

---

⭐ Jika repository ini bermanfaat, jangan ragu memberikan star pada repository ini.
