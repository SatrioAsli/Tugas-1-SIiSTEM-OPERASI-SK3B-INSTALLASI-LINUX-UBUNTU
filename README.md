# Tugas-1-SISTEM-OPERASI-SK3B-INSTALLASI-LINUX-UBUNTU

TUGAS INSTALASI LINUX UBUNTU 24.0.4 LTS DI VIRTUAL BOX
Nama   : Satrio Joronggur Mahendra
Kelas  : SK3B
Nim    : 09011282328092

1. Pertama, download terlebih dahulu file iso linux Ubuntu  deskop 24.0.4 LTS dan software virtualbox oracel, lalu instal dan jalankan virtualboxnya

   Link file iso linux : https://ubuntu.com/download/desktop
   Link software VirtualBox : https://www.virtualbox.org/wiki/Downloads

   
3. Langkah selanjutnya buka virtualbox, lalu klik new
![Screenshot 2024-08-29 202226](https://github.com/user-attachments/assets/05c7e0d6-c3be-4705-9a4d-48bafd070ea9)


4. Masukla ke halaman berikut ini, lalu isi nama nya, pilih lokasih folder untuk menyimpan linuxnya, untuk iso imagenya pilih file iso ubuntu yang sudah didownload tadi. lalu tekan next
  ![screenshot5](https://github.com/user-attachments/assets/f577ae5a-254f-42d2-be68-de3da25c36e1)


5. dibagian ini kita next aja, jika mengalami error pada hostname maka pastikan pada namanya tidak ada spasi melainkan menggukana (-)
   ![screenshot4](https://github.com/user-attachments/assets/6cce3f96-60b1-4a5c-8972-fb5802fe6e32)


6. Dibagian ini saya menggunakan dan menyarankan memory basenya menjadi 30000mb dan di bagian prosecornya di naikan minimal 2 agar tidak terjadi lag yang berlebihan
   ![screenshot3](https://github.com/user-attachments/assets/36ee6daa-3646-48c7-9953-9e534a66d964)

   
7. pada bagian ini virtual storage atau penyimpanan virtual saya menggunakan 25gb, semakin besar storage yang diatur maka storage yang tersedia itu lebih besar lalu klik next dan finish kan maka virttual box akan berjalan/running. jika virtual boxnya kembali ke halaman semula dengan tambahn file yang kita buat tadi maka klik lalu klik start untuk merunning programnya.
![screenshot2](https://github.com/user-attachments/assets/43bff0c0-7000-455a-8951-2ec79ad3229a)
![Screenshot 2024-08-29 202906](https://github.com/user-attachments/assets/f307c040-067c-406c-8705-31c4badef66f)


8. masuklah ketampilan berikut, pilih bahasa yang diinginkan 
![screenshot 10](https://github.com/user-attachments/assets/56e171df-89f9-4410-ae94-896390c0ab7c)

9. lalu next aja sampai di bagian ini bisa pilih no connection atau wired connection jika terhubung dengan koneksi internet. kemudian next lagi
![screenshot 11](https://github.com/user-attachments/assets/e10b1c72-e79a-4411-b2a9-a2bff86076d8)



10. pilih install ubuntu kemudian next lagi.
![screenshot 12](https://github.com/user-attachments/assets/83c8e369-f546-4e5a-ab03-19884dd4d4bd)



11. sampai di bagian ini centang install third party, atau bisa juga centang download and install support jika perangkkat terkoneksi internet.
![screenshot 13](https://github.com/user-attachments/assets/919b3750-f752-44a5-bebb-0a3200bda9dc)

12. dibagian ini instalasi partisi ini, saya memilih next karena memakai virtualbox yang sudah ada 1 storage virtual yang kosong.
![screenshot 14](https://github.com/user-attachments/assets/78ee2c66-cd6c-4fa2-a352-44e7beb7a410)


13. kemudian membuat username linux dan passwordnya untuk login

   ![screeshoot](https://github.com/user-attachments/assets/3c9bc4fe-14c2-4b20-8bad-0988fc101b7f)


14. lalu pilih titik lokasi kalian, kalo saya pilih di jakarta saja, lalu next
![screenshot 8](https://github.com/user-attachments/assets/bc3a8633-9f19-4789-9801-1d8db64d27be)


15. masuklah ke proses installasi yang membutuhkan waktu yang cukup lama, setelah selasai kita disuruh login dengan memasukan usename dan password tadi lalu muncul  pilihan mau restart atau continue dan ini terserah mau pilih yang mana
![screenshot 9](https://github.com/user-attachments/assets/2e0ddc8a-64ee-4190-9005-58a0c553945a)
![15](https://github.com/user-attachments/assets/880d8684-79c7-4e64-9fc7-af967ccf61be)





Analisalah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi Mount Point?
pada proses instalasi linux, awalnya saya menggunakan auto partition tetapi pada percobaan kedua saya mencoba manual partition untuk mengetahui apa saja perbedaan nya dan untuk menjawab pertanyaan no 2 ini.

Saat instalasi Ubuntu, memilih "/" sebagai opsi mount point berarti kita mengatur partisi tersebut untuk menjadi root directory dari sistem. Direktori "/" adalah tempat utama di mana semua file sistem, aplikasi, dan data pengguna disimpan. Dengan memilih "/" untuk partisi ini, kita memastikan bahwa seluruh struktur file sistem Linux akan berada di partisi tersebut

3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32, btrfs
   
Ext4 adalah sistem file yang sering digunakan di Linux Ext4 menggunakan jurnal yang lebih efisien untuk melindungi data dan mengurangi fragmentasi file sehingga memberikan kecepatan dan stabilitas yang lebih baik

Ext3 adalah sistem file Linux yang menggunakan jurnal untuk melindungi data dan mempermudah pemulihan dari kegagalan Ext3 memiliki batasan ukuran file dan kinerja dibandingkan dengan Ext4 yang menawarkan peningkatan dalam kapasitas dan kecepatan

Swap adalah ruang di hard drive yang digunakan sebagai tambahan memori ketika RAM penuh memungkinkan sistem untuk menyimpan data yang tidak aktif di RAM ke disk sehingga memori fisik dapat digunakan untuk proses yang lebih penting swap membantu mencegah kehabisan memori meski akses ke swap lebih lambat dibandingkan dengan RAM

NTFS adalah sistem file yang dikembangkan oleh Microsoft dan digunakan terutama di Windows NTFS mendukung fitur-fitur canggih seperti izin file, enkripsi, dan kompresi data ini juga dapat menangani file dan partisi yang sangat besar dengan efisien NTFS sering digunakan untuk hard drive dan SSD di komputer Windows tetapi Linux juga dapat membaca dan menulis ke partisi NTFS dengan alat tambahan

FAT32 adalah sistem file yang kompatibel dengan banyak sistem operasi dan sering digunakan pada drive USB dan kartu memori dan memiliki batas ukuran file maksimal 4gb dan partisi maksimal 8TB FAT32 menawarkan kompatibilitas luas tanpa fitur canggih seperti enkripsi

Btrfs adalah sistem file modern di Linux yang menawarkan fitur seperti snapshot, kompresi, dan cek integritas data Btrfs dirancang untuk menggantikan Ext4 dengan keunggulan dalam manajemen ruang, pemulihan data, dan skalabilitas, mendukung partisi dan file besar dengan efisiensi tinggi

