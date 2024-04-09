# JCDSOL13_CapstoneProject2_StefanusAndrewSusanto
JCDSOL13_CapstoneProject2_StefanusAndrewSusanto


# Dataset Supermarket 
# LATAR BELAKANG
Sejak berdirinya pada tahun 2012, sebuah perusahaan supermarket telah mengumpulkan beragam data mengenai pelanggan dan interaksi pelanggan dengan perusahaan yang disimpan dalam sebuah database. Hal ini menjadi penting bagi Data Scientist pada perusahaan untuk dapat memahami profil pelanggan, perilaku mereka terhadap perusahaan, kecocokan produk perusahaan dengan preferensi pelanggan, efektivitas upaya promosi, lokasi pembelian pelanggan, serta umpan balik yang diterima. Analisa Data yang mendalam ini tentunya akan berguna bagi stakeholders perusahaan dalam memberikan wawasan yang diperlukan bagi perusahaan untuk mengambil keputusan yang tepat guna memenuhi kebutuhan pelanggan, meningkatkan strategi pemasaran, dan merencanakan ekspansi di masa depan.

# Pernyataan Masalah
1. Perusahaan perlu mengidentifikasi dan menganalisa profil pelanggan, produk, promosi, dan lokasi pembelian guna meningkatkan penetrasi pasar dan pengambilan keputusan strategis.
2. Perusahaan perlu mengidentifikasi dan menganalisa segementasi dari pelanggan serta bagaimana trend utama dari produk dan penjualan perusahaan.
3. Perusahaan perlu menganalisa dan mengidentifikasi bagaimana korelasi antara produk yang dimiliki perusahaan terhadap profile customer dan sebagainya.
4. Perusahaan perlu menganalisa dan mengidentifikasi bagaimana upaya promosi yang dilakukan serta korelasinya pada produk yang dimiliki oleh perusahaan.
5. Perusahaan perlu menganalisa dan mengidentifikasi bagaimana korelasi antara lokasi pembelian terhadap produk maupun upaya promosi yang dilakukan oleh perusahaan serta customer profile.
6. Perusahaan perlu menganalisa dan mengidentifikasi bagaimana feedback yang dimiliki oleh customer dan korelasinya terhadap customer profile, produk, promosi serta lokasi pembelian yang dilakukan oleh customer

# DATASET
Jumlah baris dan kolom di dataset df adalah (2240, 29)

# DATA CLEANING AND UNDERSTANDING
- Null & Missing Value -> Kolom Income -> ambil mean

# DATA ANALYSIS
- Pembuatan EDA
- Pembuatan Segmentasi Pelanggan
- Analisa Trend Waktu
- Analisa Trend Produk
- Analisa Korelasi Produk dengan Variabel lain seperti profile customer
- Analisa Korelasi Lokasi Pembelian dengan Variabel lain seperti profile customer
- Analisa Korelasi Campaign dengan Variabel lain seperti profile customer

# KESIMPULAN 
Perusahaan Supermarket yang sudah berdiri pada tahun 2012 memiliki berbagai jenis pelanggan yang berinteraksi terhadap perusahaan dan interaksi yang terjadi antara pelanggan dengan perusahaan tersimpan dalam sebuah database. Secara keseluruhan, perusahaan Supermarket memiliki berbagai jenis pelanggan yang unik dan dapat dikategorikan berdasarkan 4 segmentasi mulai dari penghasilan, produk yang dibeli, lokasi pembelian. Perusahaan Supermarket memiliki segmentasi pelanggan yang didominasi oleh klaster 1 yang memiliki pendapatan rata-rata relatif rendah. Meskipun begitu, pada pemeriksaan EDA didapatkan rata-rata pendapatan pelanggan adalah sekitar 52247 dimana masuk dalam klaster 0 dan 3. Hal ini tentunya akan mempersulit bagi sebuah perusahaan khususnya stakeholders dalam melakukan keputusan khususnya dalam melakukan kampanye karena tidak memliki segmentasi pasar yang jelas. Hal ini juga dapat dilihat pada hasil EDA dimana respons terhadap penawaran dan kampanye cukup rendah.

Selain itu, pada tahun 2013 terjadi lonjakan yang cukup signifikan dari jumlah customer yang ada. Pada analisa didapatkan korelasi positif antara penerimaan beberapa kampanye spesifik (AcceptedCmp1, AcceptedCmp4, dan AcceptedCmp5) dengan pembelian produk tertentu, seperti wine, daging, dan ikan. Ini menunjukkan bahwa kampanye-kampanye ini mungkin berhasil menargetkan segmen pelanggan tertentu yang cenderung membeli produk-produk tersebut pada tahun 2013. Namun terjadi penurunan pada tahun 2014 kembali yang dapat disebabkan oleh kampanye pemasaran yang kurang baik.

Perusahaan Supermarket memiliki 5 produk utama yaitu (Wines, Fruits, Fish, Meats, Gold) namun jumlah pembelian terbanyak dari perusahaan didominasi oleh Wines. Pada analisa interaksi antara perusahaan khususnya produk wine dengan customer didapatkan hubungan yang linear dan positif terhadap Income customer, Kampanye 1 dan 2, dan pembelian di toko secara langsung. Hal ini juga sesuai dengan jumlah lokasi pembelian yang didominasi di toko secara langsung serta kampannye 2 yang memiliki hasil tertinggi.

Disisi lain, ke-5 produk dari perusahaan tidak memiliki pengaruh yang signifikan terhadap keluhan pelanggan serta memiliki korelasi yang negatif dengan jumlah anak di rumah. Hal ini menunjukkan bahwa semua produk yang dimiliki perusahaan tidak memberikan dampak signifikan terhadap complain pelanggan, serta pelanggan yang memiliki anak dirumah cenderung bukan merupakan segmentasi dari perusahaan.

Meskipun begitu, data yang dimiliki tidak dapat disimpulkan terhadap keberhasilan perusahaan terhadap customer karena data ini tidak didukung dengan pendapatan atau revenue sehingga tidak ada marker yang dapat dijadikan sebuah standar terhadap hasil dari perusahaan.

Secara keseluruhan perusahaan memiliki segmentasi pasar dengan penghasilan sekitar 34844$ dan tidak memiliki anak dirumah dengan kecenderungan pembelian produk didominasi oleh produk wine yang berhubungan secara linear dan positif dengan pendapatan customer dengan pembelian di toko secara langsung menggunakan kampanye 2 sebagai strategi pemasaran.

# SARAN

Perlu adanya data khususnya pendapatan perusahaan untuk dapat mengukur keberhasilan interaksi pelanggan dengan perusahaan. Perusahaan perlu melakukan segmentasi secara jelas terhadap customer yang dimiliki agar dapat melakukan kegiatan kampanye yang efisien. Sebaiknya perusahaan lebih memperhatikan segmentasi pelanggan yang cenderung rendah ke tengah (sekitar 30000 sampai 60000) yang tidak memiliki anak dirumah dengan fokus pada penjualan produk wine di toko secara langsung menggunakan kampanye seperti cmp2. Selain itu, perusahaan juga dapat melakukan ekspansi perusahaan sesuai dengan segmentasi customer yang dimliki.
