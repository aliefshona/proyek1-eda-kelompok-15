# proyek1-eda-kelompok-15
# Volume Lalu Lintas Jalan Tol I-94 Minneapolis–Saint Paul Tahun 2012–2018  
Nama : Alief Shoufiya Nafi  
NRP : 5027261006  
Nama : Anggito Abhinaya Sulistyo  
NRP : 5027261066  
Nama : Daniel Darius Darrell S.  
NRP : 5027261112  
Kelompok 15  
Smart City
Sumber : UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)  
Link lisensi : https://creativecommons.org/licenses/by/4.0/legalcode  
- Temuan paling menarik (3–5) Ditemukan nilai anomali ekstrem pada rain_1h — 1 baris tercatat 9.831,3 mm curah hujan dalam 1 jam, jauh melampaui rekor dunia (~305 mm), dipastikan kesalahan input data. Ditemukan 10 baris dengan temp = 0 Kelvin (suhu mutlak nol, mustahil secara fisik), seluruhnya terjadi di jam dini hari pada 2 tanggal spesifik (31 Januari & 2 Februari 2014) — mengindikasikan kegagalan sensor/API cuaca, bukan kesalahan acak. Ditemukan 7.629 baris dengan date_time yang sama namun kondisi cuaca berbeda, mengindikasikan beberapa laporan cuaca dicatat dalam jam yang sama. Ketiga variabel numerik utama (temp, clouds_all, traffic_volume) secara konsisten menunjukkan pola miring ke kiri, menunjukkan adanya kecenderungan nilai-nilai rendah ekstrem (musim dingin, langit sangat cerah, jam sepi) yang menarik rata-rata sedikit di bawah median.


