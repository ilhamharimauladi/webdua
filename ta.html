<?php
include("header.php");
include("menu.php");
require_once("config.php");

// $sql = "SELECT * FROM ta";
$sql = "SELECT 
	        ta.id, ta.nota, ta.judul, mahasiswa.nama as mahasiswa, dosen.nama as pembimbing
        FROM
	        ta 
            LEFT JOIN mahasiswa ON mahasiswa.id = ta.mahasiswa
            LEFT JOIN dosen ON dosen.id = ta.pembimbing";

$query = mysqli_query($koneksi, $sql);
?>

<h2 align="center">Data Tugas Akhir</h2>
<p><a href="ta_add.php" class="btn btn-primary">Tambah Data</a></p>
<!-- <table class="table table-striped"> -->
<table class="display" id="myTable">
    <thead>
        <tr>
        <th>No. TA</th>
        <th>Judul</th>
        <th>Mahasiswa</th>
        <th>Pembimbing</th>
        <th>Opsi</th>
        </tr>
    </thead>
    <tbody>
        <?php
        while($data = mysqli_fetch_assoc($query)){
            echo "<tr>";
            echo "<td>". $data['nota'] ."</td>";
            echo "<td>". $data['judul'] ."</td>";
            echo "<td>". $data['mahasiswa'] ."</td>";
            echo "<td>". $data['pembimbing'] ."</td>";
            echo "<td>
                <a href='ta_edit.php?id=$data[id]' class='btn btn-warning'>Edit</a>
                <a href='ta_del.php?id=".$data['id']."' class='btn btn-danger' onclick=\"return confirm('Apakah anda yakin ingin menghapus data ini?');\">Hapus</a>
            </td>";
            echo "</tr>";
        }
        ?>
    </tbody>
</table>

<?php
include("footer.php");
?>