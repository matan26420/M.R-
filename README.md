<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R - הכל לבית שלך! | שירותים והצעות מחיר</title>
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --accent: #f59e0b;
            --whatsapp: #25D366;
            --bg-main: #f8fafc;
            --card-bg: #ffffff;
            --text-main: #0f172a;
            --text-muted: #64748b;
            --radius-lg: 20px;
            --radius-md: 12px;
            --shadow-subtle: 0 4px 20px -2px rgba(15, 23, 42, 0.06);
            --shadow-hover: 0 20px 30px -10px rgba(15, 23, 42, 0.12);
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background-color: var(--bg-main);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* כותרת ראשית אלגנטית וממוקדת */
        header {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 4px solid var(--primary);
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        }

        .brand-container {
            max-width: 800px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 12px;
        }

        .brand-badge {
            background: linear-gradient(135deg, var(--primary), #3b82f6);
            color: white;
            padding: 12px 35px;
            border-radius: 50px;
            font-size: 2.2rem;
            font-weight: 800;
            letter-spacing: 1px;
            box-shadow: 0 8px 20px rgba(37, 99, 235, 0.3);
            border: 2px solid rgba(255,255,255,0.2);
        }

        header p {
            margin: 0;
            color: #94a3b8;
            font-size: 1.15rem;
            font-weight: 500;
        }

        /* לשוניות ניווט נקיות ומודרניות */
        .nav-tabs {
            display: flex;
            justify-content: center;
            gap: 15px;
            background: #ffffff;
            padding: 18px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.04);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #e2e8f0;
        }

        .tab-btn {
            background-color: #f1f5f9;
            border: none;
            padding: 12px 28px;
            border-radius: 12px;
            font-weight: 700;
            cursor: pointer;
            color: var(--text-muted);
            transition: all 0.25s ease;
            font-size: 1rem;
        }

        .tab-btn.active, .tab-btn:hover {
            background-color: var(--primary);
            color: white;
            box-shadow: 0 4px 12px rgba(37, 99, 235, 0.25);
            transform: translateY(-1px);
        }

        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin: 10px 0 35px 0;
            color: var(--text-main);
            font-size: 2rem;
            font-weight: 800;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background: var(--primary);
            margin: 10px auto 0;
            border-radius: 2px;
        }

        .page-section {
            display: none;
        }

        .page-section.active {
            display: block;
            animation: fadeIn 0.4s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(8px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .hero-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
            margin-bottom: 45px;
        }

        .hero-card {
            background: var(--card-bg);
            border-radius: var(--radius-lg);
            padding: 20px;
            box-shadow: var(--shadow-subtle);
            text-align: center;
            border: 1px solid #e2e8f0;
        }

        .hero-card h3 {
            margin-top: 0;
            color: var(--text-main);
            font-size: 1.2rem;
        }

        .hero-card img {
            max-width: 100%;
            border-radius: var(--radius-md);
            object-fit: contain;
        }

        /* רשת שירותים מסודרת ואחידה */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: var(--card-bg);
            border-radius: var(--radius-lg);
            box-shadow: var(--shadow-subtle);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
        }

        .service-card:hover {
            transform: translateY(-6px);
            box-shadow: var(--shadow-hover);
            border-color: #cbd5e1;
        }

        .card-header {
            background: linear-gradient(135deg, #1e293b, #0f172a);
            color: white;
            padding: 18px;
            text-align: center;
            font-size: 1.15rem;
            font-weight: 700;
        }

        .media-container {
            padding: 18px 18px 0 18px;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .gallery-grid img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            border-radius: var(--radius-md);
            background: #f1f5f9;
        }

        .card-body {
            padding: 18px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .description {
            font-size: 0.95rem;
            line-height: 1.6;
            color: var(--text-muted);
            margin-bottom: 20px;
        }

        .sub-options {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-bottom: 15px;
        }

        .whatsapp-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            background-color: var(--whatsapp);
            color: white;
            text-decoration: none;
            padding: 14px;
            border-radius: var(--radius-md);
            font-weight: 700;
            font-size: 0.95rem;
            transition: background 0.2s, transform 0.2s;
            text-align: center;
            box-shadow: 0 4px 12px rgba(37, 211, 102, 0.2);
        }

        .whatsapp-btn:hover {
            background-color: #20ba5a;
            transform: scale(1.01);
        }

        .whatsapp-btn.secondary {
            background-color: #334155;
            box-shadow: 0 4px 12px rgba(51, 65, 85, 0.15);
        }
        .whatsapp-btn.secondary:hover {
            background-color: #1e293b;
        }

        /* גלריית עבודות מוקפדת */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
        }

        .portfolio-item {
            background: var(--card-bg);
            border-radius: var(--radius-lg);
            overflow: hidden;
            box-shadow: var(--shadow-subtle);
            display: flex;
            flex-direction: column;
            border: 1px solid #e2e8f0;
            transition: transform 0.3s ease;
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .portfolio-item img, .portfolio-item video {
            width: 100%;
            height: 240px;
            object-fit: cover;
            background: #000;
        }

        .portfolio-content {
            padding: 20px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            flex-grow: 1;
        }

        .portfolio-content h3 {
            margin: 0 0 8px 0;
            font-size: 1.2rem;
            color: var(--text-main);
        }

        footer {
            background-color: #0f172a;
            color: #94a3b8;
            border-top: 1px solid #1e293b;
            padding: 40px 20px;
            text-align: center;
            margin-top: 60px;
        }

        footer p {
            margin: 0;
            font-size: 0.95rem;
        }
    </style>
</head>
<body>

<header>
    <div class="brand-container">
        <div class="brand-badge">M.R</div>
        <h1 style="margin: 0; font-size: 2.2rem; font-weight: 800;">הכל לבית שלך!</h1>
        <p>שירותים מקצועיים ומקיפים באיכות הגבוהה ביותר בכל הארץ</p>
    </div>
</header>

<div class="nav-tabs">
    <button class="tab-btn active" onclick="switchPage('services', event)">שירותים והצעות מחיר</button>
    <button class="tab-btn" onclick="switchPage('portfolio', event)">גלריית עבודות מהשטח</button>
</div>

<div class="container">

    <!-- עמוד 1: שירותים והצעות מחיר -->
    <div id="services-page" class="page-section active">
        
        <section class="hero-section">
            <div class="hero-card">
                <h3>המומחיות שלנו</h3>
                <img src="14854.jpg" alt="M.R כרטיס ביקור ושירותים" onerror="this.style.display='none'">
            </div>
            <div class="hero-card">
                <h3>שירות מקצועי ומהיר</h3>
                <img src="14856.jpg" alt="M.R דמות המותג" onerror="this.style.display='none'">
            </div>
        </section>

        <h2 class="section-title">תפריט שירותים והצעות מחיר</h2>

        <div class="services-grid">
            
            <!-- עבודות הריסה ופינוי -->
            <div class="service-card">
                <div class="card-header">עבודות הריסה, פינוי ובטון</div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="14295.jpg" alt="הריסה 1" onerror="this.src='https://via.placeholder.com/150?text=הריסה+1'">
                        <img src="14275.jpg" alt="הריסה 2" onerror="this.src='https://via.placeholder.com/150?text=הריסה+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">הריסת קירות בטון מזוין, פירוק תשתיות, הריסת קירות פנים ופינוי פסולת בניין בצורה בטיחותית ומקצועית.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודת%20הריסה/פינוי.%20מצורפות%20תמונות/סרטונים%20של%20האזור:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר
                    </a>
                </div>
            </div>

            <!-- שירותי הובלות -->
            <div class="service-card">
                <div class="card-header">שירותי הובלות מקיפים</div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="moving1.jpg" alt="הובלות 1" onerror="this.src='https://via.placeholder.com/150?text=הובלות+1'">
                        <img src="moving2.jpg" alt="הובלות 2" onerror="this.src='https://via.placeholder.com/150?text=הובלות+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">שירות הובלה מקצועי ובטוח לכל סוגי הציוד והדירות. בחר קטגוריה לקבלת הצעת מחיר מהירה:</div>
                    
                    <div class="sub-options">
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20דירה.%20מצורפות%20תמונות/פירוט:" class="whatsapp-btn secondary" target="_blank">
                            🚚 הובלת דירות (גדולות / בינוניות)
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20משרד.%20מצורפות%20תמונות:" class="whatsapp-btn secondary" target="_blank">
                            🏢 הובלת משרדים ועסקים
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלה%20קטנה.%20מצורפות%20תמונות%20הציוד:" class="whatsapp-btn" target="_blank">
                            📦 הובלה קטנה / ציוד בודד
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20רהיט%20אחד.%20מצורפת%20תמונת%20הרהיט:" class="whatsapp-btn" target="_blank">
                            🪑 הובלה ופירוק/הרכבת רהיט
                        </a>
                    </div>
                </div>
            </div>

            <!-- אינסטלציה -->
            <div class="service-card">
                <div class="card-header">עבודות אינסטלציה</div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="plumbing1.jpg" alt="אינסטלציה 1" onerror="this.src='https://via.placeholder.com/150?text=אינסטלציה+1'">
                        <img src="plumbing2.jpg" alt="אינסטלציה 2" onerror="this.src='https://via.placeholder.com/150?text=אינסטלציה+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">איתור נזילות, פיצוצי צנרת, התקנת כלים סניטריים ופתיחת סתימות בצורה מהירה ויסודית.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודת%20אינסטלציה.%20מצורפות%20תמונות/סרטונים%20של%20הבעיה:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר
                    </a>
                </div>
            </div>

            <!-- שיפוצים, גבס וצבע -->
            <div class="service-card">
                <div class="card-header">שיפוצים, גבס וצבע</div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="14230.jpg" alt="שיפוץ 1" onerror="this.src='https://via.placeholder.com/150?text=שיפוץ+1'">
                        <img src="14231.jpg" alt="שיפוץ 2" onerror="this.src='https://via.placeholder.com/150?text=שיפוץ+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">עבודות גבס, צבע חיצוני ופנימי, טיח וריצוף ברמת גימור מעולה וסטנדרט גבוה.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודות%20שיפוצים/צבע.%20מצורפות%20תמונות%20של%20האזור:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר
                    </a>
                </div>
            </div>

            <!-- ניקיון וחידוש רהיטים -->
            <div class="service-card">
                <div class="card-header">ניקיון וחידוש רהיטים</div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="cleaning1.jpg" alt="ניקיון 1" onerror="this.src='https://via.placeholder.com/150?text=ניקיון+1'">
                        <img src="cleaning2.jpg" alt="ניקיון 2" onerror="this.src='https://via.placeholder.com/150?text=ניקיון+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">ניקיון יסודי לאחר שיפוץ ואכלוס, הברקת רצפות, ניקיון משרדים וחידוש חללים.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לשירותי%20ניקיון.%20הנה%20תמונות%20של%20החלל:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר
                    </a>
                </div>
            </div>

        </div>
    </div>

    <!-- עמוד 2: גלריית עבודות מהשטח -->
    <div id="portfolio-page" class="page-section">
        <h2 class="section-title">גלריית עבודות ופרויקטים מהשטח</h2>
        <p style="text-align: center; color: var(--text-muted); margin-bottom: 30px;">צפו בסרטונים ובתמונות אמיתיות מתוך אתרי העבודה שלנו</p>

        <div class="portfolio-grid">
            
            <div class="portfolio-item">
                <video controls><source src="14275.mp4" type="video/mp4"></video>
                <div class="portfolio-content">
                    <div>
                        <h3>תיעוד עבודה מהשטח</h3>
                        <p class="description">הצגה של תהליכי עבודה וביצוע פרויקטים מקיפים.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20סרטון%20העבודה%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <video controls><source src="video_1.mp4" type="video/mp4"></video>
                <div class="portfolio-content">
                    <div>
                        <h3>סרטון ביצוע פרויקט</h3>
                        <p class="description">סקירת עבודה מקצועית בשטח.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20הסרטון%20ואשמח%20לפרטים." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14295.jpg" alt="הריסת קירות בטון וזיון" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div>
                        <h3>הריסת קירות בטון וזיון</h3>
                        <p class="description">עבודות הריסה מורכבות של קירות ממ"ד ובטון מזוין.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20פרויקט%20הריסת%20הבטון%20ואשמח%20להצעת%20מחיר%20לפרויקט%20דומה." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14270.jpg" alt="שיפוץ חדר וצבע פנים" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div>
                        <h3>שיפוץ וצביעת חדר פנימי</h3>
                        <p class="description">עבודות צבע, גימור קירות והכנת חללים למגורים.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20פרויקט%20צביעת%20החדר%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14305.jpg" alt="חלל פנימי ומסדרון מעוצב" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div>
                        <h3>עיצוב וחלוקת חללים פנימיים</h3>
                        <p class="description">עבודות גמר, דלתות ותשתיות פנים ברמה הגבוהה ביותר.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20עבודות%20הגמר%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14251.jpg" alt="עבודות הצללה וכיסוי" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div>
                        <h3>עבודות הצללה וכיסוי</h3>
                        <p class="description">התקנה מדויקת של פתרונות הצללה למבנים ולשטחים פתוחים.</p>
                    </div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20תמונת%20ההצללה%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 פנה בוואטסאפ</a>
                </div>
            </div>

        </div>
    </div>

</div>

<footer>
    <p>כל הזכויות שמורות ל-M.R - שירות מקיף ומקצועי בכל מקום בישראל</p>
</footer>

<script>
    function switchPage(pageId, event) {
        document.querySelectorAll('.page-section').forEach(sec => sec.classList.remove('active'));
        document.querySelectorAll('.tab-btn').forEach(btn => btn.classList.remove('active'));

        if (pageId === 'services') {
            document.getElementById('services-page').classList.add('active');
        } else if (pageId === 'portfolio') {
            document.getElementById('portfolio-page').classList.add('active');
        }
        event.target.classList.add('active');
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }
</script>

</body>
</html>
