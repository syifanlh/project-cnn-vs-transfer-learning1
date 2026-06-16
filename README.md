# project-cnn-vs-transfer-learning1
# Perbandingan CNN From Scratch dan Transfer Learning MobileNetV2 untuk Klasifikasi Citra

## Nama Mahasiswa
- Nama: Assyifa Nailah Abdullah
- NIM: 452024618077
- Program Studi: Teknik Informatika

## Deskripsi Project
Project ini bertujuan untuk membandingkan performa metode Convolutional Neural Network (CNN) From Scratch dan Transfer Learning menggunakan MobileNetV2 pada tugas klasifikasi citra. Eksperimen dilakukan menggunakan dataset CIFAR-10 untuk mengevaluasi akurasi, loss, serta efektivitas kedua pendekatan dalam menyelesaikan permasalahan klasifikasi gambar.

## Library yang Digunakan
Project ini menggunakan beberapa library Python, yaitu:

- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## Cara Menjalankan Notebook

1. Buka Google Colab atau Jupyter Notebook.
2. Upload file notebook (.ipynb).
3. Jalankan seluruh cell secara berurutan.
4. Tunggu proses training CNN From Scratch selesai.
5. Jalankan proses Transfer Learning menggunakan MobileNetV2.
6. Lihat hasil evaluasi berupa akurasi, loss, grafik, confusion matrix, dan contoh prediksi.

## Struktur Folder Project

```text
Project/
│
├── notebook.ipynb
├── laporan.pdf
├── README.md
├── images/
│   ├── cnn_accuracy.png
│   ├── cnn_loss.png
│   ├── cnn_confusion_matrix.png
│   ├── tl_accuracy.png
│   ├── tl_loss.png
│   └── tl_confusion_matrix.png
│
└── hasil/
    ├── prediksi_cnn.png
    └── prediksi_transfer_learning.png
```

## Ringkasan Hasil Eksperimen

| Model | Training Accuracy | Validation Accuracy | Testing Accuracy |
|---------|---------|---------|---------|
| CNN From Scratch | 77.55% | 70.66% | 70.00% |
| Transfer Learning (MobileNetV2) | 66.22% | 66.95% | 66.50% |

### Analisis Singkat
- CNN From Scratch menghasilkan akurasi testing yang lebih tinggi.
- Transfer Learning memiliki proses pelatihan yang lebih cepat dan lebih efisien.
- CNN lebih cocok ketika jumlah data besar tersedia.
- Transfer Learning lebih cocok ketika data dan waktu terbatas.

## Kesimpulan

Berdasarkan hasil eksperimen, CNN From Scratch memperoleh akurasi testing sebesar 70,00%, sedangkan Transfer Learning menggunakan MobileNetV2 memperoleh akurasi testing sebesar 66,50%. CNN memberikan performa yang lebih baik pada dataset yang digunakan, namun Transfer Learning menawarkan proses pelatihan yang lebih cepat dan mudah diterapkan. Pemilihan metode terbaik perlu mempertimbangkan ukuran dataset, sumber daya komputasi, dan kebutuhan aplikasi.
