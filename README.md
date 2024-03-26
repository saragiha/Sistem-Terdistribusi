# Sistem-Terdistribusi

![Screenshot (834)](https://github.com/saragiha/Sistem-Terdistribusi/assets/151798271/44518f6e-b96c-49eb-b77f-558603214b8e)
1. install lxc dengan perintah:
   sudo apt update
   sudo apt install lxc
![Screenshot (836)](https://github.com/saragiha/Sistem-Terdistribusi/assets/151798271/ba1a7471-5482-4902-afd4-c7b7f60dfcb3)
2. kemudian buat container untuk microservice1:
   sudo lxc launch ubuntu:20.04 microservice1
3. kemudian untuk microservice2:
   sudo lxc launch ubuntu:18.04 microservice2
4. konfigurasi setiap container:
   sudo lxc exec microservice1 -- /bin/bash
   sudo lxc exec microservice2 -- /bin/bash
5. konfigurasi jaringan menggunakan opsi lxc untuk menetapkan jaringan antara container.
6. jalankan container:
   sudo lxc start microservice1
   sudo lxc start microservice2

sekian terimakasih.
