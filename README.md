# UUTS

MALA HASANATUL AMANAH-2106042

#KESIMPULAN
Pada kode diatas menjelaskan tentang Histogram citra (image histogram) merupakan informasi yang penting mengenai isi citra digital. Histogram citra adalah grafik yang menggambarkan penyebaran nilai-nilai intensitas pixel dari suatu citra atau bagian tertentu di dalam citra. Dari Histogram juga dapat menunjukkan banyak hal tentang kecerahan (brightness) dan kontas (contrast) dari sebuah gambar. Pada kode diatas menampilkan setiap gambar citra berwarna dengan komponen R, G, dan B, dan histogram dibuat untuk setiap kanal warna, kemudian analisis dan memanipulasi citra menggunakan pustaka seperti matplotlib di google collab.

• Mounting Google Drive: Kode ini memungkinkan akses ke file dan folder di Google Drive, yang berguna untuk memuat gambar dari penyimpanan Google Drive.

• Memuat dan Menampilkan Gambar: Menggunakan io.imread untuk memuat gambar dari Google Drive. Mengonversi warna dari BGR ke RGB menggunakan cv.cvtColor. Menggunakan cv.hconcat dan cv2_imshow untuk menampilkan gambar asli dan yang sudah diubah secara horizontal.

• Analisis Histogram: Menggunakan cv.calcHist untuk menghitung histogram dari gambar asli dan gambar yang sudah dikonversi. Menggunakan plt.plot untuk menampilkan histogram warna biru, hijau, dan merah secara terpisah. Memvisualisasikan histogram dengan menggunakan plt.show.

• Manipulasi Gambar Keabuan: Menggunakan cv.split untuk memisahkan kanal warna B, G, dan R. Menampilkan dan memvisualisasikan histogram dari kanal warna tertentu. Melakukan manipulasi gambar keabuan seperti inversi warna, pencerahan, dan peningkatan kontras. Dimana Terdapat Empat tipe citra berdasarkan kekontrasannya: Citra gelap (under exposed), Citra terang (over exposed), Citra kontras rendah (low contrast), Citra kontras tinggi (high contrast)
