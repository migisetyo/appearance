<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migi Setyo Sugiarto Adi | F&B Operations Specialist</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --whatsapp: #22c55e;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --bg: #f8fafc;
            --white: #ffffff;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .portfolio-container {
            background: var(--white);
            max-width: 800px;
            width: 95%;
            margin: 40px 0;
            border-radius: 32px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.08);
            overflow: hidden;
            position: relative;
        }

        /* Banner Section */
        .banner {
            width: 100%;
            height: 250px;
            background: linear-gradient(135deg, #0f172a 0%, #2563eb 100%);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }

        .banner h1 {
            font-size: 2.5rem;
            margin: 0;
            letter-spacing: -1px;
        }

        .banner p {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-top: 10px;
        }

        .main-content {
            padding: 40px;
        }

        .header-meta {
            text-align: center;
            margin-bottom: 40px;
        }

        .badge {
            background: #eff6ff;
            color: var(--accent);
            padding: 6px 16px;
            border-radius: 100px;
            font-size: 13px;
            font-weight: 700;
            text-transform: uppercase;
            display: inline-block;
            margin-bottom: 10px;
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin-top: 20px;
        }

        .info-card {
            background: #f8fafc;
            padding: 24px;
            border-radius: 20px;
            border: 1px solid #e2e8f0;
        }

        h3 {
            font-size: 14px;
            color: var(--accent);
            text-transform: uppercase;
            margin-top: 0;
            margin-bottom: 12px;
            letter-spacing: 0.05em;
        }

        p {
            font-size: 15px;
            line-height: 1.6;
            margin: 0;
        }

        .actions {
            margin-top: 40px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .btn {
            padding: 16px;
            border-radius: 16px;
            text-decoration: none;
            font-weight: 700;
            text-align: center;
            transition: 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-download {
            background: var(--primary);
            color: white;
        }

        .btn-download:hover {
            background: #000;
            transform: translateY(-2px);
        }

        .btn-whatsapp {
            border: 2px solid var(--whatsapp);
            color: var(--whatsapp);
        }

        .btn-whatsapp:hover {
            background: var(--whatsapp);
            color: white;
            transform: translateY(-2px);
        }

        @media (max-width: 640px) {
            .content-grid { grid-template-columns: 1fr; }
            .banner h1 { font-size: 1.8rem; }
            .main-content { padding: 25px; }
        }
    </style>
</head>
<body>

    <div class="portfolio-container">
        <div class="banner">
            <h1>Migi Setyo Sugiarto Adi</h1>
            <p>Food & Beverage Professional | Operations & Store Management</p>
        </div>

        <div class="main-content">
            <div class="header-meta">
                <span class="badge">Professional Profile</span>
                <div style="color: var(--text-muted); font-size: 14px;">Semarang, Indonesia | migisetyosa@gmail.com</div>
            </div>

            <div class="content-grid">
                <div class="info-card">
                    <h3>Tentang Saya</h3>
                    <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di operasional restoran, bar, dan manajemen toko[cite: 2]. Ahli dalam mengelola inventory, menekan biaya operasional, dan sistem manajemen berbasis data (Excel)[cite: 4, 5].</p>
                </div>

                <div class="info-card">
                    <h3>Tujuan Karier</h3>
                    <p>Mencari posisi di bidang F&B Operations / Store Management / Purchasing untuk berkontribusi langsung dalam peningkatan efisiensi operasional dan pertumbuhan bisnis[cite: 6].</p>
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
