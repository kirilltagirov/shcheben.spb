<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Щебень с доставкой по СПб и ЛО | Купить гранитный щебень</title>
    <meta name="description" content="Продажа и доставка щебня всех фракций в Санкт-Петербурге и Ленинградской области. Гранитный, гравийный, известняковый щебень. Быстрая доставка, выгодные цены, гарантия качества.">
    <meta name="keywords" content="щебень, доставка щебня, щебень СПб, гранитный щебень, гравийный щебень, известняковый щебень, купить щебень">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.css">
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8fafc;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            width: 100%;
        }
        
        main {
            flex: 1;
        }
        
        /* Header Styles */
        .header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 50;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #1e3a8a;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            text-decoration: none;
        }
        
        .logo-icon {
            color: #f97316;
        }
        
        .nav-links {
            display: flex;
            gap: 1.5rem;
        }
        
        .nav-link {
            color: #1e3a8a;
            font-weight: 500;
            transition: color 0.2s;
            text-decoration: none;
        }
        
        .nav-link:hover {
            color: #f97316;
        }
        
        .phone-link {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            color: #1e3a8a;
            font-weight: 600;
            text-decoration: none;
        }
        
        .phone-icon {
            color: #f97316;
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            cursor: pointer;
            color: #1e3a8a;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #1e3a8a 0%, #1a3375 100%);
            color: white;
            border-radius: 16px;
            padding: 3rem 2rem;
            margin: 2rem 0;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 50%;
            height: 100%;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,255,255,0.1)"/></svg>');
            background-size: cover;
        }
        
        .hero-content {
            max-width: 600px;
            position: relative;
            z-index: 1;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        /* Form Styles */
        .request-form {
            background: white;
            border-radius: 16px;
            padding: 2.5rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            margin: 3rem 0;
        }
        
        .request-form h2 {
            font-size: 2rem;
            color: #1e3a8a;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #4a5568;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group select {
            width: 100%;
            padding: 0.75rem 1rem;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            font-size: 1rem;
            transition: border-color 0.3s;
        }
        
        .form-group input:focus,
        .form-group select:focus {
            outline: none;
            border-color: #1e3a8a;
        }
        
        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        
        /* Features Grid */
        .features {
            margin: 4rem 0;
        }
        
        .features h2 {
            font-size: 2rem;
            color: #1e3a8a;
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .feature-card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #f97316;
        }
        
        .feature-title {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 0.75rem;
            color: #1e3a8a;
        }
        
        .feature-text {
            color: #666;
            line-height: 1.5;
        }
        
        /* Buttons */
        .btn {
            display: inline-block;
            padding: 0.75rem 2rem;
            border-radius: 8px;
            font-weight: 600;
            text-align: center;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s ease;
            border: none;
            font-size: 1rem;
        }
        
        .btn-primary {
            background-color: #1e3a8a;
            color: white;
        }
        
        .btn-primary:hover {
            background-color: #1a3375;
        }
        
        .btn-accent {
            background-color: #f97316;
            color: white;
        }
        
        .btn-accent:hover {
            background-color: #ea580c;
        }
        
        .btn-block {
            width: 100%;
            padding: 1rem;
            font-size: 1.1rem;
        }
        
        /* Footer Styles */
        .footer {
            background-color: #1e3a8a;
            color: white;
            padding: 3rem 0 1.5rem;
            margin-top: auto;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .footer-logo {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            color: white;
        }
        
        .footer-logo-icon {
            color: #f97316;
        }
        
        .footer-about {
            margin-bottom: 1.5rem;
            color: #e5e7eb;
            line-height: 1.6;
        }
        
        .footer-heading {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 1.5rem;
            color: white;
        }
        
        .footer-links {
            display: flex;
            flex-direction: column;
            gap: 0.75rem;
        }
        
        .footer-link {
            color: #e5e7eb;
            text-decoration: none;
            transition: color 0.2s;
        }
        
        .footer-link:hover {
            color: #f97316;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            margin-bottom: 1rem;
            color: #e5e7eb;
        }
        
        .contact-icon {
            color: #f97316;
        }
        
        .copyright {
            text-align: center;
            padding-top: 1.5rem;
            border-top: 1px solid #334155;
            color: #e5e7eb;
            font-size: 0.9rem;
        }
        
        /* Responsive Adjustments */
        @media (max-width: 1024px) {
            .features-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .request-form {
                padding: 1.5rem;
            }
            
            .footer-container {
                grid-template-columns: 1fr;
            }
            
            .hero::before {
                display: none;
            }
        }
        
        @media (max-width: 640px) {
            .features-grid {
                grid-template-columns: 1fr;
            }
            
            .hero {
                padding: 2rem 1.5rem;
            }
            
            .hero h1 {
                font-size: 1.75rem;
            }
            
            .features h2 {
                font-size: 1.75rem;
            }
            
            .request-form h2 {
                font-size: 1.75rem;
            }
            
            .header-container {
                flex-wrap: wrap;
            }
            
            .phone-link span {
                display: none;
            }
        }
        
        /* Modal for mobile menu */
        .mobile-menu {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            z-index: 100;
            padding: 2rem;
            overflow-y: auto;
        }
        
        .mobile-menu.active {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        .mobile-menu-header {
            display: flex;
            justify-content: flex-end;
            width: 100%;
            margin-bottom: 2rem;
        }
        
        .mobile-menu-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 2rem;
            width: 100%;
        }
        
        .mobile-menu-link {
            color: white;
            text-decoration: none;
            font-size: 1.5rem;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .mobile-menu-link:hover {
            color: #f97316;
        }
        
        .mobile-phone {
            color: #f97316;
            font-size: 1.25rem;
            font-weight: 600;
            text-decoration: none;
            margin-top: 2rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        /* Success message */
        .success-message {
            display: none;
            background-color: #10b981;
            color: white;
            padding: 1rem;
            border-radius: 8px;
            text-align: center;
            margin-top: 1rem;
        }
        
        .success-message.active {
            display: block;
        }
        
        /* Loading spinner */
        .loading {
            display: none;
            text-align: center;
            padding: 1rem;
        }
        
        .loading.active {
            display: block;
        }
        
        .spinner {
            border: 3px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top: 3px solid white;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container header-container">
            <a href="#" class="logo">
                <i data-feather="box" class="logo-icon"></i>
                <span>ЩебеньСПб</span>
            </a>
            
            <nav class="nav-links">
                <a href="#hero" class="nav-link">Главная</a>
                <a href="#request" class="nav-link">Заявка</a>
                <a href="#features" class="nav-link">Преимущества</a>
                <a href="#footer" class="nav-link">Контакты</a>
            </nav>
            
            <a href="tel:+79111234567" class="phone-link">
                <i data-feather="phone" class="phone-icon"></i>
                <span>+7 (911) 123-45-67</span>
            </a>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i data-feather="menu"></i>
            </button>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div class="mobile-menu" id="mobileMenu">
        <div class="mobile-menu-header">
            <button class="mobile-menu-btn" id="closeMobileMenu">
                <i data-feather="x" style="color: white;"></i>
            </button>
        </div>
        <div class="mobile-menu-content">
            <a href="#hero" class="mobile-menu-link" data-mobile-link>Главная</a>
            <a href="#request" class="mobile-menu-link" data-mobile-link>Заявка</a>
            <a href="#features" class="mobile-menu-link" data-mobile-link>Преимущества</a>
            <a href="#footer" class="mobile-menu-link" data-mobile-link>Контакты</a>
            <a href="tel:+79111234567" class="mobile-phone">
                <i data-feather="phone"></i>
                +7 (911) 123-45-67
            </a>
        </div>
    </div>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="hero">
            <div class="container hero-content">
                <h1>Щебень с доставкой по СПб и ЛО</h1>
                <p>Оптовые и розничные поставки качественного щебня всех фракций. Быстрая доставка и гибкие цены.</p>
                <a href="#request" class="btn btn-accent">Оставить заявку</a>
            </div>
        </section>

        <!-- Request Form -->
        <section id="request" class="container">
            <div class="request-form">
                <h2>Оставьте заявку на расчет стоимости</h2>
                <form id="requestForm">
                    <div class="form-grid">
                        <div class="form-group">
                            <label for="name">Ваше имя</label>
                            <input type="text" id="name" name="name" placeholder="Иван Иванов" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="phone">Телефон</label>
                            <input type="tel" id="phone" name="phone" placeholder="+7 (911) 123-45-67" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="fraction">Фракция щебня</label>
                            <select id="fraction" name="fraction" required>
                                <option value="">Выберите фракцию</option>
                                <option value="5-20">5-20 мм (мелкая)</option>
                                <option value="20-40">20-40 мм (средняя)</option>
                                <option value="40-70">40-70 мм (крупная)</option>
                                <option value="other">Другая (уточним)</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="volume">Объем (тонн)</label>
                            <input type="number" id="volume" name="volume" placeholder="10" min="1" required>
                        </div>
                    </div>
                    
                    <div class="form-group">
                        <label for="comment">Комментарий к заявке (необязательно)</label>
                        <textarea id="comment" name="comment" rows="3" placeholder="Уточните адрес доставки, срочность или другие детали"></textarea>
                    </div>
                    
                    <div class="loading" id="formLoading">
                        <div class="spinner"></div>
                    </div>
                    
                    <div class="success-message" id="successMessage">
                        Спасибо! Ваша заявка принята. Мы свяжемся с вами в ближайшее время.
                    </div>
                    
                    <button type="submit" class="btn btn-accent btn-block">Отправить заявку</button>
                </form>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="container features">
            <h2>Почему выбирают нас</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🚚</div>
                    <h3 class="feature-title">Быстрая доставка</h3>
                    <p class="feature-text">Доставка в день заказа по Санкт-Петербургу и Ленинградской области</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">💰</div>
                    <h3 class="feature-title">Выгодные цены</h3>
                    <p class="feature-text">Оптовые скидки и специальные предложения для постоянных клиентов</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">💎</div>
                    <h3 class="feature-title">Гарантия качества</h3>
                    <p class="feature-text">Сертифицированный щебень от проверенных поставщиков с документами</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">⏰</div>
                    <h3 class="feature-title">Работаем 24/7</h3>
                    <p class="feature-text">Принимаем заказы круглосуточно, доставляем в удобное для вас время</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">👷</div>
                    <h3 class="feature-title">Опытные специалисты</h3>
                    <p class="feature-text">Консультации по выбору фракции и расчету необходимого объема</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">📦</div>
                    <h3 class="feature-title">Широкий ассортимент</h3>
                    <p class="feature-text">Гранитный, гравийный, известняковый щебень всех фракций</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer id="footer" class="footer">
        <div class="container">
            <div class="footer-container">
                <div>
                    <div class="footer-logo">
                        <i data-feather="box" class="footer-logo-icon"></i>
                        <span>ЩебеньСПб</span>
                    </div>
                    <p class="footer-about">
                        Продажа и доставка щебня в Санкт-Петербурге и Ленинградской области. 
                        Качество, надежность, выгодные цены.
                    </p>
                </div>
                
                <div>
                    <h3 class="footer-heading">Меню</h3>
                    <div class="footer-links">
                        <a href="#hero" class="footer-link">Главная</a>
                        <a href="#request" class="footer-link">Заявка</a>
                        <a href="#features" class="footer-link">Преимущества</a>
                    </div>
                </div>
                
                <div>
                    <h3 class="footer-heading">Контакты</h3>
                    <div class="footer-links">
                        <div class="contact-item">
                            <i data-feather="map-pin" class="contact-icon"></i>
                            <span>Санкт-Петербург</span>
                        </div>
                        <div class="contact-item">
                            <i data-feather="phone" class="contact-icon"></i>
                            <a href="tel:+79111234567" class="footer-link">+7 (911) 123-45-67</a>
                        </div>
                        <div class="contact-item">
                            <i data-feather="mail" class="contact-icon"></i>
                            <a href="mailto:info@scheben-spb.ru" class="footer-link">info@scheben-spb.ru</a>
                        </div>
                        <div class="contact-item">
                            <i data-feather="clock" class="contact-icon"></i>
                            <span>Круглосуточно</span>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="footer-heading">Мы в соцсетях</h3>
                    <div class="footer-links">
                        <a href="#" class="footer-link">
                            <i data-feather="facebook" class="contact-icon"></i>
                            <span>Facebook</span>
                        </a>
                        <a href="#" class="footer-link">
                            <i data-feather="instagram" class="contact-icon"></i>
                            <span>Instagram</span>
                        </a>
                        <a href="#" class="footer-link">
                            <i data-feather="youtube" class="contact-icon"></i>
                            <span>YouTube</span>
                        </a>
                        <a href="#" class="footer-link">
                            <i data-feather="message-circle" class="contact-icon"></i>
                            <span>Telegram</span>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="copyright">
                &copy; 2023 ЩебеньСПб. Все права защищены.
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script>
        // Инициализация feather icons
        feather.replace();
        
        // Мобильное меню
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const closeMobileMenuBtn = document.getElementById('closeMobileMenu');
        const mobileMenu = document.getElementById('mobileMenu');
        const mobileMenuLinks = document.querySelectorAll('[data-mobile-link]');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.add('active');
            document.body.style.overflow = 'hidden';
        });
        
        closeMobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.remove('active');
            document.body.style.overflow = '';
        });
        
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('active');
                document.body.style.overflow = '';
            });
        });
        
        // Обработка формы
        const requestForm = document.getElementById('requestForm');
        const formLoading = document.getElementById('formLoading');
        const successMessage = document.getElementById('successMessage');
        
        requestForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Показать индикатор загрузки
            formLoading.classList.add('active');
            
            // Собрать данные формы
            const formData = {
                name: document.getElementById('name').value,
                phone: document.getElementById('phone').value,
                fraction: document.getElementById('fraction').value,
                volume: document.getElementById('volume').value,
                comment: document.getElementById('comment').value,
                date: new Date().toLocaleString('ru-RU')
            };
            
            // Имитация отправки на сервер
            setTimeout(() => {
                // В реальном приложении здесь будет отправка на сервер
                console.log('Данные формы:', formData);
                
                // Скрыть индикатор загрузки
                formLoading.classList.remove('active');
                
                // Показать сообщение об успехе
                successMessage.classList.add('active');
                
                // Очистить форму
                requestForm.reset();
                
                // Скрыть сообщение через 5 секунд
                setTimeout(() => {
                    successMessage.classList.remove('active');
                }, 5000);
            }, 1500);
        });
        
        // Плавная прокрутка для ссылок в меню
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Автоматическое форматирование телефона
        const phoneInput = document.getElementById('phone');
        phoneInput.addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, '');
            
            if (value.length === 0) {
                e.target.value = '';
                return;
            }
            
            if (!value.startsWith('7') && !value.startsWith('8')) {
                value = '7' + value;
            }
            
            if (value.length > 11) {
                value = value.substring(0, 11);
            }
            
            let formattedValue = '+7';
            if (value.length > 1) {
                formattedValue += ' (' + value.substring(1, 4);
            }
            if (value.length >= 4) {
                formattedValue += ') ' + value.substring(4, 7);
            }
            if (value.length >= 7) {
                formattedValue += '-' + value.substring(7, 9);
            }
            if (value.length >= 9) {
                formattedValue += '-' + value.substring(9, 11);
            }
            
            e.target.value = formattedValue;
        });
    </script>
</body>
</html>
