# Dokumentasi Instalasi, Konfigurasi, Service Management

## Install & Config Node.Js di Linux (Ubuntu)
__untuk menginstall node.js bisa mengikuti langkah-langkah berikut :__
- __masukkan command pada terminal :__
  > curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

![input installation command](https://user-images.githubusercontent.com/90192123/134821899-682b2288-386b-4a13-a4ca-db57b7233936.png)

- > __cek versi instalasi__
> nvm install 14.7.0

![nvm install 14 7 0](https://user-images.githubusercontent.com/90192123/134822450-fa9ddffd-da4f-4e59-8ab6-0f8d050b8be6.png)

![Output command install nvm 14 7 0](https://user-images.githubusercontent.com/90192123/134823062-0e9f331f-def4-45c9-81f7-9a0edeaacfbc.png)


> nvm use 14

![nvm use 14](https://user-images.githubusercontent.com/90192123/134822472-f9599d57-03ad-4c56-9ff3-aead91b8c8b6.png)

![output nvm use 14](https://user-images.githubusercontent.com/90192123/134822571-b02ad9cb-0dd8-4028-b525-a57fcd20c575.png)

jika sudah kita bisa melakukan cek dengan command berikut jika nvm yang telah diinstall belum terdeteksi
- > exec bash
jika menggunakan bash

![exec bash](https://user-images.githubusercontent.com/90192123/134821931-dc85a39b-f7b1-47aa-a827-8d1b9204219e.png)
![output exec bash (2)](https://user-images.githubusercontent.com/90192123/134822551-a94b548a-0a44-4dc5-be9a-4d38f052e672.png)
- > exec zsh
jika menggunakan zsh

setelah tahap instalasi kita bisa melakukan pengecekan versi dengan menginput perintah pada terminal
- > node-v

![node -v](https://user-images.githubusercontent.com/90192123/134822605-e6591ffc-ce55-4aec-96d4-24972173ff36.png)

- > npm-v

![input output node - v npm -v](https://user-images.githubusercontent.com/90192123/134822616-071196bd-f616-4fee-8c87-6067a9c8067b.png)

### Membuat example app dengan node js & express js dengan perintah berikut :

untuk membuat folder baru kita bisa melakukan berikut pada terminal
- > mkdir myapp-nodejs

setelah tahap membuat folder, kita pindah ke directory yang sudah kita buat dengan melakukan perintah berikut :
- > cd myapp-nodejs

![input output mkdir cd myapp nodejs](https://user-images.githubusercontent.com/90192123/134822700-2230e579-e6aa-4256-ba9d-2cfab29e2722.png)

- > npm init -y

![npm init -y](https://user-images.githubusercontent.com/90192123/134822738-de7eb8e6-6c32-4b28-a76b-731ed8673e31.png)

![output npm init -y](https://user-images.githubusercontent.com/90192123/134823007-70f7aed9-a8b0-48d6-a8b1-33db60ef1ef3.png)

- install express
  - > npm install express --save

![npm install express --save](https://user-images.githubusercontent.com/90192123/134822896-7cf421d9-125d-486f-9a49-e67ab57d1ed6.png)

![output install express --save](https://user-images.githubusercontent.com/90192123/134822949-580245a0-e0c7-4568-88ee-f72755dcd372.png)

jika sudah terinstal maka menghasilkan output seperti ini :

![output npm init -y](https://user-images.githubusercontent.com/90192123/134822842-7d5a25ea-cb46-4a72-a420-1ae5d102c38e.png)

Next input example app dengan perintah berikut :
- > nano index.js

![nano index js](https://user-images.githubusercontent.com/90192123/134823092-7e06d06d-cb60-4e1f-95d2-73ec492dfd0a.png)

![output nano index js input script js](https://user-images.githubusercontent.com/90192123/134823189-b7ee17df-336f-46a9-81ae-595bd2b00c91.png)
lalu save (CTRL+X) lalu tekan Y, Enter

setelah berhasil disave, jalankan dengan melakukan perintah berikut pada terminal :
- > node.inde.js

![output nano index js](https://user-images.githubusercontent.com/90192123/134823144-fa98a019-2906-4976-ba2a-a7e998b6570d.png)

Cek pada Browser dengan url :
- > localhost: 3000
akan menampilkan output berikut :

![output localhost js](https://user-images.githubusercontent.com/90192123/134823318-e278de4e-0263-48cb-b645-fad057fb1b96.png)
artinya App yang kita buat berhasil dijalankan

## Instal & Config Python di Linux (Ubuntu)
ikuti langkah-langkah berikut :
- > __lakukan update dengan perintah pada terminal seperti berikut :__
  - > sudo apt update

![sudo apt update](https://user-images.githubusercontent.com/90192123/134824601-42df7510-e405-431b-9a6e-2d10bc134f94.png)

![output sudo apt update](https://user-images.githubusercontent.com/90192123/134824624-536c9484-813a-438b-865a-40e106122104.png)

- > __setelah update, lakukan upgrade dengan perintah berikut :__
  - > sudo apt upgrade -y

![sudo apt upgrade -y](https://user-images.githubusercontent.com/90192123/134824637-026e94f8-137b-4de3-af61-53ddb339f993.png)

![output sudo apt upgrade -y](https://user-images.githubusercontent.com/90192123/134824644-8bf978c9-aca2-4bf9-9bc8-aaed6cdbc419.png)

- > __setelah upgrade, kita cek versi Python yang terinstal, karena defaultnya menggunakan Python3, dengan melakukan perintah berikut :___
  - > python3 -V

![input output python3 -V](https://user-images.githubusercontent.com/90192123/134824654-c92039a1-c269-43da-a6a3-8ae3c0b06aab.png)

__setelah mengetahui versi python yang terinstal, lalu masukkan perintah berikut ini untuk menginstall package manager :__
  - > sudo apt install python3-pip
tunggu sampai proses instalasi selesai, jika sudah lakukan perintah berikut untuk menginstall flask :
  - > pip install flask

![pip install flask](https://user-images.githubusercontent.com/90192123/134824673-2854812f-4140-4607-ab01-a80597926ac5.png)

__Membuat folder Python dengan perintah berikut :__
- > mkdir-python

![mkdir-python](https://user-images.githubusercontent.com/90192123/134824683-30455082-4202-41bb-a325-0f6bb0a3a319.png)

__lalu buatlah folder dengan perintah berikut :__
- > nano index.py

![nano index py](https://user-images.githubusercontent.com/90192123/134824744-38b0441a-2a03-4a8a-bbfd-4afbc03b2a8c.png)

__masukkan script codenya__

![nano index py script](https://user-images.githubusercontent.com/90192123/134824756-0bc6b655-5b4f-4e96-8685-52afea0f83fe.png)

__lalu tekan CTRL+X, Y, Enter__

__Jalankan app dengan perintah berikut :__
- > python3 index.py

![output python3 index py](https://user-images.githubusercontent.com/90192123/134824804-045e34ea-a75c-47b1-98ae-f28243c84ae2.png)

__lalu buka browser dan masukkan url dengan port 5000:__
- > localhost:5000
![localhost python](https://user-images.githubusercontent.com/90192123/134824874-895e40e3-5da6-4985-bee5-95c25d19e383.png)

### Install & Config Golang di Linux (Ubuntu)
__hal pertama yang harus dilakukan adalah mendownload go, dengan melakukan perintah berikut :__
- > wget https://golang.org/dl/go1.16.5.linux-amd64.tar.gz && sudo su

![install go](https://user-images.githubusercontent.com/90192123/134827007-458338cf-0af3-4ac1-82d3-feda799d30ca.png)

![apt install go](https://user-images.githubusercontent.com/90192123/134827024-23e14b0d-2c88-4dee-afca-a5315cfdd775.png)

__lalu selanjutnya extract dan copy data__
- > rm-rf/usr/local/go&&tar-C/usr/local-xzf go1.16.5.linux-amd64.tar.gz && exit

![extrak dan copy go](https://user-images.githubusercontent.com/90192123/134827053-14df8096-c4e2-49a6-a69c-3025372475a1.png)

__langkah selanjutnya adalah memasukkan path go pada bashrc__
- > export PATH=$PATH:/usr/local/go/bin

![path go bash](https://user-images.githubusercontent.com/90192123/134827094-1797b733-cb6e-4d3b-be1a-f1b7370b1308.png)

__cek versi yang telah terinstall__

![go version](https://user-images.githubusercontent.com/90192123/134827122-a99d86be-9918-4a4b-b4cd-cf6326b6beb7.png)

__Membuat folder go dengan melakukan perintah berikut :__
- > mkdir myapp-golang

![mkdir go](https://user-images.githubusercontent.com/90192123/134827149-58b55653-c532-48dc-b97a-69146053963a.png)

pindah ke directory yang sudah dibuat 
- > cd myapp-golang

![cd myapp go](https://user-images.githubusercontent.com/90192123/134827208-f34bb97d-f5b9-423b-9eea-20db278e90f0.png)

__selanjutkan buatlah file dengan melakukan perintah berikut :__
- > nano index.go

![nano index go](https://user-images.githubusercontent.com/90192123/134827230-e96a4e26-fbbc-4f0d-b0a5-d7f0a717ad83.png)

__*masukkan script code*__

![script golang](https://user-images.githubusercontent.com/90192123/134827241-58571219-a564-4021-b230-3a41b2d6565e.png)

__jalankan app dengan menggunakan perintah berikut : __
- > go run index.go

![go run index go](https://user-images.githubusercontent.com/90192123/134827282-0610a350-d56d-4e5f-b95d-aaebb614c9c3.png)

__*jika ingin di build bisa melakukan perintah berikut :*__
- > go build index.go

![go build](https://user-images.githubusercontent.com/90192123/134827311-695de00f-bf0c-4b7b-91c6-ac7e15e723ea.png)

__*perintah untuk menjalankan program go yang sudah di build*__
- > ./index

![go new build](https://user-images.githubusercontent.com/90192123/134827347-fc092009-f7a6-4517-8bfa-4093897baedb.png)
