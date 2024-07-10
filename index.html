<?php
session_start();
include("header.php");
include("menu.php");
include_once("config.php");

// Check if the user is logged in
if (!isset($_SESSION['email']) || empty($_SESSION['email'])) {
    header("Location: login.php"); // Redirect to login page if not logged in
    exit();
}

$sql_mhs = "SELECT id FROM mahasiswa";
$query_mhs = mysqli_query($koneksi, $sql_mhs);
$jml_mhs = mysqli_num_rows($query_mhs); 

$sql_dosen = "SELECT id FROM dosen";
$query_dosen = mysqli_query($koneksi, $sql_dosen);
$jml_dosen = mysqli_num_rows($query_dosen); 

$sql_ta = "SELECT id FROM ta";
$query_ta = mysqli_query($koneksi, $sql_ta);
$jml_ta = mysqli_num_rows($query_ta); 

$email = $_SESSION['email'];
$sql_user = "SELECT name FROM users WHERE email = '$email'";
$query_user = mysqli_query($koneksi, $sql_user);
if ($row = mysqli_fetch_assoc($query_user)) {
    $username = $row['name'];
} else {
    $username = "Pengguna";
}

?>
<br>
<br>
<h2 align="center">Selamat datang, <?php echo $username; ?></h2>
<br>

<div class="row">
    <div class="col-md-4 col-sm-6">
        <div class="card">
            <div class="card-body">
                <h4 class="card-title">Mahasiswa</h4>
                <p class="card-text">Jumlah: <?=$jml_mhs;?></p>
                <a href="mahasiswa.php" class="btn btn-primary">Lihat</a>
            </div>
        </div>
    </div>
    <div class="col-md-4 col-sm-6">
        <div class="card">
            <div class="card-body">
                <h4 class="card-title">Dosen</h4>
                <p class="card-text">Jumlah: <?=$jml_dosen;?></p>
                <a href="dosen.php" class="btn btn-primary">Lihat</a>
            </div>
        </div>
    </div>
    <div class="col-md-4 col-sm-12">
        <div class="card">
            <div class="card-body">
                <h4 class="card-title">Tugas Akhir</h4>
                <p class="card-text">Jumlah: <?=$jml_ta;?> </p>
                <a href="ta.php" class="btn btn-primary">Lihat</a>
            </div>
        </div>
    </div>
</div>
