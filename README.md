<!DOCTYPE html>
<html>
<head>
    <title>Belajar Membuat Form</title>
</head>
<body>
<form action="formulir.html" method="get">
Nama: <input type="text" name="nama" value="" />
<br />

Password: <input type="password" name="password" />
<br />
Jenis Kelamin :
<input type="radio" name="jenis_kelamin" value="laki-laki" />
Laki - Laki
<input type="radio" name="jenis_kelamin" value="perempuan" />
Perempuan
<br />
Hobi: <input type="checkbox" name="hobi_baca" /> Membaca Buku
<input type="checkbox" name="hobi_nulis" /> Menulis
<input type="checkbox" name="hobi_mancing" /> Memancing
<br />
Asal Kota:
    <select name="asal_kota">
        <option value="Kota Jakarta"> Jakarta</option>
        <option value="Kota Bandung">Bandung</option>
        <option value="Kota Semarang">Semarang</option>
        <option value="Kota Jombang">Jombang</option>
    </select>
<br />
<h4>Manakah Logo Unipdu?</h4>
<table border="1">
    <tr>
        <td>
            <input type="radio"/>
            <img src="logo unipdu.jpg" width="200">
        </td>
        <td>
            <input type="radio"/>
            <img src="Contong.jpg" width="200">
        </td>
    </tr>
    <tr>
        <td>
            <input type="radio"/>
            <img src="logo jatim.jpg" width="200">
        </td>
        <td>
            <input type="radio"/>
            <img src="OIP.jpg" width="200">
        </td>
    </tr>
</table>
<br />
Komentar Anda:
<textarea name="komentar" cols="20" rows="5">
    SELAMAT MENCOBA
</textarea>
<br />
<input type="submit" value="Mulai Proses!">
</form>
</body>
</html>
