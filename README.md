<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Portfolio - Migi Setyo Sugiarto Adi</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-body: #f3f4f6;
            --text-dark: #111827;
            --text-muted: #6b7280;
            --accent-blue: #0077b5;
            --whatsapp-green: #25d366;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-body);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .portfolio-wrapper {
            background: white;
            max-width: 800px;
            width: 100%;
            border-radius: 24px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
        }

        .banner-box {
            width: 100%;
            padding: 20px;
            box-sizing: border-box;
        }

        .banner-img {
            width: 100%;
            border-radius: 20px;
            display: block;
        }

        .profile-content {
            padding: 0 40px 40px 40px;
        }

        .badge-professional {
            display: inline-flex;
            align-items: center;
            background: #f3f4f6;
            padding: 6px 16px;
            border-radius: 50px;
            margin-bottom: 15px;
        }

        .badge-icon {
            background: var(--accent-blue);
            color: white;
            width: 20px;
            height: 20px;
            border-radius: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: bold;
            margin-right: 8px;
        }

        .badge-text {
            font-size: 14px;
            font-weight: 600;
            color: #374151;
        }

        h1 {
            font-size: 32px;
            margin: 0;
            color: var(--text-dark);
        }

        .location-text {
            color: var(--text-muted);
            font-size: 15px;
            margin-top: 8px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 40px 0;
        }

        .info-card {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            padding: 24px;
            border-radius: 16px;
        }

        .info-card h3 {
            font-size: 15px;
            color: var(--text-dark);
            margin-top: 0;
            margin-bottom: 12px;
        }

        .info-card p {
            font-size: 14px;
            line-height: 1.6;
            color: var(--text-muted);
            margin: 0;
        }

        .objective-highlight {
            color: var(--accent-blue);
            font-weight: 600;
        }

        /* Actions Section - Only 2 Buttons */
        .actions-section {
            margin-top: 30px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            align-items: center;
        }

        .btn {
            width: 100%;
            max-width: 400px;
            padding: 14px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 15px;
            text-align: center;
            transition: 0.2s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-download {
            background: black;
            color: white;
        }

        .btn-download:hover {
            opacity: 0.8;
            transform: translateY(-2px);
        }

        .btn-whatsapp {
            background: var(--whatsapp-green);
            color: white;
        }

        .btn-whatsapp:hover {
            background: #20bd5c;
            transform: translateY(-2px);
        }

        @media (max-width: 640px) {
            .info-grid { grid-template-columns: 1fr; }
            .profile-content { padding: 20px; }
        }
    </style>
</head>
<body>

    <div class="portfolio-wrapper">
        <div class="banner-box">
            <img src="banner.png" alt="Banner Migi Setyo" class="banner-img">
        </div>

        <div class="profile-content">
            <div class="badge-professional">
                <div class="badge-icon">in</div>
                <span class="badge-text">Professional Portfolio</span>
            </div>

            <h1>Migi Setyo Sugiarto Adi</h1>
            <div class="location-text">📍 Semarang, Central Java @ Indonesia</div>

            <div class="info-grid">
                <div class="info-card">
                    <h3>Executive Summary</h3>
                    <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Ahli dalam manajemen inventaris, menekan biaya operasional, serta bekerja efektif lintas tim.</p>
                </div>
                <div class="info-card">
                    <h3>Professional Objective</h3>
                    <p><span class="objective-highlight">Tujuan Karier</span><br>
                    Berkontribusi langsung dalam peningkatan efisiensi operasional, kualitas layanan pelanggan, serta pertumbuhan bisnis perusahaan.</p>
                </div>
            </div>

            <div class="actions-section">
                <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn btn-download" download>
                    DOWNLOAD CV PDF
                </a>
                
                <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20melihat%20profil%20profesional%20Anda%20dan%20tertarik%20untuk%20berdiskusi." 
                   class="btn btn-whatsapp" target="_blank">
                    WHATSAPP
                </a>
            </div>
        </div>
    </div>

</body>
</html>
