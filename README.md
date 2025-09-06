# 🌳 STUDI KOMPARASI KINERJA MODEL TRANSFER LEARNING DENSENET201, RESNET50, DAN VGG16 PADA CITRA SATELIT LANDSAT-8 UNTUK KLASIFIKASI HUTAN  

## 📖 Ringkasan
Repositori ini berisi implementasi dan hasil dari skripsi saya:  
**"STUDI KOMPARASI KINERJA MODEL TRANSFER LEARNING DENSENET201, RESNET50, DAN VGG16 PADA CITRA SATELIT LANDSAT-8 UNTUK KLASIFIKASI HUTAN"**  

Penelitian ini membandingkan tiga model transfer learning (**DenseNet201, ResNet50, dan VGG16**) untuk klasifikasi hutan dan non-hutan pada citra satelit **Landsat-8**. Studi kasus dilakukan di **Taman Buru Semidang Bukit Kabu, Provinsi Bengkulu**, yang merupakan kawasan konservasi yang terdampak deforestasi.  

## 🎯 Tujuan
- Mengevaluasi kinerja model **DenseNet201, ResNet50, dan VGG16** dalam mengklasifikasi hutan dan non-hutan.  
- Membandingkan akurasi dan performa ketiga model.  
- Menganalisis perubahan luas hutan di Taman Buru Semidang Bukit Kabu pada periode **2016–2020**.  

## 📂 Struktur Repositori
```
📁 Data Penelitian Sebelumnya   # Data rujukan penelitian terdahulu
📁 Dataset                      # Dataset citra Landsat-8
📁 Evaluasi                     # Hasil evaluasi model (confusion matrix dan grafik training)
📁 Hasil Klasifikasi Raster     # Hasil klasifikasi raster
📁 Laporan dan Jurnal           # Laporan, jurnal, dan dokumentasi
📁 Model Revisi                 # Model revisi
📁 Notebook Revisi              # Notebook (Jupyter) untuk preprocessing & training
📁 Raster Revisi                # Raster hasil revisi

📄 Flowchart Penelitian.png     # Diagram alur penelitian
📄 Lembar Revisi Semhas.docx    # Catatan revisi seminar hasil
📄 Perbandingan Luas (Rev).xlsx # Tabel perbandingan perubahan luas hutan
📄 Sidang Skripsi.pptx          # Slide presentasi sidang
📄 lampiran *.jpeg / *.jpg      # Visualisasi hasil
```

## ⚙️ Metodologi
- **Kerangka**: CRISP-DM (Business Understanding → Data Understanding → Data Preparation → Modeling → Evaluation).  
- **Model**: DenseNet201, ResNet50, VGG16 (pre-trained pada ImageNet).  
- **Preprocessing**: Koreksi radiometrik, cloud masking, kombinasi band (4-3-2 natural view).  
- **Evaluasi**: Akurasi, Precision, Recall, F1-Score, Confusion Matrix.  

## 📊 Hasil
| Model      | Akurasi |
|------------|---------|
| DenseNet201 | **99,87%** ✅ |
| ResNet50    | 98,03% |
| VGG16       | 96,85% |

- **DenseNet201** memberikan performa terbaik dalam mendeteksi dan mengklasifikasi tutupan hutan.  
- Analisis perubahan luas hutan (2016–2020) di Taman Buru Semidang Bukit Kabu lebih akurat ketika menggunakan DenseNet201, sehingga lebih andal untuk pemantauan deforestasi.  

## 🛠️ Teknologi yang Digunakan
- Python (TensorFlow/Keras, NumPy, Pandas, Matplotlib)  
- Google Earth Engine  
- Jupyter Notebook  

## 📌 Kata Kunci
`Deep Learning` `Transfer Learning` `Penginderaan Jauh` `Landsat 8` `DenseNet201` `ResNet50` `VGG16` `Pemantauan Hutan`  
