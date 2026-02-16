<style>
    :root {
        --mts-red: #e30613; /* Фирменный красный МТС */
        --mts-dark: #1d1d1b;
        --light-bg: #f2f3f7;
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
        position: relative;
        padding-bottom: 56.25%; /* Соотношение сторон 16:9 */
        height: 0;
        overflow: hidden;
        margin: 20px 0;
        border-radius: 8px;
    }

    .video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: none;
    }

    .video-label {
        font-weight: bold;
        color: var(--mts-dark);
        margin-bottom: 10px;
        display: block;
    }

    .law-links {
        background: #fff0f0;
        padding: 20px;
        border-left: 5px solid var(--mts-red);
    }

    .law-links a {
        color: #d32f2f;
        display: block;
        margin: 10px 0;
        text-decoration: none;
        font-weight: bold;
    }

    .law-links a:hover {
        text-decoration: underline;
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
    <div class="logo">MTS PROJECT</div>
    <nav>
        <a href="#">Главная</a>
        <a href="#">О проекте</a>
    </nav>
</header>

<div class="container">
    <section>
        <h2>Рекламный ролик</h2>
        <span class="video-label">Реклама МТС</span>
        <div class="video-container">
            <iframe src="https://vk.com/video_ext.php?oid=-194202961&id=456243360&hash=57125368a6d61d15" allow="autoplay; encrypted-media; fullscreen; picture-in-picture;" allowfullscreen></iframe>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2026 Все права защищены</p>
    <div class="credits">
        Над сайтом работали Дряннов Александр и Козичев Илья
    </div>
</footer>
