![Logo](https://purwadhikax.com/static/media/purwadhika_logo_no_tagline.40622a0f.png)

#### SEBELUM ANDA MULAI MENGERJAKAN, Bacalah soal baik-baik. Jika ada pertanyaan mengenai soal, silakan ditanyakan
#### Ujian ini bersifat _open book_. Kalian boleh melihat catatan atau mencari materi di internet, tapi **mohon untuk tidak berdiskusi satu sama lain**
#### Nyalakan kamera kalian pada zoom
#### Jelaskan langkah-langkah yang kalian lakukan di kode kalian melalui komen (#).
#### Setelah kamu selesai, _commit_ file jawaban kamu ke _repository_ github, dengan Ujian Modul 3 sebagai nama repo. Kirimkan link github kalian ke brigita.gems@gmail.com dan cc ke operational@purwadhika.com.
#### Kamu punya waktu 5 jam untuk mengerjakan ujian ini.

#

> ###  ``Hotel Reservation Cancellation Prediction``

Anda adalah Data Scientist di sebuah perusahaan hotel. Anda diberikan dataset berisi informasi pemesanan kamar hotel (*booking information*) baik untuk hotel kota (*city hotel*) maupun hotel resort. Dataset ini juga mengandung kapan *booking* dilakukan, lama menginap, jumlah pengunjung dewasa, anak-anak, dan/atau bayi, serta ketersediaan tempat parkir. Informasi lain mengenai dataset bisa Anda baca di keterangan dataset di bawah ini:  

#

### **Dataset**

Dataset ini berasal dari paper Jurnal Ilmiah berjudul "Hotel booking demand datasets" yang ditulis oleh Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. Penjelasan tiap feature/variabel dari Jurnal bisa Anda akses di  https://www.sciencedirect.com/science/article/pii/S2352340918315191

Apabila Anda kesulitan download dataset pada repo ini atau ingin mengetahui keterangan di setiap kolom, Anda bisa akses ke: https://www.kaggle.com/jessemostipak/hotel-booking-demand/data. 

![image](https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1050&q=80)  

#

## **Instruksi Ujian**

### **A. EDA** (25 poin)

__Batasan Data untuk Ujian__
* __Ukuran data__ yang digunakan adalah 5000 baris (_rows_) awal [:5000].
* __Variabel__ yang dipakai berjumlah 16 kolom, yaitu: ['hotel', 'is_canceled', 'adults', 'children', 'babies', 'meal', 'country', 'market_segment', 'distribution_channel', 'reserved_room_type', 'booking_changes', 'deposit_type', 'days_in_waiting_list', 'customer_type', 'required_car_parking_spaces', 'total_of_special_requests']

Jalankan Exploratory Data Analysis untuk:  
1) Memahami profil tamu/konsumen hotel (_customer profiling_).  
2) Memahami kebiasaan tamu/konsumen hotel (_customer behavior_).  

Berikan penjelasan tentang _insight_ yang Anda temukan dari hasil _Exploratory Data Analysis_ ke manajemen hotel!  

### **B. Data Cleaning & Preprocessing** (15 poin)

Jelaskan tahapan dan alasan untuk setiap langkah preprocessing yang Anda lakukan.  

Buatlah kode untuk preprocessing yang Anda lakukan dengan `Pipeline`, jika diperlukan, dan `ColumnTransformer`. Simpan kode tersebut di dalam variable `transformer`.  

### **C. Model Benchmark & Evaluation Metric** (40 poin)

1) Pilihlah setidaknya 3 model _machine learning_ yang Anda pahami untuk mendapatkan benchmark model ML untuk memprediksi apakah user akan *cancel booking* atau tidak! 
>* Jelaskan secara singkat cara kerja model ML yang Anda gunakan!  

2) Ada **2 jenis kesalahan** yang mungkin terjadi dalam model ML di studi kasus ini, yaitu:
>* Model memprediksi user akan *cancel booking* (membatalkan pesanan), padahal sebenarnya/realisasinya user tidak membatalkan pesanan.
>* Model memprediksi user tidak membatalkan pesanan, padahal sebenarnya/realisasinya user *cancel booking* (membatalkan pesanan).  

Dalam konteks bisnis perhotelan, apabila pengunjung diasumsikan tidak *cancel booking* maka pihak hotel akan menyiapkan beberapa hal untuk menyambut kedatangan mereka, di antaranya:  
>* Menghubungi pengunjung terkait kapan perkiraan datang ke hotel,
>* Membersihkan, merapikan, dan menyiapkan kamar sesuai pesanan pengunjung,
>* Menyiapkan makanan dan minuman untuk menyambut kedatangan pengunjung,
>* Menolak pengunjung lain yang memesan kamar yang telah dipesan (*booked room*), dan
>* Memberi layanan penjemputan di bandara/stasiun/terminal apabila diperlukan.  

a. Pilih jenis kesalahan yang paling berpengaruh pada kerugian finansial perusahaan dan jelaskan alasan pilihan Anda!  

b. Pilih *evaluation metric* yang bisa menekan jenis kesalahan yang Anda pilih! Berikan alasan!  

### **D. Hyper-parameter Tuning** (20 poin)

1. Setelah Anda memilih _benchmark_ model terbaik, lakukan hyperparameter tunning untuk meningkatkan preforma model Anda! `Parameter` apa saja yang anda pilih untuk `tunning`? Jelaskan maksud dari tiap-tiap parameter tersebut!

2. Bagaimana performa model Anda setelah *Hyper-parameter Tuning*? Apakah ada tahap lanjutan yang bisa Anda lakukan untuk meningkatkan performa model lebih jauh? Buat kesimpulan akhir, model mana yang akan Anda pakai untuk memprediksi apakah user akan *cancel booking* atau tidak!

<hr>

## ``Good luck & Happy Coding``


Apabila sudah selesai, buat repository baru di github kalian dengan nama **Ujian Modul 3** dan _commit_ jawaban kalian ke _repository_ tersebut. Kirimkan link repository kalian ke brigita.gems@gmail.com dan cc ke operational@purwadhika.com.
