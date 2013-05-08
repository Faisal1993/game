game
====

visual basic game TETRIZ

NAMA ANGGOTA KELOMPOK

1. Faisal Akhmad Yuli Andika  -110533430522 -PTI B
2. Akhmad Aprilianto          -110533406995 -PTI A
3. Nani Masrifah              -110533406988 -PTI A
4. M. Zainul Askiya           -110533430571 -PTI C



Pengertian Game Tetriz

Tetris adalah permainan teka-teki yang disusun dan diprogram oleh sepasang programmer berkebangsaan Rusia.Dalam permainan tetris, balok-balok tetris berjatuhan ke area permainan dalam waktu konstan.Balok tetris selalu terdiri dari 4 balok kecil yang membentuk 7 macam rupa.


Algoritma

Pemain dapat mengontrol balok tetris yang jatuh melalui 4 tombol arah panah untuk menggeser ke kanan atau ke kiri dan tombol arah panah ke bawah untuk mempercepat jatuhnya balok tetris. Satu kendali yang lain adalah untuk memutar bentuk balok tetris 90º’
Algoritma yang gunakan untuk mencari solusi dari permainan tetris adalah algoritma yang menggunakan konsep-konsep yang ada dalam algoritma Greedy dan Algoritma BruteForce.Algoritma Greedy merupakan metode yang paling umum digunakan untuk memecahkan masalah optimasi.Algoritma ini sederhana dan sesuai dengan tujuan yang ada.

Algoritma Greedy memecahkan masalah langkah per langkah, pada setiap langkah:
1. mengambil pilihan yang terbaik yang dapat diperoleh pada saat itu tanpa memperhatikan konsekuensi ke depan (prinsip “take what you can get now!”)
2. berharap bahwa dengan memilih optimum local pada setiap langkah akan berakhir dengan optimum global Brute force adalah sebuah pendekatan yang sesuai (straightforward) untuk memecahkan suatu masalah, biasanya didasarkan pada pernyataan masalah (problem statement) dan definisi konsep yang dilibatkan.

Algoritma brute force memecahkan masalah dengan sangat sederhana, langsung dan dengan cara yang jelas (obvious way). Algoritma yang digunakan untuk mendapatkan susunan tumpukan balok yang paling baik dengan menempatkan balok ke tempat yang tepat.Algoritma ini menggunakan prinsip Greedy dalam mencari langkah sollusi yang paling menguntungkan. Prioritas keuntungan yang tersusun terdiri dari:
1. Membentuk satu atau lebih baris paling penuh
2. Membentuk satu atau lebih baris paling mendekati penuh
3. Tidak membentuk ruang kosong pada susunan tumpukan balok
4. Balok dapat masuk ke dalam susunan tumpukan balok paling dalam Algoritma yang kami kemukakan akan mencari penempatan balok yang jatuh ke ruang yang paling tepat sesuai prioritas keuntungan di atas diantara susunan tumpukan  balok. Pencarian ini akan dilakukan secara Brute Force. Balok yang jatuh akan dicoba untuk ditempatkan ke ruang di antara susunan tumpukan balok dibawah.
