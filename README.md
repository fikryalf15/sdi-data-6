# sdi-data-6
## ***Title Project***
***TripAdvisor Hotel Reviews Classification and Summarization using IBM Granite***
## ***Project Overview***
Industri perhotelan merupakan salah satu sektor ekonomi krusial industri pariwisata dengan fokus pada penyediaan akomodasi, makanan dan minuman, serta layanan terkait bagi wisatawan. Keberhasilan industri perhotelan sangat bergantung pada ulasan dan penilaian tamu yang mencerminkan kualitas layanan, reputasi, dan citra hotel. Dengan kemajuan teknologi, saat ini tamu dapat dengan mudah memberikan ulasan dan penilaian melalui berbagai *platform* digital seperti TripAdvisor. Namun, ulasan sebagai data teks merupakan data yang tidak terstruktur, sehingga diperlukan analisis sentimen. Di sisi lain, penilaian (*rating*) sebagai data terstruktur hanya menggambarkan pengalaman tamu secara global, sehingga diperlukan analisis sentimen untuk memahami pengalaman tamu dalam menikmati kualitas layanan hotel secara komprehensif.
## ***Raw Dataset Link***
Data dalam Project ini dapat diakses secara publik melalui tautan berikut.
***https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews?select=tripadvisor_hotel_reviews.csv***
## ***Insight & Findings***
1. Berdasarkan tiga gambar *Word Cloud* yang disediakan, tampak bahwa ulasan tamu bersifat saling tumpang tindih. Hal ini terlihat dari kemunculan kata atau tokenisasi berupa “*Good*” pada *Word Cloud* dengan Label Aktual Negatif, ataupun tokenisasi berupa “*n’t*” yang muncul pada *Word Cloud* dengan Label Aktual Positif. 
2. Hal ini menjadi tantangan tersendiri, terutama dalam menangkap *insight* bagi pihak pengelola hotel. Word Cloud hanya menunjukkan frekuensi kata, bukan hubungan antarkata atau sentimen sebenarnya. 
3. Kata yang sering muncul belum tentu paling penting atau paling mewakili keluhan ataupun pujian utama.
4. Berdasarkan hasil *Confusion Matrix*, tampak bahwa ulasan tamu dengan kelas aktual Netral memiliki kriteria kebaikan model yang lebih rendah dibandingkan dengan kelas lain. Hal ini dapat terjadi sebagai akibat dari kerancuan ulasan dari tamu, di mana ulasan dengan kategori netral dapat berisi kata atau frasa yang mengarah pada sentimen tertentu, baik negatif maupun positif, sehingga berakibat pada penurunan kriteria.
5. Beberapa kesimpulan yang dapat ditarik berdasarkan analisis yang telah dilakukan adalah sebagai berikut.<br>
   a. Kekuatan utama hotel terletak pada lokasi, kebersihan, kenyamanan kamar, serta keramahan staf.<br>
   b. Namun demikian, masih terdapat sejumlah tantangan dan inkonsistensi dalam pelayanan, fasilitas, dan kualitas makanan.<br>
   c. Beberapa aspek teknis dan estetika (seperti desain dan kondisi fasilitas) menjadi sumber komentar netral atau negatif.<br>
## ***AI Support Explanation***
Proyek ini melibatkan penggunaan beberapa AI sebagai berikut. 
1. ChatGPT, sebagai sarana *brainstorming* ide, eksplorasi penggunaan sintaks, dan evaluasi luaran (*output*) dari IBM Granite.
2. IBM Granite untuk melaksanakan task ***Text Classification and Summarization***.
