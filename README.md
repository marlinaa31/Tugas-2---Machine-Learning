# Tugas 2 Machine Learning

Pada tugas ini saya mencoba membangun model machine learning dengan menggunakan SVM. Saya menggunakan artikel [ini](https://medium.com/@youness.habach/support-vector-machines-svm-explanation-mini-project-9d4b4962be52) sebagai referensi dalam mengerjakan tugas 2 mata kuliah machine learning. 

## About Me
Nama: Muhammad Farhan                                                                         
NPM: 210810701050

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install depedencies.

```bash
pip install -r requirements.txt
```

## Library
* Numpy
* Matplotlib
* Scikit-learn
* Pandas
* Seaborn


### Support Vector Clasifier (SVC)
Source dataset: https://www.kaggle.com/datasets/erdemtaha/cancer-data/data

Atribut:
* radius_mean
* texture_mean
* perimeter_mean
* area_mean 
* smoothness_mean
* compactness_mean 
* concavity_mean
* concave points_mean

semua atribut ini Mewakili nilai rata-rata dari visual kanker/penampilan kanker

Label:
* Diagnosis: Menunjukkan jenis kanker. Properti ini dapat mengambil nilai "M" (Ganas) atau "B" (Jinak)


### Support Vector Regresion (SVR)

Source dataset: https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant

Atribut:
* Ambient variables Temperature (AT): Nilai rata-rata dari temperature per jam
* Ambient Pressure (AP): Nilai rata-rata dari Tekanan Sekitar
* Relative Humidity (RH): Nilai rata-rata dari Kelembaban relatif
* Exhaust Vacuum (V): Nilai rata-rata dari zat yang dibuang

Label:
* Electrical energy output (EP): Listrik yang dihasilkan per jam 







