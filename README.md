# Praktikum Modul 1 Kelompok B06

Anggota Kelompok B06 :
| Nama | NRP |
| ---------------------- | ---------- |
| Muhammad Dafian Zakiakhdan | 5025211108 |
| Dewangga Dika Darmawan | 5025211109 |

---

<br />
<br />

1. User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.
   <br />
   ```
    a. Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut?
   - Gunakan command ftp.request.command == “STOR”
   - Cari Sequence Number (raw)
   ```

![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/91c7d381-789c-48f6-8935-5404f6e433a4)

  <br />

    b. Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut?
    - Gunakan command ftp.request.command == “STOR”
    - Cari Acknowledge Number (raw)

![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/41158695-cea9-4a36-83e2-f5c9b80434df)

<br />

    c. Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

    - Gunakan ftp.response ambil packet setelah 147 untuk response nya
    - Cari Acknowledge Number (raw)

![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/a64921ce-d08f-4031-99a9-687cd910e0ba)

    d. Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
    - Gunakan ftp.response ambil packet setelah 147 untuk response nya
    - Cari Sequence Number (raw)

![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/e1564b5b-c6b2-487f-b155-9ad2cceaea83)

<br />

## Flag :

![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/fbbb5881-9063-417c-9922-a139a8874d85)

<br />

2. Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!

   - Gunakan ip.addr == 10.21.78.111
   - Ambil salah satu packet HTTP lalu cari Server di Hypertext Transfer Protokol

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/dddf5292-5b43-402b-8c94-f356936ddbbe)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/3498b659-eb96-4c30-a3ac-287ec69a7b27)

   <br />
   <br />

3. Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:

   a. Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?

   - Gunakan ip.addr == 239.255.255.250 && udp.port == 3702
   - Hitung jumlah packet

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/98855fec-b7e7-4b97-b1e5-4380321e486b)

   b Protokol layer transport apa yang digunakan?

   - Gunakan ip.addr == 239.255.255.250 && udp.port == 3702
   - Lihat Protocol

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/36c6402b-2862-46fb-951e-6dd7796e96e8)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/a3a4e14d-5e07-46cc-8da7-ad774702b8ec)

   <br />
   <br />

4. Berapa nilai checksum yang didapat dari header pada paket nomor 130?

   - Cari packet no 130
   - Cari checksum

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/173fae9d-c7a7-4852-8078-ce64c5faa3d6)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/99eb451f-7f44-49f6-9a88-48fa5bedabbc)

<br />
<br />

5. Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.

   - Cari packet yang memiliki protokol unik dan didalam stream terdapat password yang harus di decode base 64
   - Buka file txt dan masukan password
   - Pada file terdapat NC script dan jalankan di terminal

    <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/bdefd02d-fedc-4113-bff7-68a51aefb20d)

    <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/528ab8e9-44be-4806-bfad-61c5107ca117)

    <br />

   a. Berapa banyak packet yang berhasil di capture dari file pcap tersebut?

   - Packet dijumlahkan ada 60

    <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/66a3c799-85ef-4697-a9a5-a87ce36db2de)

    <br />

   b. Port berapakah pada server yang digunakan untuk service SMTP?

   - Pilih salah satu packet smtp dan cari port

    <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/1183ce80-b329-43da-a33f-e3b090f847fe)

    <br />

   c. Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?

   - Karena ip yang diawali 10 biasanya local dan hanya ada ip lain

    <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/a35539a9-4ec5-40d4-a80d-b61a976bfc32)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/5049f067-7152-4373-9c0c-f8225f014bb4)

    <br />
    <br />

6. Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.

<br />
<br />

7. Berapa jumlah packet yang menuju IP 184.87.193.88?

   - Gunakan ip.dst == 184.87.193.88
   - Hitung jumlah packet

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/49fff87b-61df-482b-bd18-4295c943f661)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/5536a411-1f4b-4021-b458-df2c095369b3)

<br />
<br />

8. Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)

   - Masukkan jawaban sesuai dengan ketentuan script soal

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/f6412e36-3514-41f8-9e14-0b40f5617eb9)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/7137b257-2f25-482d-8ce7-406cb715915f)

<br />
<br />

9. Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!

   - Masukkan jawaban sesuai dengan ketentuan script soal

   <br />

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/54127cfb-e9c1-4860-8ad4-56a93cf1949f)

   <br />

   ## Flag

   ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/6cf265da-550f-4e4a-9506-74d7ee2a59ea)

<br />
<br />

10. Sebutkan kredensial yang benar ketika user mencoba login menggunakan Telnet

    - Gunakan Telnet
    - Cari Packet yang mengandung format username:password

    <br />

    ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/49fe6456-c0d1-440b-9e10-ad22bbc97c16)

    <br />

    ## Flag

    ![image](https://github.com/Rencist/A07_Sisop_Individu_Modul_3/assets/91055469/7ab9a013-b81b-443b-9696-93500f079c7e)

    <br />
    <br />
