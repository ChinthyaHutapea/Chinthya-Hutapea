<html>
    <head>
        <title>(Modul nomor 1)</title>
    </head>
    <body>
        <div>
            <!-- content 1 -->
            <div>
                <a href="https://library.usu.ac.id/">
                <img src="Perpustakaan Universitas Sumatera Utara.jpeg">
                <p>Perpustakaan Universitas Sumatera Utara</p>
                </a>
            </div>
            <!-- content 1 finish -->
        </div>
        <div>
            <!--content 2-->
            <audio controls>
                <source src="Coldplay Yellow.mp3"
            </audio>
        </div>
        <div>
            <!--contenct 3-->
            <video width="400" height="400"controls>
                <source src="video coldplay.mp4">
            </video>
        </div>
        <h2>Formulir Anggota Perpustakaan Universitas Sumatera Utara</h2>

 <form action="/submit.php"method="post">
    <label for="nama">Nama:</label><br>
    <input type="text" id="nama" name="nama" required><br>

    <label for="NIM">NIM</label><br>
    <input type="text" id="nim" name="nim" required><br>

    <label for="alamat">Alamat:</label><br>
    <input type="alamat" name="alamat" required><br>

    <label for="jenis kelamin">Jenis Kelamin:</label><br>
    <input type="jenis kelamin" name="jenis kelamin" required><br>

    <label for="email">Email:</label><br>
    <input type="email" name="email" required><br>

    <label for="no.hp">No.HP:</label><br>
    <input type="no.hp" name="no.hp" required><br>

    <label for="tempat lahir">Tempat Lahir</label><br>
    <input type="tempat lahir" name="tempat lahir" required><br>

    <label for="tanggal lahir">Tanggal Lahir:</label><br>
    <input type="date" id="tanggal lahir" name="tanggal lahir"required><br>

    <input type="submit" value="kirim">

    <div id="book colection">
        <h2>book colection</h2>
        <table border="1">
            <tr>
                <th>judul buku</th>
                <th>penulis</th>
                <th>tahun terbit</th>
                <th>no.panggil</th>
            </tr>
            <tr>
                <td>Perahu Kertas</td>
                <td>Dee</td>
                <td>2009</td>
                <td>813 Per</td>
            </tr>
            <tr>
                <td>Laut Bercerita</td>
                <td>Leila S.Chudori</td>
                <td>2017</td>
                <td>899.221 3 LEI l</td>
            </tr>
        </table>
    </div>
    <div id="form pemesanan">
        <h2>reservation form</h2>
        <form action="proses pemesanan.php" method="POST">
            <label for="judul">judul buku</label><br>
            <input type="text" id="judul" name="judul"><br>
            <label for="nama">nama:</label><br>
            <input type="text" id="nama" name="nama"><br>
            <label for="NIM">NIM</label><br>
            <textarea id="NIM" name="NIM"></textarea><br>
            <input type="sumbit" falue="sumbit">
        </form>
    </div>
    
    <div id="form perpanjangan">
        <h2>Renewal Form</h2>
        <form action="proses perpanjangan.php" method="POST">
            <label for="kode buku">kode buku:</label><br>
            <input type="text" id="kode buku" name="kode buku"><br>
            <label for="nama">nama peminjam:</label><br>
            <input type="text" id="nama" name="nama"><br>
            <label for="NIM">NIM:</label><br>
            <input type="NIM" id="NIM" NAME="NIM"><br>
            <input type="sumbit" value="sumbit">                        
         </form>
    </div>
    </body>
</html>
