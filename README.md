# Analisis Sinyal Provider Menggunakan Network Cell Info
Tugas analisis sinyal provider menggunakan network cell info

# Tools yang akan digunakan :
1. Network Cell Analyzer (Aplikasi)
2.	Wifi Analyzer (Aplikasi)
   
# Hasil Analisis :

# 1. Network Cell Analyzer (Aplikasi):

# •	Parameter-Parameter Yang Dianalisis :
-	RSRP (Reference Signal Received Power) : Mengukur kekuatan sinyal referensi dalam satuan dBm.
-	RSRQ (Reference Signal Received Quality) : Mengukur kualitas sinyal referensi dalam dB.
-	SINR (Signal-to-Interference-plus-Noise Ratio) : Mengukur rasio antara kekuatan sinyal dengan gangguan dan noise dalam dB.

# a.	Analisis RSRP (Kekuatan Sinyal)
RSRP berada dalam rentang -84 dBm hingga -112 dBm. Kategori kualitas sinyal berdasarkan RSRP :
- >-80 dBm → Sangat bagus
- -80 hingga -90 dBm → Baik
- -90 hingga -100 dBm → Sedang
- -100 hingga -110 dBm → Buruk
- <-110 dBm → Sangat buruk
Kesimpulan : Sebagian besar nilai RSRP berada dalam kategori "buruk" hingga "sangat buruk", yang menunjukkan sinyal lemah.

# b.	Analisis RSRP (Kekuatan Sinyal)
RSRP berada dalam rentang -84 dBm hingga -112 dBm. Kategori kualitas sinyal berdasarkan RSRP :
>-80 dBm → Sangat bagus
-80 hingga -90 dBm → Baik
-90 hingga -100 dBm → Sedang
-100 hingga -110 dBm → Buruk
<-110 dBm → Sangat buruk
Kesimpulan : Sebagian besar nilai RSRP berada dalam kategori "buruk" hingga "sangat buruk", yang menunjukkan sinyal lemah.

# c.	Analisis RSRQ (Kualitas Sinyal)
RSRQ berada dalam rentang -5 dB hingga -12 dB. Kategori kualitas sinyal berdasarkan RSRQ*:
>-10 dB → Baik
-10 hingga -15 dB → Sedang
<-15 dB → Buruk
Kesimpulan : Sebagian besar nilai RSRQ berkisar antara -5 hingga -12 dB, yang berarti kualitas sinyal masih cukup baik namun mendekati kategori sedang/buruk.

# d.	Analisis SINR (Rasio Sinyal terhadap Noise) 
SINR berada dalam rentang 12 dB hingga 7 dB. Kategori kualitas sinyal berdasarkan SINR :
>20 dB → Sangat baik 
13 hingga 20 dB → Baik
0 hingga 13 dB → Buruk
<0 dB → Sangat buruk
Kesimpulan : SINR yang berkisar antara 7 hingga 12 dB menunjukkan bahwa sinyal mengalami gangguan dan noise yang cukup tinggi.

# e.	Kesimpulan Umum
-	Kekuatan sinyal (RSRP) sebagian besar lemah, yang menunjukkan jaringan mengalami masalah dalam penerimaan sinyal.
-	Kualitas sinyal (RSRQ) masih dalam batas cukup baik, tetapi beberapa nilai mendekati kategori sedang/buruk.
-	SINR menunjukkan adanya gangguan dan noise yang signifikan, yang bisa berdampak pada kualitas komunikasi data.
 	 	 
# 2.	Wifi Analyzer (Aplikasi) :
•	Provider yang Teridentifikasi
-	Provider yang muncul dalam hasil adalah Biznet Networks
-	Ini dapat dilihat dari informasi "Carrier Name: Telkomsel" dan ASN yang terdaftar sebagai Biznet Networks

# 1. (Wi-Fi Connection Overview)
-	Perangkat terhubung ke jaringan Wi-Fi bernama "Fhra".
-	Kecepatan data yang digunakan saat ini adalah 14 KB/s (download) dan 0 KB/s (upload).
-	Default Gateway IP: 192.168.18.1 (router yang digunakan).
-	DNS Server juga menggunakan 192.168.18.1.
-	External IP: 118.99.94.249, yang berarti koneksi ke internet berasal dari ISP dengan alamat ini.
-	External IPv6 juga tertera, namun HTTP Proxy tidak digunakan.
# 2.	(Cellular Information)
-	Jaringan seluler (4G) terdeteksi, tetapi tidak terhubung (indikator merah "No" pada status koneksi).
-	Operator seluler: Indosat.
-	Dukungan VOIP: Yes (artinya jaringan mendukung panggilan berbasis internet seperti WhatsApp atau FaceTime).
-	Data yang telah digunakan sejak perangkat dinyalakan:
	687,3 MB Download
	32,8 MB Upload
# 3.	(IP Geolocation)
-	IP eksternal (118.99.94.249) terhubung melalui Biznet Networks.
-	Lokasi terdeteksi di Palembang, Sumatera Selatan, Indonesia.
-	Koordinat perkiraan: Latitude -2.9167, Longitude 104.7458.
-	Zona waktu: Asia/Jakarta.
# 4.	(Speed Test Result)
-	Tes kecepatan dilakukan menggunakan server di Jakarta, ID.
-	Provider yang digunakan adalah Biznet Networks.
-	Hasil tes kecepatan internet:
	Download: 32,7 Mbps.
	Upload: 32,4 Mbps.
-	Koneksi ini cukup baik untuk streaming, browsing, dan aktivitas online lainnya tanpa kendala.

Secara keseluruhan, iPhone terhubung ke Wi-Fi dengan jaringan Biznet di Palembang, namun jaringan seluler Indosat sedang tidak aktif. Kecepatan internet juga cukup stabil dengan kecepatan download dan upload yang seimbang.

