# Data-101
Belajar scrapping, visualisasi, Learning (Artificial Inteligence) dan sebagainya.
# Panduan Instalasi
Repositori ini menggunakan jupyter notebook dalam pengerjaannya. Berikut panduan dalam memasang jupyter notebook. 
## Anaconda Navigator
Persyaratan memasang Anaconda Navigator:
1. Sistem operasi menggunakan Windows 8 atau lebih baru, macOS 64 bit 10.13 atau lebih baru, atau Linux seperti Ubuntu, Redhat, CentOS 7+
2. Persiapkan minimal 5 GB untuk proses pemasangan Anaconda Navigator

Proses pemasangan Anaconda Navigator adalah sebagai berikut:
### Windows
1. Unduh Anaconda Installer [disini](https://www.anaconda.com/products/individual#windows)
2. Lakukan proses pemasangan Anaconda Installer
3. Pastikan instalasi anaconda telah sukses dengan mencarinya di start menu
4. Apabila ditemukan, buka Anaconda Navigator dan Jupyter Notebook akan tersedia pada kolom <em>home</em>
5. Buka Jupyter Notebook dan Anaconda Navigator akan membuka jendela peramban Jupyter Notebook

Tips:
1. Setelah menyetujui lisensi, Anda akan ditanya apakah anda hendak memasang Anaconda Navigator untuk Anda sendiri (baca: user yang anda gunakan) atau untuk semua pengguna komputer. Kecuali anda berkehendak lain, pilih "just for me"
2. Disarankan untuk <em>path</em> lokasi pemasangan tidak mengandung spasi dan karakter <em>unicode</em>

### MacOS
Langkah - langkah pemasangan menggunakan antarmuka grafis:
1. Unduh Anaconda Installer [disini](https://www.anaconda.com/products/individual#macos)
2. Lakukan proses pemasangan Anaconda Installer
3. Pastikan instalasi anaconda telah sukses dengan mencarinya di start menu
4. Apabila ditemukan, buka Anaconda Navigator dan Jupyter Notebook akan tersedia pada kolom <em>home</em>
5. Buka Jupyter Notebook dan Anaconda Navigator akan membuka jendela peramban Jupyter Notebook

Langkah - langkah pemasangan menggunakan antarmuka baris perintah (CLI):
1. Unduh Anaconda Installer versi baris perintah [disini](https://www.anaconda.com/products/individual#macos)
2. Pergi ke tempat unduhan berada dan masukan perintah berikut:
```bash
bash ~/Downloads/Anaconda3-2020.02-MacOSX-x86_64.sh
```
> Ubah folder download dengan folder tempat anda menyimpan berkas Anaconda

> Sesuaikan versi dengan berkas unduhan anda

3. Menu pemasangan akan muncul, selesaikan proses instalasi
> Menu pemasangan akan menanyai apakah pengguna mau memulai Anaconda dengan perintah conda init, pilih ya.
4. Apabila pemasangan telah selesai, tutup terminal.
5. Buka Anaconda Navigator dan Anaconda Navigator akan membuka jendela peramban Jupyter Notebook

Tips:
1. Setelah menyetujui lisensi, Anda akan ditanya apakah anda hendak memasang Anaconda Navigator untuk Anda sendiri (baca: user yang anda gunakan) atau untuk semua pengguna komputer. Kecuali anda berkehendak lain, pilih "just for me"

### Linux
Untuk menggunakan pemasangan dengan antarmuka grafis, ada beberapa paket yang perlu dipasang pada sistem anda:
1. Debian (dan turunannya)
```bash
sudo apt-get install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
```
2. Redhat (dan turunannya)
```bash
sudo yum install libXcomposite libXcursor libXi libXtst libXrandr alsa-lib mesa-libEGL libXdamage mesa-libGL libXScrnSaver
```
3. Arch Linux (dan turunannya)
```bash
sudo pacman -Sy libxau libxi libxss libxtst libxcursor libxcomposite libxdamage libxfixes libxrandr libxrender mesa-libgl  alsa-lib libglvnd
```
4. OpenSUSE/SLES (dan turunannya)
```bash
sudo zypper install libXcomposite1 libXi6 libXext6 libXau6 libX11-6 libXrandr2 libXrender1 libXss1 libXtst6 libXdamage1 libXcursor1 libxcb1 libasound2  libX11-xcb1 Mesa-libGL1 Mesa-libEGL1
```
5. Gentoo
```bash
sudo emerge x11-libs/libXau x11-libs/libxcb x11-libs/libX11 x11-libs/libXext x11-libs/libXfixes x11-libs/libXrender x11-libs/libXi x11-libs/libXcomposite x11-libs/libXrandr x11-libs/libXcursor x11-libs/libXdamage x11-libs/libXScrnSaver x11-libs/libXtst media-libs/alsa-lib media-libs/mesa
```
Proses instalasi adalah sebagai berikut:
1. Buka peramban anda, dan unduh paket instalasi linux [disini](https://www.anaconda.com/products/individual#linux)
2. Buka folder tempat unduhan anda, dan masukan perintah berikut:
```bash
bash ~/Downloads/Anaconda3-2020.02-Linux-x86_64.sh
```
> Ubah folder "Downloads" ke tempat anda menyimpan file instalasi, dan sesuaikan versi yang anda unduh
3. Jendela pemasangan akan muncul, selesaikan proses instalasinya.  
> Menu pemasangan akan menanyai apakah pengguna mau memulai Anaconda dengan perintah conda init, pilih ya.
4. Apabila pemasangan telah selesai, tutup terminal.
5. Buka Anaconda Navigator dan Anaconda Navigator akan membuka jendela peramban Jupyter Notebook
## Pemasangan Dengan Antarmuka Baris Perintah
Jupyter Lab dapat dipasang dengan perintah berikut:
```bash
pip install jupyterlab
```
Apabila telah terpasang, Jupyter Lab dapat dibuka dengan perintah:

```bash
jupyter-lab
```
