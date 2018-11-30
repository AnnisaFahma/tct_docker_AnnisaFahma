# Mencoba project (4 sknario) di katacoda 

## Skenario pertama (Deploying our first docker container

1. Melihat versi dari containernya dan menjalankannya (disini nama container yang akan saya lihat adalah redis), dengan query dibawah ini :

![gambar 1](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ss1.jpg)
![gambar 2](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ss2.jpg)
![gambar 3](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ss3.jpg)

2. Menemukan container yang sedang berjalan

![gambar 4](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ss4.jpg)

3. Mengakses container (redis)

![gambar 5](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ss5.jpg)

4. Menjalankan container (redis) dibeberapa instance

![gambar 6](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ssbaru.jpg)

5. Mempertahankan data supaya ketika dibutuhkan lagi bisa digunakan

![gambar 7](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ssbarulagi.jpg)

6. Menjalankan container (redis) di foreground

![gambar 8](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20pertama/ssbarulagi2.jpg)

## Skenario kedua (Deploy static HTML website as container)

1. Membuat dockerFile

![gambar 9](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20kedua/ss4.jpg)

2. Membangun docker image

![gambar 10](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20kedua/ss1.jpg)

3. Menjalankan image yang sudah dibuat

![gambar 11](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20kedua/ss3.jpg)

## Skenario ketiga ( Building Container Image)

1. Gambar awal
![gambar 12](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20ketiga/ss1.jpg)

Penjelasan query gambar diatas :

a. query pada baris ke 4 digunakan untuk membuat image dasar

b. query pada baris ke 5 digunakan untuk menjalankan command, dengan mengkopi file kedalam folder tertentu dan dispesifikasikan sbg bagian dari tujuan

c. query pada baris ke 6 digunakan untuk menetapkan port mana yang akan digunakan, didalam kasuss ini saya ingin web server saya dapat diakses di port 80

d. query pada baris ke 7 digunakan untuk menetapkan command mana yg akan dijalankan di aplikasi kita 

2. Membangun containers

Setelah dockerFile berhasil dibuat, maka selanjutnya adalah mengubahnya menjadi sebuah container dengan docker build

![gambar 13](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20ketiga/ss2.jpg)

3. Meluncurkan image baru

Setelah image berhasil dibuat maka selanjutnya adalah saatnya meluncurkannya

![gambar 14](https://github.com/AnnisaFahma/tct_docker_AnnisaFahma/blob/master/scenario%20ketiga/ss5.jpg)


# SEKIAN PRAKTIK HARI INI

