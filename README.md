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
            margin-top: 40px;
            background: #fafafa;
            border: 2px dashed #007bff;
            padding: 20px;
            border-radius: 8px;
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
            padding: 10px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
        }
        
        /* כוכבים פיזיים אמיתיים עם חצאים */
        .stars-container {
            display: flex;
            flex-direction: row-reverse;
            justify-content: flex-end;
            gap: 5px;
            font-size: 32px;
            cursor: pointer;
            unicode-bidi: bidi-override;
        }
        .star {
            color: #ddd;
            cursor: pointer;
            position: relative;
            display: inline-block;
            transition: color 0.2s;
        }
        .star.active {
            color: #ffc107;
        }
        .star.half {
            color: #ffc107;
        }

        .reviews-list {
            margin-top: 20px;
            border-top: 1px solid #ddd;
            padding-top: 15px;
        }
        .review-card {
            background: #fff;
            border: 1px solid #e1e1e1;
            padding: 12px 15px;
            border-radius: 6px;
            margin-bottom: 12px;
            text-align: right;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .review-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 14px;
            color: #444;
            margin-bottom: 5px;
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
        <a href="https://wa.me/972559423309" class="btn" style="background: #25d366; display: inline-block;">💬 WhatsApp · 055-9423309</a>
    </div>

    <h2>בחרו שירות · Выберите услугу</h2>
    <div class="services-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%90%D7%99%D7%A0%D7%A1%D7%98%D7%9C%D7%A6%D7%99%D7%94.">🚰 אינסטלציה</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%A6%D7%91%D7%A2.">🎨 צבע</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%A0%D7%99%D7%99%D7%9F/%D7%AA%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%97%D7%99%D7%93%D7%95%D7%A9%20%D7%A8%D7%94%D7%99%D7%98%D7%99%D7%9D.">🛋️ חידוש רהיטים</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%90%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A0%D7%99%D7%A7%D7%99%D7%95%D7%9F.">🧹 ניקיון</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%99%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%A8%D7%99%D7%A1%D7%95%D7%AA%20%D7%95%D7%A7%D7%99%D7%A8%D7%95%D7%AA.">🧱 הריסות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A9%D7%99%D7%A4%D7%95%D7%A6%D7%99%D7%9D.">📐 שיפוצים</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%A2%D7%91%D7%95%D7%93%D7%95%D7%AA%20%D7%92%D7%91%D7%A1.">🪚 עבודות גבס</a>
    </div>

    <h2>🚚 הובלות · Перевозки</h2>
    <div class="moves-grid">
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%92%D7%93%D7%95%D7%9C%D7%94.">🚛 הובלות גדולות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%9C%D7%94%20%D7%A7%D7%98%D7%95%D7%90.">📦 הובלות קטנות</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%91%D7%AA%20%D7%A8%D7%94%D7%95%D7%98%20%D7%90%D7%97%D7%93.">🛋️ הובלת רהיט אחד</a>
        <a class="btn" href="https://wa.me/972559423309?text=%D7%A9%D7%9C%D7%95%D7%9D%2C%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%A2%D7%95%D7%9D%2C%20%D7%91%D7%A9%D7%99%D7%A8%D7%95%D7%AA%3A%20%D7%94%D7%95%D7%AA%20%D7%9E%D7%A9%D7%A8%D7%93.">🏢 הובלות משרדים</a>
    </div>

    <!-- אזור תגובות ודירוגים -->
    <div class="reviews-section">
        <h2>⭐ תגובות לקוחות ודירוגים</h2>
        <h3>✍️ השאר תגובה ודרג אותנו:</h3>
        
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
                <label>דירוג כוכבים (לחץ על הכוכבים לבחירה, כולל חצאים):</label>
                <div class="stars-container" id="starPicker">
                    <span class="star" data-value="5">★</span>
                    <span class="star" data-value="4.5">★</span>
                    <span class="star" data-value="4">★</span>
                    <span class="star" data-value="3.5">★</span>
                    <span class="star" data-value="3">★</span>
                    <span class="star" data-value="2.5">★</span>
                    <span class="star" data-value="2">★</span>
                    <span class="star" data-value="1.5">★</span>
                    <span class="star" data-value="1">★</span>
                    <span class="star" data-value="0.5">★</span>
                </div>
                <div style="margin-top: 5px; font-weight: bold; color: #007bff;" id="ratingText">דירוג נבחר: 5 מתוך 5 כוכבים</div>
                <input type="hidden" id="reviewRating" value="5" required>
            </div>

            <div class="form-group">
                <label for="reviewText">התגובה שלך:</label>
                <textarea id="reviewText" rows="3" required placeholder="כתוב כאן את חוות דעתך..."></textarea>
            </div>

            <button type="submit" class="btn" style="background: #28a745; width: 100%; border: none; cursor: pointer; font-size: 16px; padding: 12px;">פרסם תגובה באתר ושלח לוואטסאפ 🚀</button>
        </form>

        <!-- אזור הצגה וסינון תגובות -->
        <div style="margin-top: 35px;">
            <div class="filter-container">
                <label for="filterCategory" style="display: inline-block; margin-left: 10px; font-weight: bold;">סנן תגובות לפי קטגוריה:</label>
                <select id="filterCategory" onchange="renderReviews()" style="width: 220px; display: inline-block;">
                    <option value="all">הצג הכל (מכל הקטגוריות)</option>
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
    // טעינת תגובות מזיכרון הדפדפן
    let reviews = JSON.parse(localStorage.getItem('mr_reviews')) || [];

    const reviewForm = document.getElementById('reviewForm');
    const reviewsList = document.getElementById('reviewsList');
    const filterCategory = document.getElementById('filterCategory');
    const reviewRatingInput = document.getElementById('reviewRating');
    const ratingText = document.getElementById('ratingText');
    const stars = document.querySelectorAll('#starPicker .star');

    // ניהול בחירת כוכבים פיזית (כולל חצאים)
    stars.forEach(star => {
        star.addEventListener('click', function() {
            let val = parseFloat(this.getAttribute('data-value'));
            reviewRatingInput.value = val;
            ratingText.innerHTML = `דירוג נבחר: ${val} מתוך 5 כוכבים`;

            // עדכון צבע הכוכבים פיזית
            stars.forEach(s => {
                let sVal = parseFloat(s.getAttribute('data-value'));
                if (sVal <= val) {
                    s.classList.add('active');
                } else {
                    s.classList.remove('active');
                }
            });
        });
    });

    // הפעלה ראשונית של סימון 5 כוכבים כברירת מחדל
    stars.forEach(s => s.classList.add('active'));

    // המרת מספר כוכבים לתצוגה בכרטיסייה
    function getStarsHTML(rating) {
        let fulls = Math.floor(rating);
        let hasHalf = (rating - fulls) >= 0.5;
        let str = '';
        for(let i=0; i<fulls; i++) str += '⭐';
        if(hasHalf) str += '✨';
        return `${str} (${rating}/5)`;
    }

    // פונקציה להצגת כל התגובות או לפי סינון
    function renderReviews() {
        reviewsList.innerHTML = '';
        let selectedFilter = filterCategory.value;

        let filteredReviews = reviews;
        if (selectedFilter !== 'all') {
            filteredReviews = reviews.filter(r => r.category === selectedFilter);
        }

        if (filteredReviews.length === 0) {
            reviewsList.innerHTML = '<p style="color: #777; text-align: center; padding: 10px;">אין עדיין תגובות להצגה בקטגוריה זו.</p>';
            return;
        }

        filteredReviews.forEach(review => {
            let card = document.createElement('div');
            card.className = 'review-card';
            card.innerHTML = `
                <div class="review-header">
                    <span>👤 ${review.name} <span style="color: #007bff; font-weight: normal;">(${review.category})</span></span>
                    <span>${getStarsHTML(review.rating)}</span>
                </div>
                <p style="margin: 8px 0; color: #333; word-break: break-word;">${review.text}</p>
                <div style="font-size: 11px; color: #888; text-align: left;">📅 ${review.date}</div>
            `;
            reviewsList.appendChild(card);
        });
    }

    // שליחת טופס התגובה
    reviewForm.addEventListener('submit', function(e) {
        e.preventDefault();

        let name = document.getElementById('reviewerName').value.trim();
        let category = document.getElementById('reviewCategory').value;
        let rating = parseFloat(reviewRatingInput.value);
        let text = document.getElementById('reviewText').value.trim();
        let date = new Date().toLocaleDateString('he-IL');

        if (!name || !category || !text) {
            alert('אנא מלא את כל השדות בטופס.');
            return;
        }

        let newReview = { name, category, rating, text, date };

        // הוספה למערך ושמירה מקומית
        reviews.unshift(newReview);
        localStorage.setItem('mr_reviews', JSON.stringify(reviews));

        // איפוס הטופס וחזרה למצב הכללי כדי לראות את התגובה
        reviewForm.reset();
        reviewRatingInput.value = '5';
        ratingText.innerHTML = 'דירוג נבחר: 5 מתוך 5 כוכבים';
        stars.forEach(s => s.classList.add('active'));
        filterCategory.value = 'all';
        renderReviews();

        // יצירת קישור וואטסאפ ופתיחתו באופן בטוח
        let whatsappMessage = `*💬 תגובה חדשה התקבלה באתר!*%0A%0A` +
                              `👤 *שם:* ${encodeURIComponent(name)}%0A` +
                              `🏷️ *קטגוריה:* ${encodeURIComponent(category)}%0A` +
                              `⭐ *דירוג:* ${rating} כוכבים%0A` +
                              `📝 *תוכן התגובה:* ${encodeURIComponent(text)}`;

        let whatsappUrl = `https://wa.me/972559423309?text=${whatsappMessage}`;
        window.open(whatsappUrl, '_blank');
    });

    // טעינת התגובות הראשונית בעליית העמוד
    renderReviews();
</script>

</body>
</html>




