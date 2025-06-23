# Klasifikasi-Ekspresi-Wajah
Proyek ini bertujuan untuk mengklasifikasikan ekspresi wajah secara otomatis menggunakan teknik computer vision dan machine learning. Dengan memanfaatkan VGG16 sebagai feature extractor dan SVM sebagai model klasifikasi, proyek ini mampu mengenali beberapa jenis ekspresi wajah dari gambar.

---

## 🎯 Tujuan
- Memuat dan memproses dataset gambar wajah dari berbagai label ekspresi.
- Mengekstraksi fitur gambar secara efektif menggunakan arsitektur **VGG16**.
- Melatih model **Support Vector Machine (SVM)** untuk mengklasifikasikan jenis-jenis ekspresi wajah.
- Mengevaluasi model dan menampilkan contoh hasil prediksi.

---

## 🧠 Alur Proyek
1. **Preprocessing dan Loading Dataset**  
   Memuat gambar dan label dari direktori dataset menggunakan `OpenCV` dan `NumPy`.
2. **Ekstraksi Fitur**  
   Mengekstraksi fitur gambar menggunakan model pretrained **VGG16** untuk mempermudah proses klasifikasi.
3. **Klasifikasi**  
   - Melatih model SVM berbasis fitur.
   - Mengevaluasi performa model dan menampilkan contoh prediksi.
4. **Visualisasi**  
   Menampilkan contoh gambar acak beserta label prediksinya untuk melihat performa model secara langsung.

---

## 🛠️ Tools & Libraries
- **Python** (Jupyter Notebook)
- **NumPy** untuk manipulasi array
- **OpenCV (cv2)** untuk pengolahan gambar
- **VGG16 (Keras)** untuk ekstraksi fitur
- **Scikit-learn** untuk model SVM dan evaluasi

---

## Dataset Link
https://drive.google.com/file/d/1xvhXK6JIN441LJrlN4cVSG37QCmezHAY/view?usp=sharing 
