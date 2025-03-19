## **1. Business Understanding**  

Tahap **Business Understanding** dalam CRISP-DM bertujuan untuk memahami apa yang ingin dicapai dari perspektif analisis data. Dalam kasus **dataset IRIS**, tujuannya adalah untuk mengklasifikasikan spesies bunga iris berdasarkan karakteristiknya.  

---

### **1.1 Menilai Situasi**  

#### **Inventarisasi Sumber Daya**  
- **Personel**: Data scientist, peneliti botani, atau mahasiswa yang mempelajari machine learning.  
- **Data**: Dataset IRIS
- **Perangkat Keras**: Komputer atau server dengan kemampuan untuk menjalankan analisis data.  
- **Software Tool**: Python dengan pustaka seperti `pandas`, `seaborn`, `scikit-learn`.  

---

#### **Persyaratan, Asumsi, dan Kendala**  
- **Persyaratan**: Model harus mampu membedakan tiga spesies bunga iris (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) secara akurat.  
- **Asumsi**: Dataset yang digunakan sudah bersih, lengkap, dan mewakili populasi bunga iris di dunia nyata.  
- **Kendala**: Dataset IRIS relatif kecil dan mungkin tidak cukup kompleks untuk mencerminkan variasi alami spesies iris secara luas.  

---

#### **Risiko dan Kontinjensi**  
- **Risiko**: Jika fitur dalam dataset tidak cukup kuat untuk membedakan spesies, maka model mungkin tidak mencapai akurasi tinggi.  
- **Kontinjensi**: Jika akurasi rendah, dapat menggunakan teknik lain seperti **feature engineering** atau mencari dataset tambahan.  

---

#### **Biaya dan Manfaat**  
- **Biaya**: Waktu dan sumber daya yang digunakan untuk analisis.  
- **Manfaat**:  
  - Memahami pola karakteristik spesies bunga iris.  
  - Mengembangkan model klasifikasi yang dapat digunakan untuk aplikasi botani atau agrikultur.  

---

### **1.2 Menentukan Tujuan Penambangan Data**  

#### **Kriteria Keberhasilan Bisnis**  
- Mampu membedakan **setiap spesies berdasarkan fitur yang diberikan**.  
- Memberikan **wawasan biologis** tentang faktor utama yang membedakan spesies.  

#### **Kriteria Keberhasilan Penambangan Data**  
- Model **harus mencapai tingkat akurasi minimal (misalnya ≥90%)** dalam mengklasifikasikan spesies.  
- Menganalisis fitur mana yang **paling berpengaruh dalam membedakan spesies**.  

---

### **1.3 Merencanakan Proyek**  

#### **Tahapan yang Akan Dieksekusi**  
1. **Data Understanding** → Memahami struktur dataset, statistik deskriptif, dan eksplorasi visual.  
2. **Data Preparation** → Menangani outliers, missing values (jika ada), dan normalisasi data.  
3. **Modeling** → Membangun model klasifikasi menggunakan algoritma seperti **KNN**.  
4. **Evaluation** → Mengevaluasi akurasi model dengan **confusion matrix dan metrik lainnya**.  
5. **Deployment** → Jika diperlukan, mengimplementasikan model dalam aplikasi.  

