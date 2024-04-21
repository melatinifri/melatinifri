<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GITHUB</title>
    <style type-"text/css">
        h2{color: #02509f;
            font-family: Segoe Script;
        }
    </style>
    <link rel="stylesheet" href="external background.css">

</head>
<body>
    <h1 style="color: #f46a8d;
                    font-family: Segoe Script;">Tugas Modul 1</h1>
    <h2>1. Daftar Berbagai Perpustakaan</h2>
    <p>Silakan klik link di bawah untuk melihat daftar perpustakaan beserta profil dan gambar perpustakaan.</p>
    <a href="PROFIL.html">Profil Perpustakaan Universitas di Indonesia</a>

    <h2>2. Penggunaan Audio dan Video</h2>
    <p><b>- Audio</b></p>
    <p> Lover - Taylor Swift</p>
    <audio controls>
    <source src="Taylor Swift - Lover (Official Music Video).mp3"type="audio/mpeg">
    </audio>
    <p><b>- Video</b></p>
    <p> Ramadhan - Maher Zain</p>
    <video controls width="320" height="240">
    <source src="Maher Zain - Ramadan ( Lyrics ) Official Video.mp4"type="video/mp4">
    </video>

    <h2>3. Kelebihan HTML5 dan Penerapannya</h2>
    <p style="color: #5d3a6f;
                    font-family: Calibri;"><b>Kelebihan HTML 5</b></p>
    <p> - Penanganan error yang lebih baik
        <p> - Memiliki Syntax yang lebih mudah
        <p> - Terdapat dukungan untuk konten Audio dan Video
        <p> - Kemudahan membuatan website
        <p> - Penyimpanan informasi secara lokal</p>
    
    <p style="color: #5d3a6f;
        font-family: Calibri;"><b>Penerapan HTML 5 pada Web Perpustakaan</b></p>
    <p> - Menggunakan elemen-elemen baru HTML5 seperti < header >, < footer >, dan < nav > untuk membuat tata letak yang lebih terstruktur dan intuitif.
        <p> - Memanfaatkan fitur audio dan video HTML5 untuk menyediakan pratinjau atau konten multimedia yang lebih kaya.
        <p> - Membangun visualisasi data interaktif menggunakan elemen < canvas > atau < svg >.
        <p> - Memanfaatkan penyimpanan lokal HTML5 untuk menyimpan preferensi pengguna, riwayat pencarian, atau bahkan cache dari buku-buku yang sering diakses.
        <p> - Memungkinkan aplikasi web Perpustakaan untuk tetap dapat diakses dan digunakan oleh pengguna meskipun mereka offline, dengan memanfaatkan cache aplikasi web HTML5.</p>
    

<h1 style="color: #f46a8d;
                    font-family: Segoe Script;">Tugas Modul 2</h1>
        <h2>1. Formulir Keanggotan Perpustakaan</h2>
<table border="1" >

	<title> Form Anggota Perpustakaan </title>

<th colspan="2"> Formulir Anggota Perpustakaan Program Studi Perpustakaan dan Sains Informasi </th>

	<tr>
		<td> Nama			
		<br> NIM 			
		<br> Alamat			
		<br> Jenis Kelamin 	
		<br> E-mail 			
		<br> No. HP			
		<br> Tempat Lahir 	
		<br> Tanggal Lahir 	</td>
		
		<td> Melati Nifri Bahri
		<br> 210709009
		<br> Jl. Kenangan Kita
		<br> Perempuan
		<br> melamelati29@students.usu.ac.id
		<br> 085761613939
		<br> Medan
		<br> 29 Mei 2003
		</td>
		
</tr>
		
</table>

<h2>2. Tabel Koleksi Buku</h2>
<table border="1">
    <tr>
        <td style="text-align:center"> <b> Judul </b> </td>
        <td style="text-align:center"> <b> No. Klasifikasi </b> </td>
        <td style="text-align:center"> <b> No. Panggil </b> </td>
        <td style="text-align:center"> <b> Pengarang </b> </td>
        <td style="text-align:center"> <b> Subjek </b> </td>
        <td style="text-align:center"> <b> Nama Penerbit </b> </td>
        <td style="text-align:center"> <b> Tahun Terbit </b> </td> 
    </tr>

    <tr>
        <td> Little Women Little Men Jo's Boys </td>
        <td> 808.83 </td>
        <td> 808.83 Alc l </td>
        <td> Alcott, Louisa May </td>
        <td> American Fiction In English</td>
        <td> The Library Of America </td>
        <td> 2005 </td>
    </tr>
    
        <td> Da Vinci Code decoded : menguak kebenaran dibalik fiksi da vinci code </td>
        <td> 808.2 </td>
        <td> 808.2 Lun d</td>
        <td> Lunn, Martin</td>
        <td> FICTION</td>
        <td> U.S. Development of Health, Education </td>
        <td> 2005 </td>
	</tr>
		<td> Berguru kepada sastrawan dunia : buku wajib menulis fiksi </td>
        <td> 808.066 813 </td>
        <td> 808.066 813 Nov b</td>
        <td> Novakovich, Josip </td>
        <td> FICTION-AUTHORSHIP </td>
        <td> Kabushiki Kaisya </td>
        <td> 2003</td>
    </tr>
    </table>

<h2>3. Formulir Pemesanan Buku</h2>
<table>
    <tr>
       <td>Nama Customer</td>
        <td><input type ="text"></td>
    </tr>
      <tr>
        <td>Jenis Kelamin</td>
        <td><input type="radio" name="jk"> laki-laki
            <input type="radio" name="jk"> perempuan 
        </td>
    </tr>
    <tr>
           <td>Tanggal Pemesanan</td>
           <td><input type="date" name="tanggal"/></td>
  </tr>
  <tr>
        <td> <label>Alamat</legend>
          <td> <input type="text" name="name"/></td>
      </tr>
      <tr>
          <td><label>Judul Buku</label> </td>
          <td><input type="text" name="name"/></td>
      </tr>
    <tr>
      <td>	<label>Pengarang</label></td>
      <td> <input type="text" name="name"/></td>
  </tr>
  <tr>
          <td><label>Jumlah Buku</label></td>
          <td><input type="text" name="name"/></td>
      <td></td>
      <td>
            <input type="submit" value="Submit">
       </td>
   </tr>
  </table>
   </p>
  </fieldset>
  </form>

  <title>FORMULIR PERPANJANGAN BUKU</title>
</head>
</body>
<h2>4. Formulir Perpanjangan Peminjaman Buku</h2>
	<p> Pengajuan perpanjangan masa pinjam buku secara daring hanya akan diproses pada hari dan jam kerja (Senin sampai Jumat pukul 08.00-15.30), dengan ketentuan bahwa peminjaman belum melebihi batas waktu pengembalian yang ditetapkan. Selain itu, perpanjangan hanya diperbolehkan sekali untuk setiap buku yang dipinjam. </p>
	
	 <form action="" method="POST">
        <fieldset>
        <p>
   <table>
      <tr>
         <td>Member ID</td>
         <td><input type ="text"></td>
      </tr>
        <tr>
            <td> Kode Eksemplar</td>
            <td><input type = "text"></td>
            </tr> 
            <tr>
              <td></td>
           <td><input type="submit" value="Submit">
               <input type="reset" value="Reset">
            </td>
        </tr>
      </table>
        </p>
 </fieldset>
</body>

<h1 style="color: #f46a8d;
                    font-family: Segoe Script;">Tugas Modul 3</h1>

<p style="color: #5d3a6f;
                    font-family: Times New Roman;"><b>HTML dan CSS</b></p>

<p>HTML merupakan singkatan dari Hypertext Markup Language, yang merupakan bahasa dasar untuk membuat dan merancang halaman web. HTML digunakan untuk struktur dasar dari sebuah halaman web, menentukan bagaimana konten seperti teks, gambar, dan media lainnya akan ditampilkan dan diatur. Secara umum, HTML terdiri dari serangkaian elemen atau tag yang memberi petunjuk kepada browser tentang bagaimana halaman web harus ditampilkan.
<p>CSS, atau Cascading Style Sheets, adalah bahasa yang digunakan untuk mengatur tampilan dan tata letak elemen-elemen HTML di dalam halaman web. Dengan CSS dapat mengatur warna, ukuran, jenis font, posisi, dan banyak lagi atribut-atribut tampilan lainnya. Misalnya, menggunakan CSS untuk membuat latar belakang transparan, membuat elemen mengambang di atas halaman, mengatur jarak antara elemen-elemen, dan mengubah tampilan saat pengguna berinteraksi dengan halaman. CSS memungkinkan untuk membuat halaman web yang lebih menarik, interaktif, dan mudah dibaca bagi pengguna.</p>

</body>
</html>
