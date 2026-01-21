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
            --accent-blue: #0077b5; /* LinkedIn Blue */
            --whatsapp-green: #25d366;
        }

        body {
            font-family: 'Inter', -apple-system, sans-serif;
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

        /* Banner Container */
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

        /* Profile Header */
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

        /* Info Grid */
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

        /* Actions Section */
        .actions-label {
            font-weight: 700;
            margin-bottom: 20px;
            display: block;
        }

        .action-row {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 15px;
        }

        .btn-black {
            background: black;
            color: white;
            padding: 10px 24px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 14px;
            min-width: 140px;
            text-align: center;
        }

        .file-name {
            font-size: 14px;
            color: #4b5563;
        }

        .wa-link-text {
            font-size: 14px;
            color: var(--text-muted);
            margin-top: 20px;
            display: block;
        }

        .wa-link-text a {
            color: var(--text-muted);
        }

        /* Footer Actions */
        .footer-buttons {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-top: 30px;
        }

        .contact-label {
            color: #059669;
            font-weight: 600;
            font-size: 14px;
            text-decoration: none;
        }

        .btn-whatsapp {
            background: var(--whatsapp-green);
            color: white;
            padding: 10px 24px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 14px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        @media (max-width: 640px) {
            .info-grid { grid-template-columns: 1fr; }
            .profile-content { padding: 20px; }
            .footer-buttons { flex-direction: column; align-items: flex-start; }
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
                    <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Terbukti mampu mengelola inventory dan menekan biaya operasional 15%.</p>
                </div>
                <div class="info-card">
                    <h3>Professional Objective</h3>
                    <p><span class="objective-highlight">Professional Objective</span><br>
                    Mencari posisi di bidang F&B Operations atau Store Management untuk meningkatkan efisiensi operasional dan pertumbuhan bisnis.</p>
                </div>
            </div>

            <span class="actions-label">Actions</span>
            
            <div class="action-row">
                <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn-black" download>btn download</a>
                <span class="file-name">Migi Setyo Sugiarto Adi (9).pdf</span>
            </div>

            <div class="action-row">
                <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn-black" download>btn - WhatsApp</a>
                <span class="file-name" style="color: #059669; font-weight: 600;">btn Resume Lengkap (PDF)</span>
            </div>

            <span class="wa-link-text">
                https://wa.me/628112683668?text=<a href="#">'Halo, saya melihat profil Anda tertarik diskusi lebih lanjut.</a>
            </span>

            <div class="footer-buttons">
                <a href="https://wa.me/628112683668" class="contact-label">Hubungi via WhatsApp</a>
                <a href="https://wa.me/628112683668" class="btn-whatsapp">
                    <svg width="18" height="18" fill="currentColor" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.316 1.592 5.43 0 9.856-4.426 9.858-9.855.002-5.43-4.425-9.856-9.855-9.858-2.646 0-5.14 1.032-7.008 2.901-1.868 1.868-2.898 4.362-2.903 7.008-.001 2.031.569 3.593 1.611 5.213l-.959 3.498 3.58-.939z"/></svg>
                    Target - & - Link
                </a>
            </div>
        </div>
    </div>

</body>
</html>
