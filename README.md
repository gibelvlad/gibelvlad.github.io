
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Владислав & Анастасия - Свадьба</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #fefefe;
            color: #5a4d3a;
            line-height: 1.7;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Montserrat', sans-serif;
            background: 
                linear-gradient(135deg, #fdfaf5 0%, #f9f4eb 100%);
            position: relative;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                radial-gradient(circle at 20% 80%, rgba(212, 175, 135, 0.03) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(212, 175, 135, 0.03) 0%, transparent 50%),
                radial-gradient(circle at 40% 40%, rgba(212, 175, 135, 0.02) 0%, transparent 50%);
            pointer-events: none;
            z-index: -1;
        }
        
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px 20px 40px;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding-top: 30px;
            position: relative;
        }

        .header::after {
            content: '❦';
            display: block;
            font-size: 24px;
            color: #d4af87;
            margin-top: 15px;
            opacity: 0.6;
        }
        
        h1 {
            font-size: 24px;
            letter-spacing: 4px;
            margin-bottom: 15px;
            color: #d4af87;
            font-weight: 400;
            text-transform: uppercase;
            font-family: 'Montserrat', sans-serif;
        }
        
        h2 {
            font-size: 42px;
            margin: 20px 0;
            color: #8b7355;
            font-weight: 500;
            font-family: 'Playfair Display', serif;
            position: relative;
            display: inline-block;
            line-height: 1.2;
        }

        h2::before, h2::after {
            content: '✦';
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            color: #d4af87;
            font-size: 16px;
            opacity: 0.6;
        }

        h2::before {
            left: -30px;
        }

        h2::after {
            right: -30px;
        }
        
        .date {
            font-size: 20px;
            margin: 30px 0;
            color: #d4af87;
            font-weight: 500;
            letter-spacing: 1px;
            position: relative;
            display: inline-block;
            padding: 0 20px;
        }

        .date::before, .date::after {
            content: '';
            position: absolute;
            top: 50%;
            width: 40px;
            height: 1px;
            background: linear-gradient(90deg, transparent, #d4af87);
        }

        .date::before {
            left: -40px;
            background: linear-gradient(90deg, #d4af87, transparent);
        }

        .date::after {
            right: -40px;
        }
        
        .childhood-photos {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin: 50px 0;
            flex-wrap: wrap;
        }
        
        .photo-container {
            width: 45%;
            max-width: 220px;
            height: 280px;
            overflow: hidden;
            position: relative;
            border-radius: 8px;
            box-shadow: 
                0 10px 25px rgba(139, 115, 85, 0.1),
                0 5px 10px rgba(139, 115, 85, 0.05);
            transition: transform 0.4s ease, box-shadow 0.4s ease;
            background: 
                url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise' x='0' y='0'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='1' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100' height='100' filter='url(%23noise)' opacity='0.08'/%3E%3C/svg%3E"),
                linear-gradient(135deg, #fdfaf5 0%, #f9f4eb 100%);
            padding: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .photo-container:hover {
            transform: translateY(-5px);
            box-shadow: 
                0 15px 30px rgba(139, 115, 85, 0.15),
                0 8px 15px rgba(139, 115, 85, 0.08);
        }
        
        .photo-frame {
            position: relative;
            width: 100%;
            height: 100%;
            padding: 8px;
            background: 
                url("data:image/svg+xml,%3Csvg width='20' height='20' viewBox='0 0 20 20' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23d4af87' fill-opacity='0.05'%3E%3Cpath d='M0,0 L20,0 L20,20 L0,20 Z' fill='none'/%3E%3Cpath d='M0,0 L20,20 M20,0 L0,20' stroke-width='0.5'/%3E%3C/g%3E%3C/svg%3E"),
                linear-gradient(135deg, #f5f0e6 0%, #ece5d8 100%);
            border-radius: 6px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .child-photo {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            border: none;
            display: block;
            border-radius: 4px;
            border: 1px solid rgba(212, 175, 135, 0.2);
            box-shadow: inset 0 0 10px rgba(139, 115, 85, 0.1);
        }
        
        .humor-note {
            font-size: 14px;
            color: #a08c6f;
            font-style: italic;
            margin-top: 5px;
            text-align: center;
            opacity: 0.7;
        }
        
        .greeting {
            font-size: 18px;
            margin: 40px 0;
            text-align: center;
            line-height: 1.8;
            background: rgba(255, 253, 250, 0.7);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.05);
            border: 1px solid rgba(212, 175, 135, 0.1);
            position: relative;
        }

        .greeting::before {
            content: '"';
            position: absolute;
            top: -10px;
            left: 20px;
            font-size: 60px;
            color: rgba(212, 175, 135, 0.2);
            font-family: 'Playfair Display', serif;
            line-height: 1;
        }
        
        .funny-element {
            background: rgba(212, 175, 135, 0.1);
            border-left: 3px solid #d4af87;
            padding: 10px 15px;
            margin: 15px 0;
            border-radius: 0 8px 8px 0;
            font-size: 15px;
        }
        
        .section {
            margin: 45px 0;
            padding: 0 10px;
        }
        
        .section-title {
            font-size: 26px;
            margin-bottom: 25px;
            padding-bottom: 12px;
            border-bottom: 1px solid rgba(212, 175, 135, 0.3);
            color: #8b7355;
            font-weight: 500;
            font-family: 'Playfair Display', serif;
            text-align: center;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -1px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 2px;
            background: linear-gradient(90deg, transparent, #d4af87, transparent);
        }
        
        .program-item {
            display: flex;
            justify-content: space-between;
            margin: 22px 0;
            padding: 18px 20px;
            background: rgba(255, 253, 250, 0.7);
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(139, 115, 85, 0.05);
            border-left: 3px solid #d4af87;
            transition: transform 0.3s ease;
        }

        .program-item:hover {
            transform: translateX(5px);
        }
        
        .program-time {
            font-weight: 600;
            color: #d4af87;
            font-size: 18px;
            min-width: 70px;
        }
        
        .program-event {
            font-size: 17px;
            color: #5a4d3a;
        }
        
        .program-note {
            font-size: 14px;
            color: #a08c6f;
            font-style: italic;
            margin-top: 5px;
            text-align: left;
            opacity: 0.8;
            padding-left: 10px;
            border-left: 2px solid rgba(212, 175, 135, 0.3);
        }
        
        .dress-text {
            font-size: 17px;
            line-height: 1.8;
            margin: 20px 0;
            text-align: center;
            background: rgba(255, 253, 250, 0.7);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid rgba(212, 175, 135, 0.1);
        }
        
        .gift-text {
            font-size: 17px;
            line-height: 1.8;
            margin: 20px 0;
            background: rgba(255, 253, 250, 0.7);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid rgba(212, 175, 135, 0.1);
        }

        .gift-text strong {
            color: #8b7355;
            font-weight: 600;
        }
        
        .address {
            font-size: 18px;
            text-align: center;
            margin: 30px 0;
            padding: 25px;
            background: rgba(255, 253, 250, 0.7);
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.05);
            border: 1px solid rgba(212, 175, 135, 0.1);
            position: relative;
        }

        .address::before {
            content: '📍';
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            background: white;
            padding: 5px 10px;
            border-radius: 50%;
            font-size: 20px;
            box-shadow: 0 3px 10px rgba(139, 115, 85, 0.1);
        }
        
        .map-button {
            display: block;
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, #d4af87, #c19a67);
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 10px;
            font-size: 18px;
            margin: 25px 0;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.2);
            font-weight: 500;
            letter-spacing: 0.5px;
            position: relative;
            overflow: hidden;
        }

        .map-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s;
        }

        .map-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(139, 115, 85, 0.3);
        }

        .map-button:hover::before {
            left: 100%;
        }
        
        .rsvp {
            text-align: center;
            margin: 40px 0;
            padding: 30px 25px;
            background: rgba(253, 250, 245, 0.8);
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(139, 115, 85, 0.1);
            border: 1px solid rgba(212, 175, 135, 0.15);
            position: relative;
        }

        .rsvp::before {
            content: '✉';
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
            background: white;
            padding: 5px 10px;
            border-radius: 50%;
            font-size: 20px;
            box-shadow: 0 3px 10px rgba(139, 115, 85, 0.1);
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
            color: #8b7355;
            font-size: 16px;
        }
        
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 14px;
            border: 1px solid rgba(212, 175, 135, 0.3);
            border-radius: 8px;
            font-size: 16px;
            background: rgba(255, 255, 255, 0.8);
            transition: all 0.3s ease;
            font-family: 'Montserrat', sans-serif;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #d4af87;
            box-shadow: 0 0 0 3px rgba(212, 175, 135, 0.1);
        }
        
        .submit-button {
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, #8b7355, #6d5a3f);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 15px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.2);
            font-weight: 500;
            letter-spacing: 0.5px;
        }

        .submit-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(139, 115, 85, 0.3);
        }
        
        .couple-photo-container {
            width: 100%;
            max-width: 450px;
            height: 320px;
            margin: 30px auto;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 
                0 15px 35px rgba(139, 115, 85, 0.15),
                0 5px 15px rgba(139, 115, 85, 0.1);
            position: relative;
            background: 
                url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise' x='0' y='0'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='1' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100' height='100' filter='url(%23noise)' opacity='0.08'/%3E%3C/svg%3E"),
                linear-gradient(135deg, #fdfaf5 0%, #f9f4eb 100%);
            padding: 12px;
        }

        .couple-photo-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            border: 1px solid rgba(212, 175, 135, 0.2);
            border-radius: 12px;
            pointer-events: none;
        }
        
        .couple-photo {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            transition: transform 0.5s ease;
            border-radius: 6px;
            border: 1px solid rgba(212, 175, 135, 0.2);
            box-shadow: inset 0 0 15px rgba(139, 115, 85, 0.1);
        }

        .couple-photo-container:hover .couple-photo {
            transform: scale(1.03);
        }
        
        .hearts {
            text-align: center;
            font-size: 2.2em;
            color: #d4af87;
            margin: 25px 0;
            animation: heartbeat 1.5s infinite;
            letter-spacing: 10px;
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
            background: rgba(255, 253, 250, 0.7);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.05);
            border: 1px solid rgba(212, 175, 135, 0.1);
        }
        
        .music-player {
            position: fixed;
            bottom: 25px;
            right: 25px;
            z-index: 1000;
        }
        
        .music-btn {
            width: 55px;
            height: 55px;
            border-radius: 50%;
            background: linear-gradient(135deg, #d4af87, #c19a67);
            color: white;
            border: none;
            font-size: 1.4em;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.3);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .music-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(139, 115, 85, 0.4);
        }
        
        .designer {
            text-align: center;
            margin-top: 50px;
            font-size: 15px;
            color: #a08c6f;
            padding-top: 20px;
            border-top: 1px solid rgba(212, 175, 135, 0.2);
            font-style: italic;
        }
        
        .photo-placeholder {
            width: 100%;
            height: 100%;
            background: 
                url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise' x='0' y='0'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='1' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100' height='100' filter='url(%23noise)' opacity='0.08'/%3E%3C/svg%3E"),
                linear-gradient(135deg, #fdfaf5 0%, #f9f4eb 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #d4af87;
            font-size: 16px;
            text-align: center;
            border: 2px dashed #d4af87;
            border-radius: 8px;
        }
        
        /* Декоративные элементы */
        .floral-divider {
            text-align: center;
            margin: 30px 0;
            color: #d4af87;
            font-size: 24px;
            opacity: 0.5;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .container {
                padding: 15px 15px 30px;
            }
            
            h2 {
                font-size: 36px;
            }
            
            h2::before, h2::after {
                display: none;
            }
            
            .date {
                font-size: 18px;
            }
            
            .childhood-photos {
                flex-direction: column;
                align-items: center;
                gap: 20px;
            }
            
            .photo-container {
                width: 85%;
                max-width: 280px;
                height: 220px;
            }
            
            .music-player {
                bottom: 15px;
                right: 15px;
            }
            
            .music-btn {
                width: 50px;
                height: 50px;
            }
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 10px 10px 20px;
            }
            
            h2 {
                font-size: 32px;
            }
            
            .date {
                font-size: 16px;
            }
            
            .photo-container {
                width: 90%;
                height: 200px;
            }
            
            .program-item {
                flex-direction: column;
                text-align: center;
            }
            
            .program-time {
                margin-bottom: 5px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Приглашение на свадьбу</h1>
            <h2>Владислав & Анастасия</h2>
            <div class="date">12 декабря 2025</div>
            
            <!-- Детские фото в одну строку с фоном пригласительного -->
            <div class="childhood-photos">
                <div class="photo-container">
                    <div class="photo-frame">
                        <img src="vlad-child.jpg" alt="Владислав в детстве" class="child-photo"
                             onerror="this.style.display='none'; this.parentNode.innerHTML='<div class=\'photo-placeholder\'>Фото Владислава в детстве</div>';">
                    </div>
                </div>
                <div class="photo-container">
                    <div class="photo-frame">
                        <img src="nastya-child.jpg" alt="Анастасия в детстве" class="child-photo"
                             onerror="this.style.display='none'; this.parentNode.innerHTML='<div class=\'photo-placeholder\'>Фото Анастасии в детстве</div>';">
                    </div>
                </div>
            </div>
            
            <div class="humor-note">
                Да-да, это мы! Те самые милые дети, которые когда-то думали, что брак - это когда делишься конфетами
            </div>
        </div>
        
        <div class="greeting">
            Дорогие наши родные и друзья!<br><br>
            Мы с радостью приглашаем вас разделить с нами самый важный день в нашей жизни - день нашей свадьбы. 
            Этот праздник был бы неполным без тех, кто сопровождал нас на пути друг к другу.
        </div>

        <div class="floral-divider">❀ ❀ ❀</div>
        
        <div class="section">
            <div class="section-title">Программа дня</div>
            
            <div class="program-item">
                <div class="program-time">14:30</div>
                <div class="program-event">
                    Сбор гостей
                    <div class="program-note">
                        Опоздавшим - дополнительное задание: рассказать анекдот
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">15:00</div>
                <div class="program-event">
                    Торжественная церемония
                    <div class="program-note">
                        Самый волнительный момент дня!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">16:00</div>
                <div class="program-event">
                    Первые танцы молодых
                    <div class="program-note">
                        Постараемся не запутаться в ногах!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">17:00</div>
                <div class="program-event">
                    Банкет: тосты и поздравления
                    <div class="program-note">
                        Готовьте самые теплые слова!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">18:30</div>
                <div class="program-event">
                    Конкурсы и развлечения
                    <div class="program-note">
                        Будет весело и незабываемо!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">20:00</div>
                <div class="program-event">
                    Торжественное разрезание торта
                    <div class="program-note">
                        Сладкий финал вечера
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">20:30</div>
                <div class="program-event">
                    Танцы и дискотека
                    <div class="program-note">
                        Танцуют все!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">21:00</div>
                <div class="program-event">
                    Окончание праздника
                    <div class="program-note">
                        Благодарим за этот прекрасный день!
                    </div>
                </div>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">Дресс-код</div>
            <div class="dress-text">
                <strong>Свободный!</strong> Приходите в том, в чем вам удобно и красиво!<br><br>
                
                <em>Хотите быть в вечернем платье или костюме? Прекрасно!</em><br>
                <em>Предпочитаете удобный стиль? Идеально!</em><br>
                <em>Главное - ваше присутствие и хорошее настроение!</em>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">Наши пожелания о подарках</div>
            <div class="gift-text">
                Ваше присутствие - уже самый ценный подарок для нас!<br><br>
                
                <div class="funny-element">
                    <strong>Вместо цветов и алкоголя мы будем рады:</strong><br><br>
                    • Подарочным картам в магазины для дома (Hoff, Leroy Merlin и др.)<br>
                    • Набору качественной посуды или кухонных принадлежностей<br>
                    • Красивому постельному белью или текстилю для дома<br>
                    • Сертификатам на совместный ужин в хорошем ресторане<br>
                    • Электронике для дома (кофемашина, блендер, умные устройства)<br>
                    • Красивым рамкам для наших совместных фото<br>
                    • Подарку-впечатлению (сертификат на спа, мастер-класс и т.д.)
                </div>
                
                <div class="humor-note" style="margin-top: 15px;">
                    P.S. Денежные подарки тоже примем с благодарностью - мы точно найдем им хорошее применение!
                </div>
            </div>
        </div>
        
        <div class="address">
            Ждём вас в банкетном зале<br>
            <strong>"Олимп"</strong><br>
            <em>Лесной тракт, 85</em>
        </div>
        
        <a href="https://go.2gis.com/Kupg2" class="map-button" target="_blank">
            ПОСМОТРЕТЬ НА КАРТЕ
        </a>
        
        <div class="rsvp">
            <div class="section-title">Подтвердите участие</div>
            <p>Пожалуйста, ответьте до 1 декабря 2025 года</p>
            
            <form class="poll-form" id="weddingPoll">
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
                    <select id="companions" name="companions">
                        <option value="1">1 человек</option>
                        <option value="2">2 человека</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="alcohol">Ваши предпочтения в напитках</label>
                    <select id="alcohol" name="alcohol">
                        <option value="none">Не употребляю алкоголь</option>
                        <option value="wine">Вино (красное/белое)</option>
                        <option value="champagne">Шампанское/игристое</option>
                        <option value="strong">Крепкие напитки</option>
                        <option value="all">Любые напитки</option>
                        <option value="other">Свой вариант (напишите в пожеланиях)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="wishes">Ваши пожелания или особые предпочтения в напитках</label>
                    <textarea id="wishes" name="wishes" rows="3" placeholder="Напишите ваши пожелания или особые предпочтения..."></textarea>
                </div>
                
                <button type="submit" class="submit-button">ОТПРАВИТЬ ОТВЕТ</button>
            </form>
        </div>
        
        <div class="couple-photo-container">
            <img src="our-photo.jpg" alt="Владислав и Анастасия" class="couple-photo"
                 onerror="this.style.display='none'; this.parentNode.innerHTML='<div class=\'photo-placeholder\' style=\'height:320px\'>Наше совместное фото</div>';">
        </div>
        
        <div class="hearts">💖 💕 💗 💓 💞</div>
        <div class="closing-message">
            С нетерпением ждём этого дня и надеемся разделить его с вами!<br>
            Этот праздник станет началом нашей семейной истории, и нам так важно, 
            чтобы вы были его частью.
        </div>
        
        <div class="designer">
            С любовью, Владислав и Анастасия
        </div>
    </div>

    <div class="music-player">
        <button class="music-btn" onclick="toggleMusic()">♫</button>
    </div>

    <audio id="weddingMusic" loop>
        <source src="wedding-music.mp3" type="audio/mpeg">
        <source src="wedding-music.ogg" type="audio/ogg">
        Ваш браузер не поддерживает аудио элемент.
    </audio>

    <script>
        document.getElementById('weddingPoll').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const attendance = document.getElementById('attendance').value;
            
            const messages = [
                "Отлично! Будем ждать вас с нетерпением!",
                "Супер! Уже представляем, как вы украсите наш праздник своим присутствием!",
                "Замечательно! Предупреждаем: будет весело и незабываемо!",
                "Ура! Готовьтесь к прекрасному дню вместе с нами!"
            ];
            
            const randomMessage = messages[Math.floor(Math.random() * messages.length)];
            
            if (attendance === 'yes') {
                alert(`Дорогой(ая) ${name}! ${randomMessage}`);
            } else if (attendance === 'no') {
                alert(`Дорогой(ая) ${name}! Очень жаль, что вы не сможете быть с нами! Спасибо, что дали знать!`);
            } else {
                alert(`Дорогой(ая) ${name}! Спасибо за ответ! Надеемся, что вы сможете присоединиться к нам в этот день!`);
            }
            
            this.reset();
        });

        const music = document.getElementById('weddingMusic');
        let isPlaying = false;

        function toggleMusic() {
            if (isPlaying) {
                music.pause();
                isPlaying = false;
                document.querySelector('.music-btn').innerHTML = '♫';
            } else {
                music.play().then(() => {
                    isPlaying = true;
                    document.querySelector('.music-btn').innerHTML = '❚❚';
                }).catch(e => {
                    alert('Нажмите на кнопку музыки еще раз чтобы включить');
                });
            }
        }

        let firstClick = true;
        document.addEventListener('click', function() {
            if (firstClick && !isPlaying) {
                firstClick = false;
                setTimeout(() => {
                    music.play().then(() => {
                        isPlaying = true;
                        document.querySelector('.music-btn').innerHTML = '❚❚';
                    }).catch(e => {
                        console.log('Автовоспроизведение заблокировано');
                    });
                }, 1000);
            }
        });
    </script>
</body>
</html>
