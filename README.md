# M.R-<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R - הכל לבית שלך! | שירותים והצעות מחיר</title>
    <style>
        :root {
            --primary-color: #1e3c72;
            --secondary-color: #2a5298;
            --whatsapp-color: #25D366;
            --bg-color: #f4f7f6;
            --card-bg: #ffffff;
            --text-color: #2c3e50;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }

        .brand-header {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        .main-logo {
            width: 90px;
            height: 90px;
            border-radius: 50%;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            border: 2px solid #fff;
        }

        /* Navigation Tabs */
        .nav-tabs {
            display: flex;
            justify-content: center;
            gap: 15px;
            background: #ffffff;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .tab-btn {
            background-color: #e9ecef;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: bold;
            cursor: pointer;
            color: var(--text-color);
            transition: all 0.3s;
        }

        .tab-btn.active, .tab-btn:hover {
            background-color: var(--primary-color);
            color: white;
        }

        .container {
            max-width: 1100px;
            margin: 20px auto 40px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin: 30px 0 20px 0;
            color: var(--primary-color);
            font-size: 1.8em;
        }

        .page-section {
            display: none;
        }

        .page-section.active {
            display: block;
        }

        .hero-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            align-items: center;
            margin-bottom: 30px;
        }

        .hero-card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            text-align: center;
        }

        .hero-card img {
            max-width: 100%;
            border-radius: 10px;
            object-fit: contain;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .service-card {
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transition: transform 0.2s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .card-header {
            background-color: var(--primary-color);
            color: white;
            padding: 12px;
            text-align: center;
        }

        .media-container {
            padding: 15px;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            margin-bottom: 12px;
        }

        .gallery-grid img {
            width: 100%;
            height: 110px;
            object-fit: cover;
            border-radius: 6px;
        }

        .card-body {
            padding: 0 15px 15px 15px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .description {
            font-size: 0.9em;
            line-height: 1.5;
            color: #555;
            margin-bottom: 15px;
        }

        /* רשימת קטגוריות פנימיות */
        .sub-options {
            display: flex;
            flex-direction: column;
            gap: 8px;
            margin-bottom: 15px;
        }

        .whatsapp-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            background-color: var(--whatsapp-color);
            color: white;
            text-decoration: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: bold;
            font-size: 0.95em;
            transition: background 0.3s;
            text-align: center;
        }

        .whatsapp-btn:hover {
            background-color: #1eb954;
        }

        /* Portfolio Gallery Page Styles */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .portfolio-item {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
            display: flex;
            flex-direction: column;
        }

        .portfolio-item img, .portfolio-item video {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .portfolio-content {
            padding: 15px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            flex-grow: 1;
        }

        footer {
            background-color: #ffffff;
            border-top: 1px solid #e0e0e0;
            padding: 30px 20px;
            text-align: center;
            margin-top: 40px;
        }

        .signature-img {
            max-width: 250px;
            height: auto;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<header>
    <div class="brand-header">
        <img src="14855.jpg" alt="M.R Logo" class="main-logo">[span_10](start_span)[span_10](end_span)
        <div>
            <h1 style="margin: 0; font-size: 2em;">M.R - הכל לבית שלך!</h1>
            <p style="margin: 5px 0 0 0; font-size: 1.1em;">Всё для вашего дома!</p>
        </div>
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
                <img src="14854.jpg" alt="M.R כרטיס ביקור ושירותים">[span_11](start_span)[span_11](end_span)
            </div>
            <div class="hero-card">
                <h3>שירות מקצועי ומהיר</h3>
                <img src="14856.jpg" alt="M.R דמות המותג">[span_12](start_span)[span_12](end_span)
            </div>
        </section>

        <h2 class="section-title">תפריט שירותים והצעות מחיר</h2>

        <div class="services-grid">
            
            <!-- אינסטלציה -->
            <div class="service-card">
                <div class="card-header"><h3 style="margin:0;">עבודות אינסטלציה</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="plumbing1.jpg" alt="אינסטלציה 1" onerror="this.src='https://via.placeholder.com/150?text=אינסטלציה+1'">
                        <img src="plumbing2.jpg" alt="אינסטלציה 2" onerror="this.src='https://via.placeholder.com/150?text=אינסטלציה+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">איתור נזילות, פיצוצי צנרת, התקנת כלים סניטריים ופתיחת סתימות.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודת%20אינסטלציה.%20מצורפות%20תמונות/סרטונים%20של%20הבעיה:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר לאינסטלציה
                    </a>
                </div>
            </div>

            <!-- שיפוצים, גבס וצבע -->
            <div class="service-card">
                <div class="card-header"><h3 style="margin:0;">שיפוצים, גבס וצבע</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="14230.jpg" alt="שיפוץ 1" onerror="this.src='https://via.placeholder.com/150?text=שיפוץ+1'">
                        <img src="14231.jpg" alt="שיפוץ 2" onerror="this.src='https://via.placeholder.com/150?text=שיפוץ+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">עבודות גבס, צבע חיצוני ופנימי, טיח וריצוף ברמת גימור מעולה.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודות%20שיפוצים/צבע.%20מצורפות%20תמונות%20של%20האזור:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר לשיפוצים
                    </a>
                </div>
            </div>

            <!-- ניקיון וחידוש רהיטים -->
            <div class="service-card">
                <div class="card-header"><h3 style="margin:0;">ניקיון וחידוש רהיטים</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="cleaning1.jpg" alt="ניקיון 1" onerror="this.src='https://via.placeholder.com/150?text=ניקיון+1'">
                        <img src="cleaning2.jpg" alt="ניקיון 2" onerror="this.src='https://via.placeholder.com/150?text=ניקיון+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">ניקיון יסודי לאחר שיפוץ ואכלוס, והברקת רצפות ומשרדים.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לשירותי%20ניקיון.%20הנה%20תמונות%20של%20החלל:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר לניקיון
                    </a>
                </div>
            </div>

            <!-- הובלות (בחירה לפי קטגוריה) -->
            <div class="service-card">
                <div class="card-header"><h3 style="margin:0;">שירותי הובלות</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="moving1.jpg" alt="הובלות 1" onerror="this.src='https://via.placeholder.com/150?text=הובלות+1'">
                        <img src="moving2.jpg" alt="הובלות 2" onerror="this.src='https://via.placeholder.com/150?text=הובלות+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">בחר סוג הובלה לקבלת הצעת מחיר בוואטסאפ:</div>
                    
                    <div class="sub-options">
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלה%20קטנה.%20מצורפות%20תמונות%20הציוד:" class="whatsapp-btn" target="_blank" style="background-color: #2a5298;">
                            📦 הובלה קטנה
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20רהיט%20אחד.%20מצורפת%20תמונת%20הרהיט:" class="whatsapp-btn" target="_blank" style="background-color: #2a5298;">
                            🪑 הובלת רהיט אחד
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלה%20גדולה%20(דירה).%20מצורפות%20תמונות:" class="whatsapp-btn" target="_blank" style="background-color: #1e3c72;">
                            🚚 הובלה גדולה (דירה)
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20משרד.%20מצורפות%20תמונות:" class="whatsapp-btn" target="_blank" style="background-color: #1e3c72;">
                            🏢 הובלת משרד
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- עמוד 2: גלריית עבודות מהשטח -->
    <div id="portfolio-page" class="page-section">
        <h2 class="section-title">גלריית עבודות ופרויקטים מהשטח</h2>
        <p style="text-align: center; color: #666; margin-bottom: 25px;">צפו בכל הסרטונים ותמונות הפרויקטים המעודכנים מתוך אתרי העבודה</p>

        <div class="portfolio-grid">
            
            <div class="portfolio-item">
                <video controls><source src="14275.mp4" type="video/mp4"></video>
                <div class="portfolio-content">
                    <div><h3>תיעוד עבודה מהשטח</h3><p class="description">הצגה של תהליכי עבודה וביצוע פרויקטים מקיפים.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20סרטון%20העבודה%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 שלח תמונות ושאלות בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <video controls><source src="video_1.mp4" type="video/mp4"></video>
                <div class="portfolio-content">
                    <div><h3>סרטון ביצוע פרויקט</h3><p class="description">סקירת עבודה מקצועית בשטח.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20הסרטון%20ואשמח%20לפרטים." class="whatsapp-btn" target="_blank">💬 שלח תמונות ושאלות בוואטסאפ</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14295.jpg" alt="הריסת קירות בטון וזיון" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div><h3>הריסת קירות בטון וזיון</h3><p class="description">עבודות הריסה מורכבות של קירות ממ"ד ובטון מזוין.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20פרויקט%20הריסת%20הבטון%20ואשמח%20להצעת%20מחיר%20לפרויקט%20דומה." class="whatsapp-btn" target="_blank">💬 שלח תמונות לפרויקט דומה</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14270.jpg" alt="שיפוץ חדר וצבע פנים" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div><h3>שיפוץ וצביעת חדר פנימי</h3><p class="description">עבודות צבע, גימור קירות והכנת חללים למגורים.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20פרויקט%20צביעת%20החדר%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 שלח תמונות לפרויקט דומה</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14305.jpg" alt="חלל פנימי ומסדרון מעוצב" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div><h3>עיצוב וחלוקת חללים פנימיים</h3><p class="description">עבודות גמר, דלתות ותשתיות פנים ברמה הגבוהה ביותר.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20עבודות%20הגמר%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 שלח תמונות לפרויקט דומה</a>
                </div>
            </div>

            <div class="portfolio-item">
                <img src="14251.jpg" alt="עבודות הצללה וכיסוי" onerror="this.src='https://via.placeholder.com/300?text=M.R+Project'">
                <div class="portfolio-content">
                    <div><h3>עבודות הצללה וכיסוי</h3><p class="description">התקנה מדויקת של פתרונות הצללה למבנים ולשטחים פתוחים.</p></div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20ראיתי%20את%20תמונת%20ההצללה%20ואשמח%20להצעת%20מחיר." class="whatsapp-btn" target="_blank">💬 שלח תמונות לפרויקט דומה</a>
                </div>
            </div>

        </div>
    </div>

</div>

<footer>
    <img src="14346.jpg" alt="Matan Richter Signature" class="signature-img" onerror="this.style.display='none'">
    <p style="margin:0; font-size: 0.9em; color: #666;">כל הזכויות שמורות ל-M.R - שירות מקיף ומקצועי בכל מקום בישראל</p>
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
