Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
...

PAUL@DESKTOP-643VO6O MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 David.cpp
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Kalkulator.cpp
 LABTBD1.sql
 Links/
'Local Settings'@
 MicrosoftEdgeBackups/
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{005cf22c-1535-11e9-8636-0800271883d7}.TM.blf
 NTUSER.DAT{005cf22c-1535-11e9-8636-0800271883d7}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{005cf22c-1535-11e9-8636-0800271883d7}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Oracle/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Sti_Trace.log
 Templates@
 Untitled-1.cpp
 Untitled-5.cpp
 Videos/
 anaconda3/
 c.cpp
 logs/
 mysql
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 sqlplus

PAUL@DESKTOP-643VO6O MINGW64 ~
$ cd Documents

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents
$ git config --global user.email "dave.haniko@gmail.com"

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents
$ git init
Initialized empty Git repository in C:/Users/PAUL/Documents/.git/

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents (master)
$ git clone https://github.com/Powerblu/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents (master)
$ ls


 C16_220211060212_DavidEvanEfraimHaniko.docx
'Custom Office Templates'/
'Dataset Tugas Modul 5 (1).zip'
 Default.rdp
'Desktop - Shortcut.lnk'*
'File C++'/
'Foto Profil Keren'/
'Foto soal Probstat'/
'Kelas 1 Tema (2,3,4)'/
'Kelebihan dan kekurangan metode agile.docx'
 KingsoftData/
 Laporan_Kelas_C_Kelompok_16_Modul_3.pdf
 Market/
'Matakuliah Teknik Informatika Unsrat'/
'Materi SO'/
'Memori Eksternal.docx'
'Memori Eksternal.pdf'
'Metodologi pengembangan Perangkat Lunak.docx'
'My Music'@
'My Pictures'@
'My Videos'@
'Pembuatan Aplikasi Warehouse.docx'
'Pemograman WEB'/
 Petunjuk.docx
'Prak Tbd'/
 RPL/
'Rekaman Kuliah'/
'SISTEM INFORMASI.docx'
'STUDY JAM'/
'Screenshot (4420).png'
'Screenshot (4421).png'
'Screenshot (4422).png'
'Screenshot (4423).png'
'Screenshot (4424).png'
'Screenshot (4425).png'
'Screenshot (4426).png'
'Screenshot (4427).png'
'Screenshot (4428).png'
'Screenshot (4429).png'
'Screenshot (4430).png'
'Screenshot (4431).png'
'TUGAS SISTEM INFORMASI.docx'
'Tugas Topic 3 Struktur Data.docx'
'Tugas Topic 3 Struktur Data.pdf'
'UTS & UAS AOK'/
'UTS & UAS Struktur data'/
 Zoom/
'_Pertemuan 7 PENENTUAN KEBUTUHAN SI.pdf'
 belajarGIT/
 ch1.pdf
 ch1.pptx
 ch2.pdf
 ch3.pdf
 ch4.pdf
 ch4.pptx
 ch5.pdf
 ch9.pdf
'data-data tabel'/
 data-integration/
 desktop.ini
 ebook-pressman-sw-engineering.pdf
 uts.zip
'~$JADWAL KULIAH INFORMATIKA.xlsx'
'~$Kamar.xlsx'
'~$ch1.pptx'
'~$ch4.pptx'
'~$gas BHS Indonesia Surat permohonan dan laporan magang.docx'
'~$gas Basis Data Bagian 2.docx'
'~$mbuatan Aplikasi Warehouse.docx'
'~$mori Eksternal.docx'
'~$ofil Perusahaan (2).docx'
'~$poran Kerja Kelompok 3 (Basis Data).docx'
'~$poran ibadah David Haniko.docx'
'~WRL2846.tmp'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents (master)
$ cd belajarGIT

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan File Tugas-git.txt"
[Tugas-git 9c1b295] Menambahkan File Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Mengedit isi file Tugas-git.txt"
[Tugas-git ecd8681] Mengedit isi file Tugas-git.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating da5e1a1..ecd8681
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 575 bytes | 287.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Powerblu/belajarGIT.git
   da5e1a1..ecd8681  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan File Tugas-html.txt"
[Tugas-html 2c5f0c1] Menambahkan File Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Mengedit isi file Tugas-html.txt"
[Tugas-html d02ec76] Mengedit isi file Tugas-html.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating ecd8681..d02ec76
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 552 bytes | 276.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Powerblu/belajarGIT.git
   ecd8681..d02ec76  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css
bash: /mingw64/bin/git: Device or resource busy

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css
fatal: a branch named 'Tugas-css' already exists

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan File Tugas-css.txt"
[Tugas-css af5772d] Menambahkan File Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Mengedit isi file Tugas-css.txt"
[Tugas-css c2c81c1] Mengedit isi file Tugas-css.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating d02ec76..c2c81c1
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 591 bytes | 295.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Powerblu/belajarGIT.git
   d02ec76..c2c81c1  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan File Tugas-js.txt"
[Tugas-js debdc07] Menambahkan File Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Mengedit isi file Tugas-js.txt"
[Tugas-js d1b99ae] Mengedit isi file Tugas-js.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating c2c81c1..d1b99ae
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 514 bytes | 257.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Powerblu/belajarGIT.git
   c2c81c1..d1b99ae  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan File Tugas-midProject.txt"
[Tugas-midProject 5c2b4ae] Menambahkan File Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Mengedit isi file Tugas-midProject.txt"
[Tugas-midProject 0e0c9f0] Mengedit isi file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating d1b99ae..0e0c9f0
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 550 bytes | 275.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Powerblu/belajarGIT.git
   d1b99ae..0e0c9f0  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan File Tugas-php.txt"
[Tugas-php d9ac10e] Menambahkan File Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Mengedit isi file Tugas-php.txt"
[Tugas-php 47ae993] Mengedit isi file Tugas-php.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 0e0c9f0..47ae993
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 523 bytes | 261.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Powerblu/belajarGIT.git
   0e0c9f0..47ae993  main -> main

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan File Tugas-finalProject.txt"
[Tugas-finalProject b8849d4] Menambahkan File Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Mengedit isi file Tugas-finalProject.txt"
[Tugas-finalProject 8089b04] Mengedit isi file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 47ae993..8089b04
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

PAUL@DESKTOP-643VO6O MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 553 bytes | 276.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Powerblu/belajarGIT.git
   47ae993..8089b04  main -> main
