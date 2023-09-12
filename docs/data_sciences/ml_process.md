# Send Artificial Object to Moon - Survival Prediction

## Permasalah bisnis
---
Sebuah perusahaan antariksa ingin memastikan keberhasilan peluncuran objek-artifisialnya ke bulan dengan meminimalkan risiko dan kerugian. Mereka ingin mengembangkan model prediktif yang dapat membantu mereka mengevaluasi peluncuran potensial dan mengidentifikasi faktor-faktor yang dapat mempengaruhi keberhasilannya.

## Objective bisnis
---
Mengembangkan model prediktif yang dapat membantu perusahaan antariksa dalam mengidentifikasi peluncuran yang memiliki tingkat keberhasilan yang tinggi, mengurangi risiko kegagalan, dan memastikan bahwa objek-artifisial mencapai tujuan mereka di bulan.

## Metrik bisnis
---
Tingkat keberhasilan misi: Persentase misi pengiriman objek ke bulan yang berhasil mencapai tujuan mereka tanpa masalah yang signifikan.

## Solusi machine learning
---
Kita akan menggunakan classification untuk memprediksi apakah objek yang dikirim ke bulan akan selamat atau gagal dengan memanfaatkan data historis selama beberapa dekade terakhir. Kita akan menggunakan algoritma `RandomForestClassifier` dan `KNeighborsClassifier`. Untuk mencari parameter terbaik untuk masing-masing algoritma, kita akan menggunakan `GridSearchCV`. Dan kita akan menghitung akurasi kedua model tersebut dengan `cross_val_score`. Terakhir kita akan memilih model mana yang lebih baik berdasarkan nilai akurasi

## Metrik machine learning
---
Kita akan menggunakan metrik akurasi untuk mengevaluasi model *machine learning* yang kita buat.

<center>
\(
\begin{align*}
\text{akurasi} = \frac{\text{jumlah prediksi yang benar}}{\text{jumlah prediksi}}
\end{align*}
\)
</center>

## References
---
- Materi kelas Pacmann Machine Learning Process
- [Moon objects survival AutoViz+CatBoost+SHAP](https://www.kaggle.com/code/dima806/moon-objects-survival-autoviz-catboost-shap)

## Sorce code
---
- [Github](https://github.com/zain3ie/ml_process)
