
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hisbiyah Nur Rochmah | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            background: #0b1020;
            color: white;
            line-height: 1.7;
        }

        header {
            background: #111a30;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
        }

        header h2 {
            color: #a99aff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }

        nav a:hover {
            color: #65d6c4;
        }

        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 60px 10%;
            gap: 40px;
        }

        .hero h1 {
            font-size: 45px;
            margin: 15px 0;
        }

        .hero h1 span {
            color: #a99aff;
        }

        .hero p {
            color: #b9c1d8;
            max-width: 550px;
        }

        .profile {
            width: 250px;
            height: 250px;
            border-radius: 30px;
            background: linear-gradient(135deg, #8272e9, #50cbb9);
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 75px;
            font-weight: bold;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: #a99aff;
            color: #101329;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 80px 10%;
        }

        section h2 {
            color: #a99aff;
            font-size: 30px;
            margin-bottom: 25px;
        }

        .card {
            background: #151e35;
            padding: 25px;
            border-radius: 18px;
            margin-bottom: 20px;
            border: 1px solid #29334c;
        }

        .card h3 {
            margin-bottom: 10px;
            color: #65d6c4;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #111a30;
            color: #b9c1d8;
        }

        @media (max-width: 700px) {
            .hero {
                flex-direction: column;
                text-align: center;
            }

            .hero h1 {
                font-size: 34px;
            }

            nav a {
                margin-left: 8px;
                font-size: 12px;
            }

            .skills {
                grid-template-columns: 1fr;
            }

            .profile {
                width: 190px;
                height: 190px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>HNR.</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <div>
            <p>WELCOME TO MY PORTFOLIO</p>
            <h1>Halo, Saya<br>
                <span>Hisbiyah Nur Rochmah</span>
            </h1>
            <p>
                Saya adalah siswi SMK Negeri 2 Lamongan
                jurusan Teknik Komputer dan Jaringan.
                Saya tertarik mempelajari teknologi dan
                dunia komputer.
            </p>
            <a href="#about" class="button">Kenali Saya</a>
        </div>

        <div class="profile">HN</div>
    </section>

    <section id="about">
        <h2>Tentang Saya</h2>
        <div class="card">
            <h3>Perkenalan</h3>
            <p>
                Halo! Nama saya Hisbiyah Nur Rochmah.
                Saya merupakan siswi SMK Negeri 2 Lamongan
                dari jurusan Teknik Komputer dan Jaringan.
                Saya ingin terus belajar, mengembangkan
                kemampuan, dan menambah pengalaman
                dalam bidang teknologi.
            </p>
            <br>
            <p><b>Nama:</b> Hisbiyah Nur Rochmah</p>
            <p><b>Sekolah:</b> SMK Negeri 2 Lamongan</p>
            <p><b>Jurusan:</b> Teknik Komputer dan Jaringan</p>
            <p><b>Status:</b> Pelajar</p>
        </div>
    </section>

    <section id="skills">
        <h2>Keahlian Saya</h2>

        <div class="skills">
            <div class="card">
                <h3>Komputer</h3>
                <p>Mempelajari perangkat keras dan perangkat lunak komputer.</p>
            </div>

            <div class="card">
                <h3>Jaringan</h3>
                <p>Mempelajari dasar jaringan komputer dan konektivitas.</p>
            </div>

            <div class="card">
                <h3>Teknologi</h3>
                <p>Terus mengeksplorasi perkembangan teknologi digital.</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>Proyek Saya</h2>

        <div class="card">
            <h3>Personal Portfolio Website</h3>
            <p>
                Membuat website portofolio pribadi
                menggunakan HTML dan CSS dengan
                GitHub Pages.
            </p>
        </div>

        <div class="card">
            <h3>Project Pembelajaran TKJ</h3>
            <p>
                Dokumentasi tugas dan kegiatan
                pembelajaran Teknik Komputer dan Jaringan.
            </p>
        </div>
    </section>

    <section id="contact">
        <h2>Hubungi Saya</h2>
        <div class="card">
            <p>Terima kasih sudah mengunjungi website portofolio saya!</p>
            <p>Salam kenal dan sampai jumpa.</p>
        </div>
    </section>

    <footer>
        <p>
            &copy; 2026 Hisbiyah Nur Rochmah.
            All Rights Reserved.
        </p>
    </footer>

</body>
</html>
# hisbiyahnurrochmah.github.io
Portofolio Digital Pribadi
