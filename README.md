<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Владислав & Анастасия - Свадьба 12 декабря 2025</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #e5cabf;
            color: #5a4d3a;
            line-height: 1.7;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #e5cabf 0%, #d8b4a5 100%);
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
                radial-gradient(circle at 20% 80%, rgba(120, 90, 80, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(120, 90, 80, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 40% 40%, rgba(120, 90, 80, 0.03) 0%, transparent 50%);
            pointer-events: none;
            z-index: -1;
        }
        
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px 20px 40px;
        }
        
        /* Стили для вашего приглашения */
        .custom-invitation {
            background: rgba(255, 253, 250, 0.9);
            padding: 0;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(139, 115, 85, 0.15);
            border: 1px solid rgba(212, 175, 135, 0.2);
            margin-bottom: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .custom-invitation::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #d4af87, #c19a67, #d4af87);
            border-radius: 12px 12px 0 0;
        }
        
        .invitation-image {
            width: 100%;
            margin: 0 auto;
        }
        
        .invitation-image img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .address {
            font-size: 18px;
            text-align: center;
            margin: 30px 0;
            padding: 25px;
            background: rgba(255, 253, 250, 0.8);
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.1);
            border: 1px solid rgba(212, 175, 135, 0.15);
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
        }

        .map-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(139, 115, 85, 0.3);
        }
        
        .rsvp {
            text-align: center;
            margin: 40px 0;
            padding: 30px 25px;
            background: rgba(253, 250, 245, 0.85);
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
            background: rgba(255, 255, 255, 0.9);
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
            background: rgba(255, 253, 250, 0.8);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(139, 115, 85, 0.1);
            border: 1px solid rgba(212, 175, 135, 0.15);
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
            color: #8b7355;
            padding-top: 20px;
            border-top: 1px solid rgba(212, 175, 135, 0.2);
            font-style: italic;
        }
        
        .floral-divider {
            text-align: center;
            margin: 30px 0;
            color: #d4af87;
            font-size: 24px;
            opacity: 0.5;
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
                width: 50px;
                height: 50px;
            }
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 10px 10px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Ваше длинное приглашение с изображением -->
        <div class="custom-invitation">
            <div class="invitation-image">
                <img src="22/long-invitation.jpg" alt="Свадебное приглашение">
            </div>
        </div>

        <div class="floral-divider">❀ ❀ ❀</div>
        
        <div class="address">
            Ждём вас в банкетном зале<br>
            <strong>"Олимп"</strong><br>
            <em>Лесной тракт, 85</em>
        </div>
        
        <a href="https://go.2gis.com/Kupg2" class="map-button" target="_blank">ПОСМОТРЕТЬ НА КАРТЕ</a>
        
        <div class="rsvp">
            <div class="section-title">Подтвердите участие</div>
            <p>Пожалуйста, ответьте до 1 декабря 2025 года</p>
            
            <form class="poll-form" action="https://formspree.io/f/manlrqre" method="POST">
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
                    <select id="companions" name="companions">
                        <option value="1">1 человек</option>
                        <option value="2">2 человека</option>
                        <option value="2">3 человека</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="alcohol">Ваши предпочтения в напитках</label>
                    <select id="alcohol" name="alcohol">
                        <option value="none">💧 Я сегодня трезвый, слежу за порядком</option>
                        <option value="wine">🍷 Вино (красное/белое) — для ценителей </option>
                        <option value="champagne">🥂 Шампанское - чтобы любовь искрилась!</option>
                        <option value="strong">🎯 Любые напитки - я доверяю вашему вкусу!</option>
                        <option value="other">💫 У меня есть особые пожелания...(напишите в пожеланиях)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="wishes">Ваши пожелания или особые предпочтения в напитках</label>
                    <textarea id="wishes" name="wishes" rows="3" placeholder="Напишите ваши пожелания или особые предпочтения..."></textarea>
                </div>
                
                <input type="text" name="_gotcha" style="display: none;">
                
                <button type="submit" class="submit-button">ОТПРАВИТЬ ОТВЕТ</button>
            </form>
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
        <source src="22/wedding-music.mp3" type="audio/mpeg">
        <source src="22/wedding-music.ogg" type="audio/ogg">
        Ваш браузер не поддерживает аудио элемент.
    </audio>

    <script>
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
