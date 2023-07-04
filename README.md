# Penjelasan

program dirancang untuk mengidentifikasi plat nomor kendaraan, dengan menggunakan program jupyter notebook. Dengan cara, citra asli diubah ke grayscale, lalu mengurangi noise pada citra namun masih tetap mempertahankan detail agar tidak pecah, lalu dideteksi tepi gambar citra, selanjutnya dengan fungsi kontur akan crop gambar plat nomor, abis itu diambil setiap kontur secara hierarki pada citra, dan diurutkan secara descending (susunan tinggi ke nada yang lebih rendah).

library yang digunakan : 
1. opencv
2. numpy
3. matplotlib
4. imutils


