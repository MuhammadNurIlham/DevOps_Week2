# Dokumentasi Instalasi, Konfigurasi, Service Management

## Install & Config Node.Js di Linux (Ubuntu)
untuk menginstall node.js bisa mengikuti langkah-langkah berikut :
- masukkan command pada terminal :
  > curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

![input installation command](https://user-images.githubusercontent.com/90192123/134821899-682b2288-386b-4a13-a4ca-db57b7233936.png)

- > installation version
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
