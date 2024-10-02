### NAMA : Louise Olivia Panggabean
### NIM : 09011282328032
### KELAS : SK3B

# Praktikum Penerapan Aplikasi Client Server

## A. INSTALASI DAN KONFIGURASI SSH SERVER PADA UBUNTU LINUX
1. Lakukan pembaruan sistem "sudo apt update" , agar dipastikan semua paket pada sistem yang terinstall sudah menggunakan versi terbaru.
  
2. Lakukan Installasi SSH server pada terminal "sudo apt install openssh-server"
   
   ![Screenshot from 2024-09-26 09-03-26](https://github.com/user-attachments/assets/94aa8ffc-9019-4296-8bb3-22107a1d26c5)

3. Lakukan pengecekan SSH untuk melihat status layanan aktif atau tidak, dan pada pada gambar tersebut terlihat layanan masih berstatus "enabled" artinya layanan belum aktif.

   ![Screenshot from 2024-09-26 09-06-07](https://github.com/user-attachments/assets/d298ab2c-f1e6-4ae9-a8c3-0b910ac1e2a7)

4. Karenan layanan SSH belum aktif, maka kita perlu mengaktifkan layanan SSH dengan menggunakan perintah "sudo systemctl enable --now ssh"

   ![Screenshot from 2024-09-26 09-07-51](https://github.com/user-attachments/assets/db71af26-5527-4afb-86ca-6070507f8fb4)

5. Setelah layanan diaktifkan lakukan pengecekan ulang status layanan, terlihat dari gambar berikut status layanan telah aktif.

   ![Screenshot from 2024-09-26 09-08-39](https://github.com/user-attachments/assets/9059d4f1-c1da-4ad0-8715-8c4a06fa5ca6)

6. Setelah layanan aktif, maka kita bisa coba untuk menghubungkan ke server dengan masukkan perintah "ssh username@IP_address", dan masukkan kata sandi client yang akan kita hubungkan. Pada gambar berikut server telah terhubung dan kita bisa mengakses server client yang telah dihungkan, dan  Disini saya mencoba untuk memerintahkan untuk mengecek "history"
   <img src="https://github.com/user-attachments/assets/129f1299-fe33-4bbe-acbd-af06d1948c62" width=500/>


## B. INSTALLASI CLIENT SERVER PuTTY
1. Aktifkan repository Universe dalam sistem ,karena PuTTY tersedia di repositori Ubuntu Universe. Kemudian, lakukan pembaruan sistem "sudo apt update" , agar dipastikan semua paket pada sistem yang terinstall sudah menggunakan versi terbaru.
   
    <img src="https://github.com/user-attachments/assets/67d53d3a-6d74-456a-8491-120526fd2f34" width=500/>

2. Lakukan installasi PuTTY pada sistem dengan perintah dalam terminal "sudo apt install -y putty". Kemudian kita cek verivikasi dan versi program dengan perintah "putty --version".
   
   <img src="https://github.com/user-attachments/assets/19595ccf-3236-45ba-bb32-a5be2d1e65b3" width=500 />

3. Untuk menjalankan PuTTY kita dapat menemukannya dalam menu aplikasi dengan mencari dan mengetik "putty". Berikut ini tampilan aplikasi PuTTY.

   <img src="https://github.com/user-attachments/assets/76d64d69-7a21-4ab6-97db-ae7579575d81" width=500/>

   
   
