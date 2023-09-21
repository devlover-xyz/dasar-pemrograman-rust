# Pengenalan tentang Rust untuk Pemula
Rust: A language empowering everyone to build reliable and efficient software.

Dalam dunia bahasa pemrograman, Rust telah muncul sebagai bintang terang, dikenal karena kekuatan, keamanan, dan fleksibilitasnya. Jika Anda baru mengenal Rust atau baru memulai perjalanan Anda ke dunia pemrograman, pengantar ini akan membantu Anda memahami apa itu Rust dan mengapa hal itu penting.

## Apa itu Rust?

Rust adalah bahasa pemrograman multi-paradigma (bahasa pemrograman yang mendukung pemrograman berorientasi objek dan aspek), dengan tujuan umum yang dirancang untuk kinerja dan keamanan, terutama konkurensi yang aman. Rust secara sintaksis mirip dengan C++, tetapi dapat menjamin keamanan memori dengan menggunakan pemeriksa pinjaman untuk memvalidasi referensi.


Bahasa pemrograman Rust merupakan bahasa komputer dengan karakteristik berorientasi objek yang sering dihargai sebagai alternatif dari C++ tradisional. Meskipun secara sintaksis mirip dengan C++, Rust juga memiliki berbagai fitur sendiri yang menjadikannya bahasa pemrograman multi-paradigma yang pada dasarnya mendukung dua pemrograman, baik yang berorientasi objek maupun aspek. Rust mendapatkan banyak perhatian karena kemampuan nya yang cukup unik dan serba bisa, sama halnya seperti Python.

## Sejarah Rust
Rust dimulai sebagai proyek sampingan milik Graydon Hoare, seorang karyawan di Mozilla. Dalam waktu singkat, Mozilla melihat potensi bahasa baru dan mulai mensponsorinya, sebelum mengungkapkannya kepada dunia pada tahun 2010.

Salah satu kemungkinan sumber nama itu, menurut Hoare, adalah “jamur karat” yang akhirnya menyebabkan pemrogram Rust mengadopsi “Rustaceans” sebagai moniker pilihan mereka.

Meskipun bahasa pemrograman ini tergolong masih baru, Rust terus meningkat di jajaran bahasa pemrograman populer. Bahkan, meskipun peringkat 33 pada Juli 2019, pada Juli 2020 telah naik ke posisi 18 di Indeks Komunitas Pemrograman TIOBE. Demikian pula, menurut Survei Pengembang Stack Overflow, Rust telah menjadi bahasa “paling dicintai” (most beloved programming language) sejak 2016. 

1. Rust pertama kali dibuat oleh salah seorang pegawai dari Mozilla yang bernama Graydon Hoare sekitar tahun 2006. Saat itu, Graydon membuat bahasa pemrograman baru dan compiler dari bahasa pemrograman tersebut menggunakan OCaml.
2. Mozilla mulai men-sponsori dan mendukung Rust untuk keperluan internal pada tahun 2009 (diumumkan tahun 2010).
3. Tahun 2010, pengembangan Rust menggunakan OCaml dihentikan, digantikan dengan self-hosting compiler (Rust dibuat dengan menggunakan Rust). Tahun 2011, Rust berhasil digunakan untuk mengkompilasi dirinya sendiri. Saat itu, Rust menggunakan LLVM sbagai compiler backend.
4. Versi stabil pertama (versi 1.0.0) dari Rust berhasil dirilis pada tanggal 15 Mei 2015.
5. Setelah itu, Rust menetapkan pola rilis pasti setiap 6 minggu, artinya setiap 6 minggu ada rilis baru untuk versi stabil, beta, dan nightly.

## Fitur Utama Rust:

Sejak awal, Rust fokus pada “safety” (keamanan) dan “performance” (performa) dan salah satu cara utama untuk mencapai fokus ini adalah dengan menekankan konkurensi yang aman. Komputasi konkuren memungkinkan bagian-bagian yang berbeda dari suatu program untuk dieksekusi secara tidak berurutan yang membuka kemungkinan komputasi paralel, di mana banyak tugas dapat diselesaikan secara bersamaan, bukan secara berurutan, dan pada akhirnya, secara signifikan meningkatkan kinerja aplikasi. Karena Rust dirancang berdasarkan prinsip ini, Rust memiliki beberapa keunggulan signifikan dalam bidang kinerja.

Dalam hal sintaks, Rust mirip dengan C dan C++, menggabungkan banyak kata kunci dan perintah dari kedua bahasa. Namun bukan klon langsung, karena Rust memiliki beberapa elemen yang tidak ditemukan di C atau C++.

Rust tidak memiliki pengumpulan “sampah” otomatis dan tidak menggunakan Penghitungan Referensi Otomatis seperti Swift. Sebaliknya, ini dirancang untuk menjadi memori yang aman dengan menggunakan prinsip-prinsip “ownership” dan “borrowing”. Karena tidak menggunakan pengumpulan sampah, ini menjadikan Rust sebagai opsi ideal untuk integrasi dengan C.

Rust pada dasarnya bertujuan untuk mempermudah dalam membangun sistem yang andal dan efisien. Rust menggabungkan kontrol tingkat rendah atas kinerja dengan kenyamanan tingkat tinggi dan jaminan keamanan yang tinggi. 

Rust juga berbeda dari bahasa pemrograman lain berdasarkan sistem tipenya, yang mewakili penyempurnaan dan kodifikasi “praktik terbaik” yang telah dilakukan oleh generasi pemrogram C dan C++. Dengan demikian, Rust memiliki sesuatu untuk ditawarkan baik untuk Programmer berpengalaman maupun pendatang baru. Programmer berpengalaman akan menemukan bahwa mereka menghemat waktu yang mereka habiskan untuk debugging, sedangkan pendatang baru dapat menulis kode tingkat rendah tanpa khawatir tentang kesalahan kecil yang menyebabkan crash misterius.

Fitur-fitur ini telah membantu Rust masuk ke beberapa perusahaan teknologi terbesar, termasuk Firefox, Cloudflare, Dropbox, Yelp, dan lainnya.


1. **Keamanan Memori**: Salah satu keunggulan terbesar Rust adalah jaminan keamanan memori yang ketat. Ini menghilangkan kesalahan pemrograman umum seperti dereferensi null pointer dan overflow buffer, menjadikannya sangat andal.

2. **Konkurensi**: Rust menyediakan alat-alat kuat untuk pemrograman konkuren tanpa risiko rasionalisasi data, berkat sistem kepemilikan dan sistem peminjaman.

3. **Kinerja**: Rust menawarkan kinerja yang sebanding dengan bahasa tingkat rendah seperti C dan C++ sambil tetap fokus pada keamanan.

4. **Sintaksis Modern**: Sintaksisnya modern dan ekspresif, sehingga mudah diakses bagi pengembang yang berasal dari bahasa pemrograman lain.

5. **Komunitas dan Ekosistem**: Rust memiliki komunitas yang aktif dan ramah, serta ekosistem yang berkembang dari perpustakaan dan alat-alat.

## Mengapa rust menjadi populer?
Menurut Survei Stack Overflow 2020 yang dilakukan di antara hampir 65.000 pengembang, Rust adalah bahasa pemrograman yang paling disukai (most beloved programming language). Pada tahun yang sama, pengembang kernel Linux mengusulkan penulisan kode kernel Linux baru di Rust. Untuk lebih jelasnya, mereka tidak ingin menulis ulang seluruh Kernel, yang awalnya ditulis dalam C, tetapi untuk menambahkan kode baru di Rust yang akan bekerja dengan infrastruktur yang ada. 

Selain itu, Google juga berencana untuk menggunakan Rust di kernel Linux setelah membawa dukungan untuk bahasa pemrograman sistem Rust ke Android. Seluruh operasi ditujukan untuk mengurangi kelemahan keamanan. Microsoft, sementara itu, telah beralih ke Rust untuk mengurangi bug terkait memori di komponen Windows.

Facebook juga telah menjalin hubungan lebih dekat dengan Rust, bergabung dengan Rust Foundation, sebuah organisasi yang dibuat pada tahun 2021 untuk mendorong pengembangan Rust dan menjadikannya “bahasa pilihan utama untuk pemrograman sistem dan seterusnya.” Facebook bergabung dengan Amazon Web Services, Google, Huawei, Microsoft, dan Mozilla dalam menggunakan Rust dalam beberapa kapasitas.

Rust saat ini memiliki basis pengguna yang luas dan overhead yang rendah sebagai manfaat praktis menggunakan Rust, sementara yang lain menunjuk ke berbagai jenis fungsionalitas, seperti kemampuan Rust untuk dikompilasi ke dalam Majelis Web.

Tahun lalu, Rust mewakili pilihan populer bagi para web developers menurut Stack Overflow. Rust juga lebih banyak dipilih karena dengan menggunakan Rust, para web developers cenderung mengurangi resiko kecil  kebocoran memori di dalam penulisan kode mereka.

Selain itu, Rust memiliki pustaka perangkat lunaknya sendiri dan kompiler yang membantu, menurut beberapa pengguna, dan relatif mudah dibaca. Kompiler Rust memiliki lisensi ganda di bawah MIT dan Apache.

## Mengapa Belajar Rust?

Belajar Rust memiliki beberapa alasan:

**Peluang Karier**: Rust banyak dibutuhkan untuk berbagai peran pengembangan perangkat lunak, terutama dalam pemrograman sistem, pengembangan game, dan embeded sistem.

**Keamanan**: Memahami Rust membantu Anda menjadi pemrogram yang lebih baik dengan mengajarkan praktik yang baik untuk menulis kode yang aman dan andal.

**Fleksibilitas**: Fleksibilitas Rust berarti Anda dapat menggunakannya untuk berbagai aplikasi, mulai dari pengembangan web hingga membangun sistem operasi.


## Memulai dengan Rust

Untuk memulai perjalanan Anda dengan Rust, Anda perlu menginstal bahasa pemrograman Rust di komputer Anda. Anda dapat menemukan petunjuk instalasi di situs web resmi Rust (https://www.rust-lang.org/). Setelah diinstal, Anda dapat mulai menulis dan menjalankan program Rust.

Sebagai kesimpulan, Rust adalah bahasa pemrograman yang luar biasa yang menggabungkan kinerja tinggi dengan keamanan dan sintaksis modern. Apakah Anda tertarik pada pemrograman sistem tingkat rendah atau membangun aplikasi yang kokoh dan konkuren, Rust memiliki banyak yang ditawarkan. Embrasilah proses belajar, jelajahi fiturnya yang unik, dan Anda akan menemukan potensi besar yang dimiliki Rust untuk usaha pemrograman Anda.

Selamat datang dalam dunia pemrograman Rust, di mana Anda akan memulai perjalanan penguasaan dan inovasi.

Jangan ragu untuk menjelajahi lebih dalam tentang Rust dan menjelajahi berbagai aspeknya saat Anda memulai perjalanan pemrograman Anda. Jika Anda memiliki pertanyaan khusus atau topik yang ingin Anda eksplorasi lebih lanjut, jangan ragu untuk bertanya.

sumber:
https://academy.alterra.id/blog/belajar-rust-pengertian-sejarah/