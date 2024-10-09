<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Identitas Diri</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-image: linear-gradient(to right, #00c6ff, #0072ff); /* Background gradient */
            margin: 0;
            padding: 0;
            color: #fff;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            background-color: rgba(0, 0, 0, 0.6); /* Background konten transparan */
            padding: 30px;
            border-radius: 15px; /* Sudut lebih melengkung */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4); /* Bayangan lebih kuat */
            text-align: center;
        }
        h1 {
            color: #00e5ff; /* Warna judul lebih cerah */
            font-size: 32px;
            margin-top: 0;
        }
        .info {
            margin-bottom: 20px;
            text-align: left;
        }
        .info strong {
            display: inline-block;
            width: 150px;
            color: #00e5ff; /* Warna label lebih cerah */
        }
        img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #00e5ff; /* Border foto lebih tebal */
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(255, 255, 255, 0.2); /* Bayangan pada gambar */
        }
        .education {
            text-align: left;
            margin-top: 30px;
        }
        .education p {
            color: #fff;
            background-color: rgba(255, 255, 255, 0.2); /* Background transparan untuk pendidikan */
            padding: 12px;
            border-radius: 8px;
            margin-bottom: 12px;
            font-style: italic;
        }
        /* Gaya untuk marquee */
        .marquee {
            margin-top: 20px;
            color: #00e5ff;
            font-size: 18px;
            font-weight: bold;
            overflow: hidden;
            white-space: nowrap;
        }
        .marquee span {
            display: inline-block;
            animation: marquee 10s linear infinite;
        }
        @keyframes marquee {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Tambahkan gambar di sini -->
        <img src="agus_marlina.jpg" alt="Foto Profil">

        <h1>Identitas Diri</h1>
        <div class="info">
            <strong>Nama:</strong> Agus Marlina Bt. Tanggo
        </div>
        <div class="info">
            <strong>NIM:</strong> 121230134
        </div>
        <div class="info">
            <strong>Prodi:</strong> Teknik Geomatika
        </div>
        <div class="info">
            <strong>Tempat, Tanggal Lahir:</strong> Semporna, 1 Agustus 2002
        </div>

        <h2 style="color: #00e5ff;">Riwayat Pendidikan</h2>
        <div class="education">
            <p>SMKN 1 Nunukan</p>
            <p>Institut Teknologi Sumatera</p>
        </div>

        <!-- Tambahkan tulisan bergerak -->
        <div class="marquee">
            <span>Selamat datang di halaman profil Agus Marlina Bt. Tanggo!</span>
        </div>
    </div>

</body>
</html>
