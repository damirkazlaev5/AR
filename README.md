<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Амирова Эльвира Рафиговна </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        header {
            background: #35424a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        section {
            padding: 40px 0;
            background: white;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .image-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .image-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #35424a;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Добро пожаловать на Делигатцыю Эльвиры Рафиговны!</h1>
            <p>Учитесь Учитесь и ещё раз пикми палка(гигант)</p>
        </div>
    </header>

    <div class="container">
        <section>
            <h2>Обо мне</h2>
            <p>Учитель года.</p>
            <div class="image-grid">
                <div class="image-item">
                    <img src="https://sch2091.mskobr.ru/attach_files/photo_new/photo_f2cf8393b69e0406ce8a2cef88199d9b_683c543540d73.jpeg" alt="">
                </div>
               
            </div>
        </section>

        <section>
            <h2>Наши услуги</h2>
            <p>Для того чтобы получить 5 напиши контрольную на 5.</p>
            <div class="image-grid">
                <div class="image-item">
                    <img src="https://avatars.mds.yandex.net/i?id=dc2083ce19aacec130c76b812446ebfb913c3865-5221713-images-thumbs&n=13" alt="Радуемся">
                </div>
                <div class="image-item">
                    <img src="https://avatars.mds.yandex.net/get-entity_search/2295215/1189293407/SUx182_2x" alt="Не радуемся">
                </div>
            </div>
        </section>

        <section>
            <h2>Контакты</h2>
            <p>Учитель года!</p>
            <p>Email: секрет<br>Телефон: неизвестно</p>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2026 Делигатцыя Эльвира Рафиговны.</p>
        </div>
    </footer>
</body>
</html>
