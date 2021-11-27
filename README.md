# Jarkom-Modul-4-TI4-2021

**Oleh:**
  * Muhammad Nur Fauzan (05311940000035)
  * Ghimnastiar Al Abiyyuna (05311940000042)
  * Christopher Benedict (05311840000024)

---
#  SUBNETTING-DAN-ROUTING

![messageImage_1635585526011](https://cdn.discordapp.com/attachments/812317762428862514/914136760492130334/unknown.png)


**VLSM (Variable Length Subnet Masking)**


Langkah 1 - Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP yang dibutuhkan.

![messageImage_1635585526011](https://cdn.discordapp.com/attachments/812317762428862514/914143065990651954/unknown.png)

Langkah 2 - (masukin lagnkaah dua buat tree penjelasan)\
Subnet besar yang dibentuk memiliki NID 192.213.1.0 dengan netmask /19. Hitung pembagian IP berdasarkan NID dan netmask tersebut menggunakan pohon.


Langkah 3 - (masukin langkah 33 pembagian IP dari tree)
Lakukan subnetting dengan menggunakan pohon untuk pembagian IP sesuai dengan kebutuhan masing-masing subnet yang ada lalu berikan tanda untuk menandakan bahwa IP tersebut akan dijadikan sebagai subnet seperti gambar di bawah.

![messageImage_1635585526011](https://cdn.discordapp.com/attachments/812317762428862514/914143119258312744/unknown.png)

Langkah 4 - Atur IP untuk masing-masing interface yang ada di setiap device sesuai dengan pembagian subnet pada pohon VLSM.\
\
Atur IP pada interface water7yang mengarah ke Foosha dengan 192.213.20.1\

![image](https://user-images.githubusercontent.com/75864703/143683226-3625fe25-8f92-418a-86ac-51693320ff88.png)

Selanjutnya atur IP pada subnet A2. Atur IP pada interface Water7 yang mengarah ke client dengan 192.213.20.2\

![image](https://user-images.githubusercontent.com/75864703/143683285-4cf0d35b-0ec5-4c55-b021-00af962c359d.png)

Atur IP pada client dengan cara :

-Masuk ke client\
-Pilih tab Desktop\
-Pilih IP Configuration\
![image](https://user-images.githubusercontent.com/75864703/143683317-dabb4ae4-2352-4c30-9a12-e1bbd9e96916.png)
\
Lakukanlah step ini pada semua interface

**Routing**
Pada CPT, Routing dapat dilakukan pada menu Config > Routing > Static pada device Router. Lalu isi Static Routes seperti gambar dibawah pada Foosha dan tekan tombol Add\
Pada static routing juga dibutuhkan default routing agar router dapat mengirimkan paket sesuai dengan tujuan. Default routing dibutuhkan untuk router yang berada di bawah router utama (router yang terhubung internet)\
\
![image](https://user-images.githubusercontent.com/75864703/143684800-c24f0457-8cac-4090-b6f9-da56f592b74f.png)


**kendala**
-Tidak dapat mengirim pesan pada host yang memiliki subnet yang berbeda\
-Tidak dapat mengerjakan CIDR pada GNS3
