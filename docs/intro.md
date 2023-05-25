---
sidebar_position: 1
---

# Sebelum Memulai

Wiki ini digunakan untuk pembelajaran dan juga sebagai materi yang bisa dilihat kapanpun. Apa saja yang akan dibahas? **Macam-macam**. Semua materi dapat kalian lihat di sidebar sebelah kiri. Jika ada materi yang di anggap salah atau tidak sesuai dengan standard yang ada, silahkan laporkan melalui email ke **lapor@kreatale.com**

Sebelum kita memulai journey kita untuk menjadi software engineer / developer ada beberapa hal yangperlu kita persiapkan. Seperti mental, uang dan tenaga... hehe. Nggak kok. Bukan itu. Tapi kita butuh untuk menginstall beberapa hal agar perjalanan kita lancar

## Code Editor (VSCode)
Untuk bisa memulai koding kita perlu suatu aplikasi untuk bisa menulisnya. Pada dasarnya text-editor apapun bisa digunakan sebagai selama kita simpan dengan ekstensi yang sesuai. Terus, buat apa kita butuh code editor? Untuk mempermudah dengan fitur color-coded, indentasi, plugin dll. Code editor yang gratis dan memiliki fitur yang cukup lengkap adalah VSCode.

### Cara Install di Windows
- Download installer VSCode [di sini](https://go.microsoft.com/fwlink/?LinkID=534107)
- Setelah selesai, klik 2x pada installer untuk menginstall

## Version Control System (Git)
Di dunia pemrogramman kita memiliki sebuah tempat penyimpanan sekaligus mesin waktu yang bisa kita gunakan untuk mengorganisir kode kita. Seperti judulnya, Git merupakan sebuah Version Control System (VCS) lebih tepatnya distributet version control system.

### Cara Install di Windows
- Buka web browser kalian dan masuk ke halaman [ini](https://git-scm.com/download/win)
- Kemudian pilih pada bagian **standalone installer** dan pilih instalasi sesuai dengan versi bit laptop kalian. [Cara ceknya disini](https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d)
- Ikuti langkah instalasinya hingga selesai
- Setelah selesai buka `PowerShell` dan ketik `git -v`

## Node Version Manager (Node JS)
NVM atau Node Version Manager adalah sebuah tools yang digunakan untuk memanage beberapa versi node js sekaligus. Saat kalian bekerja dalam suatu project yang sudah lama dibangun, biasanya mereka akan menggunakan versi node js pada waktu tersebut. 

Sebagai contoh, pada tahun 2018 Rudi memulai project membangun website menggunakan Node JS versi 14.0 yang ia download dari website resminya. Empat tahun berlalu, dan Rudi ingin membuat project baru menggunakan versi Node JS terbaru. Rudi harus install dan uninstall versi lama. Ternyata versi terbaru Node JS membuat website yang dia buat dulu jadi tidak bisa di jalankan. Masalah - masalah seperti itu yang membuat NVM biasa digunakan untuk mengatur berbagai versi Node JS.

### Cara Install di Windows
- Download installer NVM [di sini](https://github.com/coreybutler/nvm-windows/releases#:~:text=Apr%2013-,nvm%2Dsetup.exe,-5.47%20MB)
- Ikuti langkah instalasi
- Setelah selesai buka `PowerShell` dan ketik `nvm version`
- Jika sudah terinstal, akan muncul versi dari nvm yang diinstal