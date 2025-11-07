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
    
    <!-- Предзагрузка критических ресурсов -->
    <link rel="preload" href="22/photo1.png" as="image">
    <link rel="preload" href="22/photo2.png" as="image">
    <link rel="preload" href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Montserrat:wght@300;400;500&display=swap" as="style">
    
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
        }

        /* Индикатор загрузки */
        .loading-indicator {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 3px;
            background: rgba(201, 34, 54, 0.2);
            z-index: 9999;
            display: none;
        }

        .loading-progress {
            height: 100%;
            background: linear-gradient(90deg, #c92236, #ff6b6b);
            width: 0%;
            transition: width 0.3s ease;
        }

        .image-loading {
            background: #f0f0f0;
            position: relative;
            overflow: hidden;
        }

        .image-loading::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent);
            animation: loadingShimmer 1.5s infinite;
        }

        @keyframes loadingShimmer {
            0% { left: -100%; }
            100% { left: 100%; }
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
            transition: opacity 0.5s ease;
        }

        .vertical-gallery img[data-src] {
            opacity: 0;
        }

        .vertical-gallery img.loaded {
            opacity: 1;
        }
        
        .vertical-gallery img:not(:last-child) {
            margin-bottom: 0;
            border-bottom: none;
        }
        
        /* Остальные стили остаются такими же... */
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
    <!-- Индикатор загрузки -->
    <div class="loading-indicator" id="loadingIndicator">
        <div class="loading-progress" id="loadingProgress"></div>
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
                <img src="22/photo1.png" alt="Свадебное фото 1" loading="eager" 
                     onerror="this.src='https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo2.png" alt="Свадебное фото 2" loading="lazy" 
                     onerror="this.src='https://images.unsplash.com/photo-1465495976277-4387d4b0e4a6?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo3.png" alt="Свадебное фото 3" loading="lazy" 
                     onerror="this.src='https://images.unsplash.com/photo-1532712988316-4f6d2b5a0e6e?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
                <img src="22/photo4.png" alt="Свадебное фото 4" loading="lazy" 
                     onerror="this.src='https://images.unsplash.com/photo-1519741497674-611481863552?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80'">
            </div>
        </div>

        <div class="floral-divider">💍 💍 💍</div>
        
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

    <div class="music-player">
        <button class="music-btn" id="musicToggleBtn">♪♫</button>
    </div>

    <audio id="weddingMusic" loop>
        <source src="22/wedding-music.mp3" type="audio/mpeg">
        <source src="22/wedding-music.ogg" type="audio/ogg">
        Ваш браузер не поддерживает аудио элемент.
    </audio>

    <script>
        // Улучшенная загрузка изображений
        document.addEventListener('DOMContentLoaded', function() {
            const loadingIndicator = document.getElementById('loadingIndicator');
            const loadingProgress = document.getElementById('loadingProgress');
            const images = document.querySelectorAll('img');
            let loadedCount = 0;
            const totalImages = images.length;

            // Показываем индикатор загрузки
            loadingIndicator.style.display = 'block';

            images.forEach((img, index) => {
                // Добавляем класс загрузки
                img.classList.add('image-loading');

                const image = new Image();
                image.onload = function() {
                    loadedCount++;
                    const progress = (loadedCount / totalImages) * 100;
                    loadingProgress.style.width = progress + '%';
                    
                    // Убираем класс загрузки и добавляем класс загруженного
                    img.classList.remove('image-loading');
                    img.classList.add('loaded');

                    // Скрываем индикатор когда все загружено
                    if (loadedCount === totalImages) {
                        setTimeout(() => {
                            loadingIndicator.style.display = 'none';
                        }, 500);
                    }
                };

                image.onerror = function() {
                    loadedCount++;
                    const progress = (loadedCount / totalImages) * 100;
                    loadingProgress.style.width = progress + '%';
                    img.classList.remove('image-loading');
                    
                    if (loadedCount === totalImages) {
                        setTimeout(() => {
                            loadingIndicator.style.display = 'none';
                        }, 500);
                    }
                };

                image.src = img.src;
            });

            // Если нет изображений, сразу скрываем индикатор
            if (totalImages === 0) {
                loadingIndicator.style.display = 'none';
            }
        });

        // Остальной JavaScript код остается таким же...
        const music = document.getElementById('weddingMusic');
        const musicToggleBtn = document.getElementById('musicToggleBtn');
        let isPlaying = false;

        function toggleMusic() {
            if (isPlaying) {
                music.pause();
                isPlaying = false;
                musicToggleBtn.innerHTML = '♪♫';
                musicToggleBtn.classList.remove('playing');
            } else {
                music.play().then(() => {
                    isPlaying = true;
                    musicToggleBtn.innerHTML = '❚❚';
                    musicToggleBtn.classList.add('playing');
                }).catch(e => {
                    console.log('Не удалось воспроизвести музыку');
                });
            }
        }

        musicToggleBtn.addEventListener('click', toggleMusic);

        window.addEventListener('load', function() {
            setTimeout(function() {
                if (!isPlaying) {
                    music.play().then(() => {
                        isPlaying = true;
                        musicToggleBtn.innerHTML = '❚❚';
                        musicToggleBtn.classList.add('playing');
                    }).catch(error => {
                        console.log('Автовоспроизведение заблокировано. Для включения музыки нажмите на кнопку.');
                        isPlaying = false;
                        musicToggleBtn.innerHTML = '♪♫';
                        musicToggleBtn.classList.remove('playing');
                    });
                }
            }, 1000);
        });

        // Управление полем второго гостя
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
            const rect = button.getBoundingClientRect();
            
            for (let i = 0; i < 8; i++) {
                const heart = document.createElement('div');
                heart.className = 'heart';
                heart.innerHTML = '💖';
                heart.style.left = (Math.random() * 80 + 10) + '%';
                heart.style.animation = `float ${Math.random() * 1 + 1}s ease-out forwards`;
                button.appendChild(heart);
                
                setTimeout(() => {
                    heart.remove();
                }, 1200);
            }
        }

        // Код для эффектов (остается без изменений)
        // ... (остальной JavaScript код для анимаций)
    </script>
</body>
</html>
