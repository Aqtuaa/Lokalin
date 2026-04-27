# Lokalin
Website UMKM yang membantu para pengusaha UMKM mempromosikan dan memperluas jaringan produknya. 

1. System Overview
a. Tujuan dari proyek kami, Lokalin adalah website yang mempertemukan antara masyarakat dengan UMKM untuk membantu usaha kecil menengah agar mudah dikenal oleh banyak kalangan dan membantu masyarakat dalam mencari usaha yang ada di sekitarnya. 
b. Pengguna dari website ini : 
- masyarakat umum, bisa mencari umkm berdasarkan filter kategori, lokasi dan rekomendasi
- pemilik UMKM, bisa membuat profil umkm dan juga menambahkan produk
c. 3 Fitur dari Lokalin : 
- Fitur FYP, dimana sistem bisa menampilkan beberapa rekomendasi UMKM yang sudah dihitung dari jarak dan overall rating UMKM kepada user masyarakat
- Fitur Chat, user dan pemilik UMKM bisa saling mengirim pesan untuk melakukan komunikasi terkait produk yang ditawarkan dengan syarat hanya user yang bisa memulai chat dengan UMKM Owner
- Fitur Review dengan barcode, untuk menghindari review palsu atau review ngasal, user hanya bisa mengirimkan ulasan dengan barcode yang sudah di-generate oleh UMKM owner di tempat ketika sudah melakukan transaksi

2. Berdasarkan development view, struktur sistem dibagi menjadi :
FrontEnd, menggunakan HTML+CSS+JavaScript, mengatur tampilan atau UI untuk user dan pemilik UMKM, mulai dari ketika pencarian, rekomendasi, profil umkm, ulasan hingga chat dengan UMKM.
BackEnd, menggunakan Java Spring Boot, mengatur semua permintaan oleh frontEnd yang berikan oleh user melalui API dan melakukan semua operasi di belakang
Database, menggunakan mySQL, untuk menyimpan semua informasi data pribadi user, toko UMKM, produk, ulasan, dan juga chat yang sudah berlalu
Tambahan, terdapat tambahan yaitu google maps API untuk fitur lokasi sehingga bisa mendapatkan lokasi user terkini dan juga UMKM yang berada di dekatnya

3. Berdasarkan process view, alur penggunaan aplikasi antara lain : 
Tahap awal, yaitu tahap pembuatan, dimana user sebagai konsumen dan pemilik UMKM membuat akun mereka masing-masing. User membuat akun serta profill, sedangkan pemilik UMKM membuat akun, lalu membuat profil untuk tokonya dah menambahkan produk-produk. 
Tahap pencarian, dimana user bisa mencari UMKM berdasarkan rekomendasi, kategori, ataupun lokasi terdekat. Setelah pencarian, user bisa melihat detail toko yang ingin dikunjunginya dan melihat-lihat produk tersebut. User bisa memulai chat dengan pemilik UMKM untuk mendapatkan informasi lebih lanjut. Pemilik UMKM pun bisa balas chat yang disampaikan oleh si user. 
Tahap Ulasan, setelah user membeli produk UMKM di tempat, pemilik UMKM dapat mengenerate sebuah QR baru yang akan di-scan oleh user untuk memberikan ulasan kepada toko UMKM tersebut. User bisa memberikan bintang untuk berbagai aspek, komentar, dan juga foto.
