# Latihan1
##mengenal VCS
VCS merupakan sebuah sistem yang merekam perubahan-perubahan dari sebuah berkas atau sekumpulan berkas dari waktu ke waktu sehingga anda dapat melihat kembali setiap perubahannya.
salah satu DVCS (Distributed Version Control System) yang sangat populer saat ini adalah GIT. GIT adalah salah satu sistem pengontrol versi (Version Control System) pada proyek
perangkat lunak yang diciptakan oleh Linus Torvalds.
###Langkah-langkah GIT
Cara membuat repositori di GIT

Buka aplikasi "GIT Bash"
Masuk ke penyimpanan file yang akan dibuat, misalnya akan dibuat di direktori C dengan command "cd /c"
Buat file terlebih dahulu dengan command "mkdir Latihan1"
Lalu masuk ke dalam file yang telah dibuat dengan command "cd /c/Latihan1"
Lalu command "git init". Git init ini untuk meng-set folder yang digunakan tersebut sebagai repositori local git. Bisa dibilang ini instalasi GIT pertama kali.
Lalu buat file README.md dengan command "echo "# Latihan1" > README.md
Setelah itu isi file README.md dengan tugas yang sudah diberikan dengan command "nano README.md"
Langkah selanjutnya adalah mengkomit file dengan command "git commit -m "isi commit". Git commit untuk menambahkan keterangan/status perubahan saat upload ke repositori online.
Lalu meremot repositori yang sudah dibuat di github dengan command "git remote add origin https://github.com/dimasreza/Latihan1 (bisa diganti dengan link repositori anda sendiri)
Lalu upload file README.md ke repositori online dengan command "git push -u origin master"
Kemudian command "git pull origin master". Git pull untuk mengambil commit terbaru lalu otomatis menggabungkan (merge) dengan branch yang aktif.
Terakhir mengecek file README.md yang sudah diupload dengan command "ll"
