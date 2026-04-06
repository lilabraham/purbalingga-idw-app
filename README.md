# Geospatial Crime Vulnerability Analysis - Purbalingga
*(Analisis Dimensi Geospasial Kerawanan Kriminalitas di Kabupaten Purbalingga Menggunakan Inverse Distance Weighting)*

## Deskripsi Proyek
Repositori ini berisi *source code* dan model komputasi yang dikembangkan sebagai bagian dari tugas akhir (Skripsi) S1 Teknik Informatika. Proyek ini bertujuan untuk memetakan, menganalisis, dan memprediksi tingkat kerawanan kriminalitas di wilayah Kabupaten Purbalingga menggunakan metode interpolasi spasial **Inverse Distance Weighting (IDW)**.

Sistem ini mengolah dataset koordinat historis untuk menghitung probabilitas risiko di area sekitarnya, menghasilkan visualisasi *heatmap* dan zonasi yang terukur. Proyek ini mendemonstrasikan penerapan analisis data kuantitatif untuk mitigasi risiko berbasis geografis.

## Fitur Utama (Key Features)
- **Data Preprocessing & Cleansing**: Membersihkan dan memformat dataset spasial agar siap diproses oleh algoritma.
- **IDW Algorithm Implementation**: Penerapan metode statistik IDW di mana bobot titik sampel kriminalitas diperhitungkan berdasarkan proksimitas jarak (titik terdekat memiliki pengaruh kerawanan lebih besar).
- **Geospatial Visualization**: Pembuatan peta kerawanan interaktif yang membagi wilayah ke dalam beberapa klasifikasi risiko (Aman hingga Sangat Rawan).
- **Risk Mitigation Insights**: Menghasilkan *output* data yang dapat digunakan oleh *stakeholder* untuk alokasi sumber daya dan strategi pengamanan.

## Tech Stack & Tools
- **Bahasa Pemrograman**: Python, Html
- **Data Processing**: Pandas, NumPy
- **Spatial Analysis**: GeoPandas, SciPy
- **Visualization**: Folium / Matplotlib / QGIS
- **Environment**: Jupyter Notebook / VS Code

## Metodologi Singkat
**Inverse Distance Weighting (IDW)** adalah metode interpolasi spasial deterministik. Pendekatan ini mengasumsikan bahwa nilai pada lokasi yang tidak terpetakan merupakan fungsi rata-rata tertimbang dari titik-titik data terdekat. Dalam proyek ini, IDW digunakan untuk memprediksi "suhu" kerawanan suatu daerah meskipun tidak ada data kejadian spesifik di titik eksak tersebut, dengan memanfaatkan pola penyebaran kriminalitas di sekitarnya.

##Dokumen Akademik
Proyek ini merupakan implementasi teknis dari penelitian akademis dengan judul yang sama. Naskah Skripsi *Full-Text* dan Artikel Ilmiah dapat diakses pada tautan berikut:
- **https://drive.google.com/drive/folders/1q8jnOJRy_eRRP4QLGesp2kCNIbXKu5jO?usp=drive_link**

##Penulis
**Iqra Manaqibal Atqiya**
- **Email**: iqroace@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/iqra-manaqibal-atqiya-5b21881a0/
