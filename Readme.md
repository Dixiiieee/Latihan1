# Latihan1

# Pengertian VCS

Version Control System merupakan sebuah sistem yang merekam perubahan dari sebuah berkas atau sekumpulan berkas dari waktu ke waktu, sehingga anda dapat melihat kembali perubahannya.

# Langkah-langkah menggunakan GIT

Buka/masuk software "Git Bash".

Masuk ke direktori yang anda akan jadikan tempat penyimpanan file nantinya menggunakan command "cd /direktori anda"

Lalu buat file di direktori anda dengan command "mkdir 'nama file'"

Setelah dibuat, masuk kedalam file tersebut dengan command "cd /direktori/namafile"

Lalu ketik command "git init" untuk set folder tadi menjadi repositori lokal, setelah "git init" diketik akan terlihat seperti "/d/direktori/nama file (master)

Lalu buat file README.md dengan command "echo "# nama file" > README.md". reminder = tidak ada string sebelum kata echo dan setelah kata readme.md

Setelah file README.md dibuat, masuk kedalam file tersebut menggunakan command "nano README.md"

Jika sudah selesai mengisi file readme.md, langkah selanjutnya adalah meng-komit file dengan command "git commit -m "isi commit". reminder kembali = tidak ada string didepan kata git

Setelah file di komit, langkah selanjutnya adalah meremot repositori yang sudah anda buat di github dengan command "git remote add origin 'link repositori anda'". reminder = tidak ada kutip diluar link repositori anda

Lalu upload file README.md dengan command "git push -u origin master"

Kemudian ketik command "git pull origin master", untuk mengambil commit terbaru lalu menggabungkan otomatis (merge) dengan branch yang aktif.

Terakhir yaitu mengecek file README.md yang sudah diupload dengan command "ll".
