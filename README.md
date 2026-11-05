# M.R-
<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R - הכל לבית שלך! | שירותים והצעות מחיר</title>
    <style>
        :root {
            --whatsapp-color: #25D366;
            --bg-color: #fffafc;
            --card-bg: #ffffff;
            --text-color: #2c3e50;
        }

        /* רקע צבעוני ודינמי עם "כתמי צבע" עדינים ונעימים לעין */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 25%, #ffd1ff 50%, #a1c4fd 75%, #c2e9fb 100%);
            background-attachment: fixed;
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: var(--text-color);
            margin: 0;
            padding: 0;
            position: relative;
            overflow-x: hidden;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* אלמנטים דקורטיביים מרחפים ברקע (כתמי צבע חינניים) */
        .color-blob {
            position: absolute;
            border-radius: 50%;
            filter: blur(50px);
            z-index: -1;
            opacity: 0.5;
            pointer-events: none;
        }
        .blob-1 { top: 10%; right: 5%; width: 300px; height: 300px; background: #ff758c; }
        .blob-2 { top: 40% ; left: 10%; width: 350px; height: 350px; background: #764ba2; }
        .blob-3 { bottom: 15%; right: 20%; width: 400px; height: 400px; background: #4facfe; }
        .blob-4 { bottom: 5%; left: 5%; width: 250px; height: 250px; background: #43e97b; }

        header {
            background: linear-gradient(135deg, #ff6b6b, #ff8e53, #f6d365, #fda085);
            background-size: 300% 300%;
            animation: gradientHeader 10s ease infinite;
            color: white;
            padding: 25px 20px;
            text-align: center;
            box-shadow: 0 6px 20px rgba(0,0,0,0.15);
            position: relative;
            overflow: hidden;
        }

        @keyframes gradientHeader {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .brand-header {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        /* עיצוב הלוגו הראשי המבוקש מתוך הטקסט עם צבעוניות מתחלפת */
        .main-logo-text {
            background: #ffffff;
            color: #ff416c;
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 2.2em;
            font-weight: 900;
            box-shadow: 0 8px 25px rgba(0,0,0,0.2);
            border: 4px dashed #ff416c;
            letter-spacing: 2px;
            text-transform: uppercase;
            animation: bounceLogo 3s ease-in-out infinite;
        }

        @keyframes bounceLogo {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        /* Navigation Tabs */
        .nav-tabs {
            display: flex;
            justify-content: center;
            gap: 15px;
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            padding: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .tab-btn {
            background-color: #f0f2f5;
            border: none;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: bold;
            cursor: pointer;
            color: var(--text-color);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            font-size: 1.05em;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .tab-btn.active, .tab-btn:hover {
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(255, 65, 108, 0.4);
        }

        .container {
            max-width: 1100px;
            margin: 30px auto 50px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin: 40px 0 25px 0;
            color: #2b2b2b;
            font-size: 2.2em;
            font-weight: 800;
            text-shadow: 1px 1px 3px rgba(255,255,255,0.8);
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
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(8px);
            border-radius: 20px;
            padding: 20px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.08);
            text-align: center;
            border: 2px solid rgba(255,255,255,0.6);
        }

        .hero-card img {
            max-width: 100%;
            border-radius: 12px;
            object-fit: contain;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .service-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border-radius: 18px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid rgba(255,255,255,0.8);
        }

        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.15);
        }

        .card-header {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 16px;
            text-align: center;
            font-size: 1.1em;
            font-weight: bold;
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
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .gallery-grid img:hover {
            transform: scale(1.03);
        }

        .card-body {
            padding: 0 15px 15px 15px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .description {
            font-size: 0.95em;
            line-height: 1.6;
            color: #444;
            margin-bottom: 15px;
        }

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
            background: linear-gradient(135deg, #25D366, #128C7E);
            color: white;
            text-decoration: none;
            padding: 13px;
            border-radius: 10px;
            font-weight: bold;
            font-size: 0.95em;
            transition: all 0.3s;
            text-align: center;
            box-shadow: 0 4px 12px rgba(37, 211, 102, 0.3);
        }

        .whatsapp-btn:hover {
            transform: scale(1.02);
            box-shadow: 0 6px 16px rgba(37, 211, 102, 0.5);
        }

        /* Portfolio Gallery Page Styles */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .portfolio-item {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border-radius: 18px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            display: flex;
            flex-direction: column;
            border: 1px solid rgba(255,255,255,0.8);
            transition: transform 0.3s ease;
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
        }

        .portfolio-item img, .portfolio-item video {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .portfolio-content {
            padding: 18px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            flex-grow: 1;
        }

        footer {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            border-top: 1px solid rgba(255,255,255,0.5);
            padding: 30px 20px;
            text-align: center;
            margin-top: 50px;
            box-shadow: 0 -4px 15px rgba(0,0,0,0.05);
        }
    </style>
</head>
<body>

    <!-- כתמי צבע רקע דקורטיביים -->
    <div class="color-blob blob-1"></div>
    <div class="color-blob blob-2"></div>
    <div class="color-blob blob-3"></div>
    <div class="color-blob blob-4"></div>

<header>
    <div class="brand-header">
        <div class="main-logo-text">M.R - הכל לבית</div>
        <div>
            <h1 style="margin: 0; font-size: 1.8em; text-shadow: 1px 1px 3px rgba(0,0,0,0.2);">שירותים והצעות מחיר מקיפות</h1>
            <p style="margin: 5px 0 0 0; font-size: 1.1em; opacity: 0.95;">Всё для вашего дома! מקצועיות, אמינות ושירות מכל הלב</p>
        </div>
    </div>
</header>

<div class="nav-tabs">
    <button class="tab-btn active" onclick="switchPage('services', event)">🎨 שירותים והצעות מחיר</button>
    <button class="tab-btn" onclick="switchPage('portfolio', event)">✨ גלריית עבודות מהשטח</button>
</div>

<div class="container">

    <!-- עמוד 1: שירותים והצעות מחיר -->
    <div id="services-page" class="page-section active">
        
        <section class="hero-section">
            <div class="hero-card">
                <h3>המומחיות שלנו</h3>
                <img src="14854.jpg" alt="M.R כרטיס ביקור ושירותים">
            </div>
            <div class="hero-card">
                <h3>שירות מקצועי ומהיר</h3>
                <img src="14856.jpg" alt="M.R דמות המותג">
            </div>
        </section>

        <h2 class="section-title">תפריט שירותים והצעות מחיר</h2>

        <div class="services-grid">
            
            <!-- עבודות הריסה ופינוי -->
            <div class="service-card">
                <div class="card-header" style="background: linear-gradient(135deg, #ff416c, #ff4b2b);"><h3 style="margin:0;">עבודות הריסה, פינוי ובטון</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="14295.jpg" alt="הריסה 1" onerror="this.src='https://via.placeholder.com/150?text=הריסה+1'">
                        <img src="14275.jpg" alt="הריסה 2" onerror="this.src='https://via.placeholder.com/150?text=הריסה+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">הריסת קירות בטון מזוין, פירוק תשתיות, הריסת קירות פנים ופינוי פסולת בניין בצורה בטיחותית ומקצועית.</div>
                    <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20לעבודת%20הריסה/פינוי.%20מצורפות%20תמונות/סרטונים%20של%20האזור:" class="whatsapp-btn" target="_blank">
                        💬 שלח תמונות וקבל הצעת מחיר להריסות
                    </a>
                </div>
            </div>

            <!-- שירותי הובלות -->
            <div class="service-card">
                <div class="card-header" style="background: linear-gradient(135deg, #f7b733, #fc4a1a);"><h3 style="margin:0;">שירותי הובלות מקיפים</h3></div>
                <div class="media-container">
                    <div class="gallery-grid">
                        <img src="moving1.jpg" alt="הובלות 1" onerror="this.src='https://via.placeholder.com/150?text=הובלות+1'">
                        <img src="moving2.jpg" alt="הובלות 2" onerror="this.src='https://via.placeholder.com/150?text=הובלות+2'">
                    </div>
                </div>
                <div class="card-body">
                    <div class="description">שירות הובלה מקצועי ובטוח לכל סוגי הציוד והדירות. בחר קטגוריה לקבלת הצעת מחיר מהירה:</div>
                    
                    <div class="sub-options">
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20דירה.%20מצורפות%20תמונות/פירוט:" class="whatsapp-btn" target="_blank" style="background: linear-gradient(135deg, #4facfe, #00f2fe);">
                            🚚 הובלת דירות (גדולות / בינוניות)
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20משרד.%20מצורפות%20תמונות:" class="whatsapp-btn" target="_blank" style="background: linear-gradient(135deg, #4facfe, #00f2fe);">
                            🏢 הובלת משרדים ועסקים
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלה%20קטנה.%20מצורפות%20תמונות%20הציוד:" class="whatsapp-btn" target="_blank" style="background: linear-gradient(135deg, #43e97b, #38f9d7); color: #111;">
                            📦 הובלה קטנה / ציוד בודד
                        </a>
                        <a href="https://wa.me/972559423309?text=היי%20M.R,%20אני%20מעוניין%20בהצעת%20מחיר%20להובלת%20רהיט%20אחד.%20מצורפת%20תמונת%20הרהיט:" class="whatsapp-btn" target="_blank" style="background: linear-gradient(135deg, #43e97b, #38f9d7); color: #111;">
                            🪑 הובלה ופירוק/הרכבת רהיט
                        </a>
                    </div>
                </div>
            </div>

            <!-- אינסטלציה -->
            <div class="service-card">
                <div class="card-header" style="background: linear-gradient(135deg, #3b82f6, #1d4ed8);"><h3 style="margin:0;">עבודות אינסטלציה</h3></div>
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
                <div class="card-header" style="background: linear-gradient(135deg, #8b5cf6, #6d28d9);"><h3 style="margin:0;">שיפוצים, גבס וצבע</h3></div>
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
                <div class="card-header" style="background: linear-gradient(135deg, #10b981, #047857);"><h3 style="margin:0;">ניקיון וחידוש רהיטים</h3></div>
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

        </div>
    </div>

    <!-- עמוד 2: גלריית עבודות מהשטח -->
    <div id="portfolio-page" class="page-section">
        <h2 class="section-title">גלריית עבודות ופרויקטים מהשטח</h2>
        <p style="text-align: center; color: #444; margin-bottom: 25px; font-weight: 500;">צפו בכל הסרטונים ותמונות הפרויקטים המעודכנים מתוך אתרי העבודה</p>

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
    <p style="margin:0; font-size: 1em; font-weight: bold; color: #333;">כל הזכויות שמורות ל-M.R - שירות מקיף ומקצועי בכל מקום בישראל 🌟</p>
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
