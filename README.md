
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
            padding: 0 5%;
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
            max-width: 580px;
            margin: 0 auto;
            padding: 20px 0 50px;
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
            max-width: 240px;
            height: 300px;
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
        
        .time-slot {
            font-weight: 600;
            color: #d4af87;
            background: rgba(212, 175, 135, 0.1);
            padding: 2px 6px;
            border-radius: 4px;
            margin-right: 5px;
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
        
        /* Адаптивность для мобильных устройств */
        @media (max-width: 650px) {
            .childhood-photos {
                flex-direction: column;
                align-items: center;
                gap: 30px;
            }
            
            .photo-container {
                width: 85%;
                max-width: 300px;
                height: 350px;
            }

            h2 {
                font-size: 36px;
            }

            h2::before, h2::after {
                display: none;
            }
        }
        
        @media (max-width: 480px) {
            .photo-container {
                width: 90%;
                height: 300px;
            }

            h2 {
                font-size: 32px;
            }

            .date {
                font-size: 18px;
            }
        }

        /* Декоративные элементы */
        .floral-divider {
            text-align: center;
            margin: 30px 0;
            color: #d4af87;
            font-size: 24px;
            opacity: 0.5;
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
            Дорогие наши родные, друзья и те, кто просто зашел "на минуточку"!<br><br>
            Мы наконец-то решились узаконить наши ночные бдения над сериалами и совместные поиски удаленных розеток в кафе! 
            Приглашаем вас 12 декабря стать свидетелями того, как два человека официально получают право говорить друг другу "Я же тебя предупреждал(а)!"<br><br>
            <div class="funny-element">
                P.S. Обещаем, будет веселее, чем последний сезон "Игры престолов"!
            </div>
        </div>

        <div class="floral-divider">❀ ❀ ❀</div>
        
        <div class="section">
            <div class="section-title">Программа дня</div>
            
            <div class="program-item">
                <div class="program-time">14:30</div>
                <div class="program-event">
                    Сбор гостей и первые попытки вспомнить, как правильно завязывать галстук
                    <div class="program-note">
                        Опоздавшим - дополнительное задание: рассказать анекдот. 
                        Особо творческим - спеть песню про любовь!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">15:00</div>
                <div class="program-event">
                    Торжественная церемония "Да"
                    <div class="program-note">
                        Шепотом друг другу: "Ты уверен(а)?" - шутка, конечно же! 
                        На самом деле мы сто раз проверили - паспорта с собой!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">16:00</div>
                <div class="program-event">
                    Первые танцы молодых
                    <div class="program-note">
                        Предупреждаем: наш танец может напомнить "Титаник" в миниатюре, 
                        но мы обещаем не заканчивать его в бассейне!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">17:00</div>
                <div class="program-event">
                    Банкет: время проверить, чьи тосты длиннее
                    <div class="program-note">
                        Ставки принимаются: бабушкины воспоминания vs. друзья-острословы. 
                        Победителю - дополнительный кусок торта!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">18:30</div>
                <div class="program-event">
                    Конкурсы и развлечения
                    <div class="program-note">
                        Будет весело, смешно и немного неловко! 
                        Призы гарантированы - от похвалы до возможности сфотографироваться с нами!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">20:00</div>
                <div class="program-event">
                    Торжественное разрезание торта
                    <div class="program-note">
                        Момент истины: сможем ли мы сделать это синхронно? 
                        Ставки снова открыты! Тот, кто угадает, получит самый большой кусок!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">20:30</div>
                <div class="program-event">
                    Танцы до упаду (или до первой потери тапочка)
                    <div class="program-note">
                        От макарены до вальса - танцуют все! 
                        Особенно ценим тех, кто помнит движения из 90-х!
                    </div>
                </div>
            </div>
            
            <div class="program-item">
                <div class="program-time">21:00+</div>
                <div class="program-event">
                    Продолжение банкета для самых стойких
                    <div class="program-note">
                        Или "как доказать, что ты еще молод и полон сил". 
                        Для участников этой части - специальный приз: наши бесконечные благодарности и фото на память!
                    </div>
                </div>
            </div>
            
            <div class="funny-element" style="margin-top: 20px;">
                <strong>Важные пометки:</strong><br>
                • <span class="time-slot">22:00</span> - Тайный конкурс "Лучшая импровизация на тему семейной жизни"<br>
                • <span class="time-slot">23:30</span> - Флешмоб "Как мы представляли себе свадьбу в 15 лет"<br>
                • <span class="time-slot">00:00+</span> - Для настоящих героев: поиск потерянных вещей и воспоминаний
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">Дресс-код</div>
            <div class="dress-text">
                Мы будем рады, если вы поддержите цветовую палитру нашего праздника:<br>
                <strong>Нежные пастельные тона: кремовый, пудровый, лавандовый, мягкий розовый</strong><br><br>
                <em>Для мужчин: костюмы или элегантные рубашки с брюками</em><br>
                <em>Для женщин: платья миди или макси длины</em>
                
                <div class="funny-element">
                    <strong>Чего просим НЕ надевать:</strong><br>
                    - Костюмы супергероев (если только вы не настоящий супергерой)<br>
                    - Пляжные шлепанцы (разве что очень элегантные)<br>
                    - Футболку с надписью "Я дружбан жениха/невесты и горжусь этим"<br>
                    - Свадебное платье (это наша территория!)
                </div>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">Наши пожелания о подарках</div>
            <div class="gift-text">
                Ваше присутствие - уже самый ценный подарок для нас!<br><br>
                
                <div class="funny-element">
                    <strong>Если решили дарить деньги:</strong><br>
                    Мы честно потратим их на что-то нужное для нашего общего гнездышка. 
                    Возможно, даже на шторы, а не на очередную пиццу!<br><br>
                    
                    <strong>Если хотите подарить что-то материальное:</strong><br>
                    Мы обожаем настольные игры (чтобы выяснять, кто моет посуду), 
                    книги (чтобы было о чем спорить) и всё для уютного дома 
                    (особенно если это что-то, что не нужно собирать 5 часов по инструкции на непонятном языке).
                </div>
                
                <div class="humor-note" style="margin-top: 15px;">
                    P.S. Если подарите нам кота - будем и рады, и не очень одновременно!
                </div>
            </div>
        </div>
        
        <div class="address">
            Ждём вас в банкетном зале<br>
            <strong>"Олимп"</strong><br>
            <em>Лесной тракт, 85</em>
            <div class="humor-note">
                Навигатор иногда путает это место с олимпийским стадионом - не верьте ему!
            </div>
        </div>
        
        <a href="https://go.2gis.com/Kupg2" class="map-button" target="_blank">
            ПОСМОТРЕТЬ НА КАРТЕ 
            <div class="humor-note">(Чтобы не заблудиться, как в тот раз на дне рождения у Олега)</div>
        </a>
        
        <div class="rsvp">
            <div class="section-title">Подтвердите участие</div>
            <p>Пожалуйста, ответьте до 1 декабря 2025 года</p>
            <div class="humor-note">Иначе будем звонить лично в 6 утра!</div>
            
            <form class="poll-form" id="weddingPoll">
                <div class="form-group">
                    <label for="name">Ваше имя и фамилия</label>
                    <input type="text" id="name" name="name" required placeholder="Например, Иван Иванов">
                    <div class="humor-note">Можно указать псевдоним, если боитесь славы</div>
                </div>
                
                <div class="form-group">
                    <label for="attendance">Вы сможете прийти?</label>
                    <select id="attendance" name="attendance" required>
                        <option value="">Выберите вариант</option>
                        <option value="yes">Обязательно! Уже готовлю тост/танец/слезы умиления</option>
                        <option value="no">К сожалению, не смогу (надеюсь, у вас есть хорошее оправдание)</option>
                        <option value="maybe">50/50 (зависит от погоды/настроения/кота)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="companions">Сколько человек будет (включая вас)</label>
                    <select id="companions" name="companions">
                        <option value="1">1 человек (скромно, но с достоинством)</option>
                        <option value="2">2 человека (вдвоем веселее)</option>
                        <option value="3">3 человека (уже тусовка)</option>
                        <option value="4">4+ человека (настоящий десант!)</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="alcohol">Ваши предпочтения в напитках</label>
                    <select id="alcohol" name="alcohol">
                        <option value="none">Не употребляю алкоголь (уважаем!)</option>
                        <option value="wine">Вино (красное/белое - мы не расисты)</option>
                        <option value="champagne">Шампанское/игристое (для праздничного настроения)</option>
                        <option value="strong">Крепкие напитки (осторожно, с ними тосты длиннее!)</option>
                        <option value="all">Любые напитки (главное - в меру!)</option>
                        <option value="surprise">Сюрприз! (доверяем вашему вкусу)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="wishes">Ваши пожелания, советы для семейной жизни или просто привет</label>
                    <textarea id="wishes" name="wishes" rows="3" placeholder="Напишите что-нибудь приятное... или смешное! Например, рецепт счастливого брака или как выжить в ИКЕА"></textarea>
                </div>
                
                <button type="submit" class="submit-button">ОТПРАВИТЬ ОТВЕТ</button>
                <div class="humor-note">Обещаем не продавать ваши данные (разве что за очень хорошее предложение)</div>
            </form>
        </div>
        
        <div class="couple-photo-container">
            <img src="our-photo.jpg" alt="Владислав и Анастасия" class="couple-photo"
                 onerror="this.style.display='none'; this.parentNode.innerHTML='<div class=\'photo-placeholder\' style=\'height:320px\'>Наше совместное фото</div>';">
            <div class="humor-note">
                Да, мы и правда так мило выглядим вместе! Нет, это не фотошоп!
            </div>
        </div>
        
        <div class="hearts">💖 💕 💗 💓 💞</div>
        <div class="closing-message">
            Ждём каждого из вас на нашем празднике!<br>
            Обещаем: будет весело, вкусно и без лишних церемоний (разве что одна - свадебная).<br><br>
            
            <div class="funny-element">
                P.P.S. Если вы читаете это, значит вы точно особенный человек в нашей жизни! 
                Ну или просто очень любопытный. В любом случае - приходите!
            </div>
        </div>
        
        <div class="designer">
            С любовью (и чувством юмора),<br>Владислав и Анастасия
        </div>
    </div>

    <div class="music-player">
        <button class="music-btn" onclick="toggleMusic()">♫</button>
        <div class="humor-note" style="position: absolute; bottom: -25px; right: 0; width: 150px; text-align: center;">
            Наша первая песня!<br>Не "В лесу родилась ёлочка", обещаем!
        </div>
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
            
            const funnyMessages = [
                "Отлично! Готовьте свои танцевальные па и запас терпения для наших тостов!",
                "Супер! Уже представляем, как вы украсите наш праздник своим присутствием!",
                "Замечательно! Предупреждаем: будет весело, вкусно и немного сентиментально!",
                "Ура! Готовьтесь смеяться, плакать и возможно даже танцевать макарену!"
            ];
            
            const randomMessage = funnyMessages[Math.floor(Math.random() * funnyMessages.length)];
            
            if (attendance === 'yes') {
                alert(`Дорогой(ая) ${name}! ${randomMessage}`);
            } else if (attendance === 'no') {
                alert(`Дорогой(ая) ${name}! Очень жаль, что вы не сможете быть с нами!\nНо мы сохраним за вами кусочек торта (правда, очень маленький)!`);
            } else {
                alert(`Дорогой(ая) ${name}! Поняли, держим за вас кулачки (и место за столом)!\nНадеемся, что звезды сойдутся и вы сможете прийти!`);
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
                    alert('Нажмите на кнопку музыки еще раз чтобы включить\n(Иногда браузеры бывают капризными, как жених перед свадьбой!)');
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
