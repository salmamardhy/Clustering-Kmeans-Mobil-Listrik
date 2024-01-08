# Clustering menggunakan metode K-Means Berdasarkan Performa dan Harga untuk Meningkatkan Strategi Pemasaran dalam Penjualan Mobil Listrik
### **Dibuat oleh:**
**1. Khansa Farras Callista - 1306621067** <br>
**2. Salma Mardhiyah - 1306621061**

-----

Projek ini dilakukan untuk memenuhi tugas akhir mata kuliah Pengantar Pembelajaran Mesin dalam Fisika. Tujuan dari projek ini adalah melakukan Clustering untuk mengelompokkan mobil listrik berdasarkan performa (top speed dan acceleration time) mobil listrik dan harganya untuk membantu dalam memahami preferensi dan kebutuhan pelanggan dalam memilih kendaraan listrik. Hal ini memungkinkan perusahaan atau penjual untuk menyesuaikan produk dan strategi agar lebih sesuai dengan kebutuhan pasar.

A. Eksplorasi dan Pembersihan Data:
* Melakukan pengecekan apakah terdapat null pada dataset dan menghilangkannya
* Mengecek outlier pada data

B. Implementasi Clustering K-Means:
* Menerapkan teknik normalisasi data untuk meningkatkan kinerja model.
* Melakukan elbow method untuk menentukan jumlah clustering yang diperlukan
* Mengimplementasikan metode K-Mean berdasarkan fitur Price dan performa (Top_speed dan Acceleration_time) dari dataset mobil listrik
* Memvisualiasasikan hasil clustering dan centernya berdasarkan plot 3D

C. Evaluasi Model:
* Mengevaluasi hasil klustering menggunakan skor Silhouette, skor Calinski Harabasz, dan skor Davies Bouldin.
* Memvisualisasikan clustering berdasarkan masing-masing fitur yang ditetapkan dengan bar chart untuk dianalisis hasilnya
