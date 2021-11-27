
<!-- PROJECT LOGO -->
  <h3 align="center">Install Windows Server 2022 di VirtualBox 6.1 version
</h3>

  <p align="center">
    Install your iso in microsoft windows server 2022
  </p>
</div>

![img2](assetuts2021/2linkiso.png)

Link Download iso windows server 2022 at [https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022)

### Cara download file iso agar tidak gagal running saat melakukan `start` pada OS server windows 2022 maka dapat dilakukan cara berikut
***1-> pilih `download iso`, 2-> isi data yang diminta `negara asal isi dengan benar`, 3-> pilih bahasa `english` dan click `download`***

![img2step](assetuts2021/2stepdownloadiso.png)

***Notes : jika tidak `auto download` maka dapat klik unlink `windows server 2022`***

![img2cara](assetuts2021/2caradownloadisoyangbenar.png)


## UTS
<!--Soal UTS -->
<details>
  <summary>Soal dan Jawaban UTS</summary>
  <ol>
    <li>Download-ISO-Installer-windows-server-2022">Download ISO Installer windows server 2022
      <ul type="square">
        <li>https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022</li>
      </ul>
    </li>
    <li>Buat sebuah dokumentasi instalasi di github yang berisi
      <ol type="a">
        <li><a href="#Installation">Instalasi windows server 2022</a></li>
        <li><a href="#Directory">Instalasi Active Directory Domain Services</a></li>
        <li><a href="#DNS">Instalasi DNS server</a></li>
        <li><a href="#NET">Instalasi Net Framework 3.5</a></li>
        <li><a href="#Promote">Promote Server to a Domain Controller</a></li>        
      </ol>
    </li>
    <li>Kriteria Pengerjaan</li>
      <ol type="a">
        <li>Dokumentasi pada github dengan format markdown</li>
        <li>Memberikan penjelasan beserta screenshoot Langkah Langkah instalasi</li>
        <li>Cukup mengerjakan poin no 2.A</li>
        <li>Poin no 2-B sampai 2-E boleh dikerjakan, nilai dari poin no 2-B sampai 2-E bisa mengatrol nilai praktikum atau nilai UAS.</li>
      </ol>
    </li>
    <li>Referensi yang berguna:</li>
      <ul>
        <li>https://xpertstec.com/how-to-install-active-directory-in-server-2022/#Promote-Server-to-a-Domain-Controller</li>
        <li>https://docplayer.info/56976616-Laporan-instalasi-dan-konfigurasi-windows-server-2003.html</li>
      </ul>
    </li>    
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
---
# Installation
---
## Cara Install Windows Server 2022 di VirtualBox 6.1 version
----
![img1](assetuts2021/1vb.PNG)


Steps to install :
* Download and Install VirtualBox VM
* Download file iso Windows Server 2022 in top-linked
* Open your VirtualBox VM
* Create new your OS - Windows Server 2022 to installation

<p align="right">(<a href="#top">back to top</a>)</p>



### Steps on VirtualBox to create OS Windows Server

Steps to install and configuration

* Create on `New`
---
1. klik tombol `new`
2. isi bagian kolom `create virtual machine`
3. lanjutkan set `memory size` -> `harddisk` -> `harddisk file type` -> `create virtual harddisk` -> `file location and size`
4. klik tombol `start` pada os yang telah diset

  ![img3](assetuts2021/3newos.png)
  ![img4](assetuts2021/4createvm.png)
  ![img5](assetuts2021/5install.png)
  ![img6](assetuts2021/6tampilanawal.png)
* Click on `Setting` at OS Windows Server 2022
---
5. open `settings` 
   
   ***1.-> `storage` tambahkan file pada `storage devices` untuk memasukkan disk iso windows server yang telah di download 
   ***2.-> pilih file iso yang telah didownload dan tersimpan dalam lokasi `file manager` kita 
   ***3.-> `open` 
   ***4.-> pilih file iso yang telah ditambahkan
   ***5.-> `choose` 
   ***6.-> file iso berhasil ditambahkan
   ***7.-> `remove empty file` 
   ***8.-> tampilan file dalam `storage device`
   ***9.-> Checking motherboard Base Memory tersedia `4096` seperti pada awal set-up `memory size`
   ***10.-> `System` setting processors menjadi 2 CPU '<optional'
   ***11.-> `OK`***  

  ![img7](assetuts2021/7setingosstorage.png)
  ![img8](assetuts2021/8setingossystem.png)
  
  
* Get `Running` your OS
---
6. Click `Start` your OS

**`landing Microsoft OS Setup` menandakan Anda berhasil memasukkan file iso yang benar untuk melanjutkan proses installasi windows server**  

 #### 1.-> `pilih bahasa` dapat menggunakan default dengan langsung klik tombol `next`
 #### 2.-> `muncul tampilan `Install now` yuk klik -> Anda dapat berhasil menginstall hingga akhir jika ruang penyimpanan lokasi vdi berada mencukupi sesuai dengan jumlah partisi yang kita minta diawal (contohnya : kita tadi menggunakan sebesar `64 GB`)
 #### 3.-> pilih microsoft server yang kita inginkan untuk diinstall terdapat 4 pilihan dan saya memilih pilihan `opsi 2`***
 #### 4.-> `centang` persetujuan dan klik `next`
 #### 5.-> pilih `opsi 2`
 #### 6.-> gunakan default saja tanpa mengubah apapun -> klik tombol `next`
 #### 7.-> tunggu proses `installasi`
 #### 8.-> jika proses `installasi` berhasil maka akan muncul permintaan pembuatan `password` dan `konfirmasi password`
 #### 9.-> isi kolom `password` dan klik tombol `finish`
 #### 10.-> untuk `unlock` maka gunakan `ctrl+Alt+Delete` pada keyboard
 #### 11.-> akan muncul landing `Administrator` isi password yang sudah dibuat di point `9`
 #### 12.-> installasi windows server 2022 telah berhasil dan sudah muncul tampilan layar desktop di dalam VirtualBox VM Anda***  

![img9](assetuts2021/9landingwindows.PNG)
![img10](assetuts2021/10prosesinstallasi.png)
![img11](assetuts2021/11prosesinstallasi.png)




* [Vue.js](https://vuejs.org/)
* [Angular](https://angular.io/)
* [Svelte](https://svelte.dev/)
* [Laravel](https://laravel.com)
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->


## Directory

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
## DNS

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
## NET

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

## Promote

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#UTS">back to top</a>)</p>
