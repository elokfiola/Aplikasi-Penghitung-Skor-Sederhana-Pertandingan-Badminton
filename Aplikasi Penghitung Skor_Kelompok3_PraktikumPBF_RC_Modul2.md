> Optimalisasi Perhitungan Skor Pertandingan Badminton: Penggunaan
> Fungsi Reduce dan Lambda untuk Otomatisasi Perhitungan Skor
>
> Hermawan Manurung1, Elok Fiola2, Vira Putri Maharani3 , Diana
> Syafithri4 , Rani Puspita Sari5, Jihan Putri Yani6
>
> 1, 2, 3, 4,5,6 Program Studi Sains Data, Fakultas Sains, Institut
> Teknologi Sumatera, Jalan Terusan Ryacudu, Way Huwi, Kec. Jati Agung,
> Kabupaten Lampung Selatan, Lampung 35365
>
> Abstrak: Perkembangan teknologi telah memberikan dampak yang
> signifikan terhadap berbagai bidang kehidupan, termasuk dunia
> olahraga. Salah satu inovasi terkini adalah program penghitungan hasil
> pertandingan bulutangkis yang menggunakan teknologi software.
> Artikelinimembahas pengembangan dan implementasi programini.Program
> inimemfasilitasi dan meningkatkan perhitungan otomatis hasil
> pertandingan. Menggunakan fungsi pengurangan dan lambda dari bahasa
> pemrograman Python, program ini mampu meningkatkan transparansi dan
> keterbacaan hasil serta membantu meningkatkan minat dan partisipasi
> dalam olahraga. Penerapan konsep pemrograman tingkat lanjut juga
> menunjukkan kemampuan program dalam menggabungkan teknologi dan
> keahlian pemrograman untuk menciptakan solusiyang efektif dan efisien.
> Oleh karena itu, kartu skor bulutangkis tidak hanya merupakan alat
> praktis dalam olahraga, namun juga merupakan contoh nyata bagaimana
> teknologi dapat mendukung dan meningkatkan pengalaman olahraga secara
> keseluruhan.
>
> Kata kunci: tenologi pemrograman, penghitung skor, badminton, fungsi
> reduce, fungsi lambda, olahraga
>
> Pendahuluan
>
> Dewasa ini perkembangan teknologi serta kemajuan ilmu pengetahuan dan
> teknologi (Iptek) telah berkembang begitu pesat. Perkembangan
> teknologi memunculkan perubahan terhadap kehidupan seiyaahari-hari
> manusia, tidak sedikit manusia telah terbantu dalam aktivitas mereka
> oleh teknologi. Pada dasarnya teknologi diciptakan untuk memudahkan
> pekerjaan manusia. Saat ini, teknologi telah menjadi kebutuhan utama
> manusia. Faktanya, teknologi telah digunakan di semua bidang kehidupan
> manusia (Cholik, 2021).
>
> Perkembangan teknologi tidak hanya berkembang dalam bidang tertentu
> saja, menurut (Cholik, 2021) terdapat beberapa bidang utama
> perkembangan teknologi yang mempengaruhi tingkat kemajuan suatu
> negara, antara lain bidang pendidikan, bidang perekonomian, bidang
> kesehatan, bidang manajemen, dan bidang sosial budaya.Namun
> dalam(Salam,Dharma Hita,& Juliansyah,2021)mengatakan bahwa kemajuan
> teknologi dirasakan pada bidang ilmu pengetahuan, bidamg ekonomi,
> bahkan bidang olahraga.
>
> Teknologi cukup berkembang dalam bidang olahraga, baik sebagai sarana
> informasi maupunkesehatan.Dilansir dari *website* Fimela.comterdapat
> faktabahwa DOOgether
>
> yang merupakan sebuah platform aplikasi fitnes mengalami peningkatan
> pelanggan aktif lebih dari 1000persen selama 6 bulan.Hal tersebut
> diungkapkan olehFauan Gani dlam siaran pers (Putri, 2020). Aplikasi
> merupakan salah satu jalan perkembangan teknologi di bidang olahraga,
> tak sedikit aplikasi penunjang olahraga yang sudah tersedia. Bahkan
> tidak hanya aplikasi yang dapat membantu aktivitas individu saja namun
> juga terdapat beberapa aplikasi yang dapat digunakan untuk sekelompok
> individuuntuk meringankan beban kerja. Salah satucontohnya adalah
> sebuahaplikasi yang dapat menghitung skor pertandingan dan
> menyimpulkan pemenang. Aplikasi penghitung skor pertandingan badminton
> merupakan suatu aplikasi penghitung skor sederhana yang dikembangkan
> menggunakan pemrograman berbasis fungsi dengan tujuan untuk membantu
> penghitungan skor pertandingan badminton sehingga mencegah terjadinya
> kecurangan dalam menentukan pemenangnya.
>
> Metode
>
> Aplikasi penghitung skor sederhana dikembangkan menggunakan
> pemrograman berbasis fungsi dengan beberapa fungsi *built-in* dan
> *user-defined* *function* dalam Python, sebagai berikut:
>
> 1\. print( ), merupakan fungsi untuk menampilkan atau mencetak output
> di layar konsol;
>
> 2\. input( ), merupakan fungsi bawaan Python yang digunakan untuk
> menerima input dari pengguna melalui konsol;
>
> 3\. lambda( ), atau fungsi anonim merupakan suatu fungsi yang
> memungkinkan dibuat dalam satu baris dan hanya akan digunakan sekali;
>
> 4\. reduce( ), merupakan fungsi biner dari modul ‘functools’ untuk
> mengurangi iterable menjadi sebuah nilai tunggal;
>
> 5\. hitung_skor, merupakan fungsi lambda yang menghitung skor
> pertandingan berdasarkan skor yang sudah dimasukan;
>
> 6\. cek_kemenangan, merupakan fungsi lambda yang memeriksa apakah
> salah satu tim telah mencapai skor maksimal dan menentukan
> pemenangnya;
>
> 7\. main( ), merupakan fungsi utama yang mengatur alur program utama
> dan melakukan interaksi dengan pengguna.
>
> Pembahasan
>
> Dalam pembuatan aplikasi penghitung skor badminton kali ini, kami
> memanfaatkan fungsi lambda dan fungsi reduce.
>
> from functools import reduce
>
> Hal pertama yang perlu dilakukan adalah mengimport modul functools,
> yaitu modul bawaan Python yang memuat beberapa fungsi bermanfaat,
> salah satu fungsinya adalah fungsi reduce, yang digunakan untuk
> menggabungkan semua hasil pertandingan dan menghitung skor akhir.
> Berikut dilampirkan keseluruhan kode dari aplikasi penghitung skor
> badminton memanfaatkan fungsi reduce dan lambda.
>
> \# Menampilkan instruksi perintah untuk pengguna print("PAPAN
> PENGHITUNG SKOR PERTANDINGAN BADMINTON") print("\nCara Penggunaan:")
>
> print("Masukkan skor tambahan") print("'A' untuk Tim A") print("'B'
> untuk Tim B") print("'selesai' untuk mengakhiri") print("")
>
> Blok kode di atas menunjukkan bahwa program akan mencetak instruksi –
> instruksi yang ditujukan kepada pengguna aplikasi mengenai cara
> penggunaan aplikasi penghitung skor badminton, meliputi cara
> memasukkan skor dan cara mengakhiri pertandingan dengan menggunakan
> fungsi ‘print()’.
>
> \# Lambda Functions
>
> hitung_skor = lambda poin: reduce(lambda a, b: (a\[0\] + 1, a\[1\]) if
> b == 'A' else (a\[0\], a\[1\] + 1), poin, (0, 0))
>
> Pada blok kode di atas terdapat fungsi hitung_skor yang merupakan
> variabel yang mengandung fungsi lambda dan mereduksi urutan skor
> mengunakan fungsi reduce. Pada fungsi lambda terdapat parameter a yang
> merepresentasikan skor sementara kedua tim, sedangkan parameter b
> merepresentasikan skor terbaru yang ditambahkan dalam pertandingan
> badminton.
>
> cek_kemenangan = lambda skors, maks_skor, nama_tim_A, nama_tim_B: \\
>
> nama_tim_A if skors\[0\] \>= maks_skor else (nama_tim_B if skors\[1\]
> \>=
>
> maks_skor else None)
>
> Pada fungsi cek_kemenangan disimpan fungsi lambda yang digunakan untuk
> memeriksa tim mana yang memenangkan pertandingan berdasarkan skor
> akhir dan skor maksimal yang didapatkan. Tim dengan skor tertinggi
> merupakan pemenang dan jika kedua tim belum mencapai skor maksimal,
> maka fungsi lambda akan mengembalikan ‘None’ menandakan pertandingan
> belum selesai.
>
> def main():
>
> nama_tim_A = input("Masukkan nama tim A: ") nama_tim_B =
> input("Masukkan nama tim B: ") print()
>
> maksimal_skor = 21 poin_pertandingan = \[\]
>
> Fungsi main( ) berisi perintah memasukan inputan nama kedua tim dari
> pengguna juga terdapat maksimal_skor sebagai toleransi program
> berjalan. Jika salah satu skor tim melebihi 21 maka program akan
> berhenti. Terdapat list poin_pertandingan untuk menyimpan skor selama
> pertandingan badminton.
>
> while True:
>
> tambahan_skor = input(f"Masukkan skor tambahan ('A' / 'B'), atau
> 'selesai' untuk mengakhiri): ").upper()
>
> if tambahan_skor == 'A' or tambahan_skor == 'B':
> poin_pertandingan.append(tambahan_skor) skor_akhir =
> hitung_skor(poin_pertandingan)
>
> if skor_akhir\[0\] \>= maksimal_skor or skor_akhir\[1\] \>=
> maksimal_skor:
>
> break
>
> elif tambahan_skor == 'SELESAI': break
>
> else:
>
> print("Masukkan tidak valid. Silakan masukkan 'A', 'B', atau
> 'selesai'.")
>
> Kode tersebut merupakan infinite loop yang meminta user untuk input
> skor tambahan atau input selesai untuk mengakhiri perhitunagan skor
> pertandingan. Jika salah satu tim mencapai atau melebihi maksimal skor
> maka loop akan dihentikan dengan ‘break’ dan ke tahap selanjutnya.
> Pada kode tersebut juga terdpapat pesan kesalahan dimana jika input
> yang dimasukan tidak valid maka loop ini memungkinkan user untuk
> interaktif input skor tambahan.
>
> print("\nSkor Akhir Pertandingan:")
>
> print(f"\[{nama_tim_A}: {skor_akhir\[0\]}, {nama_tim_B}:
> {skor_akhir\[1\]}\]")
>
> Kode diatasmenunjukan untuk mencetak skor akhirdari pertandingan
> antara dua tim. Dengan menggunakan f-string, nilai – nilai akan
> dimasukan ke dalam string sehingga hasil cetak memberikan informasi
> yang sesuai megenai hasil akhir dari pertandingan.
>
> pemenang = cek_kemenangan(skor_akhir, maksimal_skor, nama_tim_A,
> nama_tim_B)
>
> if pemenang:
>
> print("\nTim", pemenang, "memenangkan pertandingan badminton!")
>
> print(f"Dengan skor akhir \[{skor_akhir\[0\]}, {skor_akhir\[1\]}\]")
>
> else:
>
> print("Pertandingan belum selesai.")
>
> Kode diatas berfungsi untuk menentukan pemenang dari pertandingan
> bedasarkan skor akhir pertandingan. Fungsi ‘cek_kemenangan()’
> dipanggil untuk menjalankan skor akhir, maksimal skor dan nama tim
> yang bersaing. Jika hasil string program menunjukan ada pemenang, maka
> program akan cetak nama tim yang memenangkan pertandingan.
>
> if \_\_name\_\_ == "\_\_main\_\_": main()
>
> Blok kode di atas memeriksa apakah program dijalanan secara langsung
> atau diimpor sebagai modul. Jika file program dijalankan secara
> langsung maka fungsi main( ) akan dieksekusi saat program dijalankan.
>
> Kode lengkap dapat dilihat pada tautan berikut:
> [<u>https://github.com/elokfiola/Aplikasi-Penghitung-Skor-Sederhana-Pertandingan-Badminton/blob/06641559fdfffac14ec4b80ae3270704ddf80eff/Penghitung_Skor_Ba</u>](https://github.com/elokfiola/Aplikasi-Penghitung-Skor-Sederhana-Pertandingan-Badminton/blob/06641559fdfffac14ec4b80ae3270704ddf80eff/Penghitung_Skor_Badminton.ipynb)
> [<u>dminton.ipynb</u>](https://github.com/elokfiola/Aplikasi-Penghitung-Skor-Sederhana-Pertandingan-Badminton/blob/06641559fdfffac14ec4b80ae3270704ddf80eff/Penghitung_Skor_Badminton.ipynb)
>
> Kesimpulan
>
> Program penghitungan skor pertandingan badminton merupakan sebuah
> inovasi yang memberikan dampak signifikan dalam dunia olahraga. Dengan
> memanfaatkan teknologi pemrograman, program ini memberikan kemudahan
> dan efisiensi dalam menghitung skor pertandingan secara otomatis.
> Transparansi dan keterbacaan skor menjadi lebih baik, sehingga
> memudahkan pemain, pelatih, dan penonton untuk mengikuti perkembangan
> pertandingan dengan lebih baik. Melalui kontribusinya dalam
> mempermudah penghitungan skor, program ini juga berperan dalam
> meningkatkan minat dan partisipasi masyarakat dalam olahraga, serta
> membantu dalam penyelenggaraan dan dokumentasi pertandingan. Penerapan
> konsep pemrograman lanjutan, seperti penggunaan fungsi lambda dan
> reduce, menunjukkan kemampuan program ini dalam menggabungkan
> teknologi dan keahlian pemrograman untuk menciptakan solusi yang
> efektif dan efisien dalam dunia olahraga. Dengan demikian, program
> penghitungan skor pertandingan badminton tidak hanya menjadi alat
> praktis dalam olahraga, tetapi juga merupakan contoh nyata dari
> bagaimana teknologi dapat digunakan untuk mendukung dan meningkatkan
> pengalaman olahraga secara menyeluruh.
>
> Referensi
>
> Cholik, C. A. (2021). PERKEMBANGAN TEKNOLOGI INFORMASI KOMUNIKASI /
> ICT. *Jurnal* *Fakultas* *Teknik*, 39-46.
>
> Putri, A. S. (2020, November 17). *FIMELA*. Retrieved from FIMELA
> LIFESTYLE:
> https://www.fimela.com/lifestyle/read/4409315/tren-aplikasi-olahraga-meningkat-pesat-bantu-studio-olahraga-tetap-bertahan?page=2
>
> Salam, F. A., Dharma Hita, I. A., & Juliansyah, M. A. (2021).
> AKSIOLOGI PENGGUNAAN VAR DALAM INDUSTRI OLAHRAGA. *Jurnal*
> *Penjakora*, 106-113.
