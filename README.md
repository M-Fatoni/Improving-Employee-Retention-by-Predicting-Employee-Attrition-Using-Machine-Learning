# Overview

Sumber daya manusia (SDM) adalah aset utama yang perlu dikelola dengan baik oleh perusahaan agar tujuan bisnis dapat tercapai dengan efektif dan efisien. Pada kesempatan kali ini, kita akan menghadapi sebuah permasalahan tentang sumber daya manusia yang ada di perusahaan. Fokus kita adalah untuk mengetahui bagaimana cara menjaga karyawan agar tetap bertahan di perusahaan yang ada saat ini yang dapat mengakibatkan bengkaknya biaya untuk rekrutmen karyawan serta pelatihan untuk mereka yang baru masuk. Dengan mengetahui faktor utama yang menyebabkan karyawan tidak merasa, perusahaan dapat segera menanggulanginya dengan membuat program-program yang relevan dengan permasalahan karyawan. 

# Insights

## 1. Annual Report on Employee Number Changes

![img 1](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/annual%20report%20on%20employee%20number%20changes.JPG)

### Analisis Kesehatan Perusahaan Berdasarkan Jumlah Karyawan.
**Periode 2006 – 2011: Pertumbuhan dan Ekspansi.**
- Pertumbuhan Stabil: Jumlah karyawan yang masuk meningkat setiap tahun, mencapai puncaknya pada tahun 2011 dengan 76 karyawan baru.
- Tidak Ada Pengunduran Diri: Tidak ada karyawan yang keluar selama periode ini, menunjukkan bahwa perusahaan mampu mempertahankan karyawannya dengan baik.
- Ekspansi Signifikan: Lonjakan besar dalam rekrutmen pada tahun 2011 menunjukkan ekspansi besar atau inisiatif rekrutmen yang berhasil.
- Kondisi Perusahaan: Sehat dan berkembang dengan baik.

**Periode 2012 - 2014: Fluktuatif.**
- Fluktuatif Rekrutmen: Jumlah karyawan yang masuk mulai menurun dari 76 pada tahun 2011 menjadi 41 pada tahun 2012 dan bertambah menjadi 56 pada tahun 2014.
- Meningkatnya Pengunduran Diri: Jumlah karyawan yang keluar mulai meningkat, dengan 5 karyawan keluar pada tahun 2013 dan 12 pada tahun 2014.
- Keseimbangan Rekrutmen dan Pengunduran Diri: Meskipun ada peningkatan jumlah karyawan yang keluar, jumlah karyawan yang masuk masih lebih banyak.
- Kondisi Perusahaan: Mulai mengalami penurunan dalam rekrutmen tetapi masih stabil.

**Periode 2015 - 2020: Krisis Retensi dan Stagnasi.**
- Krisis Retensi: Pada tahun 2017, jumlah karyawan yang keluar (19) melebihi jumlah yang masuk (5) untuk pertama kalinya.
- Puncak Pengunduran Diri: Tahun 2018 mencatat jumlah karyawan yang keluar tertinggi (26) dengan hanya 1 karyawan yang masuk.
- Tidak Ada Rekrutmen Baru: Pada tahun 2019 dan 2020, tidak ada karyawan baru yang direkrut, sementara masih ada karyawan yang keluar.
- Stagnasi: Jumlah karyawan yang masuk nol pada tahun 2019 dan 2020, menunjukkan bahwa perusahaan mungkin mengalami kesulitan dalam menarik karyawan baru atau melakukan ekspansi.
- Kondisi Perusahaan: Mengkhawatirkan, dengan krisis retensi dan stagnasi yang jelas.

## 2. Resign Reason Analysis for Employee Attrition Management Strategy

### 2.1 Persentase Karyawan yang Resign Berdasarkan Divisi Pekerjaan:

![img 2](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img2.JPG)

**Interpretasi:**
- Data Analyst memiliki tingkat resign tertinggi sebesar 50%.
- Product Design (UI & UX) memiliki tingkat resign sebesar 37.5%.
- Product Manager memiliki tingkat resign sebesar 35.3%.
- Software Engineer (Front End) dan Software Engineer (Back End) memiliki tingkat resign masing-masing sebesar 38.9% dan 25.7%.

### 2.2 Persentase Resign Berdasarkan Jenjang Karir:

![img 3](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img3.JPG)

**Interpretasi:**
- Freshgraduate program memiliki persentase resign tertinggi sebesar 56.2%.
- Mid level memiliki persentase resign sebesar 25.8%.
- Senior level memiliki persentase resign terendah sebesar 18%.

### 2.3 Persentase Resign Berdasarkan Performa Karyawan:

![img 4](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img4.JPG)

**Interpretasi:**
- Karyawan dengan performa Sangat bagus memiliki persentase resign tertinggi sebesar 32.6%.
- Karyawan dengan performa Biasa memiliki persentase resign sebesar 29.2%.
- Karyawan dengan performa Kurang dan Sangat kurang memiliki persentase resign terendah, masing-masing sebesar 9% dan 10.1%.

### 2.4 Alasan Resign yang Paling Umum:

![img 5](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img5.JPG)

**Interpretasi:**
- Jam kerja adalah alasan utama karyawan resign dengan total 16 kasus (17.98%).
- Ganti karir dan Kejelasan karir adalah alasan berikutnya dengan total masing-masing 14 (15.73%) dan 11 (12.36%) kasus.
- Tidak bisa remote, Toxic culture, dan Leadership juga merupakan alasan signifikan dengan masing-masing persentase di atas 10%.

### 2.5 Analisis Alasan Resign Per Divisi (Data Analyst):

![img 6](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img6.JPG)

**Alasan Resign Tertinggi:** Toxic Culture (75%).

**Rekomendasi:**
- Fokus pada peningkatan lingkungan kerja dan budaya organisasi.
- Memberikan pelatihan kepemimpinan untuk manajer dan supervisor.
- Meningkatkan transparansi dan komunikasi dalam tim.

### 2.6 Analisis Alasan Resign Per Divisi (Front End Developer):

![img 7](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img7.JPG)

**Alasan Resign Tertinggi:** Tidak Bisa Remote (26.6%).

**Rekomendasi:**
Menawarkan opsi kerja remote atau hybrid.
Menginvestasikan dalam teknologi dan infrastruktur yang mendukung kerja remote.
Memberikan pelatihan dan dukungan untuk kerja remote.


### 2.7 Analisis Alasan Resign Per Divisi (UI UX Designer):

![img 8](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/img8.JPG)

**Alasan Resign Tertinggi:** Jam Kerja (33.3%)

**Rekomendasi:**
Meninjau dan menyesuaikan jam kerja untuk memastikan fleksibilitas.
Mengimplementasikan kebijakan kerja fleksibel.
Menyediakan opsi kerja paruh waktu atau waktu cuti yang lebih fleksibel.

# Build an Automated Resignation Behavior Prediction using Machine Learning

![img 9](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/model%20ML.JPG)

![img 10](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/model%20eval.JPG)

![img 11](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/feature%20importance.JPG)

### Hasil Interpretasi Model

**1. Performance Metrics.**
- Accuracy: Semua model (lr, rf, ada, nb, lightgbm) menunjukkan akurasi tinggi (0.9870 atau 98.70%). Ini menunjukkan bahwa model mampu mengklasifikasikan data dengan benar hampir sepanjang waktu.
- AUC (Area Under Curve): AUC untuk semua model di atas 0.99 (kecuali dt, svm, dan knn). AUC mendekati 1 menunjukkan bahwa model memiliki kemampuan yang sangat baik dalam membedakan antara kelas positif dan negatif.

**2. Confusion Matrix.**
- Model hanya membuat sedikit kesalahan (1 FP dan 1 FN), menunjukkan bahwa prediksinya sangat andal.

**3. ROC Curves.**
- AUC class 0: 0.96
- AUC class 1: 0.98
- AUC mendekati 1 untuk kedua kelas menunjukkan bahwa model sangat baik dalam membedakan antara karyawan yang resign dan tidak resign.

**4. Feature Importance.**
- Fitur yang paling penting dalam menentukan prediksi adalah berbagai alasan resign, diikuti oleh umur. Ini menunjukkan bahwa alasan resign (seperti jam kerja, toxic culture, dan kejelasan karir) sangat berpengaruh dalam model.

# Presenting Machine Learning Products to the Business Users

![img SHAP](https://github.com/M-Fatoni/Improving-Employee-Retention-by-Predicting-Employee-Attrition-Using-Machine-Learning/blob/main/img/shap.JPG)

### Explainable Method: SHAP (SHapley Additive exPlanations)

**1. AlasanResign_masih_bekerja (SHAP negatif):** Karyawan yang memiliki alasan "masih bekerja" cenderung memiliki probabilitas resign yang lebih rendah. 

**Rekomendasi:** Perusahaan dapat mempertahankan program atau insentif yang meningkatkan keterlibatan dan retensi karyawan yang lebih tinggi.

**2. AlasanResign_unknown (SHAP negatif):** Kehadiran fitur ini menunjukkan faktor-faktor yang tidak terdefinisi dengan jelas yang mempengaruhi keputusan resign. 

**Rekomendasi:** Perlu dilakukan penelitian atau survey lebih lanjut untuk memahami faktor-faktor tersembunyi yang mungkin mempengaruhi keputusan resign karyawan.

**3. AlasanResign_jam_kerja (SHAP positif):** Nilai SHAP positif menunjukkan bahwa karyawan yang mengeluhkan jam kerja panjang memiliki probabilitas resign yang lebih tinggi. 

**Rekomendasi:** Evaluasi dan optimalkan kebijakan jam kerja untuk mengurangi kelelahan dan meningkatkan keseimbangan kerja-hidup.

**4. AlasanResign_ganti_karir, AlasanResign_kejelasan_karir, AlasanResign_toxic_culture, AlasanResign_tidak_bisa_remote, AlasanResign_leadership (SHAP positif):** Nilai SHAP positif untuk alasan-alasan ini menunjukkan bahwa mereka memiliki dampak positif terhadap keputusan resign. 

**Rekomendasi:** Perusahaan harus fokus pada peningkatan komunikasi, transparansi, dan pengelolaan budaya kerja untuk memperbaiki kondisi ini.

# Rekomendasi Umum

- **Survey dan Evaluasi Periodik:** Lakukan survei dan evaluasi secara teratur untuk mengidentifikasi faktor-faktor yang mempengaruhi keputusan resign karyawan, termasuk yang tidak terdefinisi dengan jelas seperti "AlasanResign_unknown“.

- **Pengembangan Karir dan Keseimbangan Kerja:** Berikan jelasnya jalur karir dan peluang pengembangan kepada karyawan, sambil memastikan kebijakan keseimbangan kerja-hidup yang sehat.

- **Pengelolaan Budaya Kerja:** Fokus pada pengelolaan dan peningkatan budaya kerja yang mendukung, dengan mengurangi toksisitas dan meningkatkan kepuasan karyawan.

- **Penggunaan Terintegrasi Explainable AI:** Perusahaan dapat mengintegrasikan metode Explainable AI seperti SHAP dalam sistem HR untuk secara terus-menerus memantau dan memahami faktor-faktor yang mempengaruhi karyawan, dan secara proaktif merespons perubahan yang terdeteksi.

