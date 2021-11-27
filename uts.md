
<!-- PROJECT LOGO -->
<body>
<h2 align="right">Name : Riska Aprilia</h2>
<h2 align="right">NIM : 1202190007</h2>
<h2 align="right">Class : IT0201</h2>
  <h3 align="center">Install Windows Server 2022 di VirtualBox 6.1 version</h3>

  <p align="center">
    Install your iso in microsoft windows server 2022
  </p>
 </body>
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
   2.-> pilih file iso yang telah didownload dan tersimpan dalam lokasi `file manager` kita 
   3.-> `open` 
   4.-> pilih file iso yang telah ditambahkan
   5.-> `choose` 
   6.-> file iso berhasil ditambahkan
   7.-> `remove empty file` 
   8.-> tampilan file dalam `storage device`
   9.-> Checking motherboard Base Memory tersedia `4096` seperti pada awal set-up `memory size`
   10.-> `System` setting processors menjadi 2 CPU '<optional'
   11.-> `OK`***  

  ![img7](assetuts2021/7setingosstorage.png)
  ![img8](assetuts2021/8setingossystem.png)
  
  
* Get `Running` your OS
---
6. Click `Start` your OS

**`landing Microsoft OS Setup` menandakan Anda berhasil memasukkan file iso yang benar untuk melanjutkan proses installasi windows server**  

 #### 1.-> `pilih bahasa` dapat menggunakan default dengan langsung klik tombol `next`
 #### 2.-> muncul tampilan `Install now` yuk klik -> Anda dapat berhasil menginstall hingga akhir 
   #### jika ruang penyimpanan lokasi vdi berada mencukupi sesuai dengan jumlah partisi yang kita minta diawal (contohnya : kita tadi menggunakan sebesar `64 GB`)
 #### 3.-> pilih microsoft server yang kita inginkan untuk diinstall terdapat 4 pilihan dan saya memilih pilihan `opsi 2`
 #### 4.-> `centang` persetujuan dan klik `next`
 #### 5.-> pilih `opsi 2`
 #### 6.-> gunakan default saja tanpa mengubah apapun -> klik tombol `next`
 #### 7.-> tunggu proses `installasi`
 #### 8.-> jika proses `installasi` berhasil maka akan muncul permintaan pembuatan `password` dan `konfirmasi password`
 #### 9.-> isi kolom `password` dan klik tombol `finish`
 #### 10.-> untuk `unlock` maka gunakan `ctrl+Alt+Delete` pada keyboard
 #### 11.-> akan muncul landing `Administrator` isi password yang sudah dibuat di point `9`
 #### 12.-> installasi windows server 2022 telah berhasil dan sudah muncul tampilan layar desktop di dalam VirtualBox VM Anda 
 
 

![img9](assetuts2021/9landingwindows.PNG)
![img10](assetuts2021/10prosesinstallasi.png)
![img11](assetuts2021/11prosesinstallasi.png)



<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING OTHER ANSWER ON QUESTION -->

## Directory
---
* Instalasi Active Directory Domain Services
* Instalasi DNS server
* Instalasi Net Framework 3.5
* Promote Server to a Domain Controller
---
_tampilan awal server manager_
`click yes` and `close (x)` the popup 

![img12](assetuts2021/12hellowwindowstrial.PNG)
![img13](assetuts2021/dr1.PNG)


_setting to promote server to a `Domain Controller`_
### click `Add roles and features`
![img14](assetuts2021/14instalsoaltambahan.png)

### click `Next`
![img15](assetuts2021/15instalsoaltambahan.png)

### click `Role-based or feature` and `Next`
![img16](assetuts2021/16instalsoaltambahan.png)

### click `Select a server from the server pool` and `Next`
![img17](assetuts2021/17instalsoaltambahan.png)

### checklist `Active Directory Domain Services` and click `Add Features` and `Next` to Instalasi Active Directory Domain Services
![img18](assetuts2021/18instalsoaltambahan.png)


## DNS
---

### unchecklist `Active Directory Certificate Service` | checklist `DNS Server` and click `Add Features` and `Continue` and `Next` to Instalasi DNS Server
![img19](assetuts2021/19instalsoaltambahan.png)
![img20](assetuts2021/20instalsoaltambahan.PNG)


## NET
---

### checklist `.NET Framework 3.5 Features` and `Next` to Instalasi Net Framework 3.5
![img21](assetuts2021/21instalsoaltambahan.png)

### click `Next` and `Next`
![img22](assetuts2021/22instalsoaltambahan.png)

### checklist `Restart the destination server ...` and `Yes` and `Install`
![img23](assetuts2021/23instalsoaltambahan.png)

### wait the process on `Feature installation` and the complete click `Close`
![img24](assetuts2021/24instalsoaltambahan.png)

### look the warning `!` you have the configuration required for Active Directory Domain Services at `WIN-9S0JADHPL64`
![img25](assetuts2021/25mengaturpromote.png)

### change name your computer server
_(1) `file manager` | this PC `properties` (2) scrool on bottom and click `Advanced system settings`  (3) click tab `Change Name` and click `Change` (4) `custom for name` (5) click `OK` (6) click `OK` (7) click `close` and Restart Now`_

![img26](assetuts2021/26changenameserver.png)



## Promote
---

### checking the server manager again 

#### 1. click `AD DS` and 2. the warning click `More` and 3. click `Promote this server to a domain...` 
![img27](assetuts2021/27mengaturpromote.png)

#### click `Add a new forest` and give the `Domain` for name domainserver and `Next`
![img28](assetuts2021/28mengaturpromote.png)

#### give the `password and confirm password` then `Next`
![img29](assetuts2021/29mengaturpromote.png)

### click `Next`
![img30](assetuts2021/30mengaturpromote.png)

### The NetBIOS domain name is `automathic` and click `Next` `Next` `Next`
![img31](assetuts2021/31mengaturpromote.png)

### click `Install`
![img32](assetuts2021/32mengaturpromote.png)

----
Wait your Windows Server is restarting
----

### Your `Promote Server to a Domain Controller` is `Done!`
![img33](assetuts2021/33mengaturpromote.png)


### checking your server manager for your domain to installed and success :)
![img34](assetuts2021/34mengaturpromote.png)



<p align="right">(<a href="#UTS">back to top</a>)</p>
