# Web-for-kids

<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บโปรไฟล์ของฉัน</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #007bff;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #0056b3;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #004494;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            margin-bottom: 1rem;
            color: #007bff;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #0056b3;
            color: white;
        }
        .profile-img {
            display: block;
            max-width: 150px;
            margin: 1rem auto;
            border-radius: 50%;
        }
        .portfolio-item {
            border: 1px solid #ddd;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>โปรไฟล์ของฉัน</h1>
        <p>ยินดีต้อนรับสู่เว็บโปรไฟล์ของฉัน!</p>
    </header>

    <nav>
        <a href="#about">เกี่ยวกับฉัน</a>
        <a href="#portfolio">ผลงาน</a>
        <a href="#skills">ทักษะ</a>
        <a href="#contact">การติดต่อ</a>
    </nav>

    <div class="container">
        <section id="about" class="section">
            <h2>เกี่ยวกับฉัน</h2>
            <img src="https://via.placeholder.com/150" alt="รูปโปรไฟล์" class="profile-img">
            <p>สวัสดีครับ/ค่ะ! ฉันเป็นผู้ที่มีความหลงใหลใน [ใส่ข้อมูลเกี่ยวกับตัวคุณ] และกำลังมุ่งหน้าสู่เป้าหมายในการเรียนต่อด้าน [ใส่สาขาวิชาที่สนใจ]</p>
        </section>

        <section id="portfolio" class="section">
            <h2>ผลงาน</h2>
            <div class="portfolio-item">
                <h3>ชื่อผลงานที่ 1</h3>
                <p>คำอธิบายสั้น ๆ เกี่ยวกับผลงานนี้และเหตุผลที่คุณภูมิใจ</p>
            </div>
            <div class="portfolio-item">
                <h3>ชื่อผลงานที่ 2</h3>
                <p>คำอธิบายสั้น ๆ เกี่ยวกับผลงานนี้</p>
            </div>
        </section>

        <section id="skills" class="section">
            <h2>ทักษะ</h2>
            <ul>
                <li>ทักษะ 1 (เช่น การพัฒนาเว็บไซต์)</li>
                <li>ทักษะ 2 (เช่น การวิเคราะห์ข้อมูล)</li>
                <li>ทักษะ 3</li>
            </ul>
        </section>

        <section id="contact" class="section">
            <h2>การติดต่อ</h2>
            <p>หากต้องการติดต่อสามารถส่งอีเมลได้ที่: <a href="mailto:example@example.com">example@example.com</a></p>
        </section>
    </div>

    <footer>
        <p>สร้างด้วยความตั้งใจ © 2024</p>
    </footer>
</body>
</html>
