<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Laporan Berbasis Web</title>
</head>
<body>
    <h1>
        Laporan Diskusi Kelompok I <br />
        Metodologi Desain Perangkat Lunak - VIII <br />
        Metode RAD
    </h1>
    <br>
    <center>
        <img src="sources/Logo UTY.png" width="750px" />
    </center>
    <br>   
    <h2>Semester Ganjil TA.2021/2022</h2>
    <br>
    <br>
    <br>
    <h3>
        Anggota Kelompok:<br />
        5200411148 - Faishal Muhammad Faatih<br />
        5200411234 - Daffa Iyad Yusuf Khoiruddin<br />
        5200411328 - Ragil Aldyansyah<br />
        5200411336 - Muhammad Fadhlurrohman<br />
        5200411341 - Harri Dwi Kurniawan<br />
        5200411359 - Rino Cahyo Putra Susanto<br />
    </h3>
    <br>
    <br>
    <br>
    <br>
    <h1>
        Universitas Teknologi Yogyakarta <br />
        Fakultas Sains & Teknologi <br />
        Prodi Informatika
    </h1>
    <br>
    <br>
    <hr>
    <br>
    <br>
    <h2>Pengembangan Aplikasi Sistem Informasi<br>Manajemen Perpustakaan<br>Berbasis Web<br>Metode RAD</h2>
    <br>
    <hr>
    <br>
    <h3>BAB I<br>PENDAHULUAN</h3>
    <br>
    <h4>1.1 Latar Belakang</h4>
    <p>Informasi merupakan sebuah elemen penting dalam kehidupan manusia yang semakin lama semakin maju. 
        Dengan adanya informasi, kita bisa mengetahui beberapa hal yang sedang terjadi di sekitar kita. 
        Tanpa informasi, kita menjadi buta akan keadaan sekitar, maka dibuatlah tempat untuk menyimpan 
        informasi yang disebut dengan perpustakaan.</p>
    <p>Perpustakaan adalah sebuah tempat dimana didalamnya terdapat banyak ilmu pengetahuan yang sangat bermanfaat bagi masyarakat. 
        Peranan perpustakaan pada kehidupan bermasyarakat adalah sebagai tempat menyimpan karya-karya masyarakat, 
        sebagai tempat mengalirnya informasi, sebagai tempat memperoleh ilmu.</p>
    <p>Seiring dengan perkembangan teknologi, sistem terkomputerisasi menjadi suatu kebutuhan dalam segala unit usaha. 
        Selain unit usaha terdapat juga unit perpustakaan yang memiliki peran sebagai salah satu tempat untuk mencari informasi. 
        Unit perpustakaan pada dasarnya membutuhkan pengelolaan terhadap aset-aset yang dimilikinya seperti pendataan aset, 
        proses transaksi pinjam-meninjam.</p>
    <p>Oleh karena itu, dibuatlah sebuah aplikasi Sistem Informasi Manajemen Perpustakaan berbasis web supaya memudahkan sekolah x 
        untuk mengelola pendataan dan transaksi yang terjadi di perpustakaan sekolah tersebut. Sistem ini dikembangkan dengan 
        menggunakan Bahasa pemrograman PHP dengan aturan sebuah web supaya lebih tersruktur menggunakan HTML, CSS.</p>
    <h4>1.2 Rumusan Masalah</h4>
        <p>Berikut permasalahan yang terjadi di perpustakaan sekolah x :</p>
    <ol>
        <li>Pendataan yang masih manual diperpustakaan tersebut.</li>
        <li>Belum adanya aplikasi manajemen perpustakaan yang mendukung pustakawan dalam mengelola data yang ada diperpustakaan.</li>
        <li>Pembuatan laporan yang lama membuat kinerja pustakawan kurang efektif dan efisien.</li>
    </ol>
    <h4>1.3 Batasan Masalah</h4>
        <p>Berikut batasan masalah adalah :</p>
    <ol>
        <li>Hak akses digunakan untuk admin, operator dan anggota</li>
        <li>Sistem dibangun menggunakan Bahasa Pemrograman PHP. dengan aturan web HTML, CSS. dan database MySQL</li>
        <li>Data yang diolah meliputi data admin, data operator dan data anggota.</li>
    </ol>
    <h4>1.4 Tujuan</h4>
        <p>Adapun tujuan yang didapat :</p>
    <ol>
        <li>Merancang sistem manajemen yang lebih efisien dalam pendataan</li>
        <li>Merancang aplikasi perpustakaan berbasis web untuk sekolah x</li>
        <li>Merancang sistem aplikasi manajemen perpustakaan yang ramah pengguna, baik dari segi antarmuka ataupun fitur-fitur yang disediakan untuk memudahkan pustakawan dalam mengelola perpustakaan.</li>
    </ol>
    <br>
    <br>
    <h3>BAB II<br>PEMBAHASAN</h3>
    <br>
    <br>
    <h4>2.1 Landasan Teori</h4>
    <ol><br>
        <li><strong>PHP</strong></li>
        <p>PHP (PHP: Hypertext Preprocessor) adalah sebuah bahasa pemrograman server side scripting yang bersifat open source.<br>
            Sebagai sebuah scripting language, PHP menjalankan instruksi pemrograman saat proses runtime. Hasil dari instruksi tentu akan berbeda tergantung data yang diproses.<br>
            PHP merupakan bahasa pemrograman server-side, maka script dari PHP nantinya akan diproses di server. Jenis server yang sering digunakan bersama dengan PHP<br>antara lain Apache, Nginx, dan LiteSpeed.<br>
            Selain itu, PHP juga merupakan bahasa pemrograman yang bersifat open source. Pengguna bebas memodifikasi dan mengembangkan sesuai dengan kebutuhan mereka.</p>
    <br>
       <li><strong>Use Case Diagram</strong></li>
        <p>Use case diagram adalah satu dari berbagai jenis diagram UML (Unified Modelling Language) yang menggambarkan hubungan interaksi antara sistem dan aktor. Use Case dapat mendeskripsikan tipe interaksi antara si pengguna sistem dengan sistemnya.
            </p>
        <p>Tentunya, use case diagram merupakan sesuatu yang mudah dipelajari. Langkah awal untuk melakukan pemodelan, tentu perlunya suatu diagram yang mampu menjabarkan aksi aktor dengan aksi sistem itu sendiri, seperti yang terdapat pada use case diagram.</p>
        <p>Adapun, fungsi dari use case diagram sebagai berikut:</p>
       <ul>
           <li>Berguna memperlihatkan proses aktivitas secara urut dalam sistem.</li>
           <li>Mampu menggambarkan proses bisnis, bahkan menampilkan urutan aktivitas pada sebuah proses.</li>
           <li>Sebagai bridge atau jembatan antara pembuat dengan konsumen untuk mendeskripsikan sebuah sistem.</li>
       </ul>
        <p>Komponen Use Case Diagram</p>
        <img src="sources/useCase.png">
            <p>Gambar 1. Komponen Use Case</p>
        <br>
        <li><strong>Activity Diagram</strong></li>
        <p>Activity Diagram merupakan rancangan aliran aktivitas atau aliran kerja dalam sebuah sistem yang akan dijalankan. Activity Diagram juga digunakan untuk mendefinisikan atau mengelompokan aluran tampilan dari sistem tersebut. Activity Diagram memiliki komponen dengan bentuk tertentu yang dihubungkan dengan tanda panah. Panah tersebut mengarah ke-urutan aktivitas yang terjadi dari awal hingga akhir.</p>
        <p>Tujuan Activity Diagram :</p>
        <ul>
            <li>Menjelaskan urutan aktivitas dalam suatu proses.</li>
            <li>Di dalam dunia bisnis biasanya digunakan untuk modeling (memperlihatkan urutan proses bisnis).</li>
            <li>Mudah dalam memahami proses yang ada dalam sistem secara keseluruhan.</li>
            <li>Merupakan metode perancangan yang terstruktur, mirip dengan Flowchart maupun Data Flow Diagram (DFD).</li>
            <li>Mengetahui aktivitas aktor/pengguna berdasarkan use case/diagram yang dibuat sebelumnya. </li>
        </ul>
        <br>
        <p>Komponen Activity Diagram</p>
        <img src="sources/activityDiagram.png" alt="">
        <p>Gambar 2. Komponen Activity Diagram</p><br>
        <li><strong>Penerapan Model RAD</strong></li>
        <p>Model RAD mengadopsi model waterfall dan pembangunan dalam waktu singkat yang dicapai dengan menerapkan :</p>
        <ul>
            <li>Component based construction ( pemrograman berbasis komponen bukan prosedural).</li>
            <li>Penekanan pada penggunaan ulang (reuse) komponen perangkat lunak yang telah ada.</li>
            <li>Pembangkitan kode program otomatis/semi otomatis.</li>
            <li>Multiple team (banyak tim), tiap tim menyelesaikan satu tugas yang selevel tapi tidak sama. Banyaknya tim tergantung dari area dan kompleksitasnya sistem yang dibangun.</li>
        </ul>
    </ol>
    <br>
    <h4>2.2 Metode Perancangan</h4>
    <ol>
        <li>Metode RAD</li>
        <img src="sources/RAD.png" width="520">
            <p>Gambar 3. Metode RAD</p>
        <p>Rapid Application Development (RAD) atau rapid prototyping adalah model proses pembangunan perangkat lunak 
            yang tergolong dalam teknik incremental (bertingkat). RAD menekankan pada siklus pembangunan pendek, singkat, 
            dan cepat. Waktu yang singkat adalah batasan yang penting untuk model ini. Rapid application development 
            menggunakan metode iteratif (berulang) dalam mengembangkan sistem di mana working model (model bekerja) 
            sistem dikonstruksikan di awal tahap pengembangan dengan tujuan menetapkan kebutuhan (requirement) user 
            dan selanjutnya disingkirkan. Working model digunakan kadang-kadang saja sebagai basis desain dan implementasi 
            sistem final.  Berikut tahap-tahap metode RAD :</p>
        <ol>
            <li>Perencanaan Kebutuhan.</li>
            <p>Tahapan ini merupakan tahap awal dalam suatu pengembangan sistem, 
                dimana pada tahap ini dilakukan identifikasi masalah dan pengumpulan data yang diperoleh 
                dari pengguna atau stakeholder pengguna yang bertujuan untuk mengidentifikasi maksud akhir 
                atau tujuan dari sistem dan kebutuhan informasi yang diinginkan.</p>
            <li>Desain Sistem.</li>
            <p>Di dalam tahap desain sistem, keaktifan pengguna yang terlibat sangatlah penting 
                untuk mencapai tujuan karena pada tahapan ini dilakukan proses desain dan proses 
                perbaikan desain secara berulang-ulang apabila masih terdapat ketidaksesuaian desain 
                terhadap kebutuhan pengguna yang telah diidentifikasi pada tahapan sebelumnya.</p>
            <li>Proses pengembangan dan pengumpulan feedback.</li>
            <p>Pada tahap ini desain sistem yang telah dibuat dan disepakati, diubah ke dalam bentuk aplikasi 
                versi beta sampai dengan versi final. Pada tahapan ini juga programmer harus terus-menerus 
                melakukan kegiatan pengembangan dan integerasi dengan bagian-bagian lainnya sambal terus 
                mempertimbangkan feedback dari pengguna atau klien. Jika proses berjalan lancar maka dapat 
                berlanjut ke tahapan berikutnya, sedangkan jika aplikasi yang dikembangkan belum menjawab kebutuhan, 
                programmer akan kembali ke tahapan desain sistem.</p>
            <li>Implementasi atau penyelesaian produk.</li>
            <p>Tahapan ini merupakan tahapan dimana programmer menerapkan desain dari suatu sistem 
                yang telah disetujui pada tahapan sebelumnya. Sebelum sistem diterapkan, terlebih dahulu 
                dilakukan proses pengujian terhadap program untuk mendeteksi kesalahan yang ada pada sistem 
                yang dikembangkan. Pada tahap ini biasa memberikan tanggapan akan sistem yang sudah dibuat dan 
                mendapat persetujuan mengenai sistem tersebut.</p>
        </ol>
    </ol>
    <br>
    <h4>2.3 Hasil dan Pembahasan</h4>
    <br>
    <ol>
        <li><strong>Requirements Planning (Perencanaan)</strong></li><br>
        <p>Penerapan metode RAD dalam membuat aplikasi ini diawali dengan tahap perencanaan syarat dan kebutuhan website. Acuan dalam pembuatan aplikasi ini yaitu dengan menganalisa kebutuhan user, 
            dimana user aplikasi ini terdiri dari admin, operator, dan anggota. Orientasi dalam fase ini adalah pemecahan masalah-masalah, berikut ini adalah hasil analisa mengenai syarat-syarat sistem, kebutuhan, data, software dan lainnya.</p>
        <ol>
            <li>Kebutuhan Fungsional</li>
            <li>Admin</li>
            <ol type="a">
              <li>Admin dapat login dan logout</li>
              <li>Admin dapat melihat data buku</li>
              <li>Admin dapat melihat data anggota</li>
              <li>Admin dapat melihat data transaksi</li>
              <li>Admin dapat melihat laporan</li>
              <li>Admin dapat mengelola data operator</li>
              <li>Admin dapat mengelola data pribadi</li>
              <li>Admin dapat menambahkan operator</li>
            </ol>
            <li>Operator</li>
            <ol type="a">
              <li>Operator dapat login dan logout</li>
              <li>Operator dapat mengelola dan melihat data buku</li>
              <li>Operator dapat mengelola data anggota</li>
              <li>Operator dapat mengelola data transaksi</li>
              <li>Operator dapat mengelola laporan</li>
              <li>Operator dapat mengelola data pribadi</li>
              <li>Operator dapat menambahkan anggota</li>
            </ol>
            <li>Anggota</li>
            <ol type="a">
              <li>Anggota dapat login dan logout</li>
              <li>Anggota dapat melihat data buku</li>
              <li>Anggota dapat melihat data transaksi</li>
              <li>Anggota dapat melihat riwayat transaksi</li>
              <li>Anggota dapat mengelola data pribadi</li>
            </ol>
            </ol><br>
            <li>Resource Requirements</li>
            <ol>
               <li>Hardware</li>
            <ol type="a">
              <li>Processor : 1.5 GHz Dual Core</li>
              <li>Memory (RAM) : 2 GB</li>
              <li>Hard disk : 120 GB</li>
            </ol>
            <li>Software</li>
            <ol type="a">
              <li>Sistem operasi : Minimum Windows 7</li>
              <li>Bahasa pemrograman : PHP, HTML, CSS</li>
              <li>Text Editor : Visual Studio Code</li>
              <li>Database : Mysql</li>
            </ol>
        </ol>
        <br>
        <li><strong>Tahap Pengujian</strong></li> 
        <table border="1" style="font-size: 14px;" >
            <tr>
                <th style="padding: 5px;">Sekenario Pengujian</th>
                <th>Hasil yang diharapkan</th>
                <th>keterangan</th>
                <th>kesimpulan</th>
            </tr>
            <tr>
                <td style="padding: 5px;">Tidak memasukkan inputan saat login</td>
                <td>Sistem tidak memberi akses dan menampilkan pesan error form harus diisi</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
            </tr>
            <tr>
                <td  style="padding: 5px;">Memasukkan username atau password salah</td>
                <td>Sistem tidak memberi akses dan menampilkan pesan error inputan tidak tepat</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
            </tr>
            <tr>
                <td  style="padding: 5px;">Memasukkan username dan password sesuai data</td>
                <td>Sistem memberikan akses kepada admin/anggota sesuai data login</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
            </tr>
            <tr>
                <td  style="padding: 5px;">Mengetik langsung halaman dashboard melalui url tanpa login</td>
                <td>Sistem menangani proses autentikasi dan langsung diarahkan ke halaman login</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
            </tr>
            <tr>
                <td  style="padding: 5px;">Anggota meminjam buku tanpa memilih buku terlebih dahulu</td>
                <td>Sistem memberikan pesan error untuk memilih buku terlebih dahulu</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
            </tr>
                <td  style="padding: 5px;">Anggota meminjam buku yang sudah tidak tersedia</td>
                <td>Sistem otomatis mematikan tombol pinjam apabila stok buku tidak tersedia</td>
                <td>Sesuai harapan</td>
                <td>Valid</td>
        </table>
        <br>
        <li><strong>Tahap Design</strong></li><br>
        <ol>
            <li>Use Case Diagram</li> 
            <p> Use Case Diagram merupakan daftar aksi atau tahapan yang mendefinisikan interaksi antara aktor dan sistem untuk mencapai suatu tujuan. Berikut adalah <i>Use case diagram</i> sistem informasi
            Perpustakaan Kelompok 1:</p>
            <img src="sources/Use Case Diagram.png" style="width: 460px; height: 500px;">
            <p>Gambar 4. Use Case Diagram</p><br>
            <p>Pada gambar di atas terdapat tiga aktor yaitu:</p>
            <ol>
                <li>Anggota<br>Yaitu siswa/siswi yang telah terdaftar sebagai anggota perpustakaan. Anggota dapat melihat data buku yang tersedia di perpustakaan dan melihat transaksi peminjaman buku.</li>
                <li>Operator<br>Yaitu bagian yang mempunyai akses penuh untuk mengelola data buku,  peminjaman dan pengembalian buku, dan data anggota.</li>
                <li>Admin<br>Yaitu bagian yang hanya bisa melihat data buku dan anggota serta mengelola data operator.</li>
            </ol>
            <li>Activity Diagram</li>
                <p>Activity Diagram merupakan rancangan aliran aktivitas atau aliran kerja dalam sebuah sistem yang akan dijalankan. 
                    Activity Diagram juga digunakan untuk mendefinisikan atau mengelompokan aluran tampilan dari sistem tersebut.
                    Dalam beberapa hal activity diagram memainkan peran mirip diagram alir, tetapi perbedaan
                    prinsip antara notasi diagram alir adalah activity diagram mendukung <i>behavior paralel.</i> Activity Diagram yang 
                    ada pada sistem informasi Perpustakaan Kelompok 1 adalah sebagai berikut:</p><br>
                <ol type="a">
                    <li>Admin</li><br>
                    <img src="sources/Activity Diagram-Admin.png" style="width: 410px; height: 480px;">
                    <p>Gambar 5. Activity Diagram Admin - mengelola data pelamar</p><br>
                    <p>Activity diagram yang ditampilkan pada gambar di atas adalah proses pendaftaran seorang operator yang dilakukan oleh admin.</p><br>
                    <li>Operator</li><br>
                    <img src="sources/Activity Diagram-Operator.png" style="width: 410px; height: 480px;">
                    <p>Gambar 6. Activity Diagram Operator</p>
                    <br><img src="sources/Activity Diagram-Operator (Pengembalian).png" style="width: 410px; height: 480px;">
                    <p>Gambar 7. Activity Diagram Operator - Pengembalian</p><br>
                    <li>Anggota</li><br>
                    <img src="sources/Activity Diagram-Anggota.png" style="width: 410px; height: 480px;">
                    <p>Gambar 8. Activity Diagram Anggota - Pendaftaran</p> 
                    <br><img src="sources/Activity Diagram-Anggota (Peminjaman).png" style="width: 410px; height: 480px;">
                    <p>Gambar 9. Activity Diagram Anggota - Peminjaman</p><br>
                </ol>
            <li>Desain User Interface</li>
            <p>Desain User Interface (UI) adalah proses yang digunakan desainer untuk membuat tampilan dalam perangkat lunak atau perangkat terkomputerisasi, dengan fokus pada tampilan atau gaya.</p>
                <ol type="a">
                    <li>UI Halaman Login</li>
                    <img src="sources/login.png">
                    <p>Gambar 10. Desain Interface pada halaman Login.</p>
                    <li>UI Halaman Admin</li>
                    <img src="sources/admin.png">
                    <p>Gambar 11. Desain Interface pada halaman Admin.</p>
                    <li>UI Halaman Operator</li>
                    <img src="sources/operator.png">
                    <p>Gambar 12. Desain Interface pada halaman Operator.</p>
                    <li>UI Halaman Anggota</li>
                    <img src="sources/anggota.png">
                    <p>Gambar 13. Desain Interface pada halaman Anggota.</p>
                </ol>
        </ol>
    </ol>
    
</body>
</html>