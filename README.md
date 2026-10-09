[index.html](https://github.com/user-attachments/files/33265986/index.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>روابط التواصل الاجتماعي</title>
    <!-- خط جوجل والأيقونات -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 420px;
            text-align: center;
        }

        .profile-img {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #38bdf8;
            margin-bottom: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }

        h1 {
            font-size: 1.5rem;
            margin-bottom: 8px;
        }

        p.bio {
            font-size: 0.95rem;
            color: #94a3b8;
            margin-bottom: 25px;
            line-height: 1.5;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-card {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 14px 20px;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            color: #ffffff;
            text-decoration: none;
            font-size: 1rem;
            font-weight: 700;
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
        }

        .link-card:hover {
            background: rgba(56, 189, 248, 0.15);
            border-color: #38bdf8;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(56, 189, 248, 0.2);
        }

        .link-card i {
            font-size: 1.4rem;
            width: 30px;
        }

        /* ألوان الأيقونات عند التمرير */
        .instagram i { color: #e1306c; }
        .tiktok i { color: #00f2fe; }
        .
        .facebook i { color: #1877f2; }
        .
        
        footer {
            margin-top: 30px;
            font-size: 0.8rem;
            color: #64748b;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- الصورة الشخصية -->
        <img src="https://via.placeholder.com/150" alt="صورة الملف الشخصي" class="profile-img">

        <!-- الاسم والوصف -->
        <h1>اسمك هنا</h1>
        <p class="bio">أهلاً بك! تجد هنا جميع حساباتي وروابط التواصل الخاصة بي.</p>

        <!-- روابط التواصل الاجتماعي -->
        <div class="links-container">

            <a href="https://instagram.com/https://www.instagram.com/yassine_mr_x29" target="_blank" class="link-card instagram">
                <i class="fab fa-instagram"></i>
                <span>إنستغرام</span>
                <i class="fas fa-arrow-left"></i>
            </a>

            <a href="https://tiktok.com/tiktok.com/@yacinemokhtar33" target="_blank" class="link-card tiktok">
                <i class="fab fa-tiktok"></i>
                <span>تيك توك</span>
                <i class="fas fa-arrow-left"></i>
            </a>

           

            <a href="https://facebook.com/https://www.facebook.com/share/1DnbGyTrdB/" target="_blank" class="link-card facebook">
                <i class="fab fa-facebook"></i>
                <span>فيسبوك</span>
                <i class="fas fa-arrow-left"></i>
            
           
            
           

        </div>

        <footer>
            © جميع الحقوق محفوظة
        </footer>
    </div>

</body>
</html>
