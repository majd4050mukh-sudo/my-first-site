<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع عبد الماجد مختار</title>
    
    <!-- خطوط عربية احترافية ودعم أيقونات التخصص -->
    <link rel="preconnect" href="https://googleapis.com">
    <link rel="preconnect" href="https://gstatic.com" crossorigin>
    <link href="https://googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">
    
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: 'Cairo', Arial, sans-serif;
            background-color: #f4f7f6;
            color: #333333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #007bff;
            color: #ffffff;
            padding: 50px 20px;
        }

        header h1 {
            margin-bottom: 10px;
            font-size: 2.2em;
        }

        main {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
        }

        .card {
            background-color: #ffffff;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            text-align: right;
        }

        .card h2 {
            margin-top: 0;
            color: #007bff;
            border-bottom: 2px solid #f4f7f6;
            padding-bottom: 10px;
        }

        /* تنسيق بطاقة الجمل والهوية الجامعية المدمجة */
        .camel-profile-card {
            background: #ffffff;
            border: 2px solid #e0e0e0;
            border-radius: 16px;
            padding: 30px;
            margin-bottom: 25px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.06);
        }

        .camel-container {
            background: #f8f9fa;
            border-radius: 50%;
            width: 130px;
            height: 130px;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 2px dashed #007bff;
        }

        .digital-camel {
            width: 90px;
            height: 90px;
            animation: camelWalk 4s infinite ease-in-out;
        }

        .student-name {
            color: #222222;
            margin: 10px 0 5px 0;
            font-size: 1.7em;
            font-weight: 700;
        }

        .university-tag {
            color: #007bff;
            margin: 0 0 15px 0;
            font-weight: 600;
            font-size: 1.2em;
        }

        .specialty-badge {
            background: #e3f2fd;
            color: #0d47a1;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.05em;
            text-align: center;
        }

        .specialty-badge hr {
            border: 0;
            border-top: 1px solid #bbdefb;
            margin: 10px 0;
        }

        ul {
            list-style-position: inside;
            padding: 0;
        }

        li {
            margin: 15px 0;
            font-size: 1.1em;
        }

        footer {
            background-color: #333333;
            color: #ffffff;
            padding: 20px 0;
            margin-top: 40px;
            width: 100%;
        }

        /* حركة تمايل الجمل الرقمي */
        @keyframes camelWalk {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-6px) rotate(2deg); }
        }
    </style>
</head>
<body>

    <header>
        <h1>أهلاً بكم في موقعي الشخصي 👋</h1>
        <p>هذا الموقع جاهز وتم رفعه بنجاح على الاستضافة المجانية.</p>
    </header>

    <main>
        <!-- بطاقة الهوية الرقمية والجمل المدمجة -->
        <section class="camel-profile-card">
            <div class="camel-container">
                <svg viewBox="0 0 100 100" class="digital-camel">
                    <path d="M15,65 Q25,35 35,40 Q45,15 60,25 Q70,30 75,20 Q80,15 80,25 Q75,45 70,50 Q60,60 45,55 Q30,60 15,65 Z" fill="none" stroke="#007bff" stroke-width="2.5"/>
                    <path d="M30,45 L40,45 M50,35 L60,35 M25,55 L35,55" stroke="#28a745" stroke-width="1.5" stroke-linecap="round"/>
                </svg>
            </div>
            
            <h2 class="student-name">عبد الماجد مختار عبدالله</h2>
            <p class="university-tag">جامعة الفاشر</p>
            
            <div class="specialty-badge">
                <span>كلية العلوم الرياضية</span>
                <hr>
                <strong>التخصص: رياضيات وحاسوب 💻 📐</strong>
            </div>
        </section>

        <!-- بطاقة من أنا المحدثة -->
        <section class="card">
            <h2>طالب في رحاب العلم</h2>
            <p>أنا  طالب في جامعة الفاشر. أجمع في دراستي بين شغف الرياضيات ومنطق الحاسوب، وأتعلم حالياً كيفية بناء وتطوير المواقع الإلكترونية على الإنترنت.</p>
        </section>

        <!-- بطاقة الخدمات -->
        <section class="card">
            <h2>مهاراتي وخدماتي</h2>
            <ul>
                <li>حل المسائل الرياضية والبرمجية</li>
                <li>تطوير صفحات الويب باستخدام HTML & CSS</li>
                <li>إدارة الاستضافات السحابية والمجانية</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>جميع الحقوق محفوظة © 2026 | عبد الماجد مختار</p>
    </footer>

</body>
</html>
