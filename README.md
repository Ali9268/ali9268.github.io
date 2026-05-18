<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مطعم وبيتزا أبو علي - المنيو الملون الفاخر</title>

<style>
    /* تصميم مستوحى من لوحة ألوان المطاعم العالمية والدافئة */
    body {
        font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        background: #2b1b12 linear-gradient(135deg, #2b1b12 0%, #170e0a 100%); /* خلفية خشبية داكنة ودافئة تعطي فخامة للمنيو */
        color: #333333;
        margin: 0;
        padding: 15px;
        line-height: 1.6;
    }

    /* الهيدر الرئيسي الفخم */
    header {
        text-align: center;
        padding: 35px 20px;
        background: linear-gradient(145deg, #7a2214 0%, #4a120a 100%); /* لون أحمر طوبي ملكي */
        border-radius: 25px;
        margin-bottom: 25px;
        border: 3px solid #d4af37; /* إطار ذهبي ملوكي */
        box-shadow: 0 8px 25px rgba(0,0,0,0.5);
    }

    header h1 {
        margin: 0;
        font-size: 32px;
        color: #ffffff;
        font-weight: 900;
        text-shadow: 0 3px 6px rgba(0,0,0,0.6);
    }

    header p {
        margin: 10px 0 0 0;
        color: #f1c40f; /* أصفر ذهبي */
        font-weight: bold;
        font-size: 16px;
    }

    /* صناديق الأقسام الملونة والمرتبة */
    section {
        margin-bottom: 30px;
        background: #ffffff; /* كروت بيضاء ساطعة لبروز الألوان والخطوط */
        padding: 20px;
        border-radius: 22px;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
        border: 1px solid rgba(255,255,255,0.1);
        overflow: hidden;
    }

    /* تنسيق ألوان العناوين لكل قسم ليكون منوع ومبهج ومرتب */
    section.pizza h2 { background: linear-gradient(90deg, #b8321a, #e67e22); } /* أحمر و برتقالي */
    section.calzone h2 { background: linear-gradient(90deg, #d35400, #f39c12); } /* برتقالي دافئ */
    section.family h2 { background: linear-gradient(90deg, #1e5631, #4c9a2a); } /* أخضر ملوكي للأحجام */
    section.toast h2 { background: linear-gradient(90deg, #7f8c8d, #bdc3c7); color: #111 !important; } /* رمادي كلاسيكي */
    section.burger h2 { background: linear-gradient(90deg, #c0392b, #962d22); } 
    section.chicken h2 { background: linear-gradient(90deg, #d35400, #a04000); }
    section.fish h2 { background: linear-gradient(90deg, #2980b9, #3498db); } /* أزرق بحري للسمك */
    section.wings h2 { background: linear-gradient(90deg, #8e44ad, #9b59b6); } /* بنفسجي للأجنحة */

    section h2 {
        font-size: 20px;
        color: #ffffff;
        padding: 10px 18px;
        margin-top: -20px;
        margin-left: -20px;
        margin-right: -20px;
        margin-bottom: 20px;
        font-weight: 800;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    li {
        background: #fdfbfc;
        margin-bottom: 12px;
        padding: 14px;
        border-radius: 14px;
        border-right: 5px solid #e67e22; /* لمسة ملونة جانبية */
        box-shadow: 0 3px 6px rgba(0,0,0,0.03);
        transition: transform 0.2s;
    }

    li:animated {
        transform: scale(0.98);
    }

    .item-row {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .item-name {
        font-weight: 700;
        font-size: 17px;
        color: #111111;
    }

    /* كبسولة السعر الدائرية الملونة بالمنيو العادي */
    .item-price {
        font-weight: 800;
        font-size: 16px;
        color: #ffffff;
        background: #c0392b; /* لون أحمر مميز للأسعار الفردية */
        padding: 5px 14px;
        border-radius: 50px;
        white-space: nowrap;
    }

    .ingredients {
        color: #666666;
        margin-top: 6px;
        font-size: 13.5px;
        font-weight: 500;
    }

    /* 🟢 جدول الأحجام الخمسة العائلية الفخم والمرتب 🟢 */
    .table-container {
        overflow-x: auto;
        margin-top: 10px;
        border-radius: 16px;
        border: 2px solid #1e5631; /* إطار أخضر ملوكي متناسق */
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    table {
        width: 100%;
        border-collapse: collapse;
        background: #ffffff; /* خلفية بيضاء صافية لتبرز الأسعار */
        font-size: 16px;
    }

    th, td {
        padding: 15px 10px;
        text-align: center;
        border: 1px solid #e0e0e0;
        white-space: nowrap;
    }

    /* سطر الأحجام الـ 5 بخلفية سوداء ملكية وخط أبيض عريض */
    th {
        background-color: #111111 !important;
        color: #ffffff !important;
        font-weight: 900;
        font-size: 18px;
    }

    tr:nth-child(even) {
        background: #f9fbf9; /* تدرج خفيف مريح جداً للعين */
    }

    /* عمود أسماء الوجبات داخل الجدول */
    td:first-child {
        font-weight: bold;
        color: #1e5631; /* اسم الوجبة باللون الأخضر الغامق المتناسق */
        text-align: right;
        background: #f4f9f4;
        font-size: 16px;
    }
    
    /* 🌟 الأسعار باللون الأسود الغامق العريض والواضح جداً تحت الـ 5 أحجام 🌟 */
    td:not(:first-child) {
        color: #000000 !important;
        font-weight: 900;
        font-size: 17px;
    }

    /* صندوق التواصل المرتب */
    .contact-section {
        background: #ffffff;
        border: 3px solid #7a2214;
        text-align: center;
    }

    .contact-card {
        margin-bottom: 20px;
        padding: 5px;
    }

    .contact-title {
        font-size: 18px;
        color: #7a2214;
        font-weight: bold;
        margin-bottom: 8px;
    }

    .contact-text {
        font-size: 18px;
        color: #111111;
        margin: 5px 0;
        font-weight: 700;
    }

    /* أزرار قنوات التواصل التفاعلية */
    .btn-link {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
        width: 88%;
        max-width: 290px;
        margin: 12px auto;
        padding: 14px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: bold;
        font-size: 16px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }

    .btn-fb {
        background: linear-gradient(135deg, #1877f2 0%, #0c5ca9 100%);
        color: #ffffff;
    }

    .btn-phone {
        background: linear-gradient(135deg, #25d366 0%, #1c9b47 100%);
        color: #ffffff;
    }
</style>
</head>

<body>

<header>
    <h1>مطعم وبيتزا أبو علي</h1>
    <p>👑 الفرع الرئيسي والأصيل - طعم ملوكي وخيارات منوعة 👑</p>
</header>

<section class="pizza">
    <h2>🍕 قسم البيتزا والمعجنات</h2>
    <ul>
        <li>
            <div class="item-row"><div class="item-name">بيتزا سمول</div><div class="item-price">8₪</div></div>
            <div class="ingredients">(ذرة، زيتون، فلفل، جبنة، صوص، نقانق)</div>
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

<section class="calzone">
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

<section class="family">
    <h2>👨‍👩‍👧‍👦 قسم الوجبات العائلية (الأحجام الـ 5 المرتبة)</h2>
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

<section class="toast">
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

<section class="burger">
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

<section class="chicken">
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

<section class="fish">
    <h2>🐟 قسم السمك</h2>
    <ul>
        <li><div class="item-row"><div class="item-name">(5) قطع فيله سمك</div><div class="item-price">25₪</div></div></li>
    </ul>
</section>

<section class="wings">
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
    <h2>📍 معلومات الفرع الرئيسي الملون</h2>
    
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
