<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>soqa ✧･ﾟ:*</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0a0a1a 0%, #1a1a2a 100%);
            color: #e0e0e0;
            line-height: 1.6;
            min-height: 100vh;
            overflow-x: hidden;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            max-width: 400px;
            width: 100%;
            background: rgba(20, 20, 35, 0.8);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 25px;
            box-shadow: 0 0 30px rgba(100, 70, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
            z-index: 10;
        }
        
        .header {
            text-align: center;
            margin-bottom: 25px;
            position: relative;
        }
        
        .header::after {
            content: "";
            display: block;
            width: 80%;
            height: 1px;
            background: linear-gradient(90deg, transparent, rgba(180, 150, 255, 0.5), transparent);
            margin: 15px auto;
        }
        
        .header-text {
            font-size: 24px;
            letter-spacing: 3px;
            margin-bottom: 10px;
            color: #ffffff;
            text-shadow: 0 0 10px rgba(180, 150, 255, 0.7);
            animation: glow 3s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from {
                text-shadow: 0 0 5px rgba(180, 150, 255, 0.5);
            }
            to {
                text-shadow: 0 0 15px rgba(180, 150, 255, 0.8), 0 0 20px rgba(130, 100, 255, 0.6);
            }
        }
        
        .section {
            margin-bottom: 25px;
            padding: 15px;
            background: rgba(30, 30, 50, 0.4);
            border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .section-title {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            color: #b496ff;
            font-size: 18px;
        }
        
        .section-title i {
            margin-right: 10px;
            font-size: 20px;
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-5px);
            }
        }
        
        .info-item {
            display: flex;
            align-items: center;
            margin-bottom: 8px;
            font-size: 14px;
        }
        
        .info-item i {
            margin-right: 10px;
            width: 20px;
            text-align: center;
            color: #a38cf0;
        }
        
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }
        
        .tag {
            background: rgba(100, 70, 255, 0.2);
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 12px;
            border: 1px solid rgba(180, 150, 255, 0.2);
            transition: all 0.3s ease;
        }
        
        .tag:hover {
            background: rgba(100, 70, 255, 0.3);
            transform: translateY(-2px);
        }
        
        .snowflakes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }
        
        .snowflake {
position: absolute;
            top: -20px;
            color: #d1d1e0;
            opacity: 0.7;
            animation: fall linear infinite;
            font-size: 16px;
        }
        
        @keyframes fall {
            to {
                transform: translateY(105vh) rotate(360deg);
            }
        }
        
        .divider {
            height: 1px;
            background: linear-gradient(90deg, transparent, rgba(180, 150, 255, 0.3), transparent);
            margin: 15px 0;
        }
        
        .heart {
            color: #ff85a2;
            animation: pulse 2s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
        }
        
        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 12px;
            opacity: 0.7;
        }
    </style>
</head>
<body>
    <div class="snowflakes" id="snowflakes"></div>
    
    <div class="container">
        <div class="header">
            <div class="header-text">⁺‧₊˚ ཐི⋆♱⋆ཋྀ ˚₊‧⁺</div>
            <div class="header-text">инфо.</div>
        </div>
        
        <div class="section">
            <div class="info-item">
                <i class="fas fa-user"></i>
                <span>soqa</span>
            </div>
            <div class="info-item">
                <i class="fas fa-star"></i>
                <span>зз: козерог 19.01</span>
            </div>
            <div class="info-item">
                <i class="fas fa-birthday-cake"></i>
                <span>возраст скрыт</span>
            </div>
            <div class="info-item">
                <i class="fas fa-heart heart"></i>
                <span>свободна</span>
            </div>
            <div class="info-item">
                <i class="fas fa-venus"></i>
                <span>прон: she/her</span>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">
                <i class="fas fa-smile"></i>
                <span>кинны</span>
            </div>
            <div class="info-item">
                <i class="fas fa-ghost"></i>
                <span>· лаума (геншин)</span>
            </div>
            <div class="info-item">
                <i class="fas fa-user-alt"></i>
                <span>· ая (парень, которым увлечена)</span>
            </div>
            <div class="info-item">
                <i class="fas fa-dragon"></i>
                <span>· астарот (геншин)</span>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">
                <i class="fas fa-gamepad"></i>
                <span>фд, интересы</span>
            </div>
            <div class="info-item">
                <i class="fas fa-book"></i>
                <span>фав фд:</span>
            </div>
            <div class="tags">
                <span class="tag">отель Хазбин</span>
                <span class="tag">последняя реальность</span>
                <span class="tag">тринадцать огней</span>
                <span class="tag">голос времени</span>
                <span class="tag">осколки снов</span>
                <span class="tag">вместе</span>
                <span class="tag">волейбол</span>
                <span class="tag">блюлок</span>
                <span class="tag">уцц</span>
                <span class="tag">металфемили</span>
                <span class="tag">дневник плохих мыслей</span>
                <span class="tag">дроны убийцы</span>
            </div>
            
            <div class="divider"></div>
            
            <div class="info-item">
                <i class="fas fa-ghost"></i>
                <span>фав игры:</span>
            </div>
            <div class="tags">
                <span class="tag">FNAF</span>
                <span class="tag">Yandere Simulator</span>
                <span class="tag">The Purgatory of Hopes</span>
                <span class="tag">майн</span>
                <span class="tag">genshin impact</span>
                <span class="tag">zzz</span>
            </div>
            
            <div class="divider"></div>
            
            <div class="info-item">
<i class="fas fa-film"></i>
                <span>фав аниме и манга:</span>
            </div>
            <div class="tags">
                <span class="tag">твоё имя</span>
                <span class="tag">бездомный бог</span>
                <span class="tag">форма голоса</span>
                <span class="tag">унесённые призраками</span>
                <span class="tag">нет игры — нет жизни</span>
                <span class="tag">семья шпиона</span>
                <span class="tag">сад изящных слов</span>
                <span class="tag">госпожа кагуя</span>
                <span class="tag">кейон!</span>
                <span class="tag">дотянуться до тебя</span>
                <span class="tag">человек-бензопила</span>
                <span class="tag">агент времени</span>
                <span class="tag">хоримия</span>
                <span class="tag">кукла влюбилась</span>
                <span class="tag">унесенными призраками</span>
                <span class="tag">повар-боец</span>
                <span class="tag">нана</span>
            </div>
            
            <div class="divider"></div>
            
            <div class="info-item">
                <i class="fas fa-tv"></i>
                <span>Твич: Еблан, 89, Шпана</span>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">
                <i class="fas fa-music"></i>
                <span>музыкальный вкус</span>
            </div>
            <div class="info-item">
                <i class="fas fa-user-circle"></i>
                <span>Любимые исполнители: mzlff (!), beabadoobee (!!), Ado (!)</span>
            </div>
            <div class="info-item">
                <i class="fas fa-music"></i>
                <span>Любимые треки: «Цветочек маленький», «Readymade», «Glue Song», «Talk»</span>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">
                <i class="fas fa-heart heart"></i>
                <span>предпочтения</span>
            </div>
            <div class="info-item">
                <i class="fas fa-book-open"></i>
                <span>фав жанры: Романтика, Фэнтези</span>
            </div>
            <div class="info-item">
                <i class="fas fa-gamepad"></i>
                <span>фав игры (в которые часто играю): Genshin Impact, Murder Mystery 2, севх</span>
            </div>
            <div class="info-item">
                <i class="fas fa-paint-brush"></i>
                <span>Хобби: Музыка, Писательство</span>
            </div>
            <div class="info-item">
                <i class="fas fa-utensils"></i>
                <span>Еда: обожаю: Гречневый суп; не переношу: Всю молочку</span>
            </div>
            <div class="info-item">
                <i class="fas fa-palette"></i>
                <span>Любимый цвет: темно-синий, белый (пастельный) и вся пастельная палитра</span>
            </div>
        </div>
        
        <div class="section">
            <div class="section-title">
                <i class="fas fa-brain"></i>
                <span>мбти (для интереса)</span>
            </div>
            <div class="info-item">
                <i class="fas fa-star"></i>
                <span>MBTI: ENTP-T (мой)</span>
            </div>
            <div class="info-item">
                <i class="fas fa-moon"></i>
                <span>грин/ф: ENFP-T, INTJ-T-A</span>
            </div>
            <div class="info-item">
                <i class="fas fa-sun"></i>
                <span>ред/ф: ENTJ</span>
            </div>
            <div class="info-item">
                <i class="fas fa-comment"></i>
                <span>пояснение: мой мбти, с развитым fe, поэтому не бойтесь я добрая</span>
            </div>
        </div>
        
        <div class="footer">
            <p>примечание: эта карточка была создана для флуда, но теперь живёт здесь для любознательных</p>
            <p>✧･ﾟ:* ⋆♱⋆ *:･ﾟ✧</p>
        </div>
    </div>

    <script>
        // Создание снежинок
        function createSnowflakes() {
            const snowflakesContainer = document.getElementById('snowflakes');
            const snowflakeSymbols = ['❄️', '❅', '❆', '✻', '✼', '❉', '❋', '✺', '✲'];
            
            for (let i = 0; i < 50; i++) {
                const snowflake = document.createElement('div');
                snowflake.className = 'snowflake';
                snowflake.innerHTML = snowflakeSymbols[Math.floor(Math.random() * snowflakeSymbols.length)];
// Случайные начальные значения
                const size = Math.random() * 15 + 10;
                const posX = Math.random() * 100;
                const delay = Math.random() * 15;
                const duration = Math.random() * 10 + 15;
                const opacity = Math.random() * 0.5 + 0.3;
                
                snowflake.style.left = `${posX}vw`;
                snowflake.style.fontSize = `${size}px`;
                snowflake.style.animationDelay = `${delay}s`;
                snowflake.style.animationDuration = `${duration}s`;
                snowflake.style.opacity = opacity;
                
                snowflakesContainer.appendChild(snowflake);
            }
        }
        
        // Запуск при загрузке страницы
        window.addEventListener('load', createSnowflakes);
    </script>
</body>
</html>

