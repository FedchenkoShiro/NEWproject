<script>
</script>
<svelte:head>
  <link rel="preconnect" href="https://fonts.gstatic.com/">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css" />
    <link rel="stylesheet" type="text/css"
        href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script defer src="https://code.jquery.com/jquery-1.11.0.min.js"></script>
    <script defer src="https://code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
    <script defer src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</svelte:head>
<section>
    <section>
        <header class="navbar default-navbar" id="navbar" role="banner">
    
            <div class="container">
                <div class="navbar-logo">
                    <img src="../../../static/img/drupal-coder.svg" alt="Логотип">
                </div>
                <div class="navbar-collapse-wrapper">
                    <div class="region region-navigation-collapsible">
                        <nav role="navigation" aria-labelledby="block-bootstrap-dc-main-menu-menu">
                            <ul class="menu nav navbar-default">
                                <li>
                                    <a href="" class="is-active" style="border-color: #f14d34; border-bottom: 3px solid;">ПОДДЕРЖКА DRUPAL</a>
                                </li>
                                <li class="expanded dropdown">
                                    <a href="" class="dropdown-toggle" data-toggle="dropdown" title="">АДМИНИСТРИРОВАНИЕ</a>
                                    <div class="container-fluid dropdown-menu-wrapper" style="position: absolute;">
                                        <ul class="menu dropdown-menu">
                                            <li>
                                                <a href="" title="">МИГРАЦИЯ</a>
                                            </li>
                                            <li>
                                                <a href="" title="">БЭКАПЫ</a>
                                            </li>
                                            <li>
                                                <a href="" title="">АУДИТ БЕЗОПАСНОСТИ</a>
                                            </li>
                                            <li>
                                                <a href="" title="">ОПТИМИЗАЦИЯ СКОРОСТИ</a>
                                            </li>
                                            <li>
                                                <a href="" title="">ПЕРЕЕЗД НА HTTPS</a>
                                            </li>
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a href="" class="is-active">ПРОДВИЖЕНИЕ</a>
                                </li>
    
                                <li>
                                    <a href="" class="is-active">РЕКЛАМА</a>
                                </li>
                                <li class="expanded dropdown">
                                    <a href="" class="dropdown-toggle" data-toggle="dropdown" title="">О НАС</a>
                                    <div class="container-fluid dropdown-menu-wrapper" style="position: absolute;">
                                        <ul class="menu dropdown-menu">
                                            <li>
                                                <a href="" title="">КОМАНДА</a>
                                            </li>
                                            <li>
                                                <a href="" title="">DRUPALGIVE</a>
                                            </li>
                                            <li>
                                                <a href="" title="">БЛОГ</a>
                                            </li>
                                            <li>
                                                <a href="" title="">КУРСЫ DRUPAL</a>
                                            </li>
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a href="" class="is-active">ПРОЕКТы</a>
                                </li>
                                <li>
                                    <a href="" class="is-active">КОНТТАКТЫ</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
    
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                </div>
            </div>
        </header>
    
        <div class="navbar-mobile">
            <nav class="navbar navbar-expand-lg fixed-bottom navbar-dark" style="background-color: black;">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <a class="d-block p-2" href="">
                        <div class="a-text">ПОДДЕРЖКА DRUPAL</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">АДМИНИСТРИРОВАНИЕ <span class="caret"></span></div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">МИГРАЦИЯ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">БЭКАПЫ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">АУДИТ БЕЗОПАСНОСТИ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">ОПТИМИЗАЦИЯ СКОРОСТИ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">ПЕРЕЕЗД НА HTTPS</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">ПРОДВИЖЕНИЕ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">РЕКЛАМА</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">О НАС <span class="caret"></span></div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">КОМАНДА</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">DRUPALGIVE</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">БЛОГ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="dropdown-text">КУРСЫ DRUPAL</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">ПРОЕКТЫ</div>
                    </a>
                    <a class="d-block p-2" href="">
                        <div class="a-text">КОНТАКТЫ</div>
                    </a>
    
                </div>
                <a class="navbar-brand" href="#">
                    <img src="../../../static/img/drupal-coder.svg" width=175 height=25 alt="Главная">
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
            </nav>
        </div>
    </section>
    <section>
        <div class="fullscreen">
            <div class="region region-fullscreen">
                <section id="block-miss" class="block ">
                    <div class="field">
                        <div class="main-block">
                            <div class="main-block-background">
                                <div class="druplicon-img">
                                    <img src="../../../static/img/druplicon.svg">
                                </div>
                                <video autoplay loop class="fillWidth" playsinline preload="auto" muted>
                                    <source src="../../../static/img/video.mp4" type="video/mp4">
                                </video>
                            </div>
                            <div class="container main-block-container">
                                <div class="row">
                                    <div class=" col-lg-6">
                                        <h1 class="page-title">Поддержка <br> сайтов на Drupal</h1>
                                        <div class="undertitle-description">
                                            Сопровождение и поддержка сайтов <br>
                                            на CMS Drupal любых версий и запущенности
                                        </div>
                                        <div class="containter-udretitle-btn">
                                            <a href="" class="undertitle-btn"> ТАРИФЫ</a>
                                        </div>
                                    </div>
                                    <div class="col-lg-6">
                                        <div class="row cup">
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="first-cup-title">
                                                        #1
                                                        <img alt="Кубок" class="cup" src="../../../static/img/cup.png">
                                                    </div>
                                                    <div class="cup-description">
                                                        Drupal-разработчик
                                                        <br>
                                                        в России по версии <br> Рейтинга Рунета
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="cup-title">
                                                        3+
                                                    </div>
                                                    <div class="cup-description">
                                                        средний опыт <br> специалистов более <br> 3 лет
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="cup-title">
                                                        14
                                                    </div>
                                                    <div class="cup-description">
                                                        лет опыта в сфере <br> Drupal
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="cup-title">
                                                        200+
                                                    </div>
                                                    <div class="cup-description">
                                                        модулей и тем <br> в формате DrupalGive
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="cup-title">
                                                        35 000
                                                    </div>
                                                    <div class="cup-description">
                                                        часов поддержки <br>сайтов на Drupal
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-md-4 col-sm-4 col-xs-6 cup">
                                                <div class="cup-wrapper">
                                                    <div class="cup-title">
                                                        200+
                                                    </div>
                                                    <div class="cup-description">
                                                        Проектов<br> на поддержке
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
        </div>
    </section>
    <section>
        <div class="Support">
            <div id="react-main"></div>
            <div class="container">
                <div class="row">
                    <div class="col-md-6">
                        <h2>13 лет совершенствуем <br> компетенции в Drupal <br> разработке!</h2>
                        <div class="Support-description">
                            Разрабатываем и оптимизируем модули, расширяем <br> функциональность
                            сайтов, обновляем дизайн
                        </div>
                    </div>
                </div>
                <br>
                <div class="row row-flex cmpt">
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="../../../static/img/competency-1.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Добавление <br>
                                    информации на сайт, <br>
                                    создание новых <br>
                                    разделов
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="../../../static/img/competency-2.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title"> 
                                    Разработка <br>
                                    и оптимизация, <br>
                                    модулей сайта
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="../../../static/img/competency-3.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Интеграция с CRM, <br>
                                    1С, платежными <br>
                                    системами, любыми <br>
                                    веб-сервисами
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="img/competency-4.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Любые доработки <br>
                                    функционала <br>
                                    и дизайна
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="img/competency-5.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Аудит и мониторинг <br>
                                    безопасности Drupal <br>
                                    сайтов
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="img/competency-6.svg">
                                    <img class="img_back" src="../../../static/img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Миграция, импорт <br>
                                    контента и апгрейд <br>
                                    Drupal
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="../../../static/img/competency-7.svg">
                                    <img class="img_back" src="img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Оптимизация <br>
                                    и ускорение <br>
                                    Drupal-сайтов
                                </div>
                            </div>
                        </div>
                    </div>
    
                    <div class="col-sm-3 col-xs-6">
                        <div class="Support-block">
                            <div class="main-Support-block">
                                <div class="Support-img">
                                    <img src="../../../static/img/competency-8.svg">
                                    <img class="img_back" src="img/icon-bg.svg" alt="fon">
                                </div>
                                <div class="Support-title">
                                    Веб-маркетинг, <br>
                                    консультации <br>
                                    и работы по SEO
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    
        <div class="support">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <h2>Поддержка <br> от Drupal-Coder</h2>
                    </div>
                </div>
                <div class="row row-flex support-blocks">
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">01.</div>
                                <div class="sup-block-title">
                                    Постановка задачи по Email
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Удобная и привычная модель постановки задач,
                                при которой задачи фиксируются и никогда не теряются.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support1.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">02.</div>
                                <div class="sup-block-title">
                                    Система Helpdesk -
                                    отчетность, прозрачность
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Возможность посмотреть все заявки в работе и отработанные часы
                                в личном кабинете через браузер.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support2.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">03.</div>
                                <div class="sup-block-title">
                                    Расширенная техническая поддержка
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Возможность организации расширенной техподдержки
                                с 6:00 до 22:00 без выходных.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support3.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">04.</div>
                                <div class="sup-block-title">
                                    Персональный менеджер проекта
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Персональный менеджер проекта всегда в курсе текущего состояния
                                проекта и в любой момент готов ответить на любые вопросы.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support4.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">05.</div>
                                <div class="sup-block-title">
                                    Удобные способы оплаты
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Безналичный расчет по договору или электронные деньги:
                                WebMoney, Яндекс.Деньги, Paypal.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support5.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">06.</div>
                                <div class="sup-block-title">
                                    Работаем с SLA и NDA
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Работа в рамках соглашений о конфиденциальности
                                и об уровне качества работ.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support6.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">07.</div>
                                <div class="sup-block-title">
                                    Штатные специалисты
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Надежные штатные специалисты, никаких фрилансеров.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support7.svg">
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6 col-md-3 col-xs-12 sup-pics">
                        <div class="support-block">
                            <div class="sup-block-header">
                                <div class="sup-num">08.</div>
                                <div class="sup-block-title">
                                    Удобные каналы связи
                                </div>
                            </div>
                            <div class="sup-block-text">
                                Консультации по телефону, скайпу, в мессенджерах.
                            </div>
                            <div class="sup-block-icon">
                                <img src="../../../static/img/support8.svg">
                            </div>
                        </div>
                    </div>
    
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="expertise">
                <div class="container">
                    <div class="laptop-img">
                        <img alt="laptop" class="laptop" src="../../../static/img/laptop.png">
                    </div>
                    <div class="row">
                        <div class="col-md-6 col-xs-12 col-md-offset-6">
                            <div class="row">
                                <div class="col-md-12">
                                    <h2 class="expertise-title"> Экспертиза в Drupal,<br> опыт 14 лет!</h2>
                                </div>
                            </div>
                            <div class="row ">
                                <div class="col-sm-6 col-xs-12 expertise-collumn">
                                    <div class="expertise-block">
                                        <div class="expertise-block-description">
                                            Только системный подход – контроль версий, резервирование и тестирование!
                                        </div>
                                    </div>
                                </div>
                                <div class="col-sm-6 col-xs-12 expertise-collumn">
                                    <div class="expertise-block">
                                        <div class="expertise-block-description">
                                            Только Drupal сайты, не берем на поддержку сайты на других CMS!
                                        </div>
                                    </div>
                                </div>
                                <div class="col-sm-6 col-xs-12 expertise-collumn">
                                    <div class="expertise-block">
                                        <div class="expertise-block-description">
                                            Участвуем в разработке ядра Drupal и модулей на Drupal.org, разрабатываем
                                            <a href="">свои модули Drupal</a>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-sm-6 col-xs-12 expertise-collumn">
                                    <div class="expertise-block">
                                        <div class="expertise-block-description">
                                            Поддерживаем сайты на Drupal 5, 6, 7 и 8
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
        </section>
	<section class="tariffs" id="tariffs">
        <h2>Тарифы</h2>
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-4 order-1 tariff-col">
                    <div class="tariff-block">
                        <div class="tariff-title">Стартовый</div>
                        <ul>
                            <li>Консультации и работы по SEO</li>
                            <li>Услуги дизайнера</li>
                            <li>Неиспользованные оплаченные часы переносятся на следующий месяц</li>
                            <li>Предоплата от 6 000 рублей в месяц</li>
                        </ul>
                        <button id="contact-button-1" class="contact-button form-opener">СВЯЖИТЕСЬ С НАМИ!</button>
                    </div>
                </div>
                <div class="col-12 col-md-4 order-3 tariff-col">
                    <div class="tariff-block">
                        <div class="tariff-title">VIP</div>
                        <ul>
                            <li>Консультации и работы по SEO</li>
                            <li>Услуги дизайнера</li>
                            <li>Максимальное время реакции - в день обращения</li>
                            <li>Неиспользованные оплаченные часы не переносятся</li>
                            <li>Предоплата от 270 000 рублей в месяц</li>
                        </ul>
                        <button id="contact-button-2" class="contact-button form-opener">СВЯЖИТЕСЬ С НАМИ!</button>
                    </div>
                </div>
                <div class="col-12 col-md-4 order-2 tariff-col default-tariff">
                    <div class="tariff-block">
                        <div class="tariff-title">Бизнес</div>
                        <ul>
                            <li>Консультации и работы по SEO</li>
                            <li>Услуги дизайнера</li>
                            <li>Высокое время реакции - до 2 рабочих дней</li>
                            <li>Неиспользованные оплаченные часы не переносятся</li>
                            <li>Предоплата от 30 000 рублей в месяц</li>
                        </ul>
                        <button id="contact-button-3" class="contact-button form-opener">СВЯЖИТЕСЬ С НАМИ!</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="tariffs-custom">
            Вам не подходят наши тарифы? Оставьте заявку и мы <br> предложим вам индивидуальные условия!<br>
            <a id="contact-button-4" class="form-opener" href="">ПОЛУЧИТЬ ИНДИВИДУАЛЬНЫЙ ТАРИФ</a>
        </div>
    </section>
    <div class="Support">
      <div id="react-main"></div>
      <div class="container">
          <div class="row">
              <div class="col-md-6">
                  <h2>Наши профессиональные разработчики <br> выполняют быстро любые задачи</h2>
              </div>
          </div>
          <br>
          <div class="row row-flex cmpt">
            <div class="col-sm-3 col-xs-6">
              <div class="Support-block">
                  <div class="main-Support-block">
                      <div class="Support-img">
                          <img src="img/competency-20.svg">
                          <img class="img_back" src="img/icon-bg.svg" alt="fon">
                      </div>
                      <div class="col-md-6">
                        <h2>От 1ч</h2>
                    </div>
                      <div class="Support-title">
                          Настройка событий GA <br>
                          в интернет-магазине
                      </div>
                  </div>
              </div>
          </div>

          <div class="col-sm-3 col-xs-6">
              <div class="Support-block">
                  <div class="main-Support-block">
                      <div class="Support-img">
                          <img src="img/competency-21.svg">
                          <img class="img_back" src="img/icon-bg.svg" alt="fon">
                      </div>
                      <div class="col-md-6">
                        <h2>От 20ч</h2>
                    </div>
                      <div class="Support-title">
                          Разработка мобильной <br>
                          версии сайта
                      </div>
                  </div>
              </div>
          </div>

          <div class="col-sm-3 col-xs-6">
              <div class="Support-block">
                  <div class="main-Support-block">
                      <div class="Support-img">
                          <img src="img/competency-22.svg">
                          <img class="img_back" src="img/icon-bg.svg" alt="fon">
                      </div>
                      <div class="col-md-6">
                        <h2>От 8ч</h2>
                    </div>
                      <div class="Support-title">
                          Интеграция <br>
                          модуля оплаты
                      </div>
                  </div>
              </div>
              </div>
          </div>
      </div>
    </div>
    <section class="team" id="team">
        <h2>Команда</h2>
        <div class="team-list">
          <div class="all-team">
            <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
              <div class="person">
                <div class="personal-photo"><img src="img/IMG_2472_0.jpg" width=200px height=200px alt="Photo" class="photo"> </div>
                <div class="person-name">
                  <a href="" title="Профиль на Drupal" target="name">Сергей Синица</a></div>
                <div class="person-info">Руководитель отдела веб-разработки, канд. техн. наук, заместитель директора</div>
              </div>
            </div>
            <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
              <div class="person">
                <div class="personal-photo">
                  <img src="img/IMG_2539_0.jpg" width=200px height=200px alt="Photo" class="photo">
                </div>
                <div class="person-name"><a href="" title="Профиль на Drupal" target="name">Роман Агабеков</a></div>
                <div class="person-info">Руководитель отдела DevOPS, директор</div>
              </div>
            </div>
            <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
              <div class="person">
                <div class="personal-photo">
                  <img src="img/IMG_2474_1.jpg" width=200px height=200px alt="Photo" class="photo">
                </div>
                <div class="person-name">
                  <a href="" title="Профиль на Drupal" target="name">Алексей Синица</a>
              </div>
              <div class="person-info">Руководитель отдела поддержки сайтов</div>
            </div>
          </div>
          <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
            <div class="person">
              <div class="personal-photo">
                <img src="img/IMG_2522_0.jpg" width=200px height=200px alt="Photo" class="photo">
              </div>
              <div class="person-name">
                <a href="" title="Профиль на Drupal" target="name">Дарья Бочкарёва</a>
              </div>
              <div class="person-info">Руководитель отдела продвижения, контекстной рекламы и контент-поддержки сайтов
              </div>
            </div>
          </div>
          <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
            <div class="person">
              <div class="personal-photo">
                <img src="img/IMG_9971_16.jpg" width=200px height=200px alt="Photo" class="photo">
              </div>
              <div class="person-name">
                <a href="" title="Профиль на Drupal" target="name">Ирина Торкунова</a>
              </div>
              <div class="person-info">Менеджер по работе с клиентами</div>
            </div>
          </div>
        </div>
        <div class="more">
          <a href="">Вся команда</a>
        </div>
      </div>
    </section>
    <section>
        <div class="cases container">
        <h2>Кейсы</h2>
        <div class="articles">
          <div class="article-block">
            <div class="article-img" style="background-image: url(../img/case-image-1.jpg)"></div>
            <h3>Кэширование данных. Апгрейд сервера. Boost работы сайта в 40 раз!</h3>
            <div class="art-data">04.05.2022</div>
              <div class="art-text">Влияние скорости загрузки сайта на отказы и конверсии. Кейс ускорения...
              </div>
            </div>
            <div class="article-block article-block-full-img">
              <div class="article-img" style="background-image: url(../img/case-image-2.jpg)"></div>
              <h3>Отчёты Ecommerce в Яндекс.Метрике</h3>
            </div>
            <div class="article-block article-block-full-img">
              <div class="article-img" style="background-image: url(../img/case-image-3.jpg)"></div>
                <h3>Повышение конверсии страницы с формой с применением AB-тестирования</h3>
                <div class="art-data">24.01.2022</div>
              </div>
            <div class="article-block article-block-full-img">
              <div class="article-img" style="background-image: url(../img/case-image-4.jpg)"></div>
                <h3>Drupal 7: ускорение времени генерации страниц интернет-магазина на 32%</h3>
              <div class="art-data">23.09.2012</div>
            </div>
            <div class="article-block">
              <div class="article-img" style="background-image: url(../img/case-image-5.jpg)"></div>
              <h3>Обмен товарами и заказами интернет-магазинов на Drupal 7 с 1С: Предприятие, МойСклад, Класс365</h3>
              <div class="art-data">22.08.2020</div>
              <div class="art-text">Опубликован <div class="ref">релиз модуля...</div>
            </div>
          </div>
        </div>
      </div>
    
    <div class="reviews-slider-block">
      <h2 class="reviews-title"> Отзывы </h2>
      <div class="reviews-slider container">
        <div class="review-content">
          <div class="review-slick">
            <div class="review-slick-slider">
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-ciel.png" alt="Логотип">
                </div>
                <div class="review-text">
                  Долгие поиски единственного и неповторимого мастера на многострадальный сайт&nbsp;www.cielparfum.com, который был собран крайне некомпетентным программистом и раз в месяц стабильно грозил погибнуть, привели меня на сайт и, в итоге, к ребятам из Drupal-coder. И вот уже практически полгода как не проходит и дня, чтобы я не поудивлялась и не порадовалась своему везению! Починили все, что не работало - от поиска до отображения меню. Провели редизайн - не отходя от желаемого, но со своими существенными и качественными дополнениями. Осуществили ряд проектов - конкурсы, тесты и тд. А уж мелких починок и доработок - не счесть! И главное - все качественно и быстро (не взирая на не самый "быстрый" тариф). Есть вопросы - замечательный Алексей всегда подскажет, поддержит, отремонтирует и/или просто сделает с нуля. Есть задумка для реализации - замечательный Сергей обсудит и предложит идеальный вариант. Есть проблема - замечательные Надежда и Роман починят, поправят, сделают! Ребята доказали, что эта CMS - мощная и грамотная система управления. Надеюсь, что наше сотрудничество затянется надолго! Спасибо!!!
                </div>
                <div class="author-of-review">
                  С уважением, Наталья Сушкова - руководитель Отдела веб-проектов Группы компаний "Си Эль парфюм"
                  <a href="https://cielparfum.com">https://cielparfum.com</a>
                </div>
              </div>
  
              <div class="review-item">
                  <div class="review-img-block">
                    <img src="../img/logo-personalwriter.png" alt="Логотип">
                  </div>
                  <div class="review-text">
                    Сергей — профессиональный, высококвалифицированый программист с огромным опытом в ИТ. Я долгое время общался с топ-фрилансерами (вся первая двадцатка) на веблансере и могу сказать, что С СЕРГЕЕМ ОНИ И РЯДОМ НЕ ВАЛЯЛИСЬ. Работаем с Сергеем до сих пор. С ним приятно работать, я доволен.
                  </div>
                  <div class="author-of-review">
                    Сергей Чепурко, руководитель проекта
                    <a href="https://personal-writer.com/">www.personal-writer.com</a>
                  </div>
              </div>
    
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-farbors.jpg" alt="Логотип">
                </div>
                <div class="review-text">
                  Выражаю глубочайшую благодарность команде специалистов компании "Инитлаб" и лично Дмитрию Купянскому и Алексею Синице. Сайт был первоклассно перевёрстан из старой табличной модели в новую на базе Drupal с дополнительной функциональностью. Всё было сделано с высочайшим качеством и точно в сроки. Всем кому хочется без нервов и лишних вопросов разработать сайт рекомендую обращаться именно к этой команде профессионалов.
                </div>
                <div class="author-of-review">
                  Леонид Александрович Ледовский
                </div>
              </div>
    
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-ournewspaper.png" alt="Логотип">
                </div>
                <div class="review-text">
                  Моя электронная газета www.nashagazeta.ch существует в Швейцарии уже 10 лет. За это время мы сменили 7 специалистов по техподдержке, и только сейчас, в последние несколько месяцев, с начала сотрудничества с Алексеем Синицей и его командой, я впервые почувствовала, что у меня есть надежный технический тыл. Без громких слов и обещаний, ребята просто спокойно и качественно делают работу, быстро реагируют, находят решения, предлагают конкретные варианты улучшения функционирования сайта и сами их оперативно осуществляют. Сотрудничество с ними – одно удовольствие!
                </div>
                <div class="author-of-review">
                  Надежда Сикорская, Женева, Швейцария
                </div>
              </div>
    
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-estee.png" alt="Логотип">
                </div>
                <div class="review-text">
                  Наша компания Estee Design занимается дизайном интерьеров. Сайт сверстан на Drupal. Искали программистов под выполнение ряда небольших изменений и корректировок по сайту. Пообщавшись с Алексеем Синицей, приняли решение о начале работ с компанией Initlab/drupal-coder. Сотрудничеством довольны на 100%. Четкая и понятная система коммуникации, достаточно оперативное решение по задачам. Дали рекомендации по улучшению програмной части сайта, исправили ряд скрытых ошибок. Никогда не пишу отзывы (нет времени), но в данном случае, по просьбе Алексея, не могу не рекомендовать Initlab другим людям - действительно компания профессионалов.
                </div>
                <div class="author-of-review">
                  Кузин Вадим, руководитель строительного направления Дизайн-бюро интерьеров Estee
                  <a href="https://estee-design.ru/">estee-design.ru</a>
                </div>
              </div>
    
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-cableman.png" alt="Логотип">
                </div>
                <div class="review-text">
                  Наша компания за несколько лет сменила несколько команд программистов и специалистов техподдержки, и почти отчаялась найти на российском рынке адекватное профессиональное предложение по разумной цене. Пока мы не начали работать с командой "Инитлаб", воплощающей в себе все наши представления о нормальной системе взаимодействия в сочетании с профессиональным неравнодушием. Впервые в моей деловой практике я чувствую надежно прикрытыми важнейшие задачи в жизни электронного СМИ, при том, что мои коллеги работают за сотни километров от нас и мы никогда не встречались лично.
                </div>
                <div class="author-of-review">
                  Константин Бельский, зам. генерального директора портала
                  <a href="https://www.cableman.ru/">Кабельщик.ру</a>
                </div>
              </div>
    
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-serebro.png" alt="Логотип">
                </div>
                <div class="review-text">
                  За довольно продолжительный срок (2014 - 2016 годы) весьма плотной работы (интернет-магазин на безумно замороченном Drupal 6: устраняли косяки разработчиков, ускоряли сайт, сделали множество новых функций и т.п.) - только самые добрые эмоции от работы с командой Initlab / Drupal-coder: всегда можно рассчитывать на быструю и толковую помощь, поддержку, совет. Даже сейчас, не смотря на то, что мы почти год не работали на постоянной основе (банально закончились задачи), случайно возникшая проблема с сайтом была решена мгновенно! В общем, только самые искренние благодарности и рекомендации! Спасибо! )
    
                </div>
                <div class="author-of-review">
                  С уважением, Владислав,
                  <a href="http://serebro.ag">Serebro.Ag</a>
                </div>
              </div>
  
              <div class="review-item">
                <div class="review-img-block">
                  <img src="../img/logo-lpcma.jpg" alt="Логотип">
                </div>
                <div class="review-text">
                  Хотел поблагодарить за работу над нашими сайтами. За 4 месяца работы привели сайт в порядок, а самое главное получили инструмент, с помощью мы теперь можем быстро и красиво выставлять контент для образования и работы с предприятиями http://lpcma.tsu.ru/ru/post/reference_material Ну и многому научись благодаря работе с вами. Мы очень рады, что удалось найти настолько компетентных ребят )
                </div>
                <div class="author-of-review">
                  Дмитрий Новиков,
                  <a href="http://lpcma.ru">lpcma.tsu.ru</a>
                </div>
              </div>
            </div>
            <div class="review-arrow-nav">
              <button id="left-arrow"></button>
                <div class="review-counter">
                  <span id="rev-num">01</span>/08
                </div>
              <button id="right-arrow"></button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="container" id="fc">
        <div class="row" id="fr">
          <div class="col-12 col-md-6" id="fb1">
            <div class="footer-block-title">
              Оставить заявку на поддержку сайта
            </div>
            <div class="footer-block-description">
              Срочно нужна поддержка сайта?
              Ваша команда не успевает справиться самостоятельно или предыдущий подрядчик не справился с
              работой?
              Тогда вам точно к нам! Просто оставьте заявку и наш менеджер с вами свяжется!
            </div>
            <div class="footer-block-contacts">
              <ul>
                <li class="footer-contacts-phone">
                  <a href="">8 800 222-26-32</a>
                </li>
                <li class="footer-contacts-mail">
                  <a href="">info@drupal-coder.ru</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6" id="fb">
            <div class="form-block">
              <form id="form" action="https://formcarry.com/s/R_aYTObeqs" method="POST">
                <input name="fname" id="fname" class="footer-form-input" placeholder="Ваше имя">
                <input name="fnumber" id="fnumber" class="footer-form-input" placeholder="Телефон">
                <input name="femail" id="femail" type="femail" class="footer-form-input" placeholder="E-mail">
                
                <textarea name="fmessage" id="fmessage" placeholder="Ваш комментарий" class="footer-form-input"></textarea>
                <label for="fpolicy" class="c_box">
                  <input name="fpolicy" type="checkbox" class="cb" id="fpolicy">
                  <span class="cb_place"></span>
                  <div>
                    <span class="checkbox-text">Отправляя заявку, я даю согласие на
                      <a href="">обработку своих персональных данных</a>.
                    </span>
                  </div>
                </label>
                <div id="recaptcha-store">
                  <div id="recaptcha" class="g-recaptcha"
                    data-sitekey="*ПУСТЬ НА ТАНИНУ ПОЧТУ ПРИСЫЛАЕТСЯ*" data-theme="dark"
                    data-callback="captchaCallback" data-expired-callback="captchaCallback"></div>
                  </div>
                <input id="sendButton" type="submit" class="footer-contact-button" value="СВЯЖИТЕСЬ С НАМИ" disabled>
              </form>
            </div>
          </div>
        </div>
        <div class="footer-social-links">
          <div class="footer-links">
            <p>
              Проект ООО «Инитлаб», Краснодар, Россия.
              <br>
              Drupal является зарегистрированной торговой маркой Dries Buytaert.
            </p>
          </div>
        </div>
      </div>
    </footer>
  </section>
</section>

<style>

</style>
