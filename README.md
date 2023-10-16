# latihanVCS
Berikut adalah penjelasan tentang cara penggunaan Git:
Instalasi Git:
Unduh dan instal Git sesuai dengan sistem operasi yang Anda gunakan, baik itu Windows, Mac, atau Linux
1
2
.
Konfigurasikan email dan username yang akan digunakan untuk akun Git Anda
2
.
Membuat Repositori Git:
Buka direktori proyek Anda menggunakan terminal atau command prompt.
Ketikkan perintah git init untuk membuat repositori Git baru
3
.
Menambahkan dan Mengcommit Perubahan:
Gunakan perintah git add <nama_file> untuk menambahkan file ke staging area.
Gunakan perintah git commit -m "pesan_commit" untuk mengcommit perubahan yang ada di staging area
3
.
Melihat Log Revisi:
Gunakan perintah git log untuk melihat daftar commit yang telah dilakukan
3
.
Menggunakan Branch:
Gunakan perintah git branch <nama_branch> untuk membuat branch baru.
Gunakan perintah git checkout <nama_branch> untuk beralih ke branch yang diinginkan
3
.
Bekerja dengan Remote Repository:
Tambahkan remote repository dengan perintah git remote add <nama_remote> <url_remote>.
Gunakan perintah git push <nama_remote> <nama_branch> untuk mengirim perubahan ke remote repository
3
.
Menggunakan Git Pull dan Git Fetch:
Gunakan perintah git pull <nama_remote> <nama_branch> untuk mengambil perubahan terbaru dari remote repository dan menggabungkannya dengan branch lokal Anda.
Gunakan perintah git fetch <nama_remote> untuk mengambil perubahan terbaru dari remote repository tanpa menggabungkannya dengan branch lokal Anda
3
.
Membatalkan Revisi:
Gunakan perintah git revert <commit_id> untuk membuat commit baru yang membatalkan perubahan dari commit tertentu.
Gunakan perintah git reset <commit_id> untuk menghapus commit tertentu dan mengembalikan branch ke commit sebelumnya
3
.
Menggunakan Git pada Visual Studio Code:
Buka proyek Anda di Visual Studio Code.
Gunakan panel Git untuk melihat status perubahan, melakukan commit, dan melakukan operasi Git lainnya
