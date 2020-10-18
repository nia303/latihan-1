Tugas repositori

Nama  : Nia Dwi Rahayu

Nim   : 312010298

Kelas : TI.20.A.2

Tugas 
1.	Langkah pertama membuat folder “NIA”, saya membuat foldernya di desktop.
2.	Klik kanan pada folder yang sudah dibuat tadi lalu klik terminal lalu akan muncul seperti gambar dibawah ini :

![image](https://user-images.githubusercontent.com/73011034/96361584-3f7b4b00-1151-11eb-8f3d-d62dba626d0c.png)

 





















3.	Kemudian buatlah folder dengan mengetik terminal “mkdir tugas”

 ![image](https://user-images.githubusercontent.com/73011034/96361605-62a5fa80-1151-11eb-8b28-0d86b11ba7b2.png)

Dan nantinya di folder NIA didalamnya ada folder baru “TUGAS”

4.	Langkah selanjutnya masuk kedalam folder “tugas” dengan mengetik “cd tugas”

 ![image](https://user-images.githubusercontent.com/73011034/96361612-73567080-1151-11eb-9474-991168c57e37.png)

5.	Buatlah folder tersebut menjadi repo (repository) dengan cara “git init”. Jika benar akan seperti gambar dibawah ini :

 ![image](https://user-images.githubusercontent.com/73011034/96361620-8701d700-1151-11eb-8bbe-1483c35d0773.png)

Jika sudah seperti ini artinya folder sudah menjadi repo

6.	Setelah itu buat file README.md dengan mengetik (echo “repositori” >> README.md)
                                       
![image](https://user-images.githubusercontent.com/73011034/96361651-c4666480-1151-11eb-8924-b7739887e847.png)







7.	Cara mengecek file tersebut ketik “git status” maka akan muncul sebagai berikut :

 ![image](https://user-images.githubusercontent.com/73011034/96361664-d2b48080-1151-11eb-966a-7f293b59bcdf.png)

Warna merah tersebut berarti file belum di add

8.	Cara nya dengan mengetik “git add <file>” atau jika file yang merah lebih dari satu (git add)

 ![image](https://user-images.githubusercontent.com/73011034/96361672-e364f680-1151-11eb-873e-5e5cf89ba8ee.png)




	


Untuk mengeceknya ketik “git status”
 
 ![image](https://user-images.githubusercontent.com/73011034/96361680-f8da2080-1151-11eb-8927-1faf62ce754a.png)

Maka warna file nya akan berubah hijau, file tersebut sudah di add.

9.	Langkah selanjutnya commit file tersebut (git commit -m “pesan”)

 ![image](https://user-images.githubusercontent.com/73011034/96361689-0b545a00-1152-11eb-8780-a10e984b7a7f.png)

	Jika tidak ada masalah maka akan seperti gambar diatas.




10.	Langka selanjutnya buatlah akun di http://github.com
11.	Jika sudah memiliki akun buatlah repository baru “new repository”

 ![image](https://user-images.githubusercontent.com/73011034/96361705-232bde00-1152-11eb-828a-565064d58c78.png)


12.	Langkah selanjutnya mengisi repository nya

 ![image](https://user-images.githubusercontent.com/73011034/96361712-33dc5400-1152-11eb-87d6-91d37aa736eb.png)

-	Isi repository nya dengan nama “latihan 1”, untuk penamaan bisa dirubah sesuai keperluan.
-	Untuk description/pesan buatlah sejalas mungkin.
-	Pilihlah publick
-	Lalu create repository


13.	Maka akan muncul seperti gambar berikut

![image](https://user-images.githubusercontent.com/73011034/96361741-743bd200-1152-11eb-911a-e8ff90b93902.png)

Copy link tersebut untuk menghubungkan dengan akun git yang ada di PC/laptop.











14.	Cara menguhubungkannya dengan mengetik “git remote add origin(origin ini nama default dri system,maka bisa kita ganti dengan nama yang kita inginkan) <link>”

 ![image](https://user-images.githubusercontent.com/73011034/96361749-8a499280-1152-11eb-93da-b32059aac52e.png)

	
	

15.	Dan Langkah terakhir ini untuk mengirim/memberikan sinyal informasi kepada server git hub, dengan cara ;   git push -u origin master
 
 ![image](https://user-images.githubusercontent.com/73011034/96361759-9e8d8f80-1152-11eb-802c-b3eb64171a4c.png)

	NOTE ;
		Mengapa disini saya menggunakan 	git push -u nia master
Karna di data sebelum nya saya telah mengganti nama default system itu menjadi (nia) .
Pesan
-	 Mkdir <nama file> untuk membuat file baru
-	Git init untuk membuat depository local
-	Gid add untuk menambahkan file baru
-	Git commit untuk menyimpan perubahan kedalam database git
-	Git remote untuk menghubungkan file ke github
-	Git push untuk mengupload file ke github
