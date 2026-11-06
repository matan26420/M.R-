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
        .reviews-section {
            margin-top: 30px;
            text-align: right;
        }
        .form-group {
            margin-bottom: 15px;
            text-align: right;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        /* Stars styling */
        .star-rating {
            display: flex;
            flex-direction: row-reverse;
            justify-content: flex-end;
            gap: 5px;
            font-size: 24px;
            cursor: pointer;
        }
        .star-rating input {
            display: none;
        }
        .star-rating label {
            color: #ddd;
            cursor: pointer;
        }
        .star-rating input:checked ~ label,
        .star-rating label:hover,
        .star-rating label:hover ~ label {
            color: #f39c12;
        }
        .reviews-list {
            margin-top: 20px;
            border-top: 1px solid #eee;
            padding-top: 15px;
        }
        .review-card {
            background: #f9f9f9;
            border: 1px solid #e1e1e1;
            padding: 10px 15px;
            border-radius: 5px;
            margin-bottom: 10px;
            text-align: right;
        }
        .review-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 14px;
            color: #555;
        }
        .filter-container {
            margin-bottom: 15px;
            text-align: right;
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
    <h1>M.R – הכול לבית שלך!</h1>
    <p>שירות מקיף ומקצועי ומהיר בכל מקום בישראל · Быстрый профессиональный сервис по всему Израилю</p>

    <div style="margin: 20px 0;">
        <a href="https://wa.me/972559423309" class="btn" style="background: #25d366; display: inline-block; margin-bottom: 10px;">💬 WhatsApp · 055-9423309</a>
    </div>

    <h2>בחרו שירות · Выберите услугу</h2>
    <div class="services-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%90%D7%99%D7%A0%D7%A1%D7%98%D7%9C%D7%A6%D7%99%D7%94.">🚰 אינסטלציה</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%A6%D7%91%D7%A2.">🎨 צבע</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%97%D7%99%D7%93%D7%95%D7%A9%20%D7%A8%D7%94%D7%99%D7%98%D7%99%D7%9D.">🛋️ חידוש רהיטים</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A0%D7%99%D7%A7%D7%99%D7%95%D7%9F.">🧹 ניקיון</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%A8%D7%99%D7%A1%D7%95%D7%AA%20%D7%95%D7%A7%D7%99%D7%A8%D7%95%D7%AA.">🧱 הריסות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A9%D7%99%D7%A4%D7%95%D7%A6%D7%99%D7%9D.">📐 שיפוצים</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%92%D7%91%D7%A1.">🪚 עבודות גבס</a>
    </div>

    <h2>🚚 הובלות · Перевозки</h2>
    <div class="moves-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%92%D7%93%D7%95%D7%9C%D7%94.">🚛 הובלות גדולות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%A7%D7%98%D7%A0%D7%94.">📦 הובלות קטנות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%AA%20%D7%A8%D7%94%D7%99%D7%98%20%D7%90%D7%97%D7%93.">🛋️ הובלת רהיט אחד</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%AA%20%D7%9E%D7%A9%D7%A8%D7%93.">🏢 הובלות משרדים</a>
    </div>

    <!-- אזור תגובות ודירוגים -->
    <div class="reviews-section">
        <h2>⭐ תגובות לקוחות</h2>
        <h3>✍️ כתבו תגובה על עבודה שעשיתי לכם</h3>
        
        <form id="reviewForm">
            <div class="form-group">
                <label for="reviewerName">שם מלא:</label>
                <input type="text" id="reviewerName" required placeholder="הכנס את שמך">
            </div>

            <div class="form-group">
                <label for="reviewCategory">בחר קטגוריה:</label>
                <select id="reviewCategory" required>
                    <option value="">בחר שירות...</option>
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

            <div class="form-group">
                <label>דירוג (0 עד 5 כוכבים, כולל חצאים):</label>
                <div style="display: flex; align-items: center; gap: 10px;">
                    <input type="number" id="reviewRating" min="0" max="5" step="0.5" value="5" required style="width: 80px;">
                    <span style="font-size: 14px; color: #666;">(לדוגמה: 4.5 או 5)</span>
                </div>
            </div>

            <div class="form-group">
                <label for="reviewText">התגובה שלך:</label>
                <textarea id="reviewText" rows="3" required placeholder="ספר על השירות שקיבלת..."></textarea>
            </div>

            <button type="submit" class="btn" style="background: #28a745; width: 100%; border: none; cursor: pointer;">שלח תגובה</button>
        </form>

        <!-- סינון תגובות -->
        <div style="margin-top: 30px;">
            <div class="filter-container">
                <label for="filterCategory" style="display: inline-block; margin-left: 10px;">סנן לפי קטגוריה:</label>
                <select id="filterCategory" onchange="renderReviews()" style="width: 200px; display: inline-block;">
                    <option value="all">הכל (מכל הקטגוריות)</option>
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

            <div class="reviews-list" id="reviewsList">
                <!-- כאן יופיעו התגובות -->
            </div>
        </div>
    </div>

    <footer>
        Matan Richter© M.R הכול לבית
    </footer>
</div>

<script>
    // טעינת תגובות שמורות מהזיכרון המקומי (LocalStorage)
    let reviews = JSON.parse(localStorage.getItem('mr_reviews')) || [];

    const reviewForm = document.getElementById('reviewForm');
    const reviewsList = document.getElementById('reviewsList');
    const filterCategory = document.getElementById('filterCategory');

    // פונקציה להמרת מספר כוכבים לאייקונים של כוכבים
    function getStarsHTML(rating) {
        let stars = '';
        let fullStars = Math.floor(rating);
        let hasHalfStar = (rating - fullStars) >= 0.5;

        for (let i = 0; i < fullStars; i++) {
            stars += '⭐';
        }
        if (hasHalfStar) {
            stars += '⭐'; // אפשר לשים חצי כוכב אם תרצה, או להסתפק בכוכב מלא/סימן
        }
        return `${stars} (${rating})`;
    }

    // הצגת התגובות באתר
    function renderReviews() {
        reviewsList.innerHTML = '';
        let selectedFilter = filterCategory.value;

        let filteredReviews = reviews;
        if (selectedFilter !== 'all') {
            filteredReviews = reviews.filter(r => r.category === selectedFilter);
        }

        if (filteredReviews.length === 0) {
            reviewsList.innerHTML = '<p style="color: #777; text-align: center;">אין עדיין תגובות בקטגוריה זו.</p>';
            return;
        }

        filteredReviews.forEach(review => {
            let card = document.createElement('div');
            card.className = 'review-card';
            card.innerHTML = `
                <div class="review-header">
                    <span>${review.name} (${review.category})</span>
                    <span>${getStarsHTML(review.rating)}</span>
                </div>
                <p style="margin: 8px 0 0 0;">${review.text}</p>
                <div style="font-size: 11px; color: #999; margin-top: 5px; text-align: left;">${review.date}</div>
            `;
            reviewsList.appendChild(card);
        });
    }

    // טיפול בשליחת הטופס
    reviewForm.addEventListener('submit', function(e) {
        e.preventDefault();

        let name = document.getElementById('reviewerName').value;
        let category = document.getElementById('reviewCategory').value;
        let rating = parseFloat(document.getElementById('reviewRating').value);
        let text = document.getElementById('reviewText').value;
        let date = new Date().toLocaleDateString('he-IL');

        let newReview = { name, category, rating, text, date };

        // הוספה לרשימה ושמירה בזיכרון המקומי של הדפדפן
        reviews.unshift(newReview);
        localStorage.setItem('mr_reviews', JSON.stringify(reviews));

        // איפוס הטופס ורענון התצוגה
        reviewForm.reset();
        document.getElementById('reviewRating').value = '5';
        renderReviews();

        // יצירת הודעה ושליחה לוואטסאפ שלך
        let whatsappMessage = `*תגובה חדשה התקבלה באתר!*%0A%0A` +
                              `👤 *שם:* ${encodeURIComponent(name)}%0A` +
                              `🏷️ *קטגוריה:* ${encodeURIComponent(category)}%0A` +
                              `⭐ *דירוג:* ${rating} כוכבים%0A` +
                              `💬 *תגובה:* ${encodeURIComponent(text)}`;

        let whatsappUrl = `https://wa.me/972559423309?text=${whatsappMessage}`;
        
        // פתיחת וואטסאפ לשליחת ההודעה אליך
        window.open(whatsappUrl, '_blank');
    });

    // טעינת התגובות בעת טעינת הדף
    renderReviews();
</script>

</body>
</html>

