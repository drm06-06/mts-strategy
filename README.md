<style>
    /* Добавляем переменные цвета, чтобы стили заработали */
    :root {
        --mts-red: #E30613;
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

    /* Стили для видео */
    .video-container {
        margin: 20px 0;
        text-align: center;
    }

    .video-label {
        display: block;
        margin-top: 10px;
        font-weight: bold;
        color: #666;
    }

    footer {
        text-align: center;
        padding: 40px;
        background: var(--mts-dark);
        color: white;
    }

    .credits {
        margin-top: 15px;
        font-size: 0.9em;
        opacity: 0.8;
    }
</style>

<header>
    <div class="logo">MTS Project</div>
    <nav>
        <a href="#">Главная</a>
        <a href="#">О нас</a>
    </nav>
</header>

<div class="hero">
    <h1>Добро пожаловать</h1>
</div>

<div class="container">
    <section>
        <h2>Рекламный ролик</h2>
        <div class="video-container">
            <iframe src="https://vk.com/video_ext.php?oid=-194202961&id=456243360&hash=792945d83627051a" 
                    width="100%" height="450" frameborder="0" allowfullscreen title="Реклама МТС"></iframe>
            <span class="video-label">Реклама МТС</span>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2026 Все права защищены.</p>
    <div class="credits">
        Над сайтом работали Дряннов Александр и Козичев Илья
    </div>
</footer>

</body>
</html>
