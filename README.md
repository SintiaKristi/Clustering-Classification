
# "Memprediksi kelulusan sekolah menengah di Portugis"
===========================================================================================================

![image](https://user-images.githubusercontent.com/33625879/113259815-bff4c900-92f7-11eb-9c0e-dd56f9464b4c.png)

Source-UCI Machine Learning Repository:Data Sets

# Classification

Objek:
Mencari metode terbaik untuk permasalahan kelulusan siswa menengah di Portugis dan untuk memprediksi kelulusan siswa menggunakan metoda tersebut bedasarkan beberapa variable parameter terkait

Dataset:
Data dari dua sekolah di Portugis yaang berisi data siswa yang terdiri dari 33 atribut dan 649 value.

Method:
Metode yang akan dibandingkan yaitu :
KNeighborsClassifier
LogisticRegression
RandomForestClassifier
 Untuk mendapatkan tingkat akurasi terbaik pada permasalahan yang terkait.

Dan data ini termasuk kedalam Unsupervised learning karena tidak ada data latih.
Didapatkan hasil yang terbaik dengan menggunakan RandomForestClassifier dan Kneighbors dengan akurasi 95%

Output:
![image](https://user-images.githubusercontent.com/33625879/113261930-3eeb0100-92fa-11eb-89e2-326b0f03b633.png)

# Clustering

Objek: 
Men-clusterkan data menjadi beberapa kelompok, disini kami kelompokkan menjadi 3 kelas antara nilai G1(first periode grade ) dan G2(second periode grade).

Method:
Disini metode yang digunakan yaitu K-Means karena yang paling sederhana dan populer .Tujuan dari algoritma ini adalah untuk menemukan grup dalam data, dengan jumlah grup yang diwakili oleh variabel K. Variabel K sendiri adalah jumlah cluster yang kita inginkan.

Proses K-Means:
Data dimulai dengan kelompok pertama centroid yang dipilih secara acak, yang digunakan sebagai titik awal untuk setiap cluster, dan kemudian melakukan perhitungan berulang (berulang) untuk mengoptimalkan posisi centroid.

Proses ini berhenti ketika:
>> Centroid telah stabil — tidak ada perubahan dalam nilai-nilai mereka karena pengelompokan telah berhasil
>> Jumlah iterasi yang ditentukan telah tercapai.

Hasil dari K-Mean Clustering adalah:
Centroid dari cluster K, yang dapat digunakan untuk memberi label data baru
Label untuk data pelatihan (setiap titik data ditugaskan ke satu clusters)

Output:
![image](https://user-images.githubusercontent.com/33625879/113262371-bae54900-92fa-11eb-8971-21d8cf7340e7.png)
