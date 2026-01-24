<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migi Setyo Sugiarto Adi | Professional Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-body: #f1f5f9;
            --text-dark: #0f172a;
            --text-muted: #64748b;
            --accent-blue: #0077b5;
            --whatsapp-green: #22c55e;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-body);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .main-card {
            background: white;
            max-width: 800px;
            width: 100%;
            border-radius: 24px;
            overflow: hidden;
            box-shadow: 0 4px 20px rgba(0,0,0,0.05);
        }

        /* Banner Container: Putih di luar gambar */
        .banner-section {
            padding: 24px 24px 0 24px;
            background: white;
        }

        .banner-img {
            width: 100%;
            border-radius: 16px;
            display: block;
        }

        .content-area {
            padding: 32px 40px 40px 40px;
        }

        .profile-header {
            margin-bottom: 32px;
        }

        .badge-linkedin {
            display: inline-flex;
            align-items: center;
            background: #e0f2fe;
            color: #0369a1;
            padding: 6px 14px;
            border-radius: 50px;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 12px;
        }

        h1 {
            font-size: 32px;
            color: var(--text-dark);
            margin: 0;
            letter-spacing: -0.5px;
        }

        .location {
            color: var(--text-muted);
            font-size: 15px;
            margin-top: 6px;
        }

        /* Grid */
        .info-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            padding: 24px;
            border-radius: 16px;
        }

        .card h3 {
            font-size: 15px;
            color: var(--text-dark);
            margin-top: 0;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .card p {
            font-size: 14px;
            line-height: 1.6;
            color: #475569;
            margin: 0;
        }

        .highlight-blue {
            color: var(--accent-blue);
            font-weight: 600;
        }

        /* Actions - Hanya 2 Tombol */
        .actions-label {
            font-size: 18px;
            font-weight: 700;
            margin-bottom: 20px;
            display: block;
        }

        .button-group {
            display: flex;
            flex-direction: column;
            gap: 16px;
            max-width: 450px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 16px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 700;
            font-size: 15px;
            transition: 0.2s;
        }

        .btn-download {
            background-color: #000;
            color: white;
        }

        .btn-download:hover {
            opacity: 0.8;
            transform: translateY(-2px);
        }

        .btn-whatsapp {
            background-color: var(--whatsapp-green);
            color: white;
        }

        .btn-whatsapp:hover {
            background-color: #16a34a;
            transform: translateY(-2px);
        }

        @media (max-width: 640px) {
            .info-grid { grid-template-columns: 1fr; }
            .content-area { padding: 24px; }
            h1 { font-size: 26px; }
        }
    </style>
</head>
<body>

    <div class="main-card">
        <div class="banner-section">
            <img src="banner.png" alt="Migi Setyo Sugiarto Adi" class="banner-img">
        </div>

        <div class="content-area">
            <div class="profile-header">
                <div class="badge-linkedin">in Professional Portfolio</div>
                <h1>Migi Setyo Sugiarto Adi</h1>
                <div class="location">📍 Semarang, Central Java | Indonesia</div>
            </div>

            <div class="info-grid">
                <div class="card">
                    <h3>Executive Summary</h3>
                    <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran dan manajemen toko. Teruji dalam manajemen inventory, cost control, dan kepemimpinan tim.</p>
                </div>
                <div class="card">
                    <h3>Professional Objective</h3>
                    <p><span class="highlight-blue">Tujuan Karier:</span> Berkontribusi dalam efisiensi operasional dan pertumbuhan bisnis melalui posisi manajemen strategis di industri F&B.</p>
                </div>
            </div>

            <span class="actions-label">Actions</span>
            <div class="button-group">
                <a href="Migi Setyo Sugiarto Adi (10).pdf" class="btn btn-download" download>
                    DOWNLOAD CV PDF
                </a>
                
                <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20melihat%20profil%20Anda%20dan%20tertarik%20untuk%20berdiskusi." 
                   class="btn btn-whatsapp" target="_blank">
                    WHATSAPP
                </a>
            </div>
        </div>
    </div>

</body>
</html>
