# Improving Employee Retention by Predicting Employee Attrition Using Machine Learning

![1692972429255](image/README/1692972429255.png)

## Introduction

We know that larger companies contain more than thousand employees working for them, so taking care of the needs and satisfaction of each employee is a challenging task to do, it results in valuable and talented employees leave the company without giving the proper reason.

Employee churn is a major problem for many firms these days. Great talent is scarce, hard to keep and in high demand. Given the well-known direct relationship between happy employees and happy customers, it becomes of utmost importance to understand the drivers of employee dissatisfaction.


## Data

The dataset contains 287 data rows and 25 features thats contains information about employees

## Tools

During this project we've use :

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 		as programming language

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)		as notebook

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)	as IDE

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)		![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 	as data preprocessing library

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)	as data visualization library

---

## Contents

#### Columns Details

| Nama Fitur                         | Deskripsi Fitur                                 |
| :--------------------------------- | :---------------------------------------------- |
| Username                           | Username karyawan                               |
| EnterpriseID                       | Nomor induk karyawan                            |
| StatusPernikahan                   | Status pernikahan karyawan                      |
| JenisKelamin                       | Jenis kelamin karyawan                          |
| StatusKepegawaian                  | Status kepegawaian karyawan                     |
| Pekerjaan                          | Posisi pekerjaan karyawan                       |
| JenjangKarir                       | Tingkat karir karyawan                          |
| PerformancePegawai                 | Nilai kinerja karyawan                          |
| AsalDaerah                         | Asal daerah karyawan                            |
| HiringPlatform                     | Platform yang digunakan untuk merekrut karyawan |
| SkorSurveyEngagement               | Skor survei keterlibatan karyawan               |
| SkorKepuasanPegawai                | Skor kepuasan karyawan                          |
| JumlahKeikutsertaanProjek          | Jumlah proyek yang diikuti oleh karyawan        |
| JumlahKeterlambatanSebulanTerakhir | Jumlah keterlambatan bulanan terbaru karyawan   |
| JumlahKetidakhadiran               | Jumlah ketidakhadiran karyawan                  |
| NomorHP                            | Nomor ponsel karyawan                           |
| Email                              | Alamat email karyawan                           |
| TingkatPendidikan                  | Tingkat pendidikan karyawan                     |
| PernahBekerja                      | Pengalaman kerja karyawan                       |
| IkutProgramLOP                     | Partisipasi dalam program LOP                   |
| AlasanResign                       | Alasan pengunduran diri karyawan                |
| TanggalLahir                       | Tanggal lahir karyawan                          |
| TanggalHiring                      | Tanggal perekrutan karyawan                     |
| TanggalPenilaianKaryawan           | Tanggal penilaian kinerja karyawan              |
| TanggalResign                      | Tanggal pengunduran diri karyawan               |

#### Exploratory Data Analysis and Data Pre-Processing 

* check and handling missing values
* check unique values
* feature transfromations to get the best possible features
* doing over-sampling with SMOTE *(Synthetic Minority Oversampling Technique)* to handling imbalance feature
* scalling data using MinMaxScaler

#### Modelling

* Determine Models with `LazyPredict` Library
* Top 5 Models : XGBClassifier, CalibratedClassifierCV , DummyClassifier, LogisticRegression,RandomForestClassifier
* Visualization using *Confusion Matrix to evaluate the performance of the classification model.

#### Insight

* Employees with the role of Software Engineer who resign, like those in the Data Analyst role, are mostly female and unmarried, have a Freshgraduate career path and are fulltime employees.
* Working hours and Career are the reasons that often trigger them to choose to resign.

#### Recomendation

Several strategies from company management must be taken as soon as possible, to increase employee retention.

* Build a positive company culture that can help create a work environment that can motivate and increase employee loyalty, for example by holding Focus Group Discussions, Family Gatherings or coaching with a spiritual approach.
* Provide career opportunities and training for employees.
* Accommodate flexible working hours by implementing Remote Work, Work From Anywhere or Hybrid, so that in addition to employees being able to maximize working time according to their wishes, company targets are also still achieved.
