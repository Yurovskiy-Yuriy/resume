<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Юровский Юрий - Сетевой инженер</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(135deg, #F5F5DC 0%, #FDF6E3 50%, #FAF0E6 100%);
            padding: 40px 20px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            min-height: 100vh;
            color: #4A3728;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .header {
            background: linear-gradient(135deg, #D2B48C 0%, #F5DEB3 50%, #DEB887 100%);
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            margin-bottom: 40px;
            overflow: hidden;
        }
        .photo {
            float: left;
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-right: 20px;
            filter: sepia(0.3) saturate(1.3) brightness(1.05);
        }
        .header h1 {
            color: #8B4513;
            font-weight: bold;
            font-size: 2.2em;
            margin-bottom: 5px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        .header .title {
            color: #5D4037;
            font-size: 1.3em;
            margin-bottom: 15px;
        }
        .header .email {
            color: #6D4C41;
            font-weight: bold;
            text-decoration: none;
        }
        .header .email:hover {
            text-decoration: underline;
        }
        .section {
            background: rgba(255,255,255,0.7);
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .section h2 {
            color: #5D4037;
            font-size: 1.8em;
            margin-bottom: 15px;
            border-bottom: 2px solid #DEB887;
            padding-bottom: 8px;
        }
        .section h3 {
            color: #3E2723;
            font-size: 1.4em;
            margin: 20px 0 12px 0;
        }
        .experience-duration {
            color: #3E2723;
            font-size: 1.2em;
            font-weight: bold;
            margin-bottom: 15px;
        }
        ul {
            list-style: none;
            padding-left: 0;
        }
        ul li {
            color: #4A3728;
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }
        ul li:before {
            content: "▸";
            color: #8B4513;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        .clearfix::after {
            content: "";
            display: table;
            clear: both;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header clearfix">
            <img src="https://github.com/Yurovskiy-Yuriy/resume/raw/main/photo.jpg" alt="Юрий Юровский" class="photo">
            <div>
                <h1>Юровский Юрий</h1>
                <div class="title"><strong>Сетевой инженер</strong> | <em>41 год</em></div>
                <div>✉️ <a href="mailto:yurovskiy2007@yandex.ru" class="email">yurovskiy2007@yandex.ru</a></div>
            </div>
        </div>

        <div class="section">
            <h2>🎯 Специализации</h2>
            <ul>
                <li>Сетевой инженер</li>
            </ul>
        </div>

        <div class="section">
            <h2>💼 Опыт работы</h2>
            <div class="experience-duration">7 лет 11 месяцев</div>
            <h3>Сетевой инженер, системный администратор</h3>
            <ul>
                <li>Настройка коммутаторов и маршрутизаторов с нуля</li>
                <li>Создание отказоустойчивых топологий коммутаторов и маршрутизаторов</li>
                <li>Проектирование и создание безопасных корпоративных сетей</li>
                <li>Установка и настройка систем мониторинга сетевого оборудования</li>
                <li>Сбор и анализ сетевого трафика</li>
                <li>Поиск и устранение проблем в локальных и глобальных сетях</li>
                <li>Администрирование операционной системы Linux на базовом уровне</li>
                <li>Понимание механизмов защиты сетей передачи данных</li>
                <li>Настройка средств защиты информации</li>
            </ul>
        </div>
    </div>
</body>
</html>