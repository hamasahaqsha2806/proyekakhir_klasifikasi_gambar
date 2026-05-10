# Image Classification - Vehicle Image Classification Dataset

## Deskripsi Project

Project ini merupakan implementasi Convolutional Neural Network (CNN) untuk melakukan klasifikasi gambar hewan menggunakan dataset Vehicle Image Classification.

Model dikembangkan menggunakan TensorFlow dan Keras dengan arsitektur Sequential API yang terdiri dari beberapa layer Conv2D, MaxPooling2D, Flatten, Dense, Dropout, dan MobileNetV2.

Project ini dibuat sebagai submission pada kelas Belajar Fundamental Deep Learning.

---

## Dataset

Dataset yang digunakan:

Vehicle Image Classification Dataset by mohamedmaher5

Sumber dataset:
https://www.kaggle.com/datasets/mohamedmaher5/vehicle-classification/data

Dataset terdiri dari 7 kelas:
- Auto Rickshaw
- Bike
- Car
- Motorcycle
- Plane
- Ship
- Train

Jumlah dataset lebih dari 5000 gambar.

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
- GlobalAveragePooling2D
- BatchNormalization

Optimizer:
- Adam

Loss Function:
- categorical_crossentropy

Metrics:
- accuracy

---

## Hasil Training

Hasil training model:
- Training Accuracy : ~85%
- Validation Accuracy : 86.5%
- Testing Accuracy : 86.58%

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
