# Image Classification - Animals10 Dataset

## Deskripsi Project

Project ini merupakan implementasi Convolutional Neural Network (CNN) untuk melakukan klasifikasi gambar hewan menggunakan dataset Animals10.

Model dikembangkan menggunakan TensorFlow dan Keras dengan arsitektur Sequential API yang terdiri dari beberapa layer Conv2D, MaxPooling2D, Flatten, Dense, dan Dropout.

Project ini dibuat sebagai submission pada kelas Belajar Fundamental Deep Learning.

---

## Dataset

Dataset yang digunakan:

Animals10 Dataset by alessiocorrado99

Sumber dataset:
https://www.kaggle.com/datasets/alessiocorrado99/animals10

Dataset terdiri dari 10 kelas hewan:
- Butterfly
- Cat
- Chicken
- Cow
- Dog
- Elephant
- Horse
- Sheep
- Spider
- Squirrel

Jumlah dataset lebih dari 13000 gambar.

---

## Pembagian Dataset

Dataset dibagi menjadi:
- Train Set : 70%
- Validation Set : 15%
- Test Set : 15%

---

## Arsitektur Model

Model CNN dibuat menggunakan:
- Sequential API
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- MobileNetV2

Optimizer:
- Adam

Loss Function:
- categorical_crossentropy

Metrics:
- accuracy

---

## Hasil Training

Hasil training model:
- Training Accuracy : 94.78%
- Validation Accuracy : 80.92%
- Testing Accuracy : 82.44%

> Ganti nilai XX sesuai hasil training Anda.

---

## Visualisasi Training

Project ini juga menampilkan:
- Plot Accuracy
- Plot Loss

untuk memantau performa model selama proses training.

---

## Format Model

Model berhasil dikonversi ke beberapa format:
- TensorFlow SavedModel
- TensorFlow Lite (TFLite)
- TensorFlow.js (TFJS)

---

## Struktur Folder

```text
submission/
├── tfjs_model/
│   ├── group1-shard1of1.bin
│   └── model.json
├── tflite/
│   ├── model.tflite
│   └── label.txt
├── saved_model/
│   ├── saved_model.pb
│   └── variables/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## Cara Menjalankan Project

### 1. Install Dependency

```bash
pip install -r requirements.txt
```

### 2. Jalankan Notebook

Buka file:

```text
notebook.ipynb
```

kemudian jalankan seluruh cell secara berurutan.

---

## Library yang Digunakan

- TensorFlow
- TensorFlowJS
- NumPy
- Matplotlib
- Split-Folders

---

## Author

Nama: Hamasah Fazal Aqsha

Proyek Akhir Klasifikasi Gambar
