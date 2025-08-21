# sdi-data-6
## ***Title Project***
***TripAdvisor Hotel Reviews Classification and Summarization using IBM Granite***
## ***Project Overview***

<p align="justify">
   Industri perhotelan merupakan salah satu sektor ekonomi krusial industri pariwisata dengan fokus pada penyediaan akomodasi, makanan dan minuman, serta layanan terkait bagi wisatawan. Keberhasilan industri perhotelan sangat bergantung pada ulasan dan penilaian tamu yang mencerminkan kualitas layanan, reputasi, dan citra hotel. Dengan kemajuan teknologi, saat ini tamu dapat dengan mudah memberikan ulasan dan penilaian melalui berbagai <i>platform</i> digital seperti TripAdvisor. Namun, ulasan sebagai data teks merupakan data yang tidak terstruktur, sehingga diperlukan analisis sentimen. Di sisi lain, penilaian (<i>rating</i>) sebagai data terstruktur hanya menggambarkan pengalaman tamu secara global, sehingga diperlukan analisis sentimen untuk memahami pengalaman tamu dalam menikmati kualitas layanan hotel secara komprehensif.
   </p>

## ***Raw Dataset Link***
<p align="justify">
Data dalam Project ini dapat diakses secara publik melalui tautan berikut.
<b><i>https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews?select=tripadvisor_hotel_reviews.csv</i></b>
   <p>

## ***Insight & Findings***
<p align="justify">
1. Berdasarkan tiga gambar <i>Word Cloud</i> yang disediakan, tampak bahwa ulasan tamu bersifat saling tumpang tindih. Hal ini terlihat dari kemunculan kata atau tokenisasi berupa “<i>Good</i>” pada <i>Word Cloud</i> dengan Label Aktual Negatif, ataupun tokenisasi berupa “<i>n’t</i>” yang muncul pada <i>Word Cloud</i> dengan Label Aktual Positif. 
<p>

<p align="justify">   
2. Hal ini menjadi tantangan tersendiri, terutama dalam menangkap <i>insight</i> bagi pihak pengelola hotel. <i>Word Cloud</i> hanya menunjukkan frekuensi kata, bukan hubungan antarkata atau sentimen sebenarnya.
<p>

<p align="justify">
3. Kata yang sering muncul belum tentu paling penting atau paling mewakili keluhan ataupun pujian utama.
<p>

<p align="justify">
4. Berdasarkan hasil <i>Confusion Matrix</i>, tampak bahwa ulasan tamu dengan kelas aktual Netral memiliki kriteria kebaikan model yang lebih rendah dibandingkan dengan kelas lain. Hal ini dapat terjadi sebagai akibat dari kerancuan ulasan dari tamu, di mana ulasan dengan kategori netral dapat berisi kata atau frasa yang mengarah pada sentimen tertentu, baik negatif maupun positif, sehingga berakibat pada penurunan kriteria.
<p>

<p align="justify">
5. Beberapa kesimpulan yang dapat ditarik berdasarkan analisis yang telah dilakukan adalah sebagai berikut.<br>
   a. Kekuatan utama hotel terletak pada lokasi, kebersihan, kenyamanan kamar, serta keramahan staf.<br>
   b. Namun demikian, masih terdapat sejumlah tantangan dan inkonsistensi dalam pelayanan, fasilitas, dan kualitas makanan.<br>
   c. Beberapa aspek teknis dan estetika (seperti desain dan kondisi fasilitas) menjadi sumber komentar netral atau negatif.<br>
<p>

## ***AI Support Explanation***
<p align="justify">
Proyek ini melibatkan penggunaan beberapa AI sebagai berikut. 
1. ChatGPT, sebagai sarana <i>brainstorming</i> ide, eksplorasi penggunaan sintaks, dan evaluasi luaran (<i>output</i>) dari IBM Granite.
2. IBM Granite untuk melaksanakan task <b><i>Text Classification and Summarization</i></b>.
<p>
