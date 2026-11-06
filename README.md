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
<!-- אזור התגובות והכוכבים -->
<section id="reviews-section" class="reviews-container">
  <h2>⭐ חוות דעת ותגובות לקוחות</h2>
  
  <!-- טופס הוספת תגובה -->
  <form id="review-form" class="review-form">
    <h3>✍️ השארת חוות דעת</h3>
    
    <label for="reviewer-name">שם מלא:</label>
    <input type="text" id="reviewer-name" required placeholder="הכנס את שמך">
    
    <label for="service-category">בחר שירות / קטגוריה:</label>
    <select id="service-category" required>
      <option value="" disabled selected>בחר שירות...</option>
      <option value="אינסטלציה">🚰 אינסטלציה</option>
      <option value="צבע">🎨 צבע</option>
      <option value="חידוש רהיטים">🛋️ חידוש רהיטים</option>
      <option value="ניקיון">🧹 ניקיון</option>
      <option value="הריסות">🧱 הריסות</option>
      <option value="שיפוצים">📐 שיפוצים</option>
      <option value="הובלות">🚚 הובלות</option>
      <option value="עבודות גבס">🪚 עבודות גבס</option>
    </select>
    
    <label>דירוג (0 עד 5 כוכבים):</label>
    <div class="star-rating">
      <span class="star" data-value="1">★</span>
      <span class="star" data-value="2">★</span>
      <span class="star" data-value="3">★</span>
      <span class="star" data-value="4">★</span>
      <span class="star" data-value="5">★</span>
    </div>
    <input type="hidden" id="selected-rating" value="0">
    <div id="rating-text">דירוג נבחר: 0 מתוך 5 כוכבים</div>
    
    <label for="review-comment">תגובה / פירוט:</label>
    <textarea id="review-comment" rows="4" required placeholder="ספר לנו על חווית השירות..."></textarea>
    
    <button type="submit" class="submit-btn">פרסם תגובה ושלח לוואטסאפ 💬</button>
  </form>

  <hr style="margin: 20px 0; border: 0; border-top: 1px solid #ddd;">

  <!-- סינון תגובות לפי קטגוריה -->
  <div class="filter-container">
    <label for="filter-category"><strong>סינון תגובות לפי קטגוריה:</strong></label>
    <select id="filter-category" onchange="renderReviews()" style="padding: 5px; margin-right: 10px; border-radius: 4px;">
      <option value="ALL">כל הקטגוריות</option>
      <option value="אינסטלציה">🚰 אינסטלציה</option>
      <option value="צבע">🎨 צבע</option>
      <option value="חידוש רהיטים">🛋️ חידוש רהיטים</option>
      <option value="ניקיון">🧹 ניקיון</option>
      <option value="הריסות">🧱 הריסות</option>
      <option value="שיפוצים">📐 שיפוצים</option>
      <option value="הובלות">🚚 הובלות</option>
      <option value="עבודות גבס">🪚 עבודות גבס</option>
    </select>
  </div>

  <!-- רשימת התגובות -->
  <div id="reviews-list" class="reviews-list"></div>
</section>

<!-- עיצוב CSS (אפשר להעביר גם לתגיות ה-Style המרכזיות באתר) -->
<style>
  .reviews-container {
    max-width: 600px;
    margin: 20px auto;
    padding: 15px;
    direction: rtl;
    font-family: sans-serif;
    text-align: right;
  }
  .review-form {
    background: #f9f9f9;
    padding: 15px;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    gap: 10px;
    border: 1px solid #e5e5e5;
  }
  .review-form input, 
  .review-form select, 
  .review-form textarea {
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 14px;
  }
  .star-rating {
    display: flex;
    gap: 5px;
    font-size: 28px;
    cursor: pointer;
  }
  .star {
    color: #ccc;
    transition: color 0.2s;
  }
  .star.active {
    color: #ffc107;
  }
  .submit-btn {
    background-color: #25d366;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
  }
  .submit-btn:hover {
    background-color: #20ba5a;
  }
  .reviews-list {
    margin-top: 15px;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .review-card {
    border: 1px solid #ddd;
    padding: 12px;
    border-radius: 6px;
    background: #fff;
  }
  .review-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .badge {
    background: #e2e8f0;
    padding: 2px 8px;
    border-radius: 12px;
    font-size: 12px;
    color: #333;
  }
  .review-stars {
    color: #ffc107;
    margin: 5px 0;
    font-size: 14px;
  }
  .review-body {
    margin: 5px 0;
    color: #333;
  }
  .review-date {
    color: #888;
    font-size: 11px;
  }
</style>

<!-- סקריפט JavaScript לפעילות המערכת -->
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<script>
  const SUPABASE_URL = 'YOUR_SUPABASE_URL';
  const SUPABASE_KEY = 'YOUR_SUPABASE_ANON_KEY';
  const supabase = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);

  let currentRating = 0;
  const stars = document.querySelectorAll('.star');
  const ratingInput = document.getElementById('selected-rating');
  const ratingText = document.getElementById('rating-text');

  stars.forEach(star => {
    star.addEventListener('click', function() {
      currentRating = parseInt(this.getAttribute('data-value'));
      ratingInput.value = currentRating;
      ratingText.innerText = `דירוג נבחר: ${currentRating} מתוך 5 כוכבים`;
      updateStarUI();
    });
  });

  function updateStarUI() {
    stars.forEach(star => {
      const val = parseInt(star.getAttribute('data-value'));
      if (val <= currentRating) {
        star.classList.add('active');
      } else {
        star.classList.remove('active');
      }
    });
  }

  document.getElementById('review-form').addEventListener('submit', async function(e) {
    e.preventDefault();
    
    const name = document.getElementById('reviewer-name').value;
    const category = document.getElementById('service-category').value;
    const rating = parseInt(document.getElementById('selected-rating').value);
    const comment = document.getElementById('review-comment').value;

    const { data, error } = await supabase
      .from('reviews')
      .insert([{ name, category, rating, comment, created_at: new Date() }]);

    if (error) {
      alert('שגיאה בשמירת התגובה. אנא נסה שוב.');
      console.error(error);
      return;
    }

    const whatsappPhone = '972559423309';
    const starsStr = '⭐'.repeat(rating) || '0 כוכבים';
    const message = `שלום M.R! התקבלה חוות דעת חדשה באתר:\n\n👤 *שם:* ${name}\n🛠️ *קטגוריה:* ${category}\n⭐ *דירוג:* ${rating}/5 (${starsStr})\n💬 *תגובה:* ${comment}`;
    
    const waUrl = `https://wa.me/${whatsappPhone}?text=${encodeURIComponent(message)}`;
    window.open(waUrl, '_blank');

    document.getElementById('review-form').reset();
    currentRating = 0;
    updateStarUI();
    ratingText.innerText = 'דירוג נבחר: 0 מתוך 5 כוכבים';
    fetchReviews();
  });

  let allReviews = [];
  async function fetchReviews() {
    const { data, error } = await supabase
      .from('reviews')
      .select('*')
      .order('created_at', { ascending: false });

    if (!error && data) {
      allReviews = data;
      renderReviews();
    }
  }

  function renderReviews() {
    const container = document.getElementById('reviews-list');
    const filter = document.getElementById('filter-category').value;
    container.innerHTML = '';

    const filtered = filter === 'ALL' 
      ? allReviews 
      : allReviews.filter(r => r.category === filter);

    if (filtered.length === 0) {
      container.innerHTML = '<p style="color: #666; font-size: 14px;">אין עדיין תגובות בקטגוריה זו.</p>';
      return;
    }

    filtered.forEach(r => {
      const item = document.createElement('div');
      item.className = 'review-card';
      const starsDisplay = '⭐'.repeat(r.rating) || '0 כוכבים';
      item.innerHTML = `
        <div class="review-header">
          <strong>${r.name}</strong>
          <span class="badge">${r.category}</span>
        </div>
        <div class="review-stars">${starsDisplay} (${r.rating}/5)</div>
        <p class="review-body">${r.comment}</p>
        <small class="review-date">${new Date(r.created_at).toLocaleDateString('he-IL')}</small>
      `;
      container.appendChild(item);
    });
  }

  fetchReviews();
</script>
