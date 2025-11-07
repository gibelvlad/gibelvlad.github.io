<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Владислав & Анастасия - Свадьба 12 декабря 2025</title>
    
    <!-- Open Graph метатеги -->
    <meta property="og:title" content="Владислав & Анастасия - Свадьба 12 декабря 2025">
    <meta property="og:description" content="Приглашение на свадьбу Владислава и Анастасии. Ждём вас 12 декабря 2025 года">
    <meta property="og:image" content="https://example.com/wedding-preview.jpg">
    <meta property="og:url" content="https://example.com">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Свадьба Владислава и Анастасии">
    
    <!-- Twitter Card метатеги -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Владислав & Анастасия - Свадьба 12 декабря 2025">
    <meta name="twitter:description" content="Приглашение на свадьбу Владислава и Анастасии">
    <meta name="twitter:image" content="https://example.com/wedding-preview.jpg">
    
    <!-- Дополнительные метатеги -->
    <meta name="description" content="Приглашение на свадьбу Владислава и Анастасии. 12 декабря 2025 года">
    <meta name="keywords" content="свадьба, приглашение, Владислав, Анастасия, 12 декабря 2025">
    
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #e9cec5;
            color: #5a4d3a;
            line-height: 1.7;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #e9cec5 0%, #eedad3 100%);
            position: relative;
            touch-action: manipulation;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                radial-gradient(circle at 20% 80%, rgba(201, 34, 54, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(201, 34, 54, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 40% 40%, rgba(201, 34, 54, 0.03) 0%, transparent 50%);
            pointer-events: none;
            z-index: -1;
        }
        
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px 20px 40px;
            position: relative;
            z-index: 2;
        }
        
        .custom-invitation {
            background: rgba(248, 247, 243, 0.95);
            padding: 0;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(201, 34, 54, 0.15);
            border: 1px solid rgba(201, 34, 54, 0.1);
            margin-bottom: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .vertical-gallery {
            width: 100%;
        }
        
        .vertical-gallery img {
            width: 100%;
            height: auto;
            display: block;
            object-fit: cover;
        }
        
        .vertical-gallery img:not(:last-child) {
            margin-bottom: 0;
            border-bottom: none;
        }
        
        /* Обновленные стили для мероприятий */
        .events {
            margin: 30px 0;
        }
        
        .event {
            background: rgba(248, 247, 243, 0.9);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(201, 34, 54, 0.1);
            border: 1px solid rgba(201, 34, 54, 0.08);
            margin-bottom: 20px;
            position: relative;
            z-index: 2;
            text-align: center;
        }

        .event::before {
            content: '💒';
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            background: #f8f7f3;
            padding: 5px 10px;
            border-radius: 50%;
            font-size: 20px;
            box-shadow: 0 3px 10px rgba(201, 34, 54, 0.1);
            color: #c92236;
        }

        .event.reception::before {
            content: '🎉';
        }
        
        .event-time {
            font-size: 18px;
            color: #c92236;
            font-weight: 600;
            margin: 10px 0;
        }
        
        .event-location {
            font-size: 20px;
            margin: 10px 0;
        }
        
        .event-address {
            font-style: italic;
            margin: 10px 0;
        }
        
        .address-link {
            color: inherit;
            text-decoration: none;
            border-bottom: 1px dotted #c92236;
            transition: all 0.3s ease;
        }

        .address-link:hover {
            color: #c92236;
            border-bottom: 1px solid #c92236;
        }
        
        .event-note {
            font-size: 14px;
            color: #888;
            margin-top: 10px;
            font-style: italic;
        }

        .map-button {
            position: relative;
            display: block;
            width: 100%;
            padding: 18px 32px;
            background: linear-gradient(135deg, #c92236, #b31e30);
            color: #f8f7f3;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: 500;
            cursor: pointer;
            text-decoration: none;
            text-align: center;
            overflow: hidden;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(201, 34, 54, 0.4);
            font-family: 'Montserrat', sans-serif;
            letter-spacing: 0.5px;
            margin: 25px 0;
            z-index: 2;
        }

        .map-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(201, 34, 54, 0.6);
            background: linear-gradient(135deg, #d9263a, #c92236);
        }

        .map-button:active {
            transform: translateY(1px);
        }

        @keyframes bubble {
            0% {
                transform: translateY(0) scale(0.5);
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                transform: translateY(-80px) scale(1.2);
                opacity: 0;
            }
        }

        .bubble {
            position: absolute;
            bottom: -20px;
            background: rgba(248, 247, 243, 0.7);
            border-radius: 50%;
            pointer-events: none;
            animation: bubble 2s infinite;
        }

        .bubble:nth-child(1) {
            left: 20%;
            width: 20px;
            height: 20px;
            animation-delay: 0s;
        }

        .bubble:nth-child(2) {
            left: 40%;
            width: 15px;
            height: 15px;
            animation-delay: 0.5s;
        }

        .bubble:nth-child(3) {
            left: 60%;
            width: 25px;
            height: 25px;
            animation-delay: 1s;
        }

        .bubble:nth-child(4) {
            left: 80%;
            width: 18px;
            height: 18px;
            animation-delay: 1.5s;
        }
        
        .rsvp {
            text-align: center;
            margin: 40px 0;
            padding: 30px 25px;
            background: rgba(248, 247, 243, 0.9);
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(201, 34, 54, 0.1);
            border: 1px solid rgba(201, 34, 54, 0.08);
            position: relative;
            z-index: 2;
        }

        .rsvp::before {
            content: '✉';
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            background: #f8f7f3;
            padding: 5px 10px;
            border-radius: 50%;
            font-size: 20px;
            box-shadow: 0 3px 10px rgba(201, 34, 54, 0.1);
            color: #c92236;
        }
        
        .poll-form {
            margin-top: 25px;
            text-align: left;
        }
        
        .form-group {
            margin-bottom: 25px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 10px;
            font-weight: 500;
            color: #c92236;
            font-size: 16px;
        }
        
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 14px;
            border: 1px solid rgba(201, 34, 54, 0.2);
            border-radius: 8px;
            font-size: 16px;
            background: rgba(255, 255, 255, 0.9);
            transition: all 0.3s ease;
            font-family: 'Montserrat', sans-serif;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #c92236;
            box-shadow: 0 0 0 3px rgba(201, 34, 54, 0.1);
        }

        /* Стиль для скрытого поля второго гостя */
        .companion-field {
            display: none;
            margin-top: 15px;
            padding: 15px;
            background: rgba(201, 34, 54, 0.05);
            border-radius: 8px;
            border-left: 3px solid #c92236;
        }

        .companion-field.show {
            display: block;
        }

        .companion-note {
            font-size: 14px;
            color: #888;
            margin-top: 5px;
            font-style: italic;
        }
        
        /* Новая анимация для кнопки отправки */
        @keyframes sparkle {
            0%, 100% { 
                transform: scale(1);
                box-shadow: 0 5px 15px rgba(201, 34, 54, 0.3);
            }
            50% { 
                transform: scale(1.02);
                box-shadow: 0 8px 25px rgba(201, 34, 54, 0.5);
            }
        }
        
        .submit-button {
            width: 100%;
            padding: 18px;
            background: linear-gradient(135deg, #c92236, #b31e30);
            color: #f8f7f3;
            border: none;
            border-radius: 12px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 15px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(201, 34, 54, 0.3);
            font-weight: 500;
            letter-spacing: 0.5px;
            position: relative;
            overflow: hidden;
            z-index: 2;
            animation: sparkle 2s infinite;
        }

        .submit-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(201, 34, 54, 0.6);
            background: linear-gradient(135deg, #d9263a, #c92236);
            animation: none;
        }

        .submit-button:active {
            transform: translateY(1px);
        }
        
        /* Анимация сердечек для кнопки */
        @keyframes float {
            0%, 100% { 
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            50% { 
                opacity: 1;
            }
            100% { 
                transform: translateY(-20px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .heart {
            position: absolute;
            font-size: 16px;
            opacity: 0;
            pointer-events: none;
        }
        
        .hearts {
            text-align: center;
            font-size: 2.2em;
            color: #c92236;
            margin: 25px 0;
            animation: heartbeat 1.5s infinite;
            letter-spacing: 10px;
            z-index: 2;
            position: relative;
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        .closing-message {
            text-align: center;
            font-size: 18px;
            margin: 25px 0;
            line-height: 1.8;
            background: rgba(248, 247, 243, 0.9);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(201, 34, 54, 0.1);
            border: 1px solid rgba(201, 34, 54, 0.08);
            position: relative;
            z-index: 2;
        }
        
        /* ОБНОВЛЕННЫЙ ПЛЕЕР - ЭЛЕГАНТНЫЙ КРУГ С МУЗЫКАЛЬНЫМИ НОТАМИ */
        .music-player {
            position: fixed;
            bottom: 25px;
            right: 25px;
            z-index: 1000;
        }
        
        .music-btn {
            width: 65px;
            height: 65px;
            border-radius: 50%;
            background: linear-gradient(135deg, #c92236, #b31e30);
            color: #f8f7f3;
            border: none;
            font-size: 1.6em;
            cursor: pointer;
            box-shadow: 0 5px 20px rgba(201, 34, 54, 0.4);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        .music-btn::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(135deg, #ff6b6b, #ffa726, #c92236);
            border-radius: 50%;
            z-index: -1;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .music-btn:hover::before {
            opacity: 1;
        }

        .music-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 25px rgba(201, 34, 54, 0.6);
        }

        .music-btn:active {
            transform: scale(1.05);
        }

        /* Анимация пульсации для кнопки музыки */
        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(201, 34, 54, 0.7);
            }
            70% {
                box-shadow: 0 0 0 15px rgba(201, 34, 54, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(201, 34, 54, 0);
            }
        }

        .music-btn.playing {
            animation: pulse 2s infinite;
        }
        
        .designer {
            text-align: center;
            margin-top: 50px;
            font-size: 15px;
            color: #c92236;
            padding-top: 20px;
            border-top: 1px solid rgba(201, 34, 54, 0.2);
            font-style: italic;
            position: relative;
            z-index: 2;
        }
        
        /* ОБНОВЛЕННЫЙ РАЗДЕЛИТЕЛЬ - СВАДЕБНЫЕ КОЛЬЦА */
        .floral-divider {
            text-align: center;
            margin: 30px 0;
            color: #c92236;
            font-size: 28px;
            opacity: 0.7;
            position: relative;
            z-index: 2;
            letter-spacing: 15px;
        }

        .section-title {
            font-size: 24px;
            color: #c92236;
            margin-bottom: 15px;
            font-family: 'Playfair Display', serif;
            font-weight: 600;
        }

        .effects-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
            overflow: hidden;
        }

        #effectsCanvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .success-message {
            display: none;
            text-align: center;
            padding: 20px;
            background: rgba(248, 247, 243, 0.95);
            border-radius: 12px;
            margin: 20px 0;
            border: 2px solid #c92236;
            box-shadow: 0 5px 20px rgba(201, 34, 54, 0.3);
            position: relative;
            z-index: 2;
        }

        .side-effects-left, .side-effects-right {
            position: absolute;
            top: 0;
            width: 200px;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .side-effects-left {
            left: 0;
        }

        .side-effects-right {
            right: 0;
        }

        .side-effects-canvas {
            position: absolute;
            top: 0;
            width: 100%;
            height: 100%;
        }

        /* Стикер для ссылки на карту */
        .map-sticker {
            display: inline-block;
            margin-right: 10px;
            font-size: 20px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        /* Подсказка для мобильных устройств */
        .mobile-music-hint {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.85);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 10000;
            color: white;
            text-align: center;
            padding: 20px;
            backdrop-filter: blur(10px);
        }

        .mobile-music-content {
            background: linear-gradient(135deg, #c92236, #b31e30);
            padding: 30px;
            border-radius: 20px;
            max-width: 320px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            animation: hintPulse 2s infinite;
        }

        @keyframes hintPulse {
            0% {
                transform: scale(1);
                box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            }
            50% {
                transform: scale(1.03);
                box-shadow: 0 15px 40px rgba(0, 0, 0, 0.6);
            }
            100% {
                transform: scale(1);
                box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            }
        }

        .mobile-music-hint h3 {
            font-size: 24px;
            margin-bottom: 15px;
            color: white;
        }

        .mobile-music-hint p {
            font-size: 16px;
            margin-bottom: 20px;
            line-height: 1.5;
        }

        .enable-music-btn {
            background: white;
            color: #c92236;
            border: none;
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 18px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .enable-music-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
        }

        @media (max-width: 768px) {
            .container {
                padding: 15px 15px 30px;
            }
            
            .music-player {
                bottom: 15px;
                right: 15px;
            }
            
            .music-btn {
                width: 60px;
                height: 60px;
                font-size: 1.5em;
            }
            
            .side-effects-left, .side-effects-right {
                width: 100px;
            }
            
            .floral-divider {
                letter-spacing: 10px;
                font-size: 24px;
            }
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 10px 10px 20px;
            }
            
            .side-effects-left, .side-effects-right {
                width: 80px;
            }
            
            .floral-divider {
                letter-spacing: 8px;
                font-size: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Подсказка для мобильных устройств -->
    <div class="mobile-music-hint" id="mobileMusicHint">
        <div class="mobile-music-content">
            <h3>🎵 Свадебная музыка 🎵</h3>
            <p>Для полного погружения в атмосферу праздника включите фоновую музыку</p>
            <button class="enable-music-btn" id="enableMusicBtn">ВКЛЮЧИТЬ МУЗЫКУ</button>
        </div>
    </div>

    <div class="effects-container">
        <canvas id="effectsCanvas"></canvas>
    </div>

    <div class="side-effects-left">
        <canvas id="leftEffectsCanvas" class="side-effects-canvas"></canvas>
    </div>
    <div class="side-effects-right">
        <canvas id="rightEffectsCanvas" class="side-effects-canvas"></canvas>
    </div>

    <div class="container">
        <div class="custom-invitation">
            <div class="vertical-gallery" id="invitationImage">
                <img src="22/photo1.png" alt="Свадебное фото 1" onerror="this.src='https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo2.png" alt="Свадебное фото 2" onerror="this.src='https://images.unsplash.com/photo-1465495976277-4387d4b0e4a6?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo3.png" alt="Свадебное фото 3" onerror="this.src='https://images.unsplash.com/photo-1532712988316-4f6d2b5a0e6e?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo4.png" alt="Свадебное фото 4" onerror="this.src='https://images.unsplash.com/photo-1519741497674-611481863552?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
            </div>
        </div>

        <!-- ОБНОВЛЕННЫЙ РАЗДЕЛИТЕЛЬ - СВАДЕБНЫЕ КОЛЬЦА -->
        <div class="floral-divider">💍 💍 💍</div>
        
        <!-- Обновленный блок с двумя мероприятиями -->
        <div class="events">
            <div class="event">
                <div class="section-title">Торжественная регистрация</div>
                <div class="event-time">09:40</div>
                <div class="event-location">Дворец бракосочетания</div>
                <div class="event-address">
                    <a href="https://go.2gis.com/TN7gW" class="address-link" target="_blank">
                        Пр. Ленина, 11 / ул. Гоголя, 46
                    </a>
                </div>
                <div class="event-note">Камерное мероприятие для самых близких</div>
            </div>
            
            <div class="event reception">
                <div class="section-title">Банкет в честь свадьбы</div>
                <div class="event-time">15:00</div>
                <div class="event-location">Банкетный зал "Олимп"</div>
                <div class="event-address">Лесной тракт, 85</div>
            </div>
        </div>
        
        <!-- Кнопка карты теперь с красивым стикером -->
        <a href="https://go.2gis.com/Kupg2" class="map-button" target="_blank">
            <span class="map-sticker">🗺️</span> ПОСМОТРЕТЬ БАНКЕТНЫЙ ЗАЛ НА КАРТЕ
            <div class="bubble"></div>
            <div class="bubble"></div>
            <div class="bubble"></div>
            <div class="bubble"></div>
        </a>
        
        <div class="rsvp">
            <div class="section-title">Подтвердите участие</div>
            <p>Пожалуйста, ответьте до 1 декабря 2025 года</p>
            
            <form class="poll-form" id="rsvpForm" action="https://formspree.io/f/manlrqre" method="POST">
                <input type="hidden" name="_subject" value="Новый ответ на свадьбу Владислава и Анастасии!">
                <input type="hidden" name="_language" value="ru">
                
                <div class="form-group">
                    <label for="name">Ваше имя и фамилия</label>
                    <input type="text" id="name" name="name" required placeholder="Например, Иван Иванов">
                </div>
                
                <div class="form-group">
                    <label for="attendance">Вы сможете прийти?</label>
                    <select id="attendance" name="attendance" required>
                        <option value="">Выберите вариант</option>
                        <option value="yes">С радостью приду!</option>
                        <option value="no">К сожалению, не смогу</option>
                        <option value="maybe">Пока не уверен(а)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="companions">Сколько человек будет (включая вас)</label>
                    <select id="companions" name="companions" required>
                        <option value="1">1 человек</option>
                        <option value="2">2 человека</option>
                    </select>
                    <div class="companion-note">Если планируете прийти с парой, выберите "2 человека"</div>
                </div>

                <!-- Новое поле для второго гостя -->
                <div class="form-group companion-field" id="companionField">
                    <label for="companion_name">Имя и фамилия вашего спутника</label>
                    <input type="text" id="companion_name" name="companion_name" placeholder="Например, Мария Петрова">
                    
                    <div class="form-group">
                        <label for="companion_alcohol">Предпочтения в напитках вашего спутника</label>
                        <select id="companion_alcohol" name="companion_alcohol">
                            <option value="none">💧 Трезвый(ая), слежу за порядком</option>
                            <option value="wine">🍷 Вино (красное/белое) — для ценителей</option>
                            <option value="champagne">🥂 Шампанское - чтобы любовь искрилась!</option>
                            <option value="strong">🥃 Крепкие напитки (водка, коньяк, виски)</option>
                            <option value="samogon">🏺 Самогон - для настоящих ценителей</option>
                            <option value="all">🎯 Любые напитки - доверяю вашему вкусу!</option>
                            <option value="other">💫 Особые пожелания...(напишите в пожеланиях)</option>
                        </select>
                    </div>
                    
                    <div class="companion-note">Пожалуйста, укажите имя и фамилию человека, который придет с вами</div>
                </div>

                <div class="form-group">
                    <label for="alcohol">Ваши предпочтения в напитках</label>
                    <select id="alcohol" name="alcohol">
                        <option value="none">💧 Я сегодня трезвый, слежу за порядком</option>
                        <option value="wine">🍷 Вино (красное/белое) — для ценителей</option>
                        <option value="champagne">🥂 Шампанское - чтобы любовь искрилась!</option>
                        <option value="strong">🥃 Крепкие напитки (водка, коньяк, виски)</option>
                        <option value="samogon">🏺 Самогон - для настоящих ценителей</option>
                        <option value="all">🎯 Любые напитки - я доверяю вашему вкусу!</option>
                        <option value="other">💫 У меня есть особые пожелания...(напишите в пожеланиях)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="wishes">Ваши пожелания или особые предпочтения в напитках</label>
                    <textarea id="wishes" name="wishes" rows="3" placeholder="Напишите ваши пожелания или особые предпочтения..."></textarea>
                </div>
                
                <input type="text" name="_gotcha" style="display: none;">
                
                <button type="submit" class="submit-button" id="submitBtn">
                    ОТПРАВИТЬ ОТВЕТ
                </button>
                
                <div class="success-message" id="successMessage">
                    <h3>Спасибо за ваш ответ! 💖</h3>
                    <p>Мы очень рады, что вы сможете разделить с нами этот особенный день!</p>
                </div>
            </form>
        </div>
        
        <div class="hearts">💖 💕 💗 💓 💞</div>
        
        <!-- Улучшенное закрывающее сообщение -->
        <div class="closing-message">
            Мы с нетерпением ждём этот день<br> 
            и будем рады разделить его с вами!<br>
            Ваше присутствие сделает наш праздник<br>
            ещё более тёплым и незабываемым.
        </div>
        
        <div class="designer">
            С любовью, Владислав и Анастасия
        </div>
    </div>

    <!-- ОБНОВЛЕННЫЙ ПЛЕЕР - ЭЛЕГАНТНЫЙ КРУГ С МУЗЫКАЛЬНЫМИ НОТАМИ -->
    <div class="music-player">
        <button class="music-btn" id="musicToggleBtn">♪♫</button>
    </div>

    <audio id="weddingMusic" loop preload="auto">
        <source src="22/wedding-music.mp3" type="audio/mpeg">
        <source src="22/wedding-music.ogg" type="audio/ogg">
        Ваш браузер не поддерживает аудио элемент.
    </audio>

    <script>
        // СОВЕРШЕННО НОВАЯ ЛОГИКА ДЛЯ МУЗЫКИ
        const music = document.getElementById('weddingMusic');
        const musicToggleBtn = document.getElementById('musicToggleBtn');
        const mobileMusicHint = document.getElementById('mobileMusicHint');
        const enableMusicBtn = document.getElementById('enableMusicBtn');
        
        let isPlaying = false;
        let musicInitialized = false;
        let userInteracted = false;

        // Проверка мобильного устройства
        function isMobileDevice() {
            return /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent);
        }

        // Инициализация музыки
        function initializeMusic() {
            if (musicInitialized) return;
            
            // Настройка музыки
            music.volume = 0.6; // Немного тише для комфорта
            music.preload = 'auto';
            
            // Предзагрузка
            music.load();
            musicInitialized = true;
            
            console.log('Музыка инициализирована');
        }

        // Функция включения музыки
        function playMusic() {
            if (!musicInitialized) initializeMusic();
            
            const playPromise = music.play();
            
            if (playPromise !== undefined) {
                playPromise.then(() => {
                    isPlaying = true;
                    musicToggleBtn.innerHTML = '❚❚';
                    musicToggleBtn.classList.add('playing');
                    mobileMusicHint.style.display = 'none';
                    userInteracted = true;
                    
                    // Сохраняем состояние в localStorage
                    localStorage.setItem('musicEnabled', 'true');
                    
                    console.log('Музыка успешно запущена');
                }).catch(error => {
                    console.log('Ошибка воспроизведения:', error);
                    // Показываем подсказку на мобильных
                    if (isMobileDevice()) {
                        mobileMusicHint.style.display = 'flex';
                    }
                });
            }
        }

        // Функция выключения музыки
        function pauseMusic() {
            music.pause();
            isPlaying = false;
            musicToggleBtn.innerHTML = '♪♫';
            musicToggleBtn.classList.remove('playing');
            localStorage.setItem('musicEnabled', 'false');
        }

        // Переключение музыки
        function toggleMusic() {
            if (isPlaying) {
                pauseMusic();
            } else {
                playMusic();
            }
        }

        // Обработчики событий
        musicToggleBtn.addEventListener('click', toggleMusic);
        enableMusicBtn.addEventListener('click', playMusic);

        // Попытка автоматического воспроизведения для десктопов
        function tryAutoPlay() {
            if (!isMobileDevice()) {
                // Для десктопов пробуем автовоспроизведение
                setTimeout(() => {
                    if (!userInteracted) {
                        playMusic();
                    }
                }, 1500);
            } else {
                // Для мобильных проверяем, был ли ранее включен звук
                const musicEnabled = localStorage.getItem('musicEnabled');
                if (musicEnabled === 'true') {
                    // Если пользователь ранее включал музыку, пробуем воспроизвести
                    setTimeout(() => {
                        playMusic();
                    }, 1000);
                } else {
                    // Показываем подсказку для мобильных
                    setTimeout(() => {
                        mobileMusicHint.style.display = 'flex';
                    }, 2000);
                }
            }
        }

        // Инициализация при загрузке страницы
        window.addEventListener('load', function() {
            initializeMusic();
            
            // Даем время на загрузку страницы
            setTimeout(() => {
                tryAutoPlay();
            }, 500);
        });

        // Обработка пользовательского взаимодействия для мобильных
        document.addEventListener('click', function() {
            userInteracted = true;
        });

        document.addEventListener('touchstart', function() {
            userInteracted = true;
        });

        // Обработка видимости страницы (когда пользователь возвращается на вкладку)
        document.addEventListener('visibilitychange', function() {
            if (!document.hidden && isPlaying && userInteracted) {
                // Если страница снова стала активной и музыка должна играть
                music.play().catch(e => console.log('Не удалось возобновить музыку'));
            }
        });

        // Код для управления полем второго гостя
        document.addEventListener('DOMContentLoaded', function() {
            const companionsSelect = document.getElementById('companions');
            const companionField = document.getElementById('companionField');
            const companionInput = document.getElementById('companion_name');

            function toggleCompanionField() {
                if (companionsSelect.value === '2') {
                    companionField.classList.add('show');
                    companionInput.required = true;
                } else {
                    companionField.classList.remove('show');
                    companionInput.required = false;
                    companionInput.value = '';
                }
            }

            toggleCompanionField();
            companionsSelect.addEventListener('change', toggleCompanionField);

            document.getElementById('rsvpForm').addEventListener('submit', function(e) {
                if (companionsSelect.value === '2' && !companionInput.value.trim()) {
                    e.preventDefault();
                    alert('Пожалуйста, укажите имя и фамилию вашего спутника');
                    companionInput.focus();
                }
            });
        });

        // Анимация сердечек для кнопки отправки
        document.getElementById('submitBtn').addEventListener('click', function(e) {
            if (document.getElementById('rsvpForm').checkValidity()) {
                createHeartsAnimation(e);
            }
        });

        function createHeartsAnimation(event) {
            const button = event.target;
            for (let i = 0; i < 8; i++) {
                const heart = document.createElement('div');
                heart.className = 'heart';
                heart.innerHTML = '💖';
                heart.style.left = (Math.random() * 80 + 10) + '%';
                heart.style.animation = `float ${Math.random() * 1 + 1}s ease-out forwards`;
                button.appendChild(heart);
                setTimeout(() => heart.remove(), 1200);
            }
        }

        // Код для эффектов (остается без изменений)
        const mainCanvas = document.getElementById('effectsCanvas');
        const mainCtx = mainCanvas.getContext('2d');
        const leftCanvas = document.getElementById('leftEffectsCanvas');
        const leftCtx = leftCanvas.getContext('2d');
        const rightCanvas = document.getElementById('rightEffectsCanvas');
        const rightCtx = rightCanvas.getContext('2d');
        
        let particles = [];
        let leftParticles = [];
        let rightParticles = [];
        let periodicFireworksInterval;

        const colors = {
            fireworks: ['#c92236', '#e9cec5', '#eedad3', '#f8f7f3', '#ffd700', '#ff6b6b', '#ffa726'],
            confetti: ['#c92236', '#e9cec5', '#eedad3', '#f8f7f3', '#ffd700', '#c0c0c0', '#ff6b6b', '#ffa726']
        };

        function resizeCanvases() {
            mainCanvas.width = window.innerWidth;
            mainCanvas.height = window.innerHeight;
            
            const invitationRect = document.getElementById('invitationImage').getBoundingClientRect();
            const imageHeight = invitationRect.height;
            
            leftCanvas.width = 200;
            leftCanvas.height = imageHeight;
            rightCanvas.width = 200;
            rightCanvas.height = imageHeight;
            
            const leftContainer = document.querySelector('.side-effects-left');
            const rightContainer = document.querySelector('.side-effects-right');
            
            leftContainer.style.top = invitationRect.top + 'px';
            leftContainer.style.height = imageHeight + 'px';
            rightContainer.style.top = invitationRect.top + 'px';
            rightContainer.style.height = imageHeight + 'px';
        }

        class Firework {
            constructor(x, y, color, isBig = false) {
                this.x = x;
                this.y = y;
                this.color = color || colors.fireworks[Math.floor(Math.random() * colors.fireworks.length)];
                this.particles = [];
                this.createParticles(isBig);
            }
            
            createParticles(isBig) {
                const particleCount = isBig ? 
                    150 + Math.floor(Math.random() * 80) :
                    100 + Math.floor(Math.random() * 50);
                
                for (let i = 0; i < particleCount; i++) {
                    const angle = Math.random() * Math.PI * 2;
                    const speed = isBig ? 
                        Math.random() * 6 + 3 :
                        Math.random() * 4 + 2;
                    const size = isBig ? 
                        Math.random() * 4 + 2 :
                        Math.random() * 3 + 1;
                    const decay = Math.random() * 0.015 + 0.01;
                    
                    this.particles.push({
                        x: this.x,
                        y: this.y,
                        vx: Math.cos(angle) * speed,
                        vy: Math.sin(angle) * speed,
                        size: size,
                        color: this.color,
                        alpha: 1,
                        decay: decay,
                        gravity: 0.05
                    });
                }
            }
            
            update() {
                for (let i = this.particles.length - 1; i >= 0; i--) {
                    const p = this.particles[i];
                    
                    p.x += p.vx;
                    p.y += p.vy;
                    p.vy += p.gravity;
                    p.alpha -= p.decay;
                    
                    if (p.alpha <= 0) {
                        this.particles.splice(i, 1);
                    }
                }
                
                return this.particles.length > 0;
            }
            
            draw(ctx) {
                for (const p of this.particles) {
                    ctx.save();
                    ctx.globalAlpha = p.alpha;
                    ctx.fillStyle = p.color;
                    ctx.beginPath();
                    ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
                    ctx.fill();
                    ctx.restore();
                }
            }
        }

        class Confetti {
            constructor(x, y, canvasWidth, isLeft = true, isBig = false) {
                this.x = x;
                this.y = y;
                this.canvasWidth = canvasWidth;
                this.isLeft = isLeft;
                this.particles = [];
                this.createParticles(isBig);
            }
            
            createParticles(isBig) {
                const particleCount = isBig ? 
                    60 + Math.floor(Math.random() * 30) :
                    40 + Math.floor(Math.random() * 20);
                
                for (let i = 0; i < particleCount; i++) {
                    const angle = this.isLeft ? 
                        Math.random() * Math.PI * 0.5 + Math.PI * 0.25 :
                        Math.random() * Math.PI * 0.5 + Math.PI * 0.75;
                    
                    const speed = isBig ? 
                        Math.random() * 4 + 2 :
                        Math.random() * 3 + 1;
                    const size = isBig ? 
                        Math.random() * 8 + 5 :
                        Math.random() * 6 + 3;
                    const shape = Math.random() > 0.5 ? 'rect' : 'circle';
                    const color = colors.confetti[Math.floor(Math.random() * colors.confetti.length)];
                    
                    this.particles.push({
                        x: this.x,
                        y: this.y,
                        vx: Math.cos(angle) * speed,
                        vy: Math.sin(angle) * speed,
                        size: size,
                        color: color,
                        shape: shape,
                        rotation: Math.random() * Math.PI * 2,
                        rotationSpeed: (Math.random() - 0.5) * 0.15,
                        gravity: 0.1
                    });
                }
            }
            
            update() {
                for (let i = this.particles.length - 1; i >= 0; i--) {
                    const p = this.particles[i];
                    
                    p.x += p.vx;
                    p.y += p.vy;
                    p.vy += p.gravity;
                    p.rotation += p.rotationSpeed;
                    
                    p.vx *= 0.99;
                    p.vy *= 0.99;
                    
                    if (p.y > this.canvasWidth || p.x < 0 || p.x > this.canvasWidth) {
                        this.particles.splice(i, 1);
                    }
                }
                
                return this.particles.length > 0;
            }
            
            draw(ctx) {
                for (const p of this.particles) {
                    ctx.save();
                    ctx.translate(p.x, p.y);
                    ctx.rotate(p.rotation);
                    ctx.fillStyle = p.color;
                    
                    if (p.shape === 'rect') {
                        ctx.fillRect(-p.size/2, -p.size/2, p.size, p.size);
                    } else {
                        ctx.beginPath();
                        ctx.arc(0, 0, p.size/2, 0, Math.PI * 2);
                        ctx.fill();
                    }
                    
                    ctx.restore();
                }
            }
        }

        function createFirework(x, y, isBig = false) {
            particles.push(new Firework(x, y, null, isBig));
        }

        function createLeftEffects() {
            for (let i = 0; i < 5; i++) {
                setTimeout(() => {
                    const x = 30;
                    const y = Math.random() * leftCanvas.height;
                    leftParticles.push(new Confetti(x, y, leftCanvas.width, true, true));
                    
                    const fireworkX = 40;
                    const fireworkY = Math.random() * leftCanvas.height * 0.8;
                    leftParticles.push(new Firework(fireworkX, fireworkY, null, true));
                }, i * 300);
            }
        }

        function createRightEffects() {
            for (let i = 0; i < 5; i++) {
                setTimeout(() => {
                    const x = rightCanvas.width - 30;
                    const y = Math.random() * rightCanvas.height;
                    rightParticles.push(new Confetti(x, y, rightCanvas.width, false, true));
                    
                    const fireworkX = rightCanvas.width - 40;
                    const fireworkY = Math.random() * rightCanvas.height * 0.8;
                    rightParticles.push(new Firework(fireworkX, fireworkY, null, true));
                }, i * 300);
            }
        }

        function startPeriodicFireworks() {
            periodicFireworksInterval = setInterval(() => {
                const x = Math.random() * mainCanvas.width;
                const y = Math.random() * mainCanvas.height * 0.3;
                createFirework(x, y, Math.random() > 0.7);
            }, 5000 + Math.random() * 3000);
        }

        function animateMain() {
            mainCtx.fillStyle = 'rgba(233, 206, 197, 0.08)';
            mainCtx.fillRect(0, 0, mainCanvas.width, mainCanvas.height);
            
            for (let i = particles.length - 1; i >= 0; i--) {
                if (!particles[i].update()) {
                    particles.splice(i, 1);
                } else {
                    particles[i].draw(mainCtx);
                }
            }
            
            requestAnimationFrame(animateMain);
        }

        function animateLeftEffects() {
            leftCtx.clearRect(0, 0, leftCanvas.width, leftCanvas.height);
            
            for (let i = leftParticles.length - 1; i >= 0; i--) {
                if (!leftParticles[i].update()) {
                    leftParticles.splice(i, 1);
                } else {
                    leftParticles[i].draw(leftCtx);
                }
            }
            
            requestAnimationFrame(animateLeftEffects);
        }

        function animateRightEffects() {
            rightCtx.clearRect(0, 0, rightCanvas.width, rightCanvas.height);
            
            for (let i = rightParticles.length - 1; i >= 0; i--) {
                if (!rightParticles[i].update()) {
                    rightParticles.splice(i, 1);
                } else {
                    rightParticles[i].draw(rightCtx);
                }
            }
            
            requestAnimationFrame(animateRightEffects);
        }

        animateMain();
        animateLeftEffects();
        animateRightEffects();

        function startSideEffects() {
            setTimeout(() => {
                createLeftEffects();
                createRightEffects();
            }, 1000);
        }

        document.getElementById('rsvpForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            document.getElementById('successMessage').style.display = 'block';
            document.getElementById('submitBtn').style.display = 'none';
            
            for (let i = 0; i < 7; i++) {
                setTimeout(() => {
                    const x = window.innerWidth / 2 + (Math.random() - 0.5) * 300;
                    const y = window.innerHeight / 2 + (Math.random() - 0.5) * 200;
                    createFirework(x, y, true);
                }, i * 250);
            }
            
            setTimeout(() => {
                this.submit();
            }, 3000);
        });

        window.addEventListener('load', () => {
            resizeCanvases();
            startSideEffects();
            startPeriodicFireworks();
            window.addEventListener('resize', resizeCanvases);
        });

        window.addEventListener('beforeunload', () => {
            if (periodicFireworksInterval) {
                clearInterval(periodicFireworksInterval);
            }
        });
    </script>
</body>
</html>
