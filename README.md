<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Profile - Migi Setyo Sugiarto Adi</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-dark: #0f172a;
            --accent-blue: #2563eb;
            --wa-green: #25d366;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --bg-site: #f1f5f9;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-site);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .main-container {
            background: white;
            max-width: 850px;
            width: 100%;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .banner {
            width: 100%;
            height: 300px;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #2563eb 100%);
            /* Jika ada file gambar banner, aktifkan baris di bawah ini: */
            /* background: url('banner.jpg') center/cover no-repeat; */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .banner h1 { font-size: 2.2rem; margin: 0; letter-spacing: -1px; }
        .banner p { font-size: 1.1rem; opacity: 0.9; margin-top: 10px; font-weight: 300; }

        .content { padding: 40px; }

        .profile-title { text-align: left; margin-bottom: 30px; }
        .badge-linkedin {
            display: inline-flex;
            align-items: center;
            background: #e0f2fe;
            color: #0369a1;
            padding: 5px 12px;
            border-radius: 50px;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 15px;
        }

        .profile-name { font-size: 32px; font-weight: 700; color: var(--primary-dark); margin: 0; }
        .location { color: var(--text-muted); font-size: 15px; margin-top: 5px; }

        /* GRID UNTUK SUMMARY & OBJECTIVE */
        .grid-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            padding: 25px;
            border-radius: 12px;
        }

        .card h3 {
            margin-top: 0;
            font-size: 16px;
            color: var(--accent-blue);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .card p { font-size: 14.5px; line-height: 1.6; color: var(--text-main); margin-bottom: 0; }

        /* TOMBOL ACTIONS */
        .actions {
            margin-top: 40px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center;
        }

        .btn {
            width: 100%;
            max-width: 400px;
            padding: 16px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 700;
            font-size: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: 0.3s;
        }

        .btn-download { background: black; color: white; }
        .btn-download:hover { opacity: 0.8; transform: translateY(-2px); }

        .btn-whatsapp {
            background: white;
            color: var(--wa-green);
            border: 2px solid var(--wa-green);
        }

        .btn-whatsapp:hover {
            background: var(--wa-green);
            color: white;
        }

        @media (max-width: 600px) {
            .grid-container { grid-template-columns: 1fr; }
            .banner h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

    <div class="main-container">
        <div class="banner">
            <h1>Migi Setyo Sugiarto Adi</h1>
            <p>Food & Beverage Professional | Operations & Store Management</p>
        </div>

        <div class="content">
            <div class="profile-title">
                <div class="badge-linkedin">in Professional Portfolio</div>
                <h2 class="profile-name">Migi Setyo Sugiarto Adi</h2>
                <div class="location">📍 Semarang, Central Java, Indonesia </div>
            </div>

            <div class="grid-container">
                <div class="card">
                    <h3>Executive Summary</h3>
                    <p>Profesional F&B dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko[cite: 2]. Ahli dalam manajemen inventaris, pengendalian biaya (Cost Control), dan kepemimpinan tim.</p>
                </div>

                <div class="card">
                    <h3>Professional Objective</h3>
                    <p>Bertekad meningkatkan efisiensi operasional dan pertumbuhan bisnis melalui posisi Food & Beverage Operations atau Store Management yang strategis.</p>
                </div>
            </div>

            <div class="actions">
                <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn btn-download" download>
                    Dapatkan CV Lengkap (PDF)
                </a>
                
                <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20melihat%20portofolio%20Anda%20dan%20tertarik%20untuk%20berdiskusi." 
                   class="btn btn-whatsapp" target="_blank">
                    Hubungi via WhatsApp
                </a>
            </div>
        </div>
    </div>

</body>
</html>
