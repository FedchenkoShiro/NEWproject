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

<style>
        #navbar {
            display: none;
            position: fixed;
            background: #000;
            bottom: -2px;
            top: auto;
            z-index: 100;
            left: 0;
            right: 0;
            padding: 0;
        }

        .navbar-logo {
            bottom: 8px;
        }

        .navbar-logo img {
            width: 37%;
        }

        .navbar-collapse-wrapper {
            width: max-content;
            float: none;
            margin-left: -15px;
            margin-right: -15px;
        }

        .nav {
            list-style: none;
        }

        .navbar-collapse a {
            padding: 0;
            width: 110%;
            margin-left: -15px;
            margin-right: -15px;
            margin-top: 2px;
            margin-bottom: 2px;
            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 13px;
            text-transform: uppercase;
            color: #fff;
            border-bottom: 1px solid #312a2a;
        }

        .a-text {
            margin-left: 10px;
        }

        .dropdown-text {
            margin-left: 30px;
        }

        .main-block-container {
            z-index: 15;
            position: relative;
            margin: auto;
        }

        .navbar-logo {
            bottom: 8px;
        }

        #navbar .logo-href {
            display: block;
            width: 190px;
            margin-right: 60px;
        }

        .navbar-toggle {
            position: relative;
            float: right;
            padding: 9px 10px;
            margin: 8px 0px;
            background-image: none;
            border-radius: 4px;
            display: block;
        }
</style>
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

<style>
        .main-block {
            overflow: hidden;
            position: relative;
            padding: 130px 0 30px;
            height: 803px;
            color: #fff;
            font-family: Montserrat;
        }

        video {
            position: absolute;
            width: auto;
            height: auto;
            top: 0;
            left: 0;
            right: 0;
            min-width: 100%;
            min-height: 100%;
            z-index: 5;
            filter: blur(3px);
            transform: scale(1.04);
            filter: brightness(0.2)
        }

        .druplicon-img {
            position: absolute;
            z-index: 6;
            top: 0;
            left: 0;
        }

        .druplicon-img img {
            width: 380px;
            height: 370px;
        }

        .row {
            margin: 0 -15px 0 0;
        }

        .main-block-container {
            top: -100px;
        }

        .main-block h1 {
            font-size: 24px;
            line-height: 60px;
            line-height: 1.2;
            text-align: center;
            font-weight: bold;
            margin-top: 0;
            margin-bottom: 20px;
        }



        .undertitle-description {
            font-size: 14px;
            line-height: 1.6;
            font-weight: 500;
            color: #fff;
            opacity: 80%;
            margin-bottom: 55px;
            text-align: center;
        }

        .undertitle-btn {
            display: inline-block;
            text-decoration: none;
            color: white;
            font-weight: 500;
            font-size: 12px;
            line-height: 1;
            padding: 20.5px 80px;
            width: 220px;
            text-align: center;
            border: 2px solid #f14d34;
            border-radius: 5px;
        }


        .containter-udretitle-btn {
            margin-bottom: 50px;
            text-align: center;
        }

        .undertitle-btn:hover {
            text-decoration: none;
            color: white;
            background-color: #f14d34;
            transition: background-color 400ms;
        }

        .main-block-container .col-xs-6 {
            width: 50%;
        }

        .cups {
            display: flex;
            margin-top: 50px;
        }

        .cup {
            margin-bottom: 32px;
        }

        .cup-wrapper {
            border-left: 3px solid #f14d34;
            padding-left: 15px;
            padding-top: 5px;
            padding-bottom: 10px;
            min-height: 80px;
            height: 100%;
        }

        .first-cup-title {
            font-size: 48px;
            margin-top: -22px;
            color: white;
            font-weight: bold;
            line-height: 1;
            margin-bottom: 5px;
            position: relative;
        }

        .cup-title {
            font-size: 24px;
            color: white;
            font-weight: bold;
            line-height: 1;
            margin-bottom: 5px;
            position: relative;
        }

        .cup-description {
            font-size: 12px;
            font-weight: 500;
            line-height: 1.25;
            color: white;
            opacity: 70%;
        }

        .first-cup-title img {
            position: absolute;
            top: -16px;
        }
</style>



<section>
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
</section>

<style>

</style>
