<?php
if(isset($_POST['simpan'])){
    $nota = $_POST['nota'];
    $judul = $_POST['judul'];
    $mahasiswa = $_POST['mahasiswa'];
    $pembimbing = $_POST['pembimbing'];

    require_once("config.php");

    $sql = "INSERT INTO ta(nota, judul, mahasiswa, pembimbing) VALUES('$nota', '$judul', $mahasiswa, $pembimbing)";
    $query = mysqli_query($koneksi, $sql);
    echo "Data sudah tersimpan. <a href='ta.php'>Lihat</a>";
}

include("header.php");
include("menu.php");
?>

<h2 align="center">Form Data Baru</h2>
<form action="" method="post">
    <label for="nota">No. TA</label>
    <input type="text" name="nota" class="form-control" required>
    <label for="judul">Judul</label>
    <input type="text" name="judul" class="form-control">
    <label for="mahasiswa">Mahasiswa</label>
    <select name="mahasiswa" class="form-control">
        <?php
            require_once("config.php");
            $sql = "SELECT id, nama from mahasiswa";
            $query = mysqli_query($koneksi, $sql);
            while($dmhs = mysqli_fetch_array($query)){
                echo "<option value='$dmhs[id]'>$dmhs[nama]</option>";
            }
        ?>
    </select>
    <label for="pembimbing">Pembimbing</label>
    <select name="pembimbing" class="form-control">
        <?php
            require_once("config.php");
            $sql = "SELECT id, nama from dosen";
            $query = mysqli_query($koneksi, $sql);
            while($ddosen = mysqli_fetch_array($query)){
                echo "<option value='$ddosen[id]'>$ddosen[nama]</option>";
            }
        ?>
    </select>
    <input type="submit" name="simpan" value="Simpan" class="mt-2 btn btn-primary">
</form>

<?php
include("footer.php");
?>