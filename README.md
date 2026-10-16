
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f7fb;
            color: #222;
            line-height: 1.6;
        }

        /* Navbar */
        nav {
            background-color: #172554;
            color: white;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            color: #93c5fd;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        nav a:hover {
            color: #93c5fd;
        }

        /* Bagian utama */
        .hero {
            min-height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #dbeafe, #f5f7fb);
        }

        .hero h1 {
            font-size: 42px;
            color: #172554;
            margin-bottom: 10px;
        }

        .hero h1 span {
            color: #2563eb;
        }

        .hero p {
            max-width: 600px;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            background-color: #2563eb;
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
        }

        .button:hover {
            background-color: #1d4ed8;
        }

        /* Bagian umum */
        section {
            padding: 60px 8%;
        }

        .section-title {
            text-align: center;
            color: #172554;
            margin-bottom: 30px;
            font-size: 30px;
        }

        /* Tentang saya */
        .about {
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        /* Keahlian */
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .skill {
            background-color: white;
            color: #1d4ed8;
            padding: 15px 25px;
            border-radius: 10px;
            box-shadow: 0 3px 10px #00000010;
        }

        /* Proyek */
        .project-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 3px 12px #00000010;
        }

        .project-card h3 {
            color: #1d4ed8;
            margin-bottom: 10px;
        }

        .project-card a {
            display: inline-block;
            margin-top: 15px;
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        /* Kontak */
        .contact {
            text-align: center;
            background-color: #dbeafe;
        }

        .contact p {
            margin-bottom: 20px;
        }

        /* Footer */
        footer {
            background-color: #172554;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Tampilan HP */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                gap: 12px;
            }

            nav ul {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .hero h1 {
                font-size: 32px;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav>
        <h2>Portofolio</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">Tentang</a></li>
            <li><a href="#skills">Keahlian</a></li>
            <li><a href="#experience">Proyek</a></li>
            <li><a href="#contact">Kontak</a></li>
        </ul>
    </nav>

    <!-- Home -->
    <section class="hero" id="home">
        <h1>Halo, Saya <span>DWI AULIA SARI</span></h1>
        <h1>NPM : 248160053 (A1)</h1>

        <p>
            Mahasiswa Teknik Informatika yang tertarik
            dengan pengembangan website, database, dan teknologi.
        </p>

        <a href="#about" class="button">Kenali Saya</a>
    </section>

    <!-- Tentang Saya -->
    <section id="about">
        <h2 class="section-title">Tentang Saya</h2>

        <div class="about">
            <p>
                Halo! Saya adalah mahasiswa Teknik Informatika
                yang sedang belajar mengembangkan kemampuan
                di bidang teknologi informasi.

                Saya memiliki ketertarikan pada pemrograman,
                pengelolaan database, dan pengembangan website.
                Saya senang mempelajari hal baru dan membuat
                proyek untuk meningkatkan kemampuan saya.
            </p>
        </div>
    </section>

    <!-- Keahlian -->
    <section id="skills">
        <h2 class="section-title">Keahlian Saya</h2>

        <div class="skills">
            <div class="skill">HTML</div>
            <div class="skill">SQL / Database</div>
        </div>
    </section>

    <!-- Pengalaman -->
    <section id="experince">
        <h2 class="section-title">Pengalaman Saya</h2>

        <div class="experince-container">

            <div class="experince-card">
                <h3>Organisasi Teknik Informatika</h3>
                <p>
                    Saya menjabat menjadi salah satu anggota humas, 
                    saya yang sering terlibat dalam interaksi sosial dengan banyak orang 
                    seperti anggota organisasi prodi lain.
                </p>
                <a href="https://drive.google.com/file/d/1eqDOOsDwUFaauhBj-Nb7FMvfcSyfSJKa/view?usp=sharing" target="_blank">
                    Lihat Dokumentasi
                </a>
            </div>

            <div class="experince-card">
                <h3>Fundamental Cybersecurity</h3>
                <p>
                    Mengikutin pelatihan Fundamental Cybersecurity yang diselenggarakan oleh 
                    Pusat Pengembangan Talenta Digital.
                </p>
                <a href="https://drive.google.com/file/d/1OvB2H88w8nGOQvG7kkbuAcQaGsviFLyU/view?usp=drive_link" target="_blank">
                    Lihat Proyek
                </a>
            </div>

            <div class="experince-card">
                <h3>Lomba Essai Nasional</h3>
                <p>
                    Mengikuti lomba essai leon dengan tema "ide gen z untuk transformasi indonesia emas 2045" 
                    tingkat nasional yang diselenggarakan oleh Forum Cendekia Muda Indonesia (forcemi) tahun 2026 .
                </p>
                <a href="https://drive.google.com/file/d/1bVmtoLeBns1t4iSGryoSy4wyT2qW9yIV/view?usp=drive_link" target="_blank">
                    Lihat Sertifikat
                </a>
            </div>

        </div>
    </section>

    <!-- Kontak -->
    <section class="contact" id="contact">
        <h2 class="section-title">Hubungi Saya</h2>
        <p>
            Tertarik bekerja sama atau ingin mengenal saya lebih jauh?
        </p>
        <p> Hubungi email dibawah</p>
        <p> dwialiasari4@gmail.com</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 dwi aulia. Dibuat dengan HTML dan CSS.</p>
    </footer>

</body>
</html>
