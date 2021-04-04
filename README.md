# Regresi-Linear-Sederhana
Prediksi Harga Rumah dengan Algoritma ML Regresi Linear Sederhana
Hasil yang didapatkan kurang memuaskan karena akurasi prediksi hanya sebesar 56% tapi hal itu sudah melewati proses pre-processing dan feature engineering. File berupa csv dan .ipynb(eksperiment)

Regresi linier sederhana adalah suatu metode yang digunakan untuk melihat hubungan antar satu variabel independent (bebas) dan mempunyai hubungan garis lurus dengan variabel dependennya (terikat). 

A. Sifat-sifat Estimator Least Squares

1. Jika semua asumsi yang diberlakukan terhadap model regresi terpenuhi, maka menurut suatu teorema (Gauss Markov theorem) estimator tersebut akan bersifat BLUE (Best Linear Unbiased Estimator).
2. Best = Terbaik, mempunyai varian yang minimum
3. Linear = Linear dalam Variabel Random Y
4. Unbiased = Tak bias
5. Artinya estimator tersebut akan unbiased, linier dan mempunyai varian yang minimum diantara semua estimator unbiased & linier yang lain.

B. Cara Menghitung Koefisien Determinasi
  Dalam regresi linier sederhana, koefisien determinasi (r2) diartikan sebagai ukuran kemampuan semua variabel bebas dalam menjelaskan varians terikat. Karena koefisien determinasi (r2) merupakan kuadrat dari koefisien korelasi (r) maka dapat rumus koefisien determinasi (r2) sama dengan rumus koefisien korelasi (r) yang dipangkatkan.

C. Langkah Membuat Regresi Linear Sederhana

1. Cari dulu apakah kedua variabel tersebut ada hubungan linear atau tidak
2. Tentukan terlebih dahulu variabel independent (x) dan variabel dependennya(y)
3. Membuat diagram pencar dari data x dan y
4. Dari diagram pencar tersebut akan diperoleh gambaran pola tebaran x dan y.apakah membentuk hubungan linear?jika ya,maka model regresinya adalah regresi linear sederhana,kalau tidak linear bias dicari regresinya.
5. Menghitung a dan b
6. Menghitung y^=a+bx, dimana y^= estimasi harga y jika x disubtitusikan kedalam persamaan regresi
7. Membuat garis y^=a+bx  pada sumbu x dan y

D. Istilah dalam Regresi Linier Sederhana

1. Koefisien Korelasi (r) adalah nilai yang menyatakan kuat atau tidaknya hubungan antara 2 variabel
2. Standar error koefisien regresi (E) adalah ukuran dari ketepatan koefisien regresi dalam memprediksi nilai populasinya.Standar error diukur berdasarkan akar kuadrat dari deviasi atau varians koefisien regresi sampel dengan koefisien regresi populasi
3. Koefisien determinasi regresi(r 2) adalah a. Nilai yang menunjukkan seberapa besar pengurangan variasi dalam Y (variabel dependent) saat satu atau lebih X (variabel independent)  masuk kedalam model regresi. b. Besarnya sumbangan / andil dari variabel x terhadap variasi atau naik turunnya y.
4. Konstanta (a) adalah perpotongan garis regresi dengan sumbu Y (nilai estimate jika x = 0)
5. Koefisien arah dari regresi linear (b) adalah nilai yang menunjukkan seberapa besar perubahan nilai Y (variabel dependen) saat X (variabel independent) bertambah satu-satuan

note : open correction and still working on it
