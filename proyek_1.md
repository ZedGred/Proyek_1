# Laporan Proyek Machine Learning - Pebiyan Firmansyah 

## Domain Proyek

Obesitas adalah penyakit kronis yang ditandai dengan penumpukan lemak berlebih di tubuh, yang dapat menyebabkan berbagai masalah kesehatan dan psikologi.

- Prediksi obesitas adalah proses untuk mengestimasi tingkat obesitas seseorang berdasarkan faktor-faktor yang mempengaruhinya. Prediksi obesitas dapat dilakukan dengan menggunakan berbagai metode, seperti regresi dan klasifikasi.

- Obesity is a multifactorial condition, whose etiopathogenesis and evolution are influenced by multiple situations interacting among them. It affects almost all scopes of people's health status, being the range of comorbidities very wide. Customization, active attitude, obesity and comorbidities assessment are crucial diagnostic factors. Taking into account the natural history of the disease, the early identification and management may avoid or lessen the evolution of comorbidities and, ultimately, reduce fatal events, improve quality of life and increase life expectancy. The high prevalence reached in developed countries, as well as the prevalence and incidence rates that it is obtaining in developing countries, have made obesity a major health worldwide problem. As consequence of its social and economic implications, obesity has become one of the main threats to public health and to maintaining the balance in health systems. :[Obesity and overweight](https://www.mendeley.com/catalogue/7ecbf93d-afbf-3501-8932-91e65c9f27ce)

## Business Understanding

Berdasarkan data yang dihimpun World Population Review, jumlah penderita obesitas di seluruh dunia meningkat hampir tiga kali lipat sejak 1975,tentu saja kita tidak ingin keluarga dan kerabat kita terkena obesitas.prediksi yang kita gunakan untuk menentukan kategori berat badan seseorang.

### Problem Statements

- berapa nilai fitur yang bisa dianggap seseorang mengalami obesitas

### Goals

- membuat model yang dapat memprediksi nilai fitur untuk menentukan kategori berat badan

### Solution statements

- untuk mencapai model yang akurat kita membutuhkan beberapa model klasifikasi dan memilih model terbaik.model yang saya gunakan adalah svm,randomforest,dan logisticregression.

- untuk memecahkan masalah klasifikasi saya menggunakan metrics accuracy

## Data Understanding

Kumpulan Data Prediksi Obesitas menyediakan kumpulan atribut komprehensif terkait demografi individu, kebiasaan gaya hidup, dan indikator kesehatan, yang bertujuan untuk memfasilitasi prediksi prevalensi obesitas.[Kaggle](https://www.kaggle.com/datasets/mrsimple07/obesity-prediction/download?datasetVersionNumber=1)
memiliki jumlah data yaitu 1000 sample.


### Variabel-variabel pada obesity prediction dataset adalah sebagai berikut:

- Age       : Usia seseorang
- Gender : Jenis kelamin individu
- Height  : Ketinggian individu
- Weight : Berat individu
- BMI      : Metrik yang dihitung berasal dari berat dan tinggi badan individu
- PhysicalActivityLevel : Tingkat aktivitas fisik individu
- ObesityCategory       : kategori obesitas

![visualisasi jumlah data](https://drive.google.com/file/d/1JOpXxPr4XtiHQcoBpmbU6ZxPAsstZ7ZR/view?usp=drivesdk)
