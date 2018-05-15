# Ketik silahkan 

 Git config --global user.name "username anda" 

 Git config --global user.email isi_dengan_email_anda@ymail.com 

# Setelah melakukan konfigurasi username dan email, sekarang kita lakukan inisiasi, ketikan

 Git init 

# Kemudian kita tambahkan semua file yang ada dalam folder project kita, ketikan

 Git add * 

# Kemudian kita buat commit project nya, misal disini saya kasih commit “versi 1.0.0” , ketikan

 Git commit –m "versi 1.0.0" 

# Setelah kita buat commit untuk project nya, sekarang kita remote repository yang kita buat tadi, tentunya kita menggunakan kunci HTTP yang ada pada repository tadi, kalo ane kan tadi contoh nya http://github.com/acchoblues/APeK.git , ketikan

 Git remote add origin http://github.com/acchoblues/APeK.git 

# Setelah me-remote repository kita tadi, sekarang kita pull project nya, ketikan

 Git pull origin master 

# Terakhir kita kirim project kita ke repository kita, ketikan

 Git push origin master 
