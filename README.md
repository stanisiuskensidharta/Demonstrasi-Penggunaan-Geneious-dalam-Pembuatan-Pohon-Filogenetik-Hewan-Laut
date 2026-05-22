# Demonstrasi-Penggunaan-Geneious-dalam-Pembuatan-Pohon-Filogenetik-Hewan-Laut


Pada demonstrasi ini, eksplorasi perangkat lunak Geneious Prime versi 2026.1.1 dilakukan dengan melakukan penjajaran, trimming, dan pembangunan ulang pohon filogenetik menggunakan sampel sekuens nukleotida spesies-spesies hewan dari jurnal acuan. Spesies yang digunakan meliputi Hippocampus algiricus, Hippocampus comes, Syngnathus pelagicus, Syngnathus floridae, Hippocampus bargibanti, dan Solenostomus paradoxus.
Jurnal acuan yang dipakai dapat diakses di <a href="https://www.the-innovation.org/article/doi/10.59717/j.xinn-geo.2025.100137">sini</a>. Geneious Prime dapat diunduh di <a href="https://www.geneious.com/updates">sini</a> 

Sebelum aplikasi Geneious dapat digunakan, perlu diperoleh sekuen nukleotida dari tiap spesies yang ingin diteliti dalam bentuk format file FASTA. Salah satu situs untuk menemukan sekuens nukleotida adalah situs National Center for Biotechnology Information (NCBI). Pada situs NCBI di dalam database nukleotida, sekuens nukleotida dapat dicari dengan menulis nama spesies, jenis gen, dan keutuhan sekuens pada kolom pencarian. Pada demonstrasi ini, digunakan sekuen coding DNA parsial pada gen COI (Cytochrome c Oxidase Subunit I) karena karakteristiknya yang bersifat highly conserved serta panjang basa yang pendek memerlukan waktu singkat untuk diproses. Sekuens yang memenuhi syarat tersebut dicari dan diunduh dalam format FASTA.


1. Sekuens DNA yang sudah diunduh kemudian diimpor ke dalam aplikasi Geneious agar dapat dimanipulasi. Import file dilakukan dengan memilih semua file FASTA yang terunduh dan menariknya ke dalam jendela aplikasi.

<img width="1327" height="818" alt="Screenshot 2026-05-22 220233" src="https://github.com/user-attachments/assets/16f6cac4-d1ca-450a-94bc-a120ca84f7bf" />


2. Sebelum file terimpor akan muncul jendela pop up yang menanyakan bagaimana sekuen-sekuen FASTA ingin disimpan dalam aplikasi Geneious. Terdapat 2 opsi yang disediakan, “Keep separate“ untuk menyimpan setiap sekuen secara terpisah, atau “Create list“ yang menggabungkan semua sekuen menjadi satu daftar. Penyimpanan terpisah memungkinkan manipulasi tiap sekuen tetapi dapat memperlambat aplikasi. Pilih opsi Create list karena semua sekuen akan dimanipulasi secara bersamaan.
<img width="685" height="821" alt="Screenshot 2026-05-22 220256" src="https://github.com/user-attachments/assets/3dfb2c3d-c381-4b4f-9b07-cd8a212d66f4" />

Setelah itu, akan terlihat User Interface (UI) dari aplikasi Geneious. Pada kolom di kiri, ditampilkan daftar direktori berisi file yang sudah diimpor. Secara standar, file disimpan pada direktori Local. File dalam direktori yang dipilih ditampilkan pada jendela di kanan atas, beserta deskripsi dari file tersebut. Pada jendela ini akan terlihat daftar sekuen nukleotida dari file FASTA yang diimpor bernama “6 nucleotide sequences”. Pilih daftar tersebut, sehingga sekuens akan ditampilkan pada jendela “Sequence view”. Tampilan sekuens nukleotida dapat diperbesar atau diperkecil dengan menekan tombol lup, dan diseret ke kanan atau kiri dengan menarik scrollbar.

3. Penjajaran nukleotida dilakukan dengan menekan tombol Align/Assemble pada toolbar, lalu di klik Multiple align untuk mensejajarkan banyak sekuens pendek tanpa memerlukan sekuen acuan.

<img width="1215" height="868" alt="Screenshot 2026-05-22 220322" src="https://github.com/user-attachments/assets/07f49050-aebc-425c-aa0f-119204a5f794" />


4. Terdapat banyak opsi algoritma penjajaran yang disediakan, seperti Geneious Alignment, MUSCLE Alignment, dan Clustal Omega. Geneious Alignment digunakan untuk jumlah data yang sedikit, MUSCLE Alignment untuk jumlah data sedang, dan Clustal Omega untuk jumlah data banyak. Pada demonstrasi ini digunakan MUSCLE Alignment dengan algoritma PPP, lalu di klik tombol “OK” untuk memulai penjajaran.

<img width="1212" height="865" alt="Screenshot 2026-05-22 220332" src="https://github.com/user-attachments/assets/81a1b673-c38f-45e4-b495-4ae4ff48afe1" />


Setelah penjajaran selesai, akan muncul file baru dalam direktori yang bernama “6 nucleotide sequences alignment”. Pilih file tersebut lalu hasil alignment akan muncul pada jendela “Alignment view”.
<img width="1200" height="831" alt="Screenshot 2026-05-22 220354" src="https://github.com/user-attachments/assets/d9de28a6-14b2-4b87-a3a0-c4ad750daac8" />

5. Sekuen hasil penjajaran perlu dirapikan dengan melakukan trimming. Trimming dilakukan dengan memotong sekuen nukleotida yang dianggap kurang baik, seperti ketika ditemukan rantai gap atau panjang basa pada ujung sebuah sekuens yang jauh melebihi sekuen lain. Pada hasil alignment yang didapatkan, terdapat gap dalam jumlah besar di ujung 3’ pada empat sekuens.
<img width="1200" height="859" alt="Screenshot 2026-05-22 220403" src="https://github.com/user-attachments/assets/d9f8fde5-a134-4797-866f-27d83d7dd611" />

6. Trimming secara manual dilakukan dengan memilih semua gap beserta nukleotida di sisi kanannya, lalu menekan tombol delete.

<img width="1226" height="864" alt="Screenshot 2026-05-22 220411" src="https://github.com/user-attachments/assets/02518a71-c553-4dea-a9ba-b918413ded8e" />


7. Trimming lebih lanjut dapat dilakukan sesuai sekuens yang digunakan dan pertimbangan masing-masing. Saat trimming sudah selesai dilakukan, perubahan basa disimpan dengan menekan tombol “Save”. 

<img width="1207" height="858" alt="Screenshot 2026-05-22 220419" src="https://github.com/user-attachments/assets/b4ba8ca1-87fc-4d00-9c2b-84ceefac7a0a" />


8. Pembuatan pohon filogenetik dilakukan dengan memilih file sekuens yang sudah dilakukan penjajaran dan trimming, lalu ditekan tombol “Tree” pada toolbar.

<img width="1212" height="845" alt="Screenshot 2026-05-22 220425" src="https://github.com/user-attachments/assets/060d8c62-86dc-4f6a-a108-b18cf2e85e06" />


9. Akan muncul popup dengan pilihan opsi pohon filogenetik, seperti model jarak genetik, metode pembangunan pohon, outgroup, dan metode pengambilan sampel ulang. Opsi yang dipilih adalah model jarak Tamura-Nei, metode pembangunan Neighbour-Joining dengan outgroup berupa sekuen Solenostomus paradoxus, serta metode pengambilan ulang sampel Bootstrap. Kemudian, di klik tombol “OK” untuk memulai pembuatan pohon filogenetik.

<img width="1233" height="858" alt="Screenshot 2026-05-22 220433" src="https://github.com/user-attachments/assets/2ac13291-2f27-4c70-bd78-cb7e109df59b" />


10. File berisi pohon filogenetik akan muncul terbentuk dengan nama “6 nucleotide sequences alignment (modified) consensus tree”, dengan pohon filogenetik ditampilkan pada jendela “Tree View”.

<img width="1217" height="859" alt="Screenshot 2026-05-22 220443" src="https://github.com/user-attachments/assets/7c408d37-e86f-4fb4-aea3-1ae2077be691" />

<img width="1218" height="848" alt="Screenshot 2026-05-22 220452" src="https://github.com/user-attachments/assets/d397fe9c-1dc5-4255-8f95-34e66eb04793" />


11. Pohon filogenetik dapat disimpan dengan menekan shortcut Ctrl+Shift+E, lalu memilih lokasi, jenis file, dan menulis nama file. Terakhir, klik tombol “Export” untuk menyimpan pohon filogenetik

PENUTUP

Geneious adalah aplikasi dengan fleksibilitas dan kompatibilitas tinggi, yang berguna antara lain dalam memodifikasi, memindahkan, visualisasi, penjajaran, dan trimming sekuens DNA, serta pembuatan pohon filogenetik seperti yang sudah didemonstrasikan pada makalah ini. Penggunaan aplikasi Geneious yang cepat dan mudah dipahami menjadikan aplikasi Geneious sebagai potensi alternatif terhadap aplikasi-aplikasi serupa. Selain itu, keragaman fitur-fitur dalam aplikasi Geneious memungkinkan pemanfaatan Geneious untuk penelitian dalam berbagai bidang bioinformatika lainnya.
