# Penjelasan Mengenai Git dan Github

Sebelum kita mengenal apa itu Git dan Github, ada baiknya kita mengetahui dulu mengenai apa itu ***Version Control System***.

## Tentang *Version Control System*
***Version Control System*** atau sistem kendali versi (file) adalah sistem di mana kita dapat menyimpan histori perubahan pada file dan bahkan mengendalikan versi dari semua histori perubahan tersebut seperti mengembalikan berkas-berkas ke keadaan sebelumnya,  mengembalikan seluruh proyek kembali ke keadaan sebelumnya, membandingkan perubahan-perubahan di setiap waktu, melihat siapa yang terakhir mengubah sesuatu yang mungkin menimbulkan masalah, siapa dan kapan yang mengenalkan sebuah isu dan masih banyak lagi.

## Git
**Git** adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.

Untuk mengetahui bagaimana menggunakan git, berikut perintah-perintah dasar git:

### Unordered List
Git init : untuk membuat repository pada file lokal yang nantinya ada folder .git
Git status : untuk mengetahui status dari repository lokal
Git add : menambahkan file baru pada repository yang dipilih
Git commit : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
Git push : untuk mengirimkan perubahan file setelah di commit ke remote repository.
Git branch : melihat seluruh branch yang ada pada repository
Git checkout : menukar branch yang aktif dengan branchyang dipilih
GIt merge : untuk menggabungkan branch yang aktif dan branch yang dipilih
Git clone : membuat Salinan repository lokal

## Github
GitHub adalah penyimpanan terbesar untuk repositori Git dan Github adalah pusat kolaborasi untuk pengembangan proyek. Sebagian besar dari semua repositori Git tersimpan di GitHub, dan  banyak  proyek open source  menggunakan Github  untuk  menyimpan Git,  memecahkan masalah, menyusun kode, dan hal-hal lainnya.

### Repositori
Repositori atau repo adalah direktori penyimpanan file proyek. Di sini, Anda bisa menyimpan apa pun yang berkaitan dengan proyek yang sedang dibuat, misalnya file kode, gambar, atau audio. Repo sendiri bertempat di penyimpanan atau storage GitHub atau repositori lokal di komputer Anda.

### Branch
Brach merupakan salinan dari repositori milik Anda. Branch digunakan ketika Anda hendak melakukan suatu pengembangan atau development secara terpisah.

Pekerjaan atau task yang dilakukan di branch tidak akan memengaruhi repositori pusat atau branch lainnya. Jika pengembangannya sudah selesai, Anda bisa menggabungkan branch saat ini ke branch lainnya dah juga repositori pusat dengan menggunakan pull request.

### Pull Request
Pull request adalah ketika Anda menginformasikan user bahwa Anda sudah push perubahan yang dilakukan di branch ke master repositori. Collaborator repositori akan menerima atau menolak pull request. Segera setelah pull request diterima, Anda bisa mendiskusikan dan mengulas proyek bersama dengan collaborator.

### Forking Repositori
Forking repositori artinya Anda membuat proyek baru berdasarkan repositori yang sudah ada. Dalam kalimat yang lebih sederhana, forking repo berarti Anda menyalin repositori yang sudah ada, kemudian membuat beberapa perubahan yang diperlukan, lalu menyimpan versi terbarunya sebagai repositori baru, dan menjadikannya proyek Anda sendiri.

Fitur ini akan memperbaiki serta meningkatkan pengembangan proyek yang dilakukan. Karena proyek hasil forking masih baru, maka tidak akan terjadi apa-apa di repositori pusat. Perubahan yang dilakukan di repositori master juga dapat diterapkan di forking Anda saat ini.
