# Penerapan Metode Clustering untuk Mengidentifikasi Fasilitas Kesehatan dan Jumlah Tenaga Medis di Provinsi Jawa Timur
## Deskripsi Proyek
Proyek ini bertujuan untuk mengidentifikasi fasilitas kesehatan dan jumlah tenaga medis di Provinsi Jawa Timur menggunakan metode clustering, dengan tujuan untuk membantu pemerintah dalam perencanaan dan prioritas pembangunan fasilitas kesehatan. Mengingat pentingnya ketersediaan fasilitas dan tenaga medis yang memadai untuk penyediaan layanan kesehatan berkualitas, proyek ini menggunakan algoritma K-Means Clustering untuk mengelompokkan data fasilitas kesehatan berdasarkan kabupaten/kota di Jawa Timur.

## Tujuan Proyek
1. Mengelompokkan fasilitas kesehatan dan jumlah tenaga medis di Provinsi Jawa Timur dengan algoritma K-Means Clustering.
2. Mengidentifikasi daerah-daerah yang memerlukan peningkatan fasilitas kesehatan dan tenaga medis.
3. Memberikan informasi yang membantu pemerintah dalam melakukan prioritas pembangunan fasilitas kesehatan.
4. Menentukan jumlah cluster optimal berdasarkan data yang ada.
5. Membuat rekomendasi untuk setiap cluster berdasarkan hasil analisis.
## Langkah-Langkah Proyek
1. Pengumpulan Data
    - Data diperoleh dari Profil Kesehatan Jawa Timur Tahun 2020, dengan variabel yang mencakup jumlah rumah sakit, jumlah dokter, jumlah tempat tidur, pasien keluar hidup, dan gross death rate.
    - Memeriksa data untuk memastikan tidak ada nilai yang hilang atau inkonsistensi.
2. Analisis dan Pemahaman Data
    - Mengidentifikasi outlier menggunakan metode standar deviasi untuk memastikan data yang bersih dan akurat.
    - Menggunakan visualisasi data untuk memahami distribusi dan karakteristik variabel yang ada.
3. Pemodelan dengan K-Means Clustering
    - Menerapkan metode clustering untuk mengelompokkan data fasilitas kesehatan dan jumlah tenaga medis.
    - Menggunakan Algoritma K-Means Clustering untuk menemukan pola atau kesamaan dalam data.
    - Melakukan Silhouette Analysis dan Elbow Method untuk menentukan jumlah cluster terbaik.
## Evaluasi Hasil
- **Silhouette Analysis**: Menunjukkan bahwa jumlah cluster optimal adalah 3 dengan nilai Silhouette Score 0,644.
- **Elbow Method**: Menghasilkan kesimpulan yang sama, menunjukkan bahwa jumlah cluster terbaik adalah 3.
- Hasil clustering membantu memahami struktur data dan mengidentifikasi daerah dengan karakteristik serupa dalam hal fasilitas kesehatan dan pelayanan medis.
## Hasil dan Temuan
- Mayoritas daerah (48,65%) termasuk dalam Cluster 0, sejumlah besar daerah (43,24%) berada di Cluster 1, dan hanya sebagian kecil daerah (8,11%) yang tergabung dalam Cluster 2.
- Cluster 0 dan Cluster 1 memiliki dominansi dalam data, dengan karakteristik yang lebih umum. Sementara Cluster 2 mungkin memiliki karakteristik yang lebih khusus atau unik.
- Analisis ini memberikan wawasan tentang fasilitas kesehatan dan jumlah tenaga medis di berbagai kabupaten/kota di Jawa Timur, memungkinkan pemerintah untuk mengambil tindakan yang sesuai.
## Rekomendasi untuk Setiap Cluster
- **Cluster 0 (Cukup Baik)**:
  - Memperbaiki fasilitas fisik, meningkatkan pelayanan, dan menambah jumlah tenaga medis.
  - Meningkatkan koordinasi dengan rumah sakit lain untuk dukungan dan bantuan tenaga medis.
- **Cluster 1 (Baik)**:
  - Meningkatkan fasilitas fisik, meningkatkan pelayanan, dan menjaga kualitas dengan evaluasi internal.
- **Cluster 2 (Sangat Baik)**:
  - Mempertahankan standar pelayanan, melakukan evaluasi berkala, dan membantu daerah dalam cluster 0 dan 1 baik dari segi tenaga medis maupun fasilitas kesehatan.
## Kesimpulan
Proyek ini menggunakan metode clustering untuk mengidentifikasi fasilitas kesehatan dan jumlah tenaga medis di Provinsi Jawa Timur. Dengan menentukan jumlah cluster terbaik dan memberikan rekomendasi untuk setiap cluster, proyek ini membantu pemerintah dalam perencanaan prioritas dan pengembangan fasilitas kesehatan. Hasil analisis ini menunjukkan bahwa metode clustering efektif dalam mengelompokkan data kesehatan, memungkinkan tindakan yang lebih terarah dalam penyediaan layanan kesehatan yang berkualitas.
