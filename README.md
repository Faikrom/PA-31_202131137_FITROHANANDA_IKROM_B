# Project Title

program dirancang untuk mengidentifikasi plat nomor kendaraan, dengan menggunakan program jupyter notebook. Dengan cara, citra asli diubah ke grayscale, lalu mengurangi noise pada citra namun masih tetap mempertahankan detail agar tidak pecah, lalu dideteksi tepi gambar citra, selanjutnya dengan fungsi kontur akan crop gambar plat nomor, abis itu diambil setiap kontur secara hierarki pada citra, dan diurutkan secara descending (susunan tinggi ke nada yang lebih rendah).

library yang digunakan : 
1. opencv
2. numpy
3. matplotlib
4. imutils

# Penjelasan Secara Teori
Ada beberapa teori dan teknik yang berkaitan dengan deteksi plat nomor dan pemrosesan citra biner. Berikut adalah beberapa konsep yang dapat digunakan dalam konteks ini:

1. Segmentasi gambar:
Segmentasi adalah proses memisahkan objek dari latar belakang suatu gambar. Dalam deteksi pelat nomor, langkah pertama adalah melakukan segmentasi gambar untuk memisahkan pelat nomor dari latar belakangnya. Teknik segmentasi seperti proses yang berbasis ambang batas atau morfologis dapat digunakan.

2. Deteksi tepi:
Deteksi tepi adalah proses menemukan perbedaan signifikan dalam intensitas piksel di sepanjang garis luar objek. Dalam deteksi pelat nomor, deteksi tepi dapat membantu mengidentifikasi kontur pelat nomor. Algoritma populer untuk deteksi tepi termasuk operator Sobel, operator Prewitt, atau operator Canny.

3. transformasi Hough:
Transformasi Hough adalah metode yang digunakan untuk mendeteksi objek berdasarkan pola atau bentuk geometrisnya. Dalam deteksi pelat nomor, transformasi Hough dapat digunakan untuk mendeteksi garis lurus tepi pada gambar yang mungkin mewakili batas pelat nomor.

4. Memproses gambar biner:
Setelah pelat nomor terdeteksi, pemrosesan citra biner dapat dilakukan untuk meningkatkan kualitas pendeteksian. Metode pemrosesan biner seperti pelebaran, erosi, penghilangan scratch/noise, atau operasi morfologi lainnya dapat diterapkan untuk meningkatkan kualitas citra biner pelat nomor.

5. Pengenalan karakter:
Metode pengenalan karakter dapat berkisar dari pendekatan berbasis model hingga pendekatan berbasis pembelajaran mesin seperti jaringan saraf atau metode berbasis klasifikasi seperti Support Vector Machines (SVM).

Penting untuk dicatat bahwa pendeteksian pelat nomor adalah masalah yang rumit dan mungkin melibatkan kombinasi berbagai metode dan teknik untuk mencapai hasil yang akurat. Berbagai faktor seperti kondisi pencahayaan, variasi font, rotasi plat nomor, dan skalabilitas juga dapat memengaruhi performa sistem deteksi. 


