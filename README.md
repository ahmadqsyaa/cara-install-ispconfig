# cara-install-ispconfig
#### step-step
- siapkan os debian minimal 7 maksimal 11 atau cek di repo distro nya **[disini](https://github.com/servisys/ispconfig_setup/tree/master/distros)**.
- jika os sudah di install dan sudah bisa digunakan lalu buka terminal.
- ketik ```su``` di terminal lalu masukan password rootnya.
- kita akan merubah url repository package lalu ketikan di terminal ``` nano /etc/apt/sources.list ``` didalam file tersebut silahkan hapus semua atau cukup beri tanda ```#``` pada setiap baris
- ``` deb http://repo.ugm.ac.id/debian/ bookworm main contrib non-free ```
- ``` deb http://repo.ugm.ac.id/debian/ bookworm-updates main contrib non-free ```
- ``` deb http://repo.ugm.ac.id/debian-securiti/ bookworm/updates main contrib non-free ```
- *masukan  ke 3 url diatas lalu pastekan, simpan dengan mengklik ctrl + s dan ctrl + x untuk keluar*.
- ketik di terminal, kita update packagenya ``` apt update && apt upgdrade ```.
- kita install unzip dengan mengetik ``` apt install unzip ```.
- lalu kita download file ispconfig dengan mengetik ``` wget --no-check-certificate https://github.com/servisys/ispconfig_setup/archive/master.zip ```.
- lalu kita ekstrak file tadi dengan mengetik ``` unzip master.zip ```.
- lalu masuk kefolder yang tadi sudah diekstrak dengan mengetik ``` cd ispconfig_setup-master ```.
- lalu kita install ispconfing dengan mengetik ```./install.sh ```.
