<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مطعم وبيتزا أبو علي - المنيو الملكي الفاخر</title>

<style>
    /* تصميم الهوية الملكية الفاخرة - ذهبي وأبيض وأسود */
    body {
        font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        background-color: #fcfbf7; /* خلفية بيضاء عاجية فاخرة */
        color: #111111; /* خطوط سوداء ملكية واضحة */
        margin: 0;
        padding: 15px;
        line-height: 1.6;
    }

    /* الهيدر الملكي العريق */
    header {
        text-align: center;
        padding: 45px 20px;
        background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%); /* خلفية سوداء فخمة للهيدر لبروز الذهب */
        border-radius: 25px;
        margin-bottom: 30px;
        border: 3px solid #d4af37; /* إطار ذهبي ملوكي */
        box-shadow: 0 10px 25px rgba(212, 175, 55, 0.2);
    }

    header h1 {
        margin: 0;
        font-size: 34px;
        color: #d4af37; /* اسم المطعم بالذهبي النقي */
        text-shadow: 0 2px 4px rgba(0,0,0,0.5);
        font-weight: 900;
        letter-spacing: 1px;
    }

    header p {
        margin: 12px 0 0 0;
        color: #ffffff;
        font-weight: bold;
        font-size: 16px;
        letter-spacing: 2px;
    }

    /* بطاقات الأقسام البيضاء المؤطرة بالذهب */
    section {
        margin-bottom: 35px;
        background: #ffffff; /* خلفية بيضاء ناصعة ونظيفة */
        padding: 24px;
        border-radius: 24px;
        border: 2px solid #e5c158; /* إطار ذهبي ناعم */
        box-shadow: 0 6px 18px rgba(0, 0, 0, 0.05);
    }

    /* عناوين الأقسام الملكية */
    section h2 {
        font-size: 22px;
        color: #0a0a0a;
        background: linear-gradient(90deg, #0a0a0a, #d4af37);
        padding: 6px 15px;
        border-right: 5px solid #d4af37; /* خط جانبي ذهبي عريض */
        margin-top: 0;
        margin-bottom: 25px;
        display: block;
        font-weight: 800;
        border-radius: 0 8px 8px 0;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 0;
    }

    /* تأثير تفاعلي ملوكي عند لمس أو الضغط على الوجبة */
    li {
        background: #fffdf9;
        margin-bottom: 14px;
        padding: 16px;
        border-radius: 16px;
        border: 1px solid #f0e6cc;
        border-bottom: 3px solid #d4af37; /* قاعدة الوجبة ذهبية */
        box-shadow: 0 3px 6px rgba(0,0,0,0.02);
        transition: all 0.2s ease;
    }

    li:active {
        transform: scale(0.98);
        background: #fbf7eb;
        box-shadow: 0 2px 4px rgba(212, 175, 55, 0.2);
    }

    .item-row {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .item-name {
        font-weight: 700;
        font-size: 18px;
        color: #0a0a0a; /* اسم الوجبة أسود عريض */
    }

    /* سعر ملكي أسود داخل كبسولة ذهبية للوجبات الفردية */
    .item-price {
        font-weight: 800;
        font-size: 18px;
        color: #000000 !important; /* أسود حالك */
        background: linear-gradient(135deg, #f9f3dd 0%, #e6cb7b 100%); /* خلفية ذهبية ملكية دافئة */
        padding: 6px 16px;
        border-radius: 12px;
        white-space: nowrap;
        border: 1px solid #d4af37;
        box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }

    .ingredients {
        color: #555555; /* خامات الوجبة واضحة ومقروءة */
        margin-top: 8px;
        font-size: 14px;
        font-weight: 500;
    }

    /* ترتيب وجدول الأحجام العائلية الـ 5 - قمة الفخامة والوضوح */
    .table-container {
        overflow-x: auto;
        margin-top: 15px;
        border-radius: 16px;
        border: 2px solid #d4af37;
        box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    }

    table {
        width: 100%;
        border-collapse: collapse;
        background: #ffffff;
        font-size: 16px;
    }

    th, td {
        padding: 16px 12px;
        text-align: center;
        border: 1px solid #e5dbbd;
        white-space: nowrap;
    }

    /* سطر الأحجام الـ 5 بالأسود الملكي الفخم وخط أبيض ناصع عريض جداً */
    th {
        background-color: #0a0a0a !important;
        color: #ffffff !important;
        font-weight: 900;
        font-size: 18px;
        letter-spacing: 1px;
    }

    tr:nth-child(even) {
        background: #fffdf7;
    }

    /* عمود أسماء الأصناف في الجدول */
    td:first-child {
        font-weight: bold;
        color: #0a0a0a; 
        text-align: right;
        background: #fdfaf2;
        font-size: 16px;
        border-left: 2px solid #e5cb7b;
    }
    
    /* الأسعار باللون الأسود الغامق العريض 100% لتكون واضحة ومبينة وفخمة جداً تحت الـ 5 أحجام */
    td:not(:first-child) {
        color: #000000 !important;
        font-weight: 800;
        font-size: 17px;
    }

    /* صندوق التواصل الملكي */
    .contact-section {
        background: linear-gradient(145deg, #ffffff 0%, #fdfaf2 100%);
        border: 3px solid #d4af37;
        text-align: center;
        box-shadow: 0 5px 20px rgba(212, 175, 55, 0.15);
    }

    .contact-card {
        margin-bottom: 25px;
        padding: 5px;
    }

    .contact-title {
        font-size: 18px;
        color: #b38f1d;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .contact-text {
        font-size: 19px;
        color: #0a0a0a;
        margin: 6px 0;
        font-weight: 700;
    }

    /* أزرار تواصل فخمة مريحة جداً */
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
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        transition: transform 0.2s;
    }

    .btn-fb {
        background: linear-gradient(135deg, #1877f2 0%, #0c5ca9 100%);
        color: #ffffff;
    }

    .btn-phone {
        background: linear-gradient(135deg, #1e7e34 0%, #155d27 100%);
        color: #ffffff;
    }
</style>
</head>

<body>

<header>
    <h1>مطعم وبيتزا أبو علي</h1>
    <p>👑 الفرع الرئيسي والأصيل - عراقة الماضي وفخامة الحاضر 👑</p>
</header>

<section>
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
    <h2>👨‍👩‍👧‍👦 قسم الوجبات العائلية (الأحجام الخمسة)</h2>
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
    <h2>📍 معلومات الفرع الرئيسي الملكي</h2>
    
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
