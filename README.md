<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Profile - Migi Setyo Sugiarto Adi</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-dark: #0f172a;
            --accent-blue: #2563eb;
            --wa-green: #22c55e;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --bg-site: #f8fafc;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-site);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .main-container {
            background: white;
            max-width: 850px;
            width: 100%;
            border-radius: 32px;
            overflow: hidden;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.08);
        }

        /* BANNER - Menggunakan file banner.png Anda */
        .banner-container {
            width: 100%;
            line-height: 0; /* Menghilangkan celah bawah gambar */
        }

        .banner-img {
            width: 100%;
            height: auto;
            display: block;
        }

        .content {
            padding: 40px;
        }

        .profile-title {
            text-align: left;
            margin-bottom: 35px;
        }

        .badge-prof {
            display: inline-flex;
            align-items: center;
            background: #eff6ff;
            color: var(--accent-blue);
            padding: 6px 14px;
            border-radius: 50px;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        .profile-name {
            font-size: 36px;
            font-weight: 700;
            color: var(--primary-dark);
            margin: 0;
            letter-spacing: -0.02em;
        }

        .location-info {
            color: var(--text-muted);
            font-size: 15px;
            margin-top: 8px;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        /* GRID UNTUK SUMMARY & OBJECTIVE */
        .grid-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin-top: 30px;
        }

        .card {
            background: #ffffff;
            border: 1px solid #f1f5f9;
            padding: 24px;
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .card:hover {
            border-color: #e2e8f0;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.04);
        }

        .card h3 {
            margin-top: 0;
            font-size: 14px;
            color: var(--accent-blue);
            text-transform: uppercase;
            letter-spacing: 0.1em;
            margin-bottom: 12px;
        }

        .card p {
            font-size: 15px;
            line-height: 1.6;
            color: var(--text-main);
            margin: 0;
        }

        /* TOMBOL ACTIONS */
        .actions {
            margin-top: 45px;
            display: flex;
            flex-direction: column;
            gap: 16px;
            align-items: center;
        }

        .btn {
            width: 100%;
            max-width: 450px;
            padding: 18px;
            border-radius: 16px;
            text-decoration: none;
            font-weight: 700;
            font-size: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
            box-sizing: border-box;
        }

        .btn-download {
            background-color: var(--primary-dark);
            color: white;
        }

        .btn-download:hover {
            background-color: #000;
            transform: translateY(-2px);
        }

        .btn-whatsapp {
            background-color: transparent;
            color: var(--wa-green);
            border: 2px solid var(--wa-green);
        }

        .btn-whatsapp:hover {
            background-color: var(--wa-green);
            color: white;
            transform: translateY(-2px);
        }

        @media (max-width: 640px) {
            .grid-container { grid-template-columns: 1fr; }
            .profile-name { font-size: 28px; }
            .content { padding: 30px 20px; }
        }
    </style>
</head>
<body>

    <div class="main-container">
        <div class="banner-container">
            <img src="banner.png" alt="Migi Setyo Sugiarto Adi Banner" class="banner-img">
        </div>

        <div class="content">
            <div class="profile-title">
                <span class="badge-prof">Professional Portfolio</span>
                <h1 class="profile-name">Migi Setyo Sugiarto Adi</h1>
                <div class="location-info">
                    <span>📍</span> Semarang, Central Java, Indonesia | migisetyosa@gmail.com
                </div>
            </div>

            <div class="grid-container">
                <div class="card">
                    <h3>Executive Summary</h3>
                    <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Ahli dalam manajemen inventaris, pengendalian biaya (Cost Control), dan kepemimpinan tim berbasis data.</p>
                </div>

                <div class="card">
                    <h3>Professional Objective</h3>
                    <p>Mencari posisi di bidang F&B Operations / Store Management / Purchasing untuk berkontribusi langsung dalam peningkatan efisiensi operasional dan pertumbuhan bisnis.</p>
                </div>
            </div>

            <div class="actions">
                <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn btn-download" download>
                    Unduh CV Lengkap (PDF)
                </a>
                
                <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20tertarik%20dengan%20profil%20profesional%20Anda." 
                   class="btn btn-whatsapp" target="_blank">
                    Hubungi via WhatsApp
                </a>
            </div>
        </div>
    </div>

</body>
</html>
