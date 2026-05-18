<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مطعم وبيتزا أبو علي - الفرع الأساسي</title>

<style>
    /* تصميم عصري ملوكي فخم ومضمون الوضوح */
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background-color: #0b0b0b;
        color: #f5f5f5;
        margin: 0;
        padding: 15px;
        line-height: 1.6;
    }

    /* الهيدر والترحيب */
    header {
        text-align: center;
        padding: 35px 15px;
        background: linear-gradient(135deg, #220b02 0%, #441505 100%);
        border-radius: 25px;
        margin-bottom: 25px;
        border: 1px solid #ff6b35;
        box-shadow: 0 4px 20px rgba(255, 107, 53, 0.15);
    }

    header h1 {
        margin: 0;
        font-size: 28px;
        color: #ff6b35;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
    }

    header p {
        margin: 8px 0 0 0;
        color: #d4af37;
        font-weight: bold;
        font-size: 15px;
        letter-spacing: 1px;
    }

    /* الأقسام والبطاقات */
    section {
        margin-bottom: 30px;
        background: #141414;
        padding: 22px;
        border-radius: 20px;
        border: 1px solid #262626;
        box-shadow: 0 5px 15px rgba(0,0,0,0.6);
    }

    section h2 {
        font-size: 20px;
        color: #ff6b35;
        border-bottom: 2px solid #ff6b35;
        padding-bottom: 8px;
        margin-top: 0;
        margin-bottom: 20px;
        display: inline-block;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    li {
        background: #1a1a1a;
        margin-bottom: 12px;
        padding: 15px;
        border-radius: 14px;
        border-right: 4px solid #ff6b35;
    }

    .item-row {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .item-name {
        font-weight: bold;
        font-size: 16px;
        color: #ffffff;
    }

    .item-price {
        font-weight: bold;
        font-size: 17px;
        color: #ff6b35;
        background: #262626;
        padding: 4px 12px;
        border-radius: 8px;
        white-space: nowrap;
    }

    .ingredients {
        color: #b0b0b0;
        margin-top: 6px;
        font-size: 13px;
        font-style: italic;
    }

    /* تنسيق الجدول العائلي والأحجام بدقة */
    .table-container {
        overflow-x: auto;
        margin-top: 15px;
        border-radius: 12px;
        border: 1px solid #383838;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        background: #141414;
        color: #ffffff;
        font-size: 15px;
    }

    th, td {
        padding: 14px 10px;
        text-align: center;
        border: 1px solid #2d2d2d;
        white-space: nowrap;
    }

    th {
        background-color: #ff6b35;
        color: #000000;
        font-weight: bold;
        font-size: 16px;
    }

    tr:nth-child(even) {
        background: #1c1c1c;
    }

    td:first-child {
        font-weight: bold;
        color: #ff6b35;
        text-align: right;
    }
    
    td:not(:first-child) {
        color: #ffffff;
        font-weight: 600;
    }

    /* صندوق التواصل */
    .contact-section {
        background: linear-gradient(135deg, #141414 0%, #22120c 100%);
        border: 1px solid #d4af37;
        text-align: center;
    }

    .contact-card {
        margin-bottom: 20px;
        padding: 10px;
    }

    .contact-title {
        font-size: 16px;
        color: #d4af37;
        font-weight: bold;
        margin-bottom: 8px;
    }

    .contact-text {
        font-size: 16px;
        color: #e0e0e0;
        margin: 5px 0;
    }

    .btn-link {
        display: inline-block;
        width: 85%;
        max-width: 280px;
        margin: 8px auto;
        padding: 12px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: bold;
        font-size: 15px;
    }

    .btn-fb {
        background: linear-gradient(135deg, #1877f2 0%, #1153a8 100%);
        color: #ffffff;
        box-shadow: 0 4px 10px rgba(24, 119, 242, 0.3);
    }

    .btn-phone {
        background: linear-gradient(135deg, #25d366 0%, #1b9a4b 100%);
        color: #ffffff;
        box-shadow: 0 4px 10px rgba(37, 211, 102, 0.3);
    }
</style>
</head>

<body>

<header>
    <h1>مطعم وبيتزا أبو علي</h1>
    <p>🍕 أصالة المذاق.. وتاريخ نعتز به (الفرع الرئيسي) 🍕</p>
</header>

<section>
    <h2>🍕 قسم البيتزا والمعجنات</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">بيتزا سمول</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(ذرة، زيتون، fلفل، جبنة، صوص، نقانق)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">مسحب / باربيكيو</div><div class="item-price">12₪</div></div>
            <div class="ingredients">(صوص، جبنة، مسحب دجاج، صوص باربيكيو)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">خضار</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(صوص، جبنة، ذرة، زيتون، فلفل / فطر حسب الرغبة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">سلامي</div><div class="item-price">10₪</div></div>
            <div class="ingredients">(صوص، جبنة، سلامي)</div>
        </li>
        <li><div class="item-row"><div class="item-name">سبانخ أقراص</div><div class="item-price">8₪</div></div></li>
        <li>
            <div class="item-row"><div class="item-name">سبانخ</div><div class="item-price">10₪</div></div>
            <div class="ingredients">(مع جبنة، مع لحمة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">مكس أجبان بدون بيض</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(جبنة بيضة، جبنة صفرا)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">مكس أجبان مع بيض</div><div class="item-price">9₪</div></div>
            <div class="ingredients">(جبنة بيضة، جبنة صفرا، زعتر دقة، بيض مسلوق)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">منكوشة لبنانية</div><div class="item-price">10₪</div></div>
            <div class="ingredients">(عجينة مطاولة، قطع جبنة بيضة حلوم، رشة زعتر، قطع بندورة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">عكاوي</div><div class="item-price">12₪</div></div>
            <div class="ingredients">(عجينة مطاولة، جبنة بيضة، جبنة صفرا، جبنة عكاوي، رشة زعتر)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">نقانق وجبنة</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(صوص، جبنة، نقانق، ذرة / أو بدون)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">مارجريتا</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(صوص، جبنة، ذرة / أو بدون)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">تونا</div><div class="item-price">10₪</div></div>
            <div class="ingredients">(صوص، تونا، زيتون، ذرة، جبنة، فلفل)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">قدسية</div><div class="item-price">9₪</div></div>
            <div class="ingredients">(جبنة، بيض، زيتون، نقانق، ذرة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">ميشولاش</div><div class="item-price">9₪</div></div>
            <div class="ingredients">(صوص، جبنة، زيتون، ذرة، بيضة مسلوقة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">جبنة عربية</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(مع زعتر أخضر، أو زعتر دقة، أو بدون)</div>
        </li>
        <li><div class="item-row"><div class="item-name">أقراص بيض</div><div class="item-price">6₪</div></div></li>
        <li>
            <div class="item-row"><div class="item-name">فطر</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(فطر مع خلطة خاصة، بصل، جبنة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">جبنة وبيض خفق</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(جبنة بيضة، جبنة صفرا، بيض، فطر أو بدون)</div>
        </li>
        <li><div class="item-row"><div class="item-name">مناقيش زعتر</div><div class="item-price">3₪</div></div></li>
        <li><div class="item-row"><div class="item-name">صفيحة بندورة</div><div class="item-price">10₪</div></div></li>
        <li>
            <div class="item-row"><div class="item-name">أقراص لحمة</div><div class="item-price">12₪ / 13₪</div></div>
            <div class="ingredients">(لحمة مفرومة مطبوخة، جبنة / أو بدون)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">معجنة أفوكادو</div><div class="item-price">10₪</div></div>
            <div class="ingredients">(عجينة مطاولة، أفوكادو، قطع بندورة، رشة زعتر)</div>
        </li>
    </ul>
</section>

<section>
    <h2>🥪 قسم المعجنات والبيتزا المسكرة (كالزوني)</h2>
    <ul>
        <li><div class="item-row"><div class="item-name">كالزوني خضار</div><div class="item-price">8₪</div></div></li>
        <li><div class="item-row"><div class="item-name">كالزوني مسحب</div><div class="item-price">12₪</div></div></li>
        <li><div class="item-row"><div class="item-name">كالزوني سلامي</div><div class="item-price">10₪</div></div></li>
        <li>
            <div class="item-row"><div class="item-name">كالزوني مكس أجبان</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(مع بيض / أو بدون)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">كالزوني جبنة</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(مع زعتر / أو بدون)</div>
        </li>
        <li><div class="item-row"><div class="item-name">كالزوني نقانق وجبنة</div><div class="item-price">8₪</div></div></li>
        <li><div class="item-row"><div class="item-name">كالزوني فطر</div><div class="item-price">8₪</div></div></li>
        <li><div class="item-row"><div class="item-name">كالزوني مارجريتا</div><div class="item-price">8₪</div></div></li>
    </ul>
</section>

<section>
    <h2>👨‍👩‍👧‍👦 قسم الوجبات العائلية</h2>
    <div class="table-container">
        <table>
            <thead>
                <tr>
                    <th>الصنف</th>
                    <th>S</th>
                    <th>M.S</th>
                    <th>M</th>
                    <th>L</th>
                    <th>XL</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>خضار</td><td>8₪</td><td>20₪</td><td>30₪</td><td>40₪</td><td>50₪</td></tr>
                <tr><td>مسحب</td><td>12₪</td><td>30₪</td><td>45₪</td><td>55₪</td><td>65₪</td></tr>
                <tr><td>سلامي</td><td>10₪</td><td>25₪</td><td>40₪</td><td>50₪</td><td>60₪</td></tr>
                <tr><td>نص مسحب - نص خضار</td><td>12₪</td><td>30₪</td><td>40₪</td><td>50₪</td><td>60₪</td></tr>
                <tr><td>نص سلامي - نص خضار</td><td>10₪</td><td>25₪</td><td>40₪</td><td>50₪</td><td>60₪</td></tr>
                <tr><td>نص مسحب - نص سلامي</td><td>12₪</td><td>30₪</td><td>45₪</td><td>55₪</td><td>65₪</td></tr>
                <tr><td>مارجريتا</td><td>8₪</td><td>20₪</td><td>30₪</td><td>40₪</td><td>50₪</td></tr>
                <tr><td>جبنة عربية</td><td>8₪</td><td>20₪</td><td>25₪</td><td>35₪</td><td>40₪</td></tr>
                <tr><td>الفصول الأربعة</td><td>-</td><td>-</td><td>45₪</td><td>55₪</td><td>65₪</td></tr>
                <tr><td>الصفيحة</td><td>10₪</td><td>25₪</td><td>40₪</td><td>50₪</td><td>60₪</td></tr>
            </tbody>
        </table>
    </div>
</section>

<section>
    <h2>🍞 قسم التوستات</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">توست سلامي</div><div class="item-price">13₪</div></div>
            <div class="ingredients">(صوص، سلامي، جبنة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">توست أجبان</div><div class="item-price">13₪</div></div>
            <div class="ingredients">(لبنة، زيتون، ذرة، جبنة، صوص)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">توست النقانق</div><div class="item-price">13₪</div></div>
            <div class="ingredients">(صوصات، نقانق، جبنة)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">روست بيف (كتف عجل)</div><div class="item-price">12₪</div></div>
            <div class="ingredients">(لبنة / أو أفوكادو، خس، بندورة، مخلل)</div>
        </li>
        <li><div class="item-row"><div class="item-name">صدر حبش</div><div class="item-price">12₪</div></div></li>
    </ul>
</section>

<section>
    <h2>🍔 قسم الساندوش</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">برجر كرسبي / 3 قطع</div><div class="item-price">22₪</div></div>
            <div class="ingredients">(صوصات، بطاطا، خس، جبنة، كولسلو اختياري، بصل، مخلل)</div>
        </li>
        <li><div class="item-row"><div class="item-name">باجيت كرسبي / 3 قطع</div><div class="item-price">22₪</div></div></li>
        <li>
            <div class="item-row"><div class="item-name">برجر شنتسل / قطعتين</div><div class="item-price">20₪</div></div>
            <div class="ingredients">(بندورة، خس، كولسلو، بصل)</div>
        </li>
        <li><div class="item-row"><div class="item-name">باجيت فيله دجاج / قطعتين</div><div class="item-price">22₪</div></div></li>
        <li><div class="item-row"><div class="item-name">إضافة صوصات</div><div class="item-price">2₪</div></div></li>
        <li><div class="item-row"><div class="item-name">علبة كولسلو</div><div class="item-price">7₪</div></div></li>
    </ul>
</section>

<section>
    <h2>🍗 قسم تشكن أبو علي</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">(5) قطع كرسبي</div><div class="item-price">25₪</div></div>
            <div class="ingredients">(كرسبي، صوصات، كولسلو، بطاطا)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">(10) قطع كرسبي</div><div class="item-price">45₪</div></div>
            <div class="ingredients">(كولا لتر)</div>
        </li>
        <li>
            <div class="item-row"><div class="item-name">(15) قطعة كرسبي</div><div class="item-price">70₪</div></div>
            <div class="ingredients">(كولا لتر)</div>
        </li>
        <li><div class="item-row"><div class="item-name">(20) قطعة كرسبي</div><div class="item-price">85₪</div></div></li>
    </ul>
</section>

<section>
    <h2>🐟 قسم السمك</h2>
    <ul>
        <li><div class="item-row"><div class="item-name">(5) قطع فيله سمك</div><div class="item-price">25₪</div></div></li>
    </ul>
</section>

<section>
    <h2>🦅 قسم الأجنحة</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">(10) قطع أجنحة</div><div class="item-price">20₪</div></div>
            <div class="ingredients">(بطاطا، كولسلو، خبز)</div>
        </li>
        <li><div class="item-row"><div class="item-name">(15) جناح</div><div class="item-price">30₪</div></div></li>
        <li><div class="item-row"><div class="item-name">(20) جناح</div><div class="item-price">35₪</div></div></li>
        <li><div class="item-row"><div class="item-name">(30) جناح</div><div class="item-price">50₪</div></div></li>
        <li><div class="item-row"><div class="item-name">فريز تشيكن</div><div class="item-price">22₪</div></div></li>
    </ul>
</section>
 
<section class="contact-section">
    <h2>📍 معلومات الفرع الرئيسي</h2>
    
    <div class="contact-card">
        <div class="contact-title">📌 العنوان</div>
        <div class="contact-text">قبلان - أول البلد</div>
    </div>

    <div class="contact-card">
        <div class="contact-title">📞 أرقام الطلبات والتوصيل</div>
        <div class="contact-text">0523073771</div>
        <div class="contact-text">0549170022</div>
        <div class="contact-text">0598482070</div>
    </div>

    <div class="contact-card">
        <div class="contact-title">💬 خدمة الواتساب الفورية</div>
        <a href="https://wa.me/972523073771" target="_blank" class="btn-link btn-phone">💬 راسلنا واتساب (رقم 1)</a>
        <a href="https://wa.me/972549170022" target="_blank" class="btn-link btn-phone">💬 راسلنا واتساب (رقم 2)</a>
    </div>

    <div class="contact-card">
        <div class="contact-title">🌐 مجتمعنا الإلكتروني</div>
        <a href="https://www.facebook.com/share/16gTDuz4Kf/" target="_blank" class="btn-link btn-fb">🌐 تابعنا على فيسبوك</a>
    </div>
</section>

</body>
</html>
