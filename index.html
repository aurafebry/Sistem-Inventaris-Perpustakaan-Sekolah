# Sistem-Inventaris-Perpustakaan-Sekolah
// koneksi.php - Menghubungkan ke database MySQL
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "inventaris_perpus";

$conn = mysqli_connect($servername, $username, $password, $dbname);

if (!$conn) {
  die("Koneksi gagal: " . mysqli_connect_error());
}
?>
// index.php - Halaman Utama untuk Menampilkan Daftar Inventaris
include 'koneksi.php';

// Mengambil data dari database
$sql = "SELECT * FROM barang";
$result = mysqli_query($conn, $sql);
?>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>SIPS - Sistem Inventaris Perpustakaan Sekolah</title>
    <style>
        /* CSS Sederhana untuk Styling Tabel */
        body { font-family: sans-serif; background-color: #f4f7f6; margin: 0; padding: 20px; }
        .header { background-color: #2c3e50; color: white; padding: 15px; text-align: center; margin-bottom: 20px; }
        table { width: 100%; border-collapse: collapse; background-color: white; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #3498db; color: white; }
        tr:nth-child(even) { background-color: #f2f2f2; }
        .btn-add { background-color: #e67e22; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px; float: right; margin-bottom: 15px; }
    </style>
</head>
<body>

<div class="header">
    <h1>Sistem Inventaris Perpustakaan Sekolah (SIPS)</h1>
</div>

<a href="tambah_barang.php" class="btn-add">+ Tambah Barang Baru</a>

<h2>Daftar Inventaris Barang</h2>

<table>
    <thead>
        <tr>
            <th>Kode Barang</th>
            <th>Nama Barang</th>
            <th>Kategori</th>
            <th>Status</th>
        </tr>
    </thead>
    <tbody>
        <?php
        // Menampilkan data per baris
        if (mysqli_num_rows($result) > 0) {
            while($row = mysqli_fetch_assoc($result)) {
                echo "<tr>";
                echo "<td>" . $row["kode_barang"] . "</td>";
                echo "<td>" . $row["nama_barang"] . "</td>";
                echo "<td>" . $row["kategori"] . "</td>";
                echo "<td>" . $row["lokasi"] . "</td>";
                echo "<td>" . $row["status"] . "</td>";
                echo "</tr>";
            }
        } else {
            echo "<tr><td colspan='5'>Tidak ada data barang.</td></tr>";
        }
        mysqli_close($conn);
        ?>
    </tbody>
</table>

</body>
</html>
