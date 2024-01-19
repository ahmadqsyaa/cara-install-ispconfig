# cara-install-ispconfig
#### step-step
- siapkan os debian minimal 7 minimal 11 atau cek di repo nya **[disini](https://github.com/servisys/ispconfig_setup/tree/master/distros)**.
- jika os sudah di install dan sudah bisa digunakan lalu buka terminal.
- ketik ```su``` di terminal lalu masukan password rootnya.
- ketikan di terminal ``` nano /etc/apt/source.list ``` didalam file tersebut silahkan hapus semua dan ganti dengan
  <p> ``` deb http://repo.ugm.ac.id/debian/ bookworm main contrib non-free deb http://repo.ugm.ac.id/debian/ bookworm-updates main contrib non-free deb http://repo.ugm.ac.id/debian-securiti/ bookworm/updates main contrib non-free ``` </p>
  *masukan  ke 3 url diatas lalu pastekan, simpan dengan mengklik ctrl + s dan ctrl + x untuk keluar*.
- ketik di terminal, kita update packagenya ``` apt update && apt upgdrade ```.
- kita install unzip dengan mengetik ``` apt install unzip ```.
- lalu kita download file ispconfig dengan mengetik ``` wget --no-check-certificate https://github.com/servisys/ispconfig_setup/archive/master.zip ```.
- lalu kita ekstrak file tadi dengan mengetik ``` unzip master.zip ```.
- lalu masuk kefolder yang tadi sudah diekstrak dengan mengetik ``` cd ispconfig_setup-master ```.
- lalu kita install ispconfing dengan mengetik ```./install.sh ```.
