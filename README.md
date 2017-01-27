# Programming Course Diagram

A [draw.io](https://www.draw.io) diagram that shows relationships among 
programming courses and its topics in the curricula used at Faculty of 
Computer Science Universitas Indonesia.

## Cara Mengunduh

Terdapat 2 (dua) cara untuk mengunduh (*download*) berkas XML
diagram. Cara pertama adalah mengunduh berkas secara manual
melalui *browser*. Pada laman GitHub, klik tombil **Clone
or Download** lalu pilih **Download ZIP**. Isi dari repositori
GitHub terkait diagram akan dijadikan berkas ZIP dan diunduh ke
komputer Anda. Setelah proses unduh selesai, lakukan ekstraksi
berkas ZIP ke folder pilihan Anda.

Cara kedua adalah menggunakan *client* Git untuk membuat salinan
lokal repositori di komputer Anda. Silakan lakukan `git clone`
repositori ini ke komputer Anda menggunakan *client* berbasis
*command-prompt/shell* ataupun GUI seperti 
[GitKraken](https://www.gitkraken.com).

## Panduan Penggunaan

Untuk membuka dan mengubah diagram ini, gunakan layanan pembuatan
diagram berbasis SaaS [draw.io](https://www.draw.io). Berikut ini
adalah panduan singkat menggunakan [draw.io](https://www.draw.io):

1. Bukalah situs [draw.io](https://www.draw.io) menggunakan peramban
(*browser*) kesayangan Anda.
2. Pilih opsi **Device** ketika memilih lokasi penyimpanan diagram.
3. Pilih opsi **Open Existing Diagram** dan cari berkas XML diagram
yang telah Anda unduh (*download*) ke komputer Anda.
4. Setelah menemukan berkas XML diagram yang akan dibuka, pilih
**Open**. Layar *browser* Anda akan menampilkan halaman pertama
diagram.
5. Silakan lakukan modifikasi sesuai dengan keinginan Anda.
6. Setelah Anda selesai melakukan perubahan, buka halaman kedua
diagram ini yang bernama **Revision History**.
7. Tuliskan deskripsi perubahan yang Anda lakukan pada tabel yang
tersedia. Anda dapat menambahkan baris (*row*) baru pada tabel
dengan cara klik dua kali area kosong pada tabel, lalu klik teks
pada baris terakhir. Selanjutnya, klik tombol bergambar matriks 3x3
pada *toolbar* dan pilih opsi **Insert Row After**.
8. Setelah menambahahkan deskripsi perubahan, Anda dapat menyimpan
kembali diagram ini kembali ke komputer Anda. Pilih menu **File**
lalu pilih **Export as --> XML**.

## Panduan Kontribusi

Ada 2 (dua) cara untuk dapat mengumpulkan kembali diagram versi Anda
kembali ke repositori GitHub. Cara pertama adalah menggunakan
mekanisme **Pull Request** di GitHub. Cara ini hanya dapat dilakukan
apabila Anda telah mengunduh repositori ini menggunakan mekanisme `git
clone` dan telah terdaftar sebagai salah satu kolaborator yang berhak
melakukan `git push` pada repositori di GitHub. Apabila belum tercatat
sebagai kolaborator, Anda boleh membuat *fork* dan menaruh perubahan-
perubahan Anda di repositori milik Anda. Repository *fork* Anda nanti
dapat diintegrasikan kembali ke repositori utama menggunakan Pull
Request. 

Berikut ini adalah langkah-langkah untuk menggabungkan diagram versi
Anda ke repositori GitHub:

1. Buatlah *branch* baru pada salinan lokal repositori Git ini di
komputer Perintah yang dapat digunakan:
`git checkout -b <NAMA_BRANCH>` Contoh:
`git checkout -b usulan-perubahan`
2. Timpa (*overwrite*) berkas XML pada salinan lokal dengan berkas
XML versi gubahan Anda.
3. Minta Git untuk mencatat revisi yang Anda lakukan. Gunakan perintah
`git add <BERKAS_XML>` untuk mencatat perubahan pada berkas XML.
Kemudian simpan perubahan tersebut ke dalam Git menggunakan perintah
`git commit`. Tuliskan pesan *commit* yang menjelaskan perubahan-
perubahan yang Anda lakukan pada diagram.
4. Kirimkan *branch* yang mengandung perubahan Anda menggunakan
perintah `git push -u origin <NAMA_BRANCH>`. Contoh: `git push -u
origin usulan-perubahan`.
5. Buat Pull Request melalui laman GitHub. Cari *branch* Anda dan
buat Pull Request dari laman *branch* Anda di GitHub.
6. Pull Request akan dikaji dan dapat didiskusikan di laman Pull
Request. Apabila tidak ada masalah, maka Pull Request dapat
diintegrasikan ke branch *master*.

Apabila Anda melakukan *fork*, maka perubahan-perubahan dapat Anda
simpan dan *push* ke branch utama (*master*) repositori Anda.
Kemudian buatlah Pull Request dari laman repositori *fork* Anda.

Cara kedua untuk mengumpulkan diagram XML adalah kirim diagram XML
versi Anda ke email pemilik atau kontributor tercatat di repositori
ini. Pull Request akan dibuatkan secara manual.
