# Transmisi-Penyimpanan-Data
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formatif Teknologi Digital</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; padding: 20px; }
        .hidden { display: none; }
        label { display: block; margin: 10px 0 5px; }
        button { margin-top: 15px; padding: 10px; }
    </style>
</head>
<body>
    <h2>Formatif Teknologi Digital</h2>
    
    <div id="startSection">
        <label for="name">Masukkan Nama Anda:</label>
        <input type="text" id="name" required>
        <button onclick="startTest()">Mulai Tes</button>
    </div>

    <div id="testSection" class="hidden">
        <h3>Soal Pilihan Ganda</h3><br>
	<h4><b>Setiap soal bernilai 5 poin</b></h4>
        <form id="testForm">
            <ol>
                <li>
                    <p>'Proses untuk melakukan pengiriman data dari salah satu sumber data ke penerima data yang dapat berlangsung satu arah maupun dua arah' adalah pengertian dari....</p>
                    <label><input type="radio" name="q1" value="Transmisi data"> Transmisi data</label>
                    <label><input type="radio" name="q1" value="Bilangan transmisi"> Bilangan transmisi</label>
                    <label><input type="radio" name="q1" value="Penyimpanan data"> Penyimpanan data</label>
                </li>
                <li>
                    <p>'Gelombang-gelombang elektronik yang bervariasi dan secara kontinu ditransmisikan melalui beragam media' adalah pengertian dari....</p>
                    <label><input type="radio" name="q2" value="sinyal digital"> sinyal digital</label>
                    <label><input type="radio" name="q2" value="sinyal analog"> sinyal analog</label>
                    <label><input type="radio" name="q2" value="sinyal data"> sinyal data</label>
                </li>
 		<li>
                    <p>'Data yang memiliki deretan nilai yang berbeda dan memiliki cara sendiri' adalah pengertian dari....</p>
                    <label><input type="radio" name="q3" value="data digital"> data digital</label>
                    <label><input type="radio" name="q3" value="data analog"> data analog</label>
                    <label><input type="radio" name="q3" value="sinyal data"> sinyal data</label>
                </li>
		<li>
                    <p>Jenis kabel yang menggunakan cahaya untuk transmisi data adalah....</p>
                    <label><input type="radio" name="q4" value="Pilin"> Pilin</label>
                    <label><input type="radio" name="q4" value="Koaksial"> Koaksial</label>
                    <label><input type="radio" name="q4" value="Serat Optik"> Serat Optik</label>
                </li>
		<li>
                    <p>Alat bantu yang biasa digunakan dalam transmisi data nirkabel disebut....</p>
                    <label><input type="radio" name="q5" value="Transceiver"> Transceiver</label>
                    <label><input type="radio" name="q5" value="Transmiter"> Transmiter</label>
                    <label><input type="radio" name="q5" value="Transistor"> Transistor</label>
                </li>
		<li>
                    <p>Media penyimpanan apa yang mengkodekan dan membaca data dengan pemantulan seberkas laser untuk memutar dan merekam data?</p>
                    <label><input type="radio" name="q6" value="Pita Magnetik"> Pita Magnetik</label>
                    <label><input type="radio" name="q6" value="Flashdisk"> Flashdisk</label>
                    <label><input type="radio" name="q6" value="Compact Disk"> Compact Disk</label>
                </li>
		<li>
                    <p>Media penyimpanan apa yang bentuknya berupa penyimpanan data yang dilakukan di server yang berada di luar lokasi pengguna?</p>
                    <label><input type="radio" name="q7" value="Compact Disk"> Compact Disk</label>
                    <label><input type="radio" name="q7" value="Memory Card"> Memory Card</label>
                    <label><input type="radio" name="q7" value="Cloud Storage"> Cloud Storage</label>
                </li>
		<li>
                    <p>Bagaimana cara kerja transmisi data dengan kabel pilin?</p>
                    <label><input type="radio" name="q8" value="Transmisi data melalui sinyal listrik"> Transmisi data melalui sinyal listrik</label>
                    <label><input type="radio" name="q8" value="Transmisi data melalui jaringan komputer"> Transmisi data melalui jaringan komputer</label>
                    <label><input type="radio" name="q8" value="Transmisi data melalui gelombang cahaya"> Transmisi data melalui gelombang cahaya</label>
                </li>
		<li>
                    <p>Berikut ini yang merupakan contoh transmisi data satu arah adalah....</p>
                    <label><input type="radio" name="q9" value="komunikasi telepon"> komunikasi telepon</label>
                    <label><input type="radio" name="q9" value="walkie-talkie"> walkie-talkie</label>
                    <label><input type="radio" name="q9" value="siaran televisi"> siaran televisi</label>
                </li>
		<li>
                    <p>Bilangan transmisi berbasis 16 adalah....</p>
                    <label><input type="radio" name="q10" value="binner"> binner</label>
                    <label><input type="radio" name="q10" value="desimal"> desimal</label>
                    <label><input type="radio" name="q10" value="heksadesimal"> heksadesimal</label>
                </li>
		<li>
                    <p>Apa fungsi media penyimpanan data?</p>
                    <label><input type="radio" name="q11" value="Agar data tidak hilang"> Agar data tidak hilang</label>
                    <label><input type="radio" name="q11" value="Agar data dapat diakses dan digunakan kembali"> Agar data dapat diakses dan digunakan kembali</label>
                    <label><input type="radio" name="q11" value="Agar lebih mudah untuk mencari dan menggunakan data"> Agar lebih mudah untuk mencari dan menggunakan data</label>
                </li>
		<li>
                    <p>Berikut ini yang merupakan jenis sinyal transmisi data, kecuali ....</p>
                    <label><input type="radio" name="q12" value="sinyal digital"> sinyal digital</label>
                    <label><input type="radio" name="q12" value="sinyal analog"> sinyal analog</label>
                    <label><input type="radio" name="q12" value="sinyal data"> sinyal data</label>
                </li>
		<li>
                    <p>Apa nama bilangan transmisi yang basisnya terdiri dari 0,1,2,3,4,5,6,7?</p>
                    <label><input type="radio" name="q13" value="Bilangan Binner"> Bilangan Binner</label>
                    <label><input type="radio" name="q13" value="Bilangan Oktal"> Bilangan Oktal</label>
                    <label><input type="radio" name="q13" value="Bilangan Heksadesimal"> Bilangan Heksadesimal</label>
                </li>
		<li>
                    <p>Dari 3 jenis kabel transmisi data yang dipelajari, jenis kabel yang terdiri dari dua macam konduktor yang dipisahkan oleh isolator adalah ....</p>
                    <label><input type="radio" name="q14" value="kabel pilin"> kabel pilin</label>
                    <label><input type="radio" name="q14" value="koaksial"> koaksial</label>
                    <label><input type="radio" name="q14" value="serat optik"> serat optik</label>
                </li>
            </ol>

            <h3>Soal Esai</h3><br>
		<h4><b>Setiap soal bernilai 10 poin</b></h4>
            <ol>
                <li><label>Jelaskan pemahamanmu mengenai transmisi data!</label><textarea name="essay1" cols="200" rows="10"></textarea></li>
                <li><label>Jelaskan pemahamanmu mengenai salah satu media transmisi data!</label><textarea name="essay2" cols="200" rows="10"></textarea></li>
		<li><label>Jelaskan pemahamanmu mengenai salah satu media penyimpanan data!</label><textarea name="essay3" cols="200" rows="10"></textarea></li>
            </ol>

            <button type="submit">Kirim Jawaban</button>
        </form>
    </div>

    <script>
        let isTestActive = false;

        function startTest() {
            const name = document.getElementById("name").value.trim();
            if (name === "") {
                alert("Harap masukkan nama Anda!");
                return;
            }
            sessionStorage.setItem("testActive", "true");
            sessionStorage.setItem("userName", name);

            document.getElementById("startSection").classList.add("hidden");
            document.getElementById("testSection").classList.remove("hidden");
            isTestActive = true;
        }

        function checkFocus() {
            if (isTestActive && document.hidden) {
                alert("Anda keluar dari tab! Tes akan direset.");
                sessionStorage.removeItem("testActive");
                location.reload();
            }
        }

        document.addEventListener("visibilitychange", checkFocus);

        document.getElementById("testForm").addEventListener("submit", function(event) {
            event.preventDefault();

            let formData = new FormData(this);
            formData.append("name", sessionStorage.getItem("userName"));

            let formObj = {};
            formData.forEach((value, key) => { formObj[key] = value; });

            fetch("https://prod-51.southeastasia.logic.azure.com:443/workflows/06fc5055c8124cc587df0f4f18422bbe/triggers/manual/paths/invoke?api-version=2016-06-01&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig=VnJpqCeur9KFPms9gD2CsyFPTeEfgh0rkxk0uvnwK58", {
                method: "POST",
                headers: { "Content-Type": "application/json" },
                body: JSON.stringify(formObj)
            }).then(response => {
                if (response.ok) {
                    alert("Tes berhasil dikirim!");
                    sessionStorage.removeItem("testActive");
                    location.reload();
                } else {
                    alert("Gagal mengirim tes. Periksa koneksi internet Anda.");
                }
            }).catch(error => {
                alert("Terjadi kesalahan: " + error);
            });
        });
    </script>
</body>
</html>
