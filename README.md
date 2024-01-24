# cara-install-ispconfig
#### step-step install ispconfig debian 11
- siapkan os debian minimal 7 maksimal 11 atau cek di repo distro nya **[disini](https://github.com/servisys/ispconfig_setup/tree/master/distros)** lihat gambar dibawah.
- <img src="https://i.imgur.com/S5sZo6o.png"/>
- jika debian sudah di install dan sudah siap digunakan lalu buka terminal.
- ketik ```su``` di terminal lalu masukan password root debian.
- kita akan merubah url repository package, ketik di terminal ``` nano /etc/apt/sources.list ``` didalam file tersebut ada beberapa text yang tidak berguna silahkan hapus semua atau cukup beri tanda ```#``` seperti contoh pada gambar dibawah ini
- <img src="https://i.imgur.com/thLMgSx.png" />
- lalu cari digoogle **repository debian 11** lalu pastekan pada file *sources.list* tadi, 📝*sesuaikan pada versi anda*.
- jika sudah di paste lalu simpan dengan mengklik **ctrl + s** dan **ctrl + x** untuk keluar.
- ketik di terminal, lalu update packagenya ``` apt update && apt upgrade ```.
- kita install unzip dengan mengetik ``` apt install unzip ```.
- lalu kita download file ispconfig dengan meetode **wget** dengan mengetik ``` wget --no-check-certificate https://github.com/servisys/ispconfig_setup/archive/master.zip ```.
- lalu kita ekstrak file tadi dengan mengetik ``` unzip master.zip ``` dia akan merubah file zip ke folder.
- lalu masuk kefolder yang tadi sudah diekstrak dengan mengetik ``` cd ispconfig_setup-master ```.
- lalu kita install ispconfig dengan mengetik ```./install.sh ```.
