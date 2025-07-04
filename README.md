Data : https://www.kaggle.com/datasets/alfanme/indonesian-batik-motifs-corak-app
🧵 Klasifikasi Batik dengan CNN (Convolutional Neural Network)
Proyek ini bertujuan untuk membangun model klasifikasi citra menggunakan Convolutional Neural Network (CNN) untuk mengidentifikasi jenis-jenis batik dari gambar. Model dilatih untuk mengenali pola-pola visual khas dari masing-masing kelas.

📂 Struktur Proyek
##Klasifikasi Batik.ipynb: Notebook utama yang berisi proses pemuatan data, preprocessing, pelatihan model CNN, evaluasi, serta visualisasi hasil.

Folder dataset:

/train/: Gambar latih, diklasifikasikan ke dalam folder subkelas.

/test/: Gambar uji untuk mengevaluasi performa model.

File hasil:

Confusion Matrix dan akurasi model

Visualisasi prediksi

Grafik training loss dan accuracy per epoch

🔧 Teknologi dan Library
Notebook ini menggunakan stack berikut:

Python

TensorFlow / Keras

NumPy

Matplotlib

Seaborn

scikit-learn

PIL (Python Imaging Library)

🚀 Langkah Utama dalam Notebook
Pemuatan dan Visualisasi Dataset

Menampilkan contoh gambar dari setiap kelas batik.

Preprocessing Data

Resize gambar ke ukuran seragam (150x150 piksel)

Normalisasi nilai pixel (0–1)

One-hot encoding pada label kelas

Arsitektur Model CNN

Dense layer dengan fungsi aktivasi ReLU dan Softmax

Optimizer: Adam

Loss function: Categorical Crossentropy

Pelatihan Model

Evaluasi akurasi dan loss pada data latih dan validasi

Visualisasi proses training dengan plot kurva

Evaluasi Model

Menggunakan confusion matrix dan classification report

Menampilkan beberapa prediksi model terhadap data uji

🧠 Potensi Pengembangan
Menambahkan augmentasi data untuk memperluas generalisasi model

Menggunakan arsitektur CNN yang lebih kompleks seperti ResNet atau MobileNet

Penerapan model ini dalam bentuk aplikasi klasifikasi gambar secara real-time
