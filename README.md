# cara-install-ispconfig
#### step-step
- siapkan os debian minimal 7 maksimal 11 atau cek di repo distro nya **[disini](https://github.com/servisys/ispconfig_setup/tree/master/distros)** lihat gambar dibawah.
- [Imgur](https://imgur.com/S5sZo6o)
- jika os sudah di install dan sudah bisa digunakan lalu buka terminal.
- ketik ```su``` di terminal lalu masukan password rootnya.
- kita akan merubah url repository package, lalu ketikan di terminal ``` nano /etc/apt/sources.list ``` didalam file tersebut silahkan hapus semua atau cukup beri tanda ```#``` seperti contoh pada gambar dibawah ini
- <img src="https://i.imgur.com/thLMgSx.png" />
- lalu cari digoogle **repository debian 11** lalu pastekan pada file *sources.list* tadi.
- jika sudah di paste lalu simpan dengan mengklik **ctrl + s** dan **ctrl + x** untuk keluar*.
- ketik di terminal, kita update packagenya ``` apt update && apt upgdrade ```.
- kita install unzip dengan mengetik ``` apt install unzip ```.
- lalu kita download file ispconfig dengan mengetik ``` wget --no-check-certificate https://github.com/servisys/ispconfig_setup/archive/master.zip ```.
- lalu kita ekstrak file tadi dengan mengetik ``` unzip master.zip ```.
- lalu masuk kefolder yang tadi sudah diekstrak dengan mengetik ``` cd ispconfig_setup-master ```.
- lalu kita install ispconfing dengan mengetik ```./install.sh ```.
