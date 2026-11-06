<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R – הכול לבית שלך!</title>
    <style>
        :root {
            --primary: #128c7e;
            --primary-dark: #075e54;
            --accent: #25d366;
            --bg: #f4f6f8;
            --card-bg: #ffffff;
            --text: #333333;
            --text-muted: #666666;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 20px 10px;
            display: flex;
            justify-content: center;
        }

        .container {
            width: 100%;
            max-width: 600px;
            background: var(--card-bg);
            padding: 25px 20px;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.08);
        }

        header {
            text-align: center;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 20px;
            margin-bottom: 25px;
        }

        h1 {
            color: var(--primary-dark);
            margin: 0 0 5px 0;
            font-size: 1.8rem;
        }

        .subtitle {
            color: var(--text-muted);
            font-size: 0.95rem;
            margin: 5px 0 15px 0;
        }

        .contact-btns {
            display: flex;
            gap: 10px;
            justify-content: center;
            margin-top: 15px;
        }

        .btn-main {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 12px 20px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            color: white;
            transition: transform 0.2s, background-color 0.2s;
            flex: 1;
        }

        .btn-whatsapp {
            background-color: var(--accent);
        }

        .btn-phone {
            background-color: var(--primary);
        }

        .btn-main:hover {
            transform: translateY(-2px);
            opacity: 0.95;
        }

        h2 {
            font-size: 1.3rem;
            color: var(--primary-dark);
            margin-top: 30px;
            margin-bottom: 15px;
            border-right: 4px solid var(--primary);
            padding-right: 10px;
        }

        .grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 12px;
        }

        @media (min-width: 480px) {
            .grid {
                grid-template-columns: 1fr 1fr;
            }
        }

        .card {
            background: #fafafa;
            border: 1px solid #eef0f2;
            border-radius: 12px;
            padding: 15px;
            text-decoration: none;
            color: var(--text);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            transition: all 0.2s ease;
        }

        .card:hover {
            border-color: var(--primary);
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            background: #fff;
        }

        .card-header {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 8px;
        }

        .card-title {
            font-size: 1.1rem;
            font-weight: bold;
        }

        .card-title small {
            display: block;
            font-weight: normal;
            color: var(--text-muted);
            font-size: 0.85rem;
        }

        .card-action {
            font-size: 0.8rem;
            color: var(--primary);
            font-weight: bold;
            margin-top: 8px;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 15px;
            border-top: 1px solid #eee;
            color: var(--text-muted);
            font-size: 0.85rem;
        }

        .floating-wa {
            position: fixed;
            bottom: 20px;
            left: 20px;
            background-color: var(--accent);
            color: white;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            text-decoration: none;
            font-size: 28px;
            z-index: 1000;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>M.R – הכול לבית שלך!</h1>
            <div class="subtitle">M.R – Всё для вашего дома!</div>
            <p>שירות מקיף ומקצועי ומהיר בכל מקום בישראל<br><small>Быстрый профессиональный сервис по всему Израилю</small></p>
            
            <div class="contact-btns">
                <a href="https://wa.me/972559423309" class="btn-main btn-whatsapp" target="_blank">💬 WhatsApp · 055-9423309</a>
                <a href="tel:0559423309" class="btn-main btn-phone">📞 התקשרו · Позвонить</a>
            </div>
        </header>

        <h2>בחרו שירות · Выберите услугу</h2>
        <div class="grid">
            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%90%D7%99%D7%A0%D7%A1%D7%98%D7%9C%D7%A6%D7%99%D7%94.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🚰</span>
                    <div class="card-title">אינסטלציה <small>Сантехника</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%A6%D7%91%D7%A2.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🎨</span>
                    <div class="card-title">צבע <small>Покраска</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%97%D7%99%D7%93%D7%95%D7%A9%20%D7%A8%D7%94%D7%99%D7%98%D7%99%D7%9D.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🛋️</span>
                    <div class="card-title">חידוש רהיטים <small>Обновление мебели</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A0%D7%99%D7%A7%D7%99%D7%95%D7%9F.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🧹</span>
                    <div class="card-title">ניקיון <small>Уборка</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%A8%D7%99%D7%A1%D7%95%D7%AA%20%D7%95%D7%A7%D7%99%D7%A8%D7%95%D7%AA.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🧱</span>
                    <div class="card-title">הריסות <small>Демонтаж</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A9%D7%99%D7%A4%D7%95%D7%A6%D7%99%D7%9D.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">📐</span>
                    <div class="card-title">שיפוצים <small>Ремонт</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%92%D7%91%D7%A1.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA%20%D7%A9%D7%9C%20%D7%94%D7%A2%D7%91%D7%95%D7%93%D7%94.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🪚</span>
                    <div class="card-title">עבודות גבס <small>Гипсокартон</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>
        </div>

        <h2 id="moves">🚚 הובלות · Перевозки</h2>
        <div class="grid">
            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%92%D7%93%D7%95%D7%9C%D7%94%20%28%D7%93%D7%99%D7%A8%D7%94/%D7%91%D7%99%D7%AA%29.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🚛</span>
                    <div class="card-title">הובלות גדולות <small>Большой переезд</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%A7%D7%98%D7%A0%D7%94.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">📦</span>
                    <div class="card-title">הובלות קטנות <small>Малые перевозки</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%AA%20%D7%A8%D7%94%D7%99%D7%98%20%D7%90%D7%97%D7%93.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🛋️</span>
                    <div class="card-title">הובלת רהיט אחד <small>Перевозка одного предмета мебели</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>

            <a href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%AA%20%D7%9E%D7%A9%D7%A8%D7%93.%20%D7%9E%D7%A6%D7%95%D7%A8%D7%A4%D7%95%D7%AA%20%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA.%20%D7%90%D7%A9%D7%9E%D7%97%20%D7%9C%D7%94%D7%A6%D7%A2%D7%AA%20%D7%9E%D7%97%D7%99%D7%A8." class="card" target="_blank">
                <div class="card-header">
                    <span style="font-size: 1.5rem;">🏢</span>
                    <div class="card-title">הובלות משרדים <small>Офисный переезд</small></div>
                </div>
                <div class="card-action">📷 שלח הודעה + תמונות</div>
            </a>
        </div>

        <footer>
            Matan Richter © M.R הכול לבית
        </footer>
    </div>

    <!-- כפתור וואטסאפ צף למובייל -->
    <a href="https://wa.me/972559423309" class="floating-wa" target="_blank" title="דברו איתי ב-WhatsApp">💬</a>

</body>
</html>
