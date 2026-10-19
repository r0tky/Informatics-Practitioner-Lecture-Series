# Webinar Implementation Projects 1–6

## 1. Webinar 1 — Make Sense of Data with Analysis and AI
**Notebook:** `1_Analisis_Penjualan_Toko.ipynb`

### Deskripsi
Implementasi analisis data penjualan untuk memahami pola data, mengidentifikasi produk dengan performa terbaik, serta menghasilkan insight yang dapat membantu pengambilan keputusan.

### Fitur Utama
- Membuat dan mengeksplorasi dataset penjualan.
- Memeriksa statistik deskriptif dan kualitas data.
- Menganalisis penjualan berdasarkan produk dan kategori.
- Memvisualisasikan tren penjualan mingguan.
- Menganalisis hubungan antarvariabel.
- Menghasilkan insight dan rekomendasi sederhana berdasarkan aturan.

### Alur Kerja Sistem
**Data penjualan → Persiapan data → Eksplorasi data → Analisis dan visualisasi → Identifikasi pola → Insight dan rekomendasi**
1. Sistem membuat dataset simulasi penjualan.
2. Data diperiksa menggunakan statistik deskriptif.
3. Sistem menganalisis penjualan berdasarkan produk dan kategori.
4. Hasil analisis ditampilkan melalui grafik.
5. Sistem mengidentifikasi pola penjualan.
6. Sistem menghasilkan insight dan rekomendasi sederhana berdasarkan aturan yang telah ditentukan.

### Output
Grafik penjualan, ringkasan statistik, pola penjualan, serta rekomendasi sederhana.

---

## 2. Webinar 2 — Bridging Global Infrastructure to Address Local Challenge with HPC
**Notebook:** `2_Simulasi_HPC.ipynb`

### Deskripsi
Implementasi eksperimen komputasi untuk memahami perbedaan pemrosesan serial dan paralel dalam menyelesaikan pekerjaan komputasi numerik.

### Fitur Utama
- Membuat dataset numerik dalam jumlah besar.
- Membagi data menjadi beberapa bagian.
- Melakukan pemrosesan serial.
- Melakukan pemrosesan paralel menggunakan beberapa proses.
- Mengukur waktu eksekusi.
- Membandingkan performa kedua metode.
- Memeriksa kesesuaian hasil komputasi.

### Alur Kerja Sistem
**Pembuatan data → Pembagian pekerjaan → Pemrosesan serial dan paralel → Pengukuran waktu → Perbandingan performa → Validasi hasil**
1. Sistem menghasilkan data numerik.
2. Data dibagi menjadi beberapa bagian.
3. Setiap bagian diproses secara berurutan pada pengujian serial.
4. Pekerjaan yang sama dibagi ke beberapa proses pada pengujian paralel.
5. Waktu eksekusi kedua metode diukur.
6. Sistem membandingkan waktu pemrosesan dan memeriksa kesesuaian hasil.

### Output
Waktu eksekusi, grafik perbandingan performa, rasio percepatan jika tercapai, dan validasi hasil komputasi.

---

## 3. Webinar 3 — Career and Competition in Industrial Era with GIS
**Notebook:** `3_GIS.ipynb`

### Deskripsi
Implementasi dasar Geographic Information System (GIS) untuk memetakan dan menganalisis persebaran fasilitas umum berdasarkan koordinat geografis.

### Fitur Utama
- Mengelola data lokasi berdasarkan latitude dan longitude.
- Memvisualisasikan persebaran lokasi.
- Menampilkan peta interaktif.
- Memfilter lokasi berdasarkan kategori fasilitas.
- Menghitung jarak garis lurus menggunakan rumus Haversine.
- Menampilkan ringkasan analisis spasial.

### Alur Kerja Sistem
**Data koordinat → Pengolahan data spasial → Visualisasi peta → Filter kategori → Perhitungan jarak → Ringkasan analisis geografis**
1. Sistem memuat data contoh fasilitas umum beserta koordinatnya.
2. Data dikelompokkan berdasarkan kategori.
3. Sistem menampilkan persebaran lokasi pada grafik dan peta interaktif.
4. Pengguna memilih kategori fasilitas untuk melihat lokasi terkait.
5. Sistem menghitung jarak garis lurus antarlokasi.
6. Hasil analisis dirangkum berdasarkan kategori dan jarak.

### Output
Peta interaktif, grafik persebaran lokasi, hasil filter, dan ringkasan analisis spasial.

---

## 4. Webinar 4 — Introduction to Machine Learning
**Notebook:** `4_Introduction_To_Machine_Learning.ipynb`

### Deskripsi
Implementasi klasifikasi spesies bunga menggunakan algoritma Decision Tree dan dataset Iris yang tersedia melalui Scikit-learn.

### Fitur Utama
- Memuat dan mengeksplorasi dataset.
- Memvisualisasikan hubungan antarfitur.
- Membagi data menjadi training dan testing.
- Melatih model Decision Tree Classifier.
- Melakukan prediksi spesies bunga.
- Mengevaluasi model menggunakan accuracy, precision, recall, F1-score, dan confusion matrix.
- Mencoba prediksi terhadap data bunga baru.

### Alur Kerja Sistem
**Dataset Iris → Eksplorasi data → Pembagian data → Pelatihan model → Prediksi → Evaluasi model**
1. Sistem memuat dataset Iris.
2. Data fitur dan label spesies dipisahkan.
3. Dataset dibagi menjadi data training dan testing.
4. Algoritma Decision Tree dilatih menggunakan data training.
5. Model memprediksi spesies pada data testing dan data baru.
6. Hasil prediksi dievaluasi menggunakan metrik klasifikasi.

### Output
Model klasifikasi, hasil prediksi spesies bunga, laporan klasifikasi, dan confusion matrix.

---

## 5. Webinar 5 — Human Computer Interaction dan Data Visualization
**Notebook:** `5_Deforestation.ipynb`

### Deskripsi
Implementasi visualisasi data dan dashboard interaktif untuk mengeksplorasi data simulasi gangguan hutan. Proyek ini menggabungkan penyajian informasi visual dengan interaksi pengguna.

### Fitur Utama
- Mengeksplorasi dataset dan statistik deskriptif.
- Memvisualisasikan distribusi penyebab gangguan hutan.
- Membandingkan luas gangguan berdasarkan penyebab.
- Menganalisis data berdasarkan wilayah.
- Menyediakan filter wilayah dan penyebab.
- Menampilkan indikator ringkasan, grafik interaktif, dan tabel data.
- Menerapkan prinsip dasar HCI, seperti kejelasan informasi, konsistensi antarmuka, dan umpan balik terhadap pilihan pengguna.

### Alur Kerja Sistem
**Dataset → Pengolahan data → Visualisasi → Interaksi pengguna → Pembaruan dashboard → Penyajian informasi**
1. Sistem memuat dataset simulasi gangguan hutan.
2. Data dianalisis berdasarkan penyebab dan wilayah.
3. Sistem menampilkan grafik dan indikator ringkasan.
4. Pengguna memilih wilayah dan penyebab melalui dropdown.
5. Sistem memfilter data berdasarkan pilihan pengguna.
6. Grafik, indikator, dan tabel diperbarui sesuai hasil filter.
7. Informasi ditampilkan dalam dashboard interaktif.

### Output
Dashboard interaktif, grafik dinamis, tabel hasil filter, dan ringkasan data.

---

## 6. Webinar 6 — Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI
**Notebook:** `6_ForestWatchAI.ipynb`

### Deskripsi
Implementasi prototipe klasifikasi kategori gangguan hutan menggunakan Random Forest sebagai pengenalan pendekatan Machine Learning dalam konteks pemantauan hutan.

### Fitur Utama
- Menyiapkan dataset simulasi gangguan hutan.
- Melakukan eksplorasi dan persiapan data.
- Melatih model Random Forest Classifier.
- Memprediksi kategori gangguan.
- Mengevaluasi performa klasifikasi.
- Menampilkan confusion matrix dan metrik evaluasi.
- Menyimpan hasil prediksi ke file CSV.

### Alur Kerja Sistem
**Dataset simulasi → Persiapan data → Pelatihan Random Forest → Prediksi kategori → Evaluasi model → Ringkasan hasil**
1. Sistem menyiapkan dataset simulasi yang mewakili karakteristik alert gangguan hutan.
2. Data dipersiapkan untuk proses klasifikasi.
3. Model Random Forest dilatih menggunakan data yang tersedia.
4. Model menghasilkan prediksi kategori gangguan.
5. Hasil prediksi dievaluasi menggunakan metrik klasifikasi.
6. Sistem menyajikan hasil evaluasi dan ringkasan prediksi.

### Output
Prediksi kategori gangguan, metrik evaluasi, confusion matrix, dan ringkasan klasifikasi.
Implementasi ini belum mencakup pemrosesan citra satelit nyata atau atribusi penyebab deforestasi langsung dari citra satelit.

---

## Alur Umum Seluruh Implementasi
Secara umum, keenam implementasi mengikuti pola berikut:
**Input data → Pengolahan data → Proses analisis atau komputasi → Visualisasi atau evaluasi → Output hasil**

Setiap implementasi memiliki tahapan khusus sesuai topik webinar:
| Webinar | Fokus proses | Hasil utama |
|---|---|---|
| 1 | Analisis data dan identifikasi pola | Insight dan rekomendasi |
| 2 | Komputasi serial dan paralel | Perbandingan performa |
| 3 | Pemetaan dan analisis spasial | Peta dan analisis geografis |
| 4 | Pelatihan dan evaluasi model | Prediksi klasifikasi |
| 5 | Interaksi pengguna dan visualisasi | Dashboard interaktif |
| 6 | Klasifikasi alert gangguan hutan | Prediksi dan evaluasi model |

## Teknologi yang Digunakan
- **Python** — bahasa pemrograman utama.
- **Google Colab** — lingkungan pengembangan notebook.
- **Pandas** — pengolahan dan analisis data.
- **NumPy** — komputasi numerik.
- **Matplotlib** — visualisasi data.
- **Plotly** — visualisasi interaktif.
- **Folium** — pemetaan geografis interaktif.
- **Scikit-learn** — pemodelan dan evaluasi Machine Learning.
- **Joblib** — pemrosesan paralel.
- **ipywidgets** — interaksi pengguna dalam notebook.


**Project Status:** Educational prototypes for Webinar 1–6.
