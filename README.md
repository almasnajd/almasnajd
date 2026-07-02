<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google-site-verification" content="ضع_الكود_هنا" />
    <title>شركة ألماس نجد | لقطع غيار الشاحنات الثقيلة</title>
    <!-- استدعاء خطوط قوقل الاحترافية وأيقونات FontAwesome -->
    <link href="https://googleapis.com" rel="stylesheet">
    <link rel="stylesheet" href="https://cloudflare.com">
    
    <style>
        :root {
            --primary: #0f172a; /* كحلي ملكي عميق */
            --accent: #d4af37;  /* ذهبي ألماسي فخم */
            --accent-hover: #f3cf65;
            --text-dark: #1e293b;
            --text-light: #f8fafc;
            --bg-light: #f1f5f9;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
        }

        /* الهيدر والقائمة العلوية */
        header {
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #fff;
            padding: 15px 8%;
            position: sticky;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 20px rgba(0,0,0,0.15);
            border-bottom: 3px solid var(--accent);
        }

        .logo h1 {
            color: var(--accent);
            font-size: 26px;
            font-weight: 900;
            display: flex;
            align-items: center;
            gap: 10px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }

        .logo h1 i {
            animation: pulse 2s infinite;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 700;
            font-size: 16px;
            transition: all 0.3s ease;
            padding: 8px 12px;
            border-radius: 5px;
        }

        nav ul li a:hover {
            color: var(--accent);
            background: rgba(255, 255, 255, 0.05);
        }

        /* الواجهة الرئيسية الفخمة */
        .hero {
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), url('https://unsplash.com') no-repeat center center/cover;
            height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
            padding: 0 20px;
        }

        .hero h2 {
            font-size: 48px;
            font-weight: 900;
            margin-bottom: 15px;
            letter-spacing: 1px;
            text-shadow: 0 4px 10px rgba(0,0,0,0.5);
        }

        .hero p {
            font-size: 22px;
            margin-bottom: 35px;
            color: #cbd5e1;
            max-width: 800px;
            font-weight: 300;
        }

        .btn-main {
            background: linear-gradient(135deg, var(--accent), #b89326);
            color: var(--primary);
            padding: 16px 40px;
            text-decoration: none;
            font-weight: 900;
            font-size: 18px;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 6px 20px rgba(212, 175, 55, 0.4);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .btn-main:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(212, 175, 55, 0.6);
            background: linear-gradient(135deg, var(--accent-hover), var(--accent));
        }

        /* أقسام المنتجات (بطاقات عصرية) */
        .container {
            max-width: 1200px;
            margin: 60px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 34px;
            font-weight: 900;
            color: var(--primary);
        }

        .section-title span {
            color: var(--accent);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 100px;
            height: 4px;
            background: linear-gradient(90deg, transparent, var(--accent), transparent);
            margin: 15px auto 0;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 30px;
        }

        .card {
            background: #fff;
            padding: 40px 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border: 1px solid #e2e8f0;
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0; left: 0; width: 100%; height: 5px;
            background: var(--primary);
            transition: all 0.3s ease;
        }

        .card:hover::before {
            background: var(--accent);
            height: 8px;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }

        .card-icon {
            font-size: 45px;
            color: var(--primary);
            margin-bottom: 20px;
            transition: all 0.3s ease;
        }

        .card:hover .card-icon {
            color: var(--accent);
            transform: scale(1.1);
        }

        .card h3 {
            margin-bottom: 15px;
            color: var(--primary);
            font-size: 22px;
            font-weight: 700;
        }

        .card p {
            color: #64748b;
            font-size: 15px;
            line-height: 1.8;
        }

        /* تصميم الفروع المطور بطابع فاخر */
        .branches-section {
            background: #0f172a;
            color: #fff;
            padding: 80px 20px;
        }

        .branches-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .branch-card {
            background: #1e293b;
            padding: 35px;
            border-radius: 15px;
            border: 1px solid #334155;
            transition: all 0.3s ease;
            position: relative;
        }

        .branch-card:hover {
            border-color: var(--accent);
            background: #1e293b;
            transform: scale(1.02);
        }

        .branch-card h4 {
            color: var(--accent);
            font-size: 24px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 700;
        }

        .branch-card p {
            margin: 15px 0;
            color: #cbd5e1;
            font-size: 16px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .branch-card .phone-link {
            color: #fff;
            text-decoration: none;
            background: #334155;
            padding: 10px 20px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-weight: 700;
            transition: all 0.3s ease;
            border: 1px solid transparent;
            margin-bottom: 10px;
            width: 100%;
        }

        .branch-card .phone-link:hover {
            background: linear-gradient(135deg, #25d366, #128c7e); /* لون الواتساب والاتصال الأخضر عند التمرير */
            color: #fff;
            border-color: #25d366;
        }

        /* قسم عن الشركة */
        .about-box {
            background: #fff;
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.02);
            text-align: center;
            border: 1px solid #e2e8f0;
        }

        /* الفوتر الأنيق */
        footer {
            background-color: #090d16;
            color: #64748b;
            text-align: center;
            padding: 30px 20px;
            font-size: 15px;
            border-top: 1px solid #1e293b;
        }

        footer p span {
            color: var(--accent);
            font-weight: bold;
        }

        /* حركات الأنيميشن */
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        /* التوافق التام مع الجوال */
        @media (max-width: 768px) {
            header { flex-direction: column; gap: 15px; text-align: center; padding: 20px; }
            nav ul { gap: 15px; }
            .hero h2 { font-size: 32px; }
            .hero p { font-size: 18px; }
            .section-title { font-size: 28px; }
        }
    </style>
</head>
<body>

    <!-- القائمة العلوية الاحترافية -->
    <header>
        <div class="logo">
            <h1><i class="fa-solid :gem"></i> شركة ألماس نجد</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home"><i class="fa-solid :house"></i> الرئيسية</a></li>
                <li><a href="#parts"><i class="fa-solid :gears"></i> المنتجات</a></li>
                <li><a href="#branches"><i class="fa-solid :location-dot"></i> فروعنا</a></li>
