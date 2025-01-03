<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil dan Materi Perangkat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 1000px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header h1 {
            color: #5a5a8a;
        }

        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            gap: 20px;
        }

        .profile img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 2px solid #ddd;
        }

        .profile-info {
            font-size: 1.2rem;
        }

        .profile-info h2 {
            margin: 0 0 10px;
            font-size: 1.5rem;
        }

        .profile-info p {
            margin: 5px 0;
        }

        .content {
            margin-top: 30px;
        }

        .content h2 {
            text-align: center;
            color: #5a5a8a;
            margin-bottom: 20px;
        }

        .content .section {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
        }

        .content .section div {
            flex: 1;
            padding: 20px;
            background: #fde4f3;
            border-radius: 8px;
        }

        .content .section div h3 {
            margin-bottom: 10px;
            color: #333;
        }

        .content .image-section {
            text-align: center;
            margin: 20px 0;
        }

        .content .image-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .content .links {
            text-align: center;
        }

        .content .links a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background-color: #fde4f3;
            color: #5a5a8a;
            text-decoration: none;
            border-radius: 8px;
        }

        .content .links a:hover {
            background-color: #f9d8e8;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9rem;
            color: #aaa;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Materi: Switch</h1>
        </div>

        <div class="profile">
            <img src="fotoprofile.jpg" alt="Foto Profil">
            <div class="profile-info">
                <h2>Nama Lengkap: Clarissa Gita Maharani</h2>
                <p>NIM: 607012400048</p>
                <p>Mata Kuliah: Jaringan Komputer</p>
            </div>
        </div>

        <div class="content">
            <div class="section">
                <div>
                    <h3>Pengertian Switch</h3>
                    <p>Switch adalah perangkat jaringan yang digunakan untuk menghubungkan perangkat-perangkat dalam suatu jaringan lokal (LAN). Fungsi switch adalah meneruskan paket data antara perangkat-perangkat yang terhubung ke switch tersebut. Switch bekerja pada lapisan data link (layer 2) dalam OSI Layer dan mampu melakukan pengiriman data berdasarkan alamat MAC (Media Access Control).</p>
                </div>
                <div>
                    <h3>Fungsi Switch</h3>
                    <p>Switch menghubungkan perangkat dalam jaringan lokal (LAN) dan meneruskan paket data dengan efisien. Beberapa fungsi utama switch adalah:</p>
                    <ul>
                        <li>Meneruskan paket data berdasarkan alamat MAC tujuan.</li>
                        <li>Segmentasi jaringan dengan VLAN.</li>
                        <li>Meningkatkan kinerja jaringan dengan mengurangi tabrakan data.</li>
                        <li>Memfilter dan mengontrol lalu lintas broadcast.</li>
                        <li>Penyampaian paket data dengan cepat.</li>
                    </ul>
                </div>
            </div>

            <div class="image-section">
                <img src="switch.jpg" alt="Gambar Switch">
                <p>Contoh gambar perangkat Switch.</p>
            </div>

            <div class="links">
                <a href="https://it.telkomuniversity.ac.id/" target="_blank">sumber materi</a>
                <a href="https://drive.google.com/file/d/1JXdwesV9WJ7UlDgbISn9PY1_NCqEs56o/view?usp=drive_link" download>Tutorial Hosting</a>
                <a href="https://drive.google.com/file/d/1fKHjQEBPqT3cd0gnP2lqjhm2KByPd2gk/view?usp=drive_link" download>Isi web</a>

            </div>
        </div>

        <div class="footer">
            <p>&copy; 2024 ClarissaGita. All Rights Reserved.</p>
        </div>
    </div>
</body>
</html>

