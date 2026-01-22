<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>زوايا البيان | إبداع يتجاوز الحدود لتجهيز المعارض</title>
    <meta name="description" content="مؤسسة زوايا البيان للدعاية والإعلان بالرياض - خبراء في تجهيز المعارض والفعاليات والحلول الإعلانية المبتكرة.">
    <meta name="keywords" content="زوايا البيان, تجهيز معارض الرياض, دعاية وإعلان السعودية, تصميم أجنحة معارض, Zawaya Al-Bayan">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #D4AF37; 
            --primary-light: #f1d279;
            --black: #0a0a0a;
            --dark: #121212;
            --gray-dark: #1e1e1e;
            --gray-light: #f8f9fa;
            --white: #ffffff;
            --transition-smooth: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            margin: 0; padding: 0; box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, sans-serif;
            scroll-behavior: smooth;
        }

        body { background-color: var(--white); color: var(--black); overflow-x: hidden; }

        header {
            background: rgba(10, 10, 10, 0.98);
            height: 90px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 8%;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 9999;
            border-bottom: 2px solid var(--primary);
            backdrop-filter: blur(15px);
        }

        .logo-container h1 { color: var(--primary); font-size: 26px; font-weight: 900; }
        .logo-container span { color: var(--white); font-size: 10px; text-transform: uppercase; letter-spacing: 3px; }

        nav ul { display: flex; list-style: none; gap: 35px; }
        nav ul li a {
            color: var(--white); text-decoration: none; font-weight: 600;
            transition: var(--transition-smooth); position: relative;
        }
        nav ul li a:hover { color: var(--primary); }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), radial-gradient(circle, #2c2c2c 0%, #000 100%);
            display: flex; align-items: center; justify-content: center;
            text-align: center; color: var(--white); padding: 0 8%;
        }
        .hero-content h3 { font-size: 4rem; line-height: 1.2; margin-bottom: 30px; }
        .hero-content h3 span { color: var(--primary); }

        /* Stats Bar */
        .stats-bar {
            background: var(--black);
            padding: 60px 8%;
            display: flex;
            justify-content: center;
            gap: 100px;
            color: var(--white);
            border-top: 3px solid var(--primary);
        }
        .stat-card { text-align: center; }
        .stat-card i { font-size: 2.5rem; color: var(--primary); margin-bottom: 15px; }
        .stat-card h5 { font-size: 2.2rem; margin-bottom: 5px; }

        /* About Section */
        .about-section { padding: 120px 8%; display: flex; align-items: center; gap: 60px; flex-wrap: wrap; }
        .about-text { flex: 1; min-width: 350px; }
        .about-text h2 { font-size: 2.8rem; margin-bottom: 25px; }
        .about-image-frame { flex: 1; min-width: 350px; height: 500px; }
        .main-img { width: 100%; height: 100%; object-fit: cover; border-radius: 20px; box-shadow: 20px 20px 0px var(--primary); }

        /* Works Section */
        .works-section { padding: 100px 8%; background-color: var(--gray-light); }
        .section-header { text-align: center; margin-bottom: 60px; }
        .works-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        .work-item {
            height: 350px; border-radius: 15px; overflow: hidden;
            position: relative; background: var(--dark);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .work-item img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.6s ease; }
        .work-item:hover img { transform: scale(1.1); }

        /* Footer */
        footer { background: var(--black); color: var(--white); padding: 80px 8% 40px; }
        .footer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 50px; }
        .contact-link { display: block; color: #ccc; text-decoration: none; margin-bottom: 15px; direction: ltr; }
        .contact-link:hover { color: var(--primary); transform: translateX(-10px); }

        @media (max-width: 768px) {
            .hero-content h3 { font-size: 2.5rem; }
            .stats-bar { gap: 40px; flex-direction: column; align-items: center; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <h1>زوايا البيان</h1>
            <span>Zawaya Al-Bayan</span>
        </div>
        <nav>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#works">معرض الأعمال</a></li>
                <li><a href="#contact">تواصل معنا</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <div class="hero-content">
            <h3>لسنا مجرد منصات عرض،<br>بل نحن <span>صنّاع تجربة.</span></h3>
            <div style="margin-top: 40px;">
                <a href="#works" style="background:var(--primary); color:var(--black); padding:15px 40px; border-radius:30px; text-decoration:none; font-weight:bold;">استكشف أعمالنا</a>
            </div>
        </div>
    </section>

    <div class="stats-bar">
        <div class="stat-card">
            <i class="fas fa-project-diagram"></i>
            <h5>+150</h5>
            <p>مشروع منجز</p>
        </div>
        <div class="stat-card">
            <i class="fas fa-smile"></i>
            <h5>100%</h5>
            <p>رضا العملاء</p>
        </div>
    </div>

    <section class="about-section" id="about">
        <div class="about-text">
            <h2>نحول المساحات الصامتة <br><span style="color:var(--primary)">إلى منصات تنبض بالحياة</span></h2>
            <p>مؤسسة زوايا البيان للدعاية والإعلان هي شريككم الإبداعي في الرياض، متخصصون في تجهيز المعارض والفعاليات والحلول الإعلانية المبتكرة التي تجعل علامتكم التجارية تبرز في كل زاوية.</p>
        </div>
        <div class="about-image-frame">
            <img src="67.jpeg" class="main-img" alt="عن زوايا البيان">
        </div>
    </section>

    <section class="works-section" id="works">
        <div class="section-header">
            <h2>معرض <span>أعمالنا</span></h2>
            <p>حيث تلتقي الدقة بالإبداع.. جولة بين أبرز بصماتنا في عالم التجهيز.</p>
        </div>

        <div class="works-grid">
            <div class="work-item"><img src="9.jpeg" alt="مشروع 9"></div>
            <div class="work-item"><img src="8.jpeg" alt="مشروع 8"></div>
            <div class="work-item"><img src="11.jpeg" alt="مشروع 11"></div>
            <div class="work-item"><img src="10.jpeg" alt="مشروع 10"></div>
            <div class="work-item"><img src="76.jpeg" alt="مشروع 76"></div>
            <div class="work-item"><img src="677.jpeg" alt="مشروع 677"></div>
            <div class="work-item"><img src="67.jpeg" alt="مشروع 67"></div>
            <div class="work-item"><img src="12.jpeg" alt="مشروع 12"></div>
        </div>
    </section>

    <footer id="contact">
        <div class="footer-grid">
            <div class="footer-col">
                <h3>زوايا البيان</h3>
                <p style="color:#aaa;">جودة في التنفيذ، سرعة في الإنجاز، وإبداع بلا حدود.</p>
            </div>
            <div class="footer-col">
                <h3>اتصل بنا</h3>
                <a href="tel:+966559792737" class="contact-link">+966 55 979 2737 <i class="fas fa-phone"></i></a>
                <a href="tel:+966538653944" class="contact-link">+966 53 865 3944 <i class="fas fa-phone"></i></a>
                <a href="tel:+966573638730" class="contact-link">+966 57 363 8730 <i class="fas fa-phone"></i></a>
            </div>
        </div>
        <div style="text-align:center; padding-top:40px; border-top:1px solid #222; margin-top:40px; color:#666;">
            &copy; 2026 مؤسسة زوايا البيان للدعاية والإعلان - جميع الحقوق محفوظة
        </div>
    </footer>

    <script>
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            header.style.background = window.scrollY > 50 ? 'rgba(0,0,0,1)' : 'rgba(10,10,10,0.98)';
        });
    </script>
</body>
</html>
