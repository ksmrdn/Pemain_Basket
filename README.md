![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

## **Hunting Pemain Basket 🏀**

<img src='https://raw.githubusercontent.com/ksmrdn/Ujian_Pemain_Basket/master/Ujian_MachineLearning_JCDS07-master/soal1.jpg' width='100%'/>

Anda adalah seorang manager klub basket ternama yang ingin merekrut pemain basket muda berbakat. Pemain yang Anda targetkan untuk direkrut memiliki kriteria sebagai berikut:

- [x] Usia (__Age__) __<= 25__ tahun, 
- [x] Tinggi badan (__Height__) __>= 180__ cm,
- [x] Berat badan (__Weight__) __<= 90__ kg,
- [x] Rata-rata point (__Average points scored__) __>= 6__, dan
- [x] Rata-rata rebound (__Average rebounds grabbed__) __>= 3__.

Tersedia __1 buah dataset (.csv)__ yang memuat data lengkap pemain basket liga profesional __NBA__ (_National Basketball Association_). Unduh dataset via Kaggle: [klik di sini](https://www.kaggle.com/justinas/nba-players-data). Dengan memanfaatkan dataset tersebut, buatlah sebuah file __Jupyter notebook (.ipynb)__ yang berisi model machine learning untuk mengklasifikasikan data __pemain muda Indonesia di bawah ini__ apakah tergolong pemain yang patut Anda rekrut atau tidak:

Name | Club | Country | Age | Height | Weight | Avg Points | Avg Rebounds 
--|--|--|--|--|--|--|--
Andakara Prastawa Dyaksa | Pelita Jaya Bakrie | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 24 | 190 | 90 | 7 | 6
Reggie Mononimbar | Pelita Jaya Bakrie | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 21 | 185 | 86 | 6 | 3
Hardianus Lakudu | Satria Muda Pertamina Jakarta | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 23 | 178 | 83 | 10 | 3
Kevin Yonas Sitorus | Satria Muda Pertamina Jakarta | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 26 | 185 | 75 | 11 | 4
Arki Dikania Wisnu | Satria Muda Pertamina Jakarta | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 20 | 183 | 80 | 5 | 2
Laurentius Steven Oei | Satria Muda Pertamina Jakarta | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 21 | 191 | 85 | 4 | 10
Mei Joni | Stapac | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 25 | 188 | 90 | 7 | 5
Vincent Rivaldi Kosasih | Stapac | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 23 | 179 | 87 | 1 | 2
Hardian Wicaksono | Pacific Caesar Surabaya | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 21 | 177 | 80 | 9 | 8
Brandon Jawato | Louvre Surabaya | <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Flag_of_Indonesia.svg/35px-Flag_of_Indonesia.svg.png' alt='lintang' style='height:13px; width:18px'/> Indonesia | 24 | 182 | 85 | 6 | 5

__Requirements:__

- Buatlah sebuah file __Jupyter Notebook (.ipynb)__.
- Download & gunakan dataset [NBA players](https://www.kaggle.com/justinas/nba-players-data). Bersihkan data, lakukan __standardisasi__ & split menjadi __82%__ untuk training set & __18%__ untuk testing set.
- Buatlah __3 model__ machine learning untuk klasifikasi (pilihan  model bebas), lakukan __hyperparameter tuning__ untuk menentukan nilai parameter terbaik tiap model.
- Gunakan parameter terbaik model untuk melakukan prediksi pada testing set. Kemudian hitung __evaluation metrics__ tiap model. Metrics yang wajib dihitung yakni: __balanced accuracy__, __precision__, __recall__, __F1 score__ & __ROC AUC score__.
- Bandingkan nilai tiap model & gunakan model terbaik yang diperoleh, untuk mengklasifikasi data pada tabel pemain muda Indonesia di atas, manakah pemain yang patut direkrut atau tidak. Tampilkan hasilnya dalam sebuah __dataframe__.

#
