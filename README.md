<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Информационный портал</title>
    <style>
        /* Добавляем переменные, которые использовались в вашем CSS */
        :root {
            --mts-red: #E30613; /* Фирменный красный */
            --mts-dark: #1d1d1b;
            --light-bg: #f2f2f2;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            background-color: var(--light-bg);
            color: #333;
        }

        header {
            background-color: white;
            padding: 20px 5%;
            border-bottom: 3px solid var(--mts-red);
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: var(--mts-red);
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: var(--mts-dark);
            font-weight: 500;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1560179707-f14e90ef3623?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            color: white;
            padding: 100px 5%;
            text-align: center;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            background: white;
            padding: 30px;
            margin-bottom: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        h2 {
            color: var(--mts-red);
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
        }

        .video-container {
            margin: 20px 0;
            text-align: center;
        }

        .video-label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
            color: var(--mts-red);
        }

        .video-link {
            display: inline-block;
            padding: 15px 25px;
            background-color: var(--mts-red);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .video-link:hover {
            background-color: #b3050f;
        }

        footer {
            text-align: center;
            padding: 40px;
            background: var(--mts-dark);
            color: white;
        }

        .authors {
            margin-top: 20px;
            font-size: 0.9em;
            opacity: 0.8;
            border-top: 1px solid #444;
            padding-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">МТС ПРОЕКТ</div>
    <nav>
        <a href="#">Главная</a>
        <a href="#">О нас</a>
        <a href="#">Контакты</a>
    </nav>
</header>

<div class="hero">
    <h1>Добро пожаловать</h1>
    <p>Информационный ресурс для вашего удобства</p>
</div>

<div class="container">
    <section>
        <h2>Рекламные материалы</h2>
        <div class="video-container">
            <span class="video-label">реклама мтс</span>
            <a href="https://vk.com/video-194202961_456243360" target="_blank" class="video-link">Смотреть видео в VK</a>
        </div>
    </section>

    <section>
        <h2>О проекте</h2>
        <p>Здесь вы можете разместить основной текст вашего сайта. Весь дизайн адаптирован под фирменный стиль с использованием красных акцентов.</p>
    </section>
</div>

<footer>
    <p>&copy; 2026 Все права защищены</p>
    <div class="authors">
        Над сайтом работали Дряннов Александр и Козичев Илья
    </div>
</footer>

</body>
</html>
