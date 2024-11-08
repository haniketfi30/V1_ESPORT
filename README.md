<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع فريق الألعاب</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>فريق الألعاب</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">عن الفريق</a></li>
                <li><a href="#games">الألعاب</a></li>
                <li><a href="#join">انضم إلينا</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>عن الفريق</h2>
        <p>نحن فريق مختص في الألعاب مثل Call of Duty و Fortnite وغيرها. هدفنا هو الفوز في المسابقات وتكوين مجتمع قوي.</p>
    </section>

    <section id="games">
        <h2>ألعابنا</h2>
        <div class="game-icons">
            <div class="game">
                <img src="cod-icon.png" alt="Call of Duty">
                <p>Call of Duty</p>
            </div>
            <div class="game">
                <img src="fortnite-icon.png" alt="Fortnite">
                <p>Fortnite</p>
            </div>
            <div class="game">
                <img src="gta-icon.png" alt="GTA Online">
                <p>GTA Online</p>
            </div>
            <div class="game">
                <img src="rocket-league-icon.png" alt="Rocket League">
                <p>Rocket League</p>
            </div>
        </div>
    </section>

    <section id="join">
        <h2>انضم إلى فريقنا</h2>
        <form action="#">
            <label for="name">الاسم الكامل:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="skills">المهارات:</label>
            <input type="text" id="skills" name="skills"><br>
            <label for="why">لماذا ترغب في الانضمام؟</label>
            <textarea id="why" name="why" required></textarea><br>
            <button type="submit">إرسال</button>
        </form>
    </section>

    <section id="contact">
        <h2>اتصل بنا</h2>
        <p>لأي استفسارات أو مساعدة، يمكنكم التواصل معنا عبر:</p>
        <p>Email: <a href="mailto:contact@team.com">contact@team.com</a></p>
    </section>

    <footer>
        <p>جميع الحقوق محفوظة © 2024</p>
    </footer>
</body>
</html>
