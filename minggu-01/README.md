# tcc
Praktikum Teknologi Cloud Computing

**Pertemuan Pertama :**

# Instalasi Git

Git tersedia untuk berbagai sistem operasi. *Precompiled binaries* bisa diperoleh di [halaman dowbload Git](https://git-scm.com/downloads) untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (*command line interface*). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau *command prompt* / PowerShell di Windows. Setelah instalasi, periksa keberhasilan instalasi dengan menggunakan:

```
$ git --version
git version 2.19.2.windows.2
```

## Windows

Pada proses installasi Git di Windows ini saya menggunakan text editor [Visual Studion Code](https://code.visualstudio.com/).

1. Setelah download Git, double click pada file yang di-download. Akan dimunculkan lisensi. Klik **Next** untuk lanjut.

![01](images/install-01.jpg)

2. Setelah itu, pilih lokasi instalasi. Secara default akan terisi *C:\Program Files\Git*. Ganti lokasi jika memang anda menginginkan lokasi lain, klik **Next**

![02](images/install-02.jpg)

3. Pilih komponen. Tidak perlu diubah-ubah, sesuai dengan default saja. Klik pada **Next**.

![03](images/install-03.jpg)

4. Mengisi shortcut untuk menu Start. Gunakan default (Git), ganti jika ingin mengganti - misalnya Git VCS.

![04](images/install-04.jpg)

5. Pilih editor yang akan digunakan bersama dengan Git. Pada pilihan ini, digunakan Notepad++.

![05](images/install-05.jpg)

6. Pada saat instalasi, Git menyediakan akses git melalui Bash maupun command prompt. Pilih pilihan kedua supaya bisa menggunakan dari dua antarmuka tersebut. Bash adalah shell di Linux. Dengan menggunakan bash di Windows, pekerjaan di command line Windows bisa dilakukan menggunakan bash - termasuk ekskusi dari Git.

![06](images/install-06.jpg)

7. Pilih OpenSSL untuk HTTPS. Git menggunakan https untuk akes ke repo GitHub atau repo-repo lain (GitLab, Assembla).

![07](images/install-07.jpg)

8. Pilih pilihan pertama untuk konversi akhir baris (CR-LF).

![08](images/install-08.jpg)

9. Pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash.

![09](images/install-09.jpg)

10. Untuk opsi ekstra, pilih serta aktifkan 1 dan 2.

![010](images/install-10.jpg)

11. Setelah itu proses instalasi akan dilakukan.

![011](images/install-11.jpg)

12. Jika selesai akan muncul dialog pemberitahuan. Klik pada **Finish**.

![012](images/install-12.jpg)

13. Untuk menjalankan, dari Start menu, ketikkan "Git", akan muncul beberapa pilihan. Pilih "Git Bash" atau "Git GUI".
 
![013](images/install-13.jpg)

14. Tampilan jika akan menggunakan "Git Bash"

![014](images/install-14.jpg)

15. Tampilan jika akan menggunakan "Git GUI"

![015](images/install-15.jpg)

16. Untuk mencoba dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, makan akan muncul hasil berikut:

![016](images/install-16.jpg)
