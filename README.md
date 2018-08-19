<img src="https://raw.githubusercontent.com/LOoLzeC/FTS/master/img/Screenshot_2018-08-20-03-38-42-15.png"/>
############################################
<br>
PROJECT TITTLE : FTS (FUCK THE SOCIAL)
<br>
CODENAME       : Python
<br>
COPYRIGHT      : (C) Copyright 2018 LOoLzeC Scurity
<br>
CODED BY       : DERAY
<br>
FACEBOOK       : Deray
<br>
INSTAGRAM      : @reyy05
<br><br>
TAG            : HACKING,PHISING,SOCIAL ENGINEERING ATTACK,SOCIAL MEDIA AND FUCKING YOU ALL SOSMED!!!
<br>                                     
###########################################
<br><br>
(step satu)
<br><br>
membuat payload<br>
command contoh : SET PAYLOAD AkSIsrR.txt<br>
deskripsi : payload ini penting untuk listening nanti jika target sudah memasukan data login nya di payload yang sudah kita buat,btw tool ini harus terhubung ke internet,not offline ya akmj!1!
<br><br>
(step dua)
<br><br>
memberi output(nama file payload nya<br>
command contoh : SET OUTPUT hack-instagram.py<br>
deskripsi: perlu di ingat,jangan lupa namakan file nya dengan ekstensi py
<br><br>
(step tiga)
<br><br>
memberi nama query(akun apa yang ingin anda hack)<br>
command contoh : SET QUERY INSTAGRAM<br>
deskripsi: jika anda memasukan query instagram,atau tittle akun apa saja yang kalian mau,otomatis query ini akan masuk ke source payload kalian contoh outputnya di target [*] Login INSTAGRAM Lu Dulu Bos...
query INSTAGRAM itu adalah query yang sudah kalian buat dengan command SET QUERY
<br><br>
(step empat)
<br><br>
memberi tanggal dan tahun<br>
contoh command : SET DATE 2018/08<br>
deskripsi : nah ini juga penting buat listening nanti,ane kan redirect log nya hanya di satu host wordpress,jadi nanti listening nya di sini http://ailisgarcia.com/wp-content/uploads/2018/08/ AkSIsrR.txt
apakah sudah mengerti? 2018/08 dan AkSIsrR.txt itu adalah date dan log payload yang sudah kita input dengan command SET PAYLOAD AkSIsrR.txt dan SET DATE 2018/08
<br><br>
(step lima)
<br><br>
generate<br>
command : generate<br>
deskripsi: dan terjadilah disini pembuatan payload kalian buat untuk di eksekusi target nanti,tunggu sampe sukses.
<br><br>
(step terakhir)
<br><br>
sebarkan payload berekstensi hack-instagram.py ke target anda,dan biarkan dia mengeksekusinya dan memasukan log data login nya terlebih dahulu
<br><br>
sekarang tugas anda adalah mendengarkan sampai korban memasukan log data login mereka<br>
command : listen
<br><br>
atau untuk contoh manual listening command:
<br><br>
fts> SET PAYLOAD AkSIsrR.txt<br>
PAYLOAD => AkSIsrR.txt<br>
fts> SET QUERY INSTAGRAM<br>
QUERY => INSTAGRAM<br>
fts> SET DATE 2018/08<br>
DATE => 2018/08<br>
fts> listen<br>
[*] listening..."<br>
[*] LISTENING TARGET......"
<img src="https://raw.githubusercontent.com/LOoLzeC/FTS/master/img/Screenshot_2018-08-20-04-12-09-30.png"/>
ditunggu saja sampai korban memasukan log nya ^^<br><br><br>

bantuan command : help,?,show options


