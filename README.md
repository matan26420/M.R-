<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R – הכול לבית שלך!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        h1, h2 {
            color: #222;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .services-grid, .moves-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            margin-bottom: 20px;
        }
        a.btn {
            display: block;
            background: #007bff;
            color: white;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        a.btn:hover {
            background: #0056b3;
        }
        .review-box {
            background: #fdfdfd;
            border: 2px solid #007bff;
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
            text-align: right;
        }
        .input-group {
            margin-bottom: 15px;
        }
        .input-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .input-group input, .input-group select, .input-group textarea {
            width: 100%;
            padding: 10px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        /* כפתורי בחירת רייטינג פיזיים */
        .rating-buttons {
            display: flex;
            gap: 5px;
            flex-wrap: wrap;
            justify-content: flex-end;
        }
        .rate-btn {
            background: #e9ecef;
            border: 1px solid #ced4da;
            padding: 8px 12px;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
            font-size: 14px;
            transition: all 0.2s;
        }
        .rate-btn.selected {
            background: #ffc107;
            color: #000;
            border-color: #d39e00;
        }
        .reviews-display {
            margin-top: 25px;
            border-top: 1px solid #ddd;
            padding-top: 15px;
        }
        .review-card {
            background: #fff;
            border: 1px solid #e0e0e0;
            padding: 12px;
            border-radius: 6px;
            margin-bottom: 10px;
            text-align: right;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        footer {
            margin-top: 20px;
            font-size: 12px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>M.R – הכול לבית שלך[span_0](start_span)[span_0](end_span)!</h1>
    <p>שירות מקיף ומקצועי ומהיר בכל מקום בישראל[span_1](start_span)[span_1](end_span)</p>

    <div style="margin: 20px 0;">
        <a href="https://wa.me/972559423309" class="btn" style="background: #25d366; display: inline-block;">💬 WhatsApp · 055-9423309[span_2](start_span)[span_2](end_span)</a>
    </div>

    <h2>בחרו שירות · Выберите услугу[span_3](start_span)[span_3](end_span)</h2>
    <div class="services-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%90%D7%99%D7%A0%D7%A1%D7%98%D7%9C%D7%A6%D7%99%D7%94.">🚰 אינסטלציה[span_4](start_span)[span_4](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%A6%D7%91%D7%A2.">🎨 צבע[span_5](start_span)[span_5](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%97%D7%99%D7%93%D7%95%D7%A9%20%D7%A8%D7%94%D7%99%D7%98%D7%99%D7%9D.">🛋️ חידוש רהיטים[span_6](start_span)[span_6](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A0%D7%99%D7%A7%D7%99%D7%95%D7%9F.">🧹 ניקיון[span_7](start_span)[span_7](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%A8%D7%99%D7%A1%D7%95%D7%AA%20%D7%95%D7%A7%D7%99%D7%A8%D7%95%D7%AA.">🧱 הריסות[span_8](start_span)[span_8](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A9%D7%99%D7%A4%D7%95%D7%A6%D7%99%D7%9D.">📐 שיפוצים[span_9](start_span)[span_9](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%92%D7%91%D7%A1.">🪚 עבודות גבס[span_10](start_span)[span_10](end_span)</a>
    </div>

    <h2>🚚 הובלות · Перевозки[span_11](start_span)[span_11](end_span)</h2>
    <div class="moves-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%92%D7%93%D7%95%D7%9C%D7%94.">🚛 הובלות גדולות[span_12](start_span)[span_12](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%A7%D7%98%D7%95%D7%90.">📦 הובלות קטנות[span_13](start_span)[span_13](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%AA%20%D7%A8%D7%94%D7%95%D7%98%20%D7%90%D7%97%D7%93.">🛋️ הובלת רהיט אחד[span_14](start_span)[span_14](end_span)</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%AA%20%D7%9E%D7%A9%D7%A8%D7%93.">🏢 הובלות משרדים[span_15](start_span)[span_15](end_span)</a>
    </div>

    <!-- אזור תגובות ודירוג חדש ונפרד לגמרי -->
    <div class="review-box">
        <h2>⭐ מערכת תגובות ורייטינג לעבודה</h2>
        <p style="font-size: 13px; color: #555;">בחר את הקטגוריה שעליה תרצה לתת חוות דעת, דרג בכוכבים (כולל חצאים) ושלח אליי ישירות!</p>

        <form id="myReviewForm">
            <div class="input-group">
                <label>שם הממליץ:</label>
                <input type="text" id="revName" required placeholder="הכנס את שמך המלא">
            </div>

            <div class="input-group">
                <label>בחר קטגוריית שירות:</label>
                <select id="revCategory" required>
                    <option value="">בחר מהרשימה...</option>
                    <option value="אינסטלציה">אינסטלציה</option>
                    <option value="צבע">צבע</option>
                    <option value="חידוש רהיטים">חידוש רהיטים</option>
                    <option value="ניקיון">ניקיון</option>
                    <option value="הריסות">הריסות</option>
                    <option value="שיפוצים">שיפוצים</option>
                    <option value="עבודות גבס">עבודות גבס</option>
                    <option value="הובלות גדולות">הובלות גדולות</option>
                    <option value="הובלות קטנות">הובלות קטנות</option>
                    <option value="הובלת רהיט אחד">הובלת רהיט אחד</option>
                    <option value="הובלות משרדים">הובלות משרדים</option>
                </select>
            </div>

            <div class="input-group">
                <label>דירוג רייטינג (בחר מספר כוכבים / חצאים):</label>
                <div class="rating-buttons" id="ratingButtons">
                    <button type="button" class="rate-btn" data-val="0.5">⭐ 0.5</button>
                    <button type="button" class="rate-btn" data-val="1">⭐ 1</button>
                    <button type="button" class="rate-btn" data-val="1.5">⭐ 1.5</button>
                    <button type="button" class="rate-btn" data-val="2">⭐ 2</button>
                    <button type="button" class="rate-btn" data-val="2.5">⭐ 2.5</button>
                    <button type="button" class="rate-btn" data-val="3">⭐ 3</button>
                    <button type="button" class="rate-btn" data-val="3.5">⭐ 3.5</button>
                    <button type="button" class="rate-btn" data-val="4">⭐ 4</button>
                    <button type="button" class="rate-btn" data-val="4.5">⭐ 4.5</button>
                    <button type="button" class="rate-btn selected" data-val="5">⭐ 5</button>
                </div>
                <input type="hidden" id="revRating" value="5">
            </div>

            <div class="input-group">
                <label>התגובה שלך על העבודה:</label>
                <textarea id="revText" rows="3" required placeholder="ספר בקצרה איך היה השירות..."></textarea>
            </div>

            <button type="submit" class="btn" style="background: #28a745; width: 100%; border: none; cursor: pointer; font-size: 16px; padding: 12px;">שמור תגובה באתר ושלח אליי לוואטסאפ 🚀</button>
        </form>

        <!-- אזור סינון והצגת התגובות -->
        <div style="margin-top: 30px;">
            <div class="input-group">
                <label style="font-weight: bold;">סנן תגובות לפי קטגוריה:</label>
                <select id="filterSelect" onchange="loadReviews()">
                    <option value="ALL">הצג את כל התגובות מכל הקטגוריות</option>
                    <option value="אינסטלציה">אינסטלציה</option>
                    <option value="צבע">צבע</option>
                    <option value="חידוש רהיטים">חידוש רהיטים</option>
                    <option value="ניקיון">ניקיון</option>
                    <option value="הריסות">הריסות</option>
                    <option value="שיפוצים">שיפוצים</option>
                    <option value="עבודות גבס">עבודות גבס</option>
                    <option value="הובלות גדולות">הובלות גדולות</option>
                    <option value="הובלות קטנות">הובלות קטנות</option>
                    <option value="הובלת רהיט אחד">הובלת רהיט אחד</option>
                    <option value="הובלות משרדים">הובלות משרדים</option>
                </select>
            </div>

            <div class="reviews-display" id="reviewsContainer">
                <!-- כאן יופיעו התגובות -->
            </div>
        </div>
    </div>

    <footer>
        Matan Richter© M.R הכול לבית[span_16](start_span)[span_16](end_span)
    </footer>
</div>

<script>
    // בחירת רייטינג בכפתורים פיזיים
    const rateButtons = document.querySelectorAll('.rate-btn');
    const revRatingInput = document.getElementById('revRating');

    rateButtons.forEach(btn => {
        btn.addEventListener('click', function() {
            rateButtons.forEach(b => b.classList.remove('selected'));
            this.classList.add('selected');
            revRatingInput.value = this.getAttribute('data-val');
        });
    });

    // מערכת שמירה והצגה של תגובות
    const reviewForm = document.getElementById('myReviewForm');
    const reviewsContainer = document.getElementById('reviewsContainer');
    const filterSelect = document.getElementById('filterSelect');

    function getSavedReviews() {
        return JSON.parse(localStorage.getItem('mr_site_reviews')) || [];
    }

    function loadReviews() {
        let reviews = getSavedReviews();
        let currentFilter = filterSelect.value;
        reviewsContainer.innerHTML = '';

        let filtered = reviews;
        if (currentFilter !== 'ALL') {
            filtered = reviews.filter(r => r.category === currentFilter);
        }

        if (filtered.length === 0) {
            reviewsContainer.innerHTML = '<p style="color: #777;">אין עדיין תגובות להצגה בקטגוריה זו.</p>';
            return;
        }

        filtered.forEach(item => {
            let card = document.createElement('div');
            card.className = 'review-card';
            card.innerHTML = `
                <div style="display: flex; justify-content: space-between; font-weight: bold; font-size: 14px; margin-bottom: 5px;">
                    <span>👤 ${item.name} <span style="color: #007bff; font-weight: normal;">(${item.category})</span></span>
                    <span>⭐ ${item.rating} / 5</span>
                </div>
                <p style="margin: 5px 0; color: #333;">${item.text}</p>
                <div style="font-size: 11px; color: #888; text-align: left;">📅 ${item.date}</div>
            `;
            reviewsContainer.appendChild(card);
        });
    }

    reviewForm.addEventListener('submit', function(e) {
        e.preventDefault();

        let name = document.getElementById('revName').value.trim();
        let category = document.getElementById('revCategory').value;
        let rating = revRatingInput.value;
        let text = document.getElementById('revText').value.trim();
        let date = new Date().toLocaleDateString('he-IL');

        if (!name || !category || !text) {
            alert('אנא מלא את כל השדות.');
            return;
        }

        let newReview = { name, category, rating, text, date };
        let reviews = getSavedReviews();
        reviews.unshift(newReview);
        localStorage.setItem('mr_site_reviews', JSON.stringify(reviews));

        // איפוס טופס
        reviewForm.reset();
        revRatingInput.value = '5';
        rateButtons.forEach(b => b.classList.remove('selected'));
        document.querySelector('.rate-btn[data-val="5"]').classList.add('selected');
        filterSelect.value = 'ALL';
        loadReviews();

        // שליחה לוואטסאפ שלך
        let msg = `*💬 תגובה ודירוג חדשים מהאתר!*%0A%0A` +
                  `👤 *שם:* ${encodeURIComponent(name)}%0A` +
                  `🏷️ *קטגוריה:* ${encodeURIComponent(category)}%0A` +
                  `⭐ *דירוג:* ${rating} כוכבים%0A` +
                  `📝 *תגובה:* ${encodeURIComponent(text)}`;

        let waUrl = `https://wa.me/972559423309?text=${msg}`;
        window.open(waUrl, '_blank');
    });

    // טעינת תגובות בעליית העמוד
    loadReviews();
</script>

</body>
</html>



