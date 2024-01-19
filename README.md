# cara-install-ispconfig
#### step-step
- siapkan os debian minimal 7 smapai 11 atau cek di repo nya **[disini](https://github.com/servisys/ispconfig_setup/tree/master/distros)**
- jika os sudah di install dan sudah bisa digunakan lalu buka terminal
- ketik su di terminal lalu masukan password rootnya
- ketikan di terminal ``` nano /etc/apt/source.list ``` didalam file tersebut silahkan hapus semua dan ganti dengan
- ``` deb http://repo.ugm.ac.id/debian/ bookworm main contrib non-free ``` ``` deb http://repo.ugm.ac.id/debian/ bookworm-updates main contrib non-free ``` ``` deb http://repo.ugm.ac.id/debian-securiti/ bookworm/updates main contrib non-free ``` lalu ctrl + s dan ctrl + x
- ketik di terminal ``` apt update && apt upgdrade ```
- lalu ketik di terminal ``` wget --no-check-certificate https://github.com/servisys/ispconfig_setup/archive/master.zip ```
- ketik ``` unzip master.zip ```
- lalu ketik ``` cd ispconfig_setup-master ```
- lalu ketik ```./install.sh ```
