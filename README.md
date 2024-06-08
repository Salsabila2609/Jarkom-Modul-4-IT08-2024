# **Kelompok IT08**

## Anggota

- Salsabila Amalia Harjanto (5027221023)
- Ditya Wahyu ()

## Laporan Resmi Modul 4

> Soal shift dikerjakan pada Cisco Packet Tracer dan GNS3 menggunakan metode perhitungan CLASSLESS yang berbeda.
> Keterangan: Bila di CPT menggunakan VLSM, maka di GNS3 menggunakan CIDR atau sebaliknya

### Rute

![rute](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/5ce685fb-f585-4e1d-a30b-15a872292de7)

---
## **CIDR**
> CIDR atau biasa dikenal *Classless Inter-Domain* Routing adalah suatu metode ``pengalamatan dan pengelompokan alamat IP`` yang memungkinkan penggunaan lebih efisien dari ruang alamat IP yang tersedia di Internet. Sebelum diperkenalkannya ``CIDR``, pengalamatan IP didasarkan pada kelas-kelas, seperti ``kelas A, kelas B, dan kelas C``.

### Topologi

![A](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/40a45e4b-ab18-4496-bc2f-6d349bff37cd)

---

### Penggabungan IP
Berikut merupakan langkah penggabungan pada topologi kami

#### Kondisi Node Awal (A)

![A](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/40a45e4b-ab18-4496-bc2f-6d349bff37cd)

#### Penggabungan ke-1 (B)

![B](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/1780607a-6ee4-4dda-bcb0-f2444e94c0a7)

![B-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/111fce69-eea3-4a5c-90a5-f1821ba6ea36)

#### Penggabungan ke-2 (C)

![C](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/34408bd3-aafe-4e52-993b-2c443d30baaf)

![C-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/90de35c3-a3cd-4a68-bba9-6096c2924a14)

#### Penggabungan ke-3 (D)

![D](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/5b34fa23-8a29-40ec-86fe-41d82e8cbeeb)

![D-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/b4b886b2-b716-4a90-b331-6d8cd5d872fb)

#### Penggabungan ke-4 (E)

![E](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/4604af92-8a7d-49dc-8778-6b50d88e7b80)

![E-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/d7f5dd0d-c322-4726-81b0-927ea2fe8929)

#### Penggabungan ke-5 (F)

![F](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/9f0a837f-5613-48c2-8704-f21b2ae8f49e)

![F-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/f8a359fb-a127-4fe4-a5fd-66ba3c87605d)

#### Penggabungan ke-6 (G)

![G](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/fb7e2632-385e-46a2-9966-88e8061c5428)

![G-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/5aaa5a2f-5fdd-43fa-9fb7-aaf248e22be6)

#### Penggabungan ke-7 (H)

![H](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/ab69be11-bb48-4f4d-b576-83dae8f6550f)

![H-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/83f9dd07-4972-413d-9606-e03d30ad289b)

#### Penggabungan ke-8 (I)

![I](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/75edd987-1a9a-45a7-818f-12cc50c57bb2)

![I-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/632f7966-bb58-44f7-a98f-00d01e77af36)

#### Penggabungan ke-9 (J)

![J](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/a6958954-ab85-4b46-8961-a9c3ddd4a313)

![J-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/4d1682c3-6064-4f54-bdb0-4aa83fa60ec4)

#### Penggabungan ke-10 (K)

![K](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/7452e97e-0a17-430c-8444-6383707e260e)

![K-1](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/6d3946a2-e30d-492a-961a-4c95403d1d5e)

---

Berdasarkan hasil penggabungan IP, disini kami menyusun tree untuk pembagian IP yang akan digunakan sebagai dasar konfigurasi

### Tree

### Pembagian IP

![IPCIDR](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/d7db2add-daf2-4bd5-b08f-64808dbdb94c)

---

### Config
- Jawa
  ```
  auto lo
  iface lo inet loopback
  
  auto eth0
  iface eth0 inet dhcp
  
  #A3
  auto eth1
  iface eth1 inet static
  	address 192.239.0.1
  	netmask 255.255.255.252
  
  #A1
  auto eth2
  iface eth2 inet static
  	address 192.245.8.1
  	netmask 255.255.255.252
  
  #A2
  auto eth3
  iface eth3 inet static
  	address 192.241.32.1
  	netmask 255.255.255.252
 
  ```
- Sumatera
  ```
  auto lo
  iface lo inet loopback
  
  #A1
  auto eth0
  iface eth0 inet static
  	address 192.245.8.2
  	netmask 255.255.255.252
    gateway 192.245.8.1

  #A4
  auto eth1
  iface eth1 inet static
  	address 192.245.2.1
  	netmask 255.255.255.224
  
  #A8
  auto eth2
  iface eth2 inet static
  	address 192.245.5.1
  	netmask 255.255.255.252
  ```
- Samosir
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.2.2
    netmask 255.255.255.224
    gateway 192.245.2.1
  ```
- Sibandang
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.2.3
    netmask 255.255.255.224
    gateway 192.245.2.1
  ```
- Sumatera Utara
  ```
  auto lo
  iface lo inet loopback
  
  #A4
  auto eth0
  iface eth0 inet static
    address 192.245.2.4
    netmask 255.255.255.224
    gateway 192.245.2.1
  
  #A5
  auto eth1
  iface eth1 inet static
    address 192.245.1.1
    netmask 255.255.255.252
  ```
- Aceh
  ```
  auto lo
  iface lo inet loopback
  
  #A5
  auto eth0
  iface eth0 inet static
    address 192.245.1.2
    netmask 255.255.255.252
    gateway 192.245.1.1
  
  #A7
  auto eth1
  iface eth1 inet static
    address 192.245.0.129
    netmask 255.255.255.224
  
  #A6
  auto eth2
  iface eth2 inet static
    address 192.245.0.1
    netmask 255.255.255.128
  ```
- Berawang-Tampu
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.0.2
    netmask 255.255.255.128
    gateway 192.245.0.1
  ```
- Enang-Enang
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.0.3
    netmask 255.255.255.128
    gateway 192.245.0.1
  ```
- Starland
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.0.4
    netmask 255.255.255.128
    gateway 192.245.0.1
  ```
- Sabang
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.0.130
    netmask 255.255.255.224
    gateway 192.245.0.129
  ```
- Lambaro
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.0.131
    netmask 255.255.255.224
    gateway 192.245.0.129
  ```
- Lampung
  ```
  auto lo
  iface lo inet loopback
  
  #A8
  auto eth0
  iface eth0 inet static
    address 192.245.5.2
    netmask 255.255.255.252
    gateway 192.245.5.1
  
  #A9
  auto eth1
  iface eth1 inet static
    address 192.245.4.1
    netmask 255.255.255.0
  ```
- Sebeku
  ```
  auto eth0
  iface eth0 inet static
    address 192.245.4.2
    netmask 255.255.255.0
    gateway 192.245.4.1
  ```
- Kalimantan
  ```
  auto lo
  iface lo inet loopback
  
  #A3
  auto eth0
  iface eth0 inet static
  	address 192.239.0.2
  	netmask 255.255.255.252
    gateway 192.239.0.1
  
  #A15
  auto eth1
  iface eth1 inet static
  	address 192.238.0.1
  	netmask 255.255.255.252
  ```
- Kalimantan Utara
  ```
  auto lo
  iface lo inet loopback
  
  #A15
  auto eth0
  iface eth0 inet static
    address 192.238.0.2
    netmask 255.255.255.252
    gateway 192.238.0.1
  
  #A16
  auto eth1
  iface eth1 inet static
    address 192.237.128.1
    netmask 255.255.255.0
  
  #A17
  auto eth2
  iface eth2 inet static
    address 192.237.64.1
    netmask 255.255.255.252
  ```
- Selimau
  ```
  auto eth0
  iface eth0 inet static
    address 192.237.128.2
    netmask 255.255.255.0
    gateway 192.237.128.1
  ```
- Kalimantan Timur
  ```
  auto lo
  iface lo inet loopback
  
  #A17
  auto eth0
  iface eth0 inet static
    address 192.237.64.2
    netmask 255.255.255.252
    gateway 192.237.64.1
  
  #A19
  auto eth1
  iface eth1 inet static
    address 192.237.32.1
    netmask 255.255.254.0
  
  #A18
  auto eth2
  iface eth2 inet static
    address 192.237.16.1
    netmask 255.255.255.252
  ```
- Bangkirai
  ```
  auto eth0
  iface eth0 inet static
    address 1192.237.32.2
    netmask 255.255.254.0
    gateway 192.237.32.1
  ```
- Lamaru
  ```
  auto eth0
  iface eth0 inet static
    address 1192.237.32.3
    netmask 255.255.254.0
    gateway 192.237.32.1
  ```
- Kalimantan Selatan
  ```
  auto lo
  iface lo inet loopback
  
  #A18
  auto eth0
  iface eth0 inet static
    address 192.237.16.2
    netmask 255.255.255.252
    gateway 192.237.16.1
  
  #A20
  auto eth1
  iface eth1 inet static
    address 192.237.8.1
    netmask 255.255.255.224
  
  #A21
  auto eth2
  iface eth2 inet static
    address 192.237.0.1
    netmask 255.255.248.0
  ```
- Angsana
  ```
  auto eth0
  iface eth0 inet static
    address 192.237.8.2
    netmask 255.255.255.224
    gateway 192.237.8.1
  ```
- Bajuin
  ```
  auto eth0
  iface eth0 inet static
    address 192.237.0.2
    netmask 255.255.248.0
    gateway 192.237.0.1
  ```
- Takisung
  ```
  auto eth0
  iface eth0 inet static
    address 192.237.0.3
    netmask 255.255.248.0
    gateway 192.237.0.1
  ```
- Batakan
  ```
  auto eth0
  iface eth0 inet static
    address 192.237.0.4
    netmask 255.255.248.0
    gateway 192.237.0.1
  ```
- Sulawesi
  ```
  auto lo
  iface lo inet loopback
  
  #A2
  auto eth0
  iface eth0 inet static
  	address 192.241.32.2
  	netmask 255.255.255.252
          gateway 192.241.32.1
  
  #A13
  auto eth1
  iface eth1 inet static
  	address 192.241.8.1
  	netmask 255.255.255.128
  
  #A11
  auto eth2
  iface eth2 inet static
  	address 192.241.16.129
  	netmask 255.255.255.248
  ```
- Makasar
  ```
  auto lo
  iface lo inet loopback
  
  #A11
  auto eth0
  iface eth0 inet static
    address 192.241.16.130
    netmask 255.255.255.248
    gateway 192.241.16.129
  
  #A10
  auto eth1
    iface eth1 inet static
    address 192.241.16.65
    netmask 255.255.255.248
  ```
- Galesong
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.16.66
    netmask 255.255.255.248
    gateway 192.241.16.65
  ```
- Topejawa-Takalar
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.16.67
    netmask 255.255.255.248
    gateway 192.241.16.65
  ```
- Belawa
  ```
  auto lo
  iface lo inet loopback
  
  #A11
  auto eth0
  iface eth0 inet static
    address 192.241.16.131
    netmask 255.255.255.248
    gateway 192.241.16.129
  
  #A12
  auto eth1
  iface eth1 inet static
    address 192.241.16.1
    netmask 255.255.255.192
  ```
- Madini
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.16.2
    netmask 255.255.255.192
    gateway 192.241.16.1
  ```
- Baru
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.16.3
    netmask 255.255.255.192
    gateway 192.241.16.1
  ```
- Gorontalo
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.8.2
    netmask 255.255.255.128
    gateway 192.241.8.1
  ```
- Marisa
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.8.3
    netmask 255.255.255.128
    gateway 192.241.8.1
  ```
- Maluku Utara
  ```
  auto lo
  iface lo inet loopback
  
  #A13
  auto eth0
  iface eth0 inet static
    address 192.241.8.4
    netmask 255.255.255.128
    gateway 192.241.8.1
  
  #A14
  auto eth1
  iface eth1 inet static
    address 192.241.0.1
    netmask 255.255.248.0
  ```
- Tobelo
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.0.2
    netmask 255.255.248.0
    gateway 192.241.0.1
  ```
- Morotai
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.0.3
    netmask 255.255.248.0
    gateway 192.241.0.1
  ```
- Ternate
  ```
  auto eth0
  iface eth0 inet static
    address 192.241.0.4
    netmask 255.255.248.0
    gateway 192.241.0.1
  ```
---
### Routing
Untuk mempermudah proses routing, disini saya menandai IP untuk setiap node

![ipjelas](https://github.com/Salsabila2609/Jarkom-Modul-4-IT08-2024/assets/128382995/2ac9c188-a156-47a3-89c7-e5c9f4ee0371)

- Aceh
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.245.1.1
  ```
- Sumatera Utara
  ```
  route add -net 192.245.0.128 netmask 255.255.255.224 gw 192.245.1.2
  route add -net 192.245.0.0 netmask 255.255.255.128 gw 192.245.1.2
  ```
- Sumatera
  ```
  route add -net 192.245.1.0 netmask 255.255.255.252 gw 192.245.2.4
  route add -net 192.245.0.128 netmask 255.255.255.224 gw 192.245.2.4
  route add -net 192.245.0.0 netmask 255.255.255.128 gw 192.245.2.4
  route add -net 192.245.4.0 netmask 255.255.255.0 gw 192.245.5.2
  ```
- Lampung
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.245.5.1
  ```
- Jawa
  ```
  route add -net 192.245.2.0 netmask 255.255.255.224 gw 192.245.8.2
  route add -net 192.245.1.0 netmask 255.255.255.252 gw 192.245.8.2
  route add -net 192.245.0.0 netmask 255.255.255.128 gw 192.245.8.2
  route add -net 192.245.0.128 netmask 255.255.255.224 gw 192.245.8.2
  route add -net 192.245.5.0 netmask 255.255.255.252 gw 192.245.8.2
  route add -net 192.245.4.0 netmask 255.255.255.0 gw 192.245.8.2
  
  route add -net 192.241.8.0 netmask 255.255.255.128 gw 192.241.32.2
  route add -net 192.241.0.0 netmask 255.255.248.0 gw 192.241.32.2
  route add -net 192.241.16.128 netmask 255.255.255.248 gw 192.241.32.2
  route add -net 192.241.16.64 netmask 255.255.255.248 gw 192.241.32.2
  route add -net 192.241.16.0 netmask 255.255.255.192 gw 192.241.32.2
  
  route add -net 192.238.0.0 netmask 255.255.255.252 gw 192.239.0.2
  route add -net 192.237.64.0 netmask 255.255.255.252 gw 192.239.0.2
  route add -net 192.237.128.0 netmask 255.255.255.0 gw 192.239.0.2
  route add -net 192.237.16.0 netmask 255.255.255.252 gw 192.239.0.2
  route add -net 192.237.32.0 netmask 255.255.254.0 gw 192.239.0.2
  route add -net 192.237.8.0 netmask 255.255.255.224 gw 192.239.0.2
  route add -net 192.237.0.0 netmask 255.255.248.0 gw 192.239.0.2
  ```
- Maluku Utara
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.241.8.1
  ```
- Sulawesi
  ```
  route add -net 192.241.0.0 netmask 255.255.248.0 gw 192.241.8.4
  route add -net 192.241.16.64 netmask 255.255.255.248 gw 192.241.16.130
  route add -net 192.241.16.0 netmask 255.255.255.192 gw 192.241.16.131
  ```
- Belawa
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.241.16.129
  ```
- Makasar
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.241.16.129
  ```
- Kalimantan
  ```
  route add -net 192.237.64.0 netmask 255.255.255.252 gw 192.238.0.2
  route add -net 192.237.16.0 netmask 255.255.255.252 gw 192.238.0.2
  route add -net 192.237.128.0 netmask 255.255.255.0 gw 192.238.0.2
  route add -net 192.237.32.0 netmask 255.255.254.0 gw 192.238.0.2
  route add -net 192.237.8.0 netmask 255.255.255.224 gw 192.238.0.2
  route add -net 192.237.0.0 netmask 255.255.248.0 gw 192.238.0.2
  ```
- Kalimantan Utara
  ```
  route add -net 192.237.16.0 netmask 255.255.255.252 gw 192.237.64.2
  route add -net 192.237.8.0 netmask 255.255.255.224 gw 192.237.64.2
  route add -net 192.237.0.0 netmask 255.255.248.0 gw 19 2.237.64.2
  route add -net 192.237.32.0 netmask 255.255.254.0 gw 192.237.64.2
  ```
- Kalimantan Timur
  ```
  route add -net 192.237.8.0 netmask 255.255.255.224 gw 192.237.16.2
  route add -net 192.237.0.0 netmask 255.255.248.0 gw 192.237.16.2
  ```
- Kalimantan Selatan
  ```
  route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.237.16.1
  ```
---

### Testing

---
























