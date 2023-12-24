<script>
	$(document).ready(function () {
  $('.review-slick-slider').slick({
    infinite: true,
    speed: 300,
    prevArrow: $("#left-arrow"),
    nextArrow: $("#right-arrow"),
    fade: true,
    swipe: false,
    draggable: false,
    slidesToShow: 1,
    adaptiveHeight: true
  });
  $('.review-slick-slider').on('afterChange', function (event, slick, currentSlide) {
    $('#rev-num').text('0' + (currentSlide + 1))
  });

  $(".first-slider").slick({
    infinite: true,
    dots: false,
    arrows: false,
    autoplay: true,
    slidesToShow: 5,
    slidesToScroll: 1,
    centerMode: true,
    centerPadding: '10%',
    autoplaySpeed: 3000,
    responsive: [
      {
        breakpoint: 1024,
        settings: { slidesToShow: 3 }
      },
      {
        breakpoint: 600,
        settings: { slidesToShow: 2 }
      }
    ]
  });

  $(".second-slider").slick({
    infinite: true,
    dots: false,
    arrows: false,
    autoplay: true,
    slidesToShow: 5,
    slidesToScroll: 1,
    centerMode: true,
    centerPadding: '10%',
    autoplaySpeed: 4000,
    responsive: [
      {
        breakpoint: 1024,
        settings: { slidesToShow: 3 }
      },
      {
        breakpoint: 600,
        settings: { slidesToShow: 2 }
      }
    ]
  });


  var acc = document.getElementsByClassName("accordion");
  var i;

  for (i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function () {
      this.classList.toggle("accordion-active");
      var panel = this.lastElementChild;
      if (panel.style.maxHeight) {
        panel.style.maxHeight = null;
      } else {
        panel.style.maxHeight = panel.scrollHeight + "px";
      }
    });
  }
});
</script>

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
                <div class="personal-photo"><img src="./img/IMG_2472_0.jpg" width=200px height=200px alt="Photo" class="photo"> </div>
                <div class="person-name">
                  <a href="" title="Профиль на Drupal" target="name">Сергей Синица</a></div>
                <div class="person-info">Руководитель отдела веб-разработки, канд. техн. наук, заместитель директора</div>
              </div>
            </div>
            <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
              <div class="person">
                <div class="personal-photo">
                  <img src="./img/IMG_2539_0.jpg" width=200px height=200px alt="Photo" class="photo">
                </div>
                <div class="person-name"><a href="" title="Профиль на Drupal" target="name">Роман Агабеков</a></div>
                <div class="person-info">Руководитель отдела DevOPS, директор</div>
              </div>
            </div>
            <div class="col-xs-6 col-sm-6 col-md-4 views-row" id="block">
              <div class="person">
                <div class="personal-photo">
                  <img src="./img/IMG_2474_1.jpg" width=200px height=200px alt="Photo" class="photo">
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
                <img src="./img/IMG_2522_0.jpg" width=200px height=200px alt="Photo" class="photo">
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
                <img src="./img/IMG_9971_16.jpg" width=200px height=200px alt="Photo" class="photo">
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
  </div>
</section>

<style>
	.support{
  font-family: Montserrat;
  margin-bottom: -212px;
}

.support h2 {
    margin-bottom: 55px;
    text-align: center;
    color: #050c33;
    font-weight: bold;
    font-size: 24px;
}
.support-blocks{
    margin-bottom: -212px;
    padding: 0 12px;
    position:relative;
    z-index:20;
}


.sup-pics{
    margin-bottom: 5px;
}
.support-block{
    background: #fff;
    border-radius: 5px;
    box-shadow: 20px 20px 40px rgba(5,12,51,.05);
    margin-left: -12px;
    margin-right: -12px;
    height: 100%;
    position: relative;
    padding: 25px 25px 45px;
    min-height: 292px;
}
.sup-block-text{
    position: relative;
    z-index: 10;
    font-weight: 500;
    font-size: 16px;
    color: #4e5a73;
    line-height: 1.37;
}
.sup-block-icon{
    position: absolute;
    right: 0;
    bottom: 0;
    z-index: 5;
}
.sup-num{
       font-weight: bold;
    font-size: 12px;
    color: #828a9b;
    margin-bottom: 20px;
    font-family: Montserrat;
}
.sup-block-title{
       font-weight: bold;
    font-size: 18px;
    color: #050c33;
    line-height: 1.22;
    margin-bottom: 15px;
}

.expertise{
  padding: 230px 0 230px 0;
  position:relative;
  background: linear-gradient(254.72deg, rgba(225,255,255,.276) -114.85%, rgba(255,255,255,0) 69.04%), #040613;
}

.expertise:before{
  content: "";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url(./img/druplicon-2.svg) no-repeat right bottom;
  background-size: contain;
  z-index: 10;
}

.expertise h2{
  font-weight: bold;
  font-size: 30px;
  margin-bottom: 65px;
  color: #fff;
  opacity: 100%;
  font-family: Montserrat;
}

.expertise-block-description{
  border-left: 3px solid #f14d34;
  padding-left: 15px;
  padding-top: 5px;
  padding-bottom: 10px;
  min-height: 88px;
  height: 100%;
  line-height: 22px;
  font-weight: 500;
  font-size: 16px;
  color: rgba(256,256,256,.7);
  width: 260px;
  font-family: Montserrat;
}

.laptop-block{
  padding: 0;
  position: absolute;
  left: 0;
  bottom: 0;
  width: 85%;
  z-index: 10;
  max-width: 735px;
}

.laptop{
  width: 100%;
  height: auto;
  transform: translateY(16%);
}

.expertise-collumn{
  margin-bottom: 30px;
}

.expertise a{
  color: #f14d34;
}

.tariffs {
  padding-bottom: 50px;
  background: url("img/D-background-opacity.svg") no-repeat right top, #fff;
  background-size: cover;
}

.tariffs h2 {
  font-size: 24px;
  padding-top: 105px;
  text-align: center;
  color: #000;
  margin-bottom: 40px
}


.tariff-block {
  border-radius: 5px;
  border: 1px solid #e6e6e6;
  padding: 30px 15px;
  background: #fff;
  margin: 0 auto;
  transition: all 500ms;
  transform-origin: center;
  width: 420px;
  max-width: 100%;
}

.tariffs>.container {
  margin-bottom: 30px;
}

.tariffs>.container>.row {
  align-items: flex-start;
}

.tariff-col:hover .tariff-block,
.default-tariff .tariff-block {
  transform: none;
  z-index: 15;
  box-shadow: 0 4px 60px rgba(150, 150, 150, .3);
}


.tariff-col:hover~.default-tariff .tariff-block {
  transform: none;
  z-index: 0;
  box-shadow: none;
}

.tariff-col {
  margin-bottom: 15px;
}

.tariff-title {
  border-bottom: 2px solid #e5e5e5;
  margin-bottom: 50px;
  font-size: 22px;
  font-weight: bold;
  color: #f14d32;
  line-height: 1.3;
  padding-bottom: 29px;
}

.tariffs li {
  margin-bottom: 18px;
  line-height: 1.2;
  font-size: 14px;
  font-weight: 100;
  position: relative;
  color: #4e5972;
  padding-left: 15px;
}

.tariffs ul {
  padding-left: 15px;
  list-style-image: url("./img/checkmark.svg");
}

.contact-button {
  display: block;
  font-weight: 500;
  font-size: 12px;
  line-height: 12px;
  color: #f14d34;
  text-decoration: none;
  padding: 20px 10px;
  width: 100%;
  text-align: center;
  border: 1px solid #f14d34;
  border-radius: 5px;
  letter-spacing: 0.06em;
  transition: background 300ms;
  margin: 0 0;
  background-color: rgba(0, 0, 0, 0);
}

.tariff-block:hover .contact-button,
.default-tariff .contact-button {
  color: #fff;
  background: #f14d34;
}

.tariff-col:hover~.default-tariff .contact-button {
  color: #f14d34;
  background: rgba(0, 0, 0, 0);
}

.tariffs-custom {
  text-align: center;
  color: #828a9b;
  line-height: 1.3;
  font-weight: 500;
  width: 475px;
  max-width: 345px;
  margin: 0 auto;
  font-size: 14px;
}

.tariffs-custom a{
  text-decoration: underline;
}

.form-opener {
  color: #050c33;
  font-size: 12px;
  text-decoration: none;
  transition: color 300ms;
  margin-top: 26px;
}

.tariffs-custom a:hover {
  color: #f14d34;
  text-decoration: none;
}

.tasks{
  min-width: 100%;
  margin-left: -15px;
  margin-right: -15px;
}

.tasks h2{
  font-size: 24px;
  margin-bottom: 20px;
  margin-top: 40px;
}
#team h2{
  padding-top: 50px;
  font-size: 24px;
  margin-bottom: 20px;
  margin-top: initial;
  text-align: center;
}

.all-team{
  display: flex;
  flex-wrap: wrap;
  text-align: left;
  font-family: 'Montserrat';
}

.all-team .col-xs-6 {
  width: 50%;
}
#block{
  padding: 0 15px;
}
.person{
  text-align: left;
  margin-bottom: 70px;
}

.person-photo{
  border-radius: 0;
  max-width: 100%;
  max-height: 100%;
  margin-bottom: 25px;
}

.person-photo img {
  width: 90.5%;
  height: 90.5%;
}

.person-name a{
  font-weight: bold;
  font-size: 16px;
  line-height: 1.37;
  color: #050c33;
  text-decoration: none;
  display: inline-block;
  margin-bottom: 5px;
}

.person-info{
  padding: 0;
  color: #505570;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.37;
  margin-bottom: 5px;
}

.more{
  margin-bottom: 30px;
  text-align: center;
}

.more a{
  display: inline-block;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 1;
  text-transform: uppercase;
  color: #050c33;
  padding: 10px 30px;
  border: 1px solid #cccdd5;
  border-radius: 5px;
  text-decoration: none;
  margin-bottom: 20px;
}

.case h2{
  font-weight: bold;
  font-size: 42px;
  margin-bottom: 46px;
  margin-top: 0;
  text-align: center;
  color: #050c33;
}

body {
  font-family: 'Montserrat';
  font-weight: 500;
  font-size: 16px;
  padding: 0;
  margin: 0;
  width: 100%;
}

h1 {
  font-weight: bold;
  font-size: 24px;
  line-height: 1.2;
  text-align: center;
  margin-top: 0;
  margin-bottom: 20px;
}

h2 {
  font-weight: bold;
  color: #050c33;
  font-size: 24px;
}

h3 {
  font-weight: bold;
  color: #050c33;
  font-size: 18px;
}

@media (max-width: 992px){
    .support .col-md-3{
      min-width: 50%;
    }
}


@media (min-width: 768px) {
  #navbar{
    display: block;
  }

.navbar-mobile{
  display: none;
}

.time{
  margin-left: 0px;
}

.tasks .col-xs-12{
  left: 0px;
  max-width: 100%;
}

.laptop-block img{
  width: 100%;
  left: 0;
  bottom: 0;
}

  .expertise .col-md-6{
    min-width: 100%;
  }

  .expertise .container .row .row {
    min-width: 750px;
  }

  .tariffs-custom {
    min-width: 475px;
    font-size: 16px;
  }

  .tariff-block{
    min-width: 220px;
  }

  .tariffs .container{
    min-width: 750px;
  }

  .Cmptn-block{
    min-width: 157px;
    text-decoration: none;
  }
  .tariffs {
    padding-bottom: 100px;
    background-size: 58%;
  }
  .contact-button{
    color: #f14d32;
  }


  .Cmptn h2 {
    font-size: 32px;
  }

  .Cmptn .col-md-6 {
    min-width: 100%;
  }

  .Cmptn .col-sm-3{
    width: 25%;
  }

  .support h2 {
    font-size: 32px;
  }

  #navbar {
    vertical-align: middle;
    position: absolute;
    z-index:100;
    padding: 30px 0px;
    top: 0;
    bottom: auto;
    left: -30px;
    right: 0;
    min-height: 43px;
    height: 105px;
    background-color: transparent;
}

.main-block{
    height: 900px;
}

.navbar-logo{
    padding-bottom: 15px;
}

.navbar-logo> img{
    width: 170px;
}

.main-block-container .col-lg-6{
    top: 140px;
    left: -18px;
}

.main-block h1{
    font-size: 52px;
    text-align: left;
}

.dropdown:hover .dropdown-menu{
    position: absolute;
    display: block;
}
.dropdown-menu:hover{
    display: block;
}

.dropdown-menu > li{
    height: 21px;
    width: 100%;
    margin: 0;
    transition: background-color 400ms;
}

.dropdown-menu > li > a{
    text-align: center;
    height: 17px;
    width: 181px;
    padding: 3px 20px;
}

.dropdown-menu > li > a:hover{
    border-bottom: 0px solid transparent;
}

.dropdown-menu>li:hover{
    color: #fff;
    background: #d13018;
    transition: background-color 400ms;
}

header li{
    height: 25px;
    margin-right: 30px;
}

header a {
    font-family: Montserrat;
    font-size: medium;
    color: white;
    font-size: 12px;
    border-color: #f14d34;
    border-bottom: 3px solid transparent;
    transition: border-color 400ms;
    width: 174px;
    height: 24px;
    padding-bottom: 5px;
}

header a:hover {
    color: white;
    text-decoration: none;
    border-color: #f14d34;
}

.dropdown-toggle{
    margin-left: 1px;
    border-bottom: 0px solid transparent;
}

.dropdown-menu{
    background-color: #f14d34;
    border-radius: 0;
    width: max-content;
    transition: all .5s;
    display: none;
    padding: 8px 0px;
}

.Cmptn-title{
  font-size: 14px;
  line-height: 1.4;
}

.dropdown-menu:hover{
    position: absolute;
    display: block;
}

.navbar-toggle{
    display: none;
}

.container{
    width: 750px;
    min-height: 43px;
}

.navbar-logo{
    margin: 0;
}
.collapse {
    display: block;
    height: auto;
    padding-bottom: 0;
}

.achivement{
    margin-bottom: 30px;
}

.undertitle-description{
    text-align: left;
    font-size: 18px;
}

.undertitle-btn{
    margin-left: 0px;
}

.containter-udretitle-btn{
    text-align: left;
}

.navbar-collapse.collapse{
    display: block;
    height: auto;
    padding-bottom: 0;
    overflow: visible;
}
.druplicon-img img{
    height: auto;
    width: auto;
}

.expertise h2{
    font-size: 32px;
    margin-bottom: 65px;
}

.expertise {
    padding: 380px 0 150px;
}

.tariff-block {
  max-width: 500px;
  width: auto;
}
.tariff-col:hover .tariff-block,
.default-tariff .tariff-block {
  transform: scale(1.1);
}

.tariffs h2 {
  font-size: 32px;
  padding-top: 160px;
  margin-bottom: 65px
}

.laptop-block{
  width: 70%;
  position: relative;
  transform: scale(1.4);
  left: -35px;
  bottom: -60px;
}

.reviews-title{
  font-size: 32px;
}

.footer #fb1{
  left: -30px;
}

.footer-block-title{
  font-size: 32px;
  min-width: 345px;
}

.person-photo{
  max-width: 100%;
  max-height: 100%;
}
.person-photo img {
  width: 80%;
  height: 80%;
}

.all-team .col-sm-6{
  min-width: 360px;
  left: 140px;
}
.all-team{
  justify-content: left;
}

#team h2 {
  font-size: 32px;
  margin-bottom:80px ;
}

.person-info{
  max-width: 260px;
}
.tasks h2{
  font-size: 32px;
  min-width: 720px;
}

.article-block {
  width: 33.3%;
}
.article-block:nth-child(2){
  width: 66.6%;
}

}

@media (min-width: 992px) {
  .tariff-block {
    padding: 70px 20px 60px;
  }

  .all-team .col-sm-6{
    left: 0;
  }

  .tasks h2{
    font-size: 42px ;
  }
  

  #team h2 {
    font-size: 42px;
  }
  .person-photo img {
    width: 100%;
    height: 100%;
  }

  .person-info{
    max-width: 330px;
  }
  .all-team{
    justify-content: left;
  }
  .review-text{
  margin-bottom: 28px;
    font-weight: bold;
    font-size: 14px;
    line-height: 1.2;
    color: #050c33;
    min-width: 460px;
}

.author-of-review{
  font-weight: 500;
  font-size: 14px;
  line-height: 1.2;
  color: #838b9c;
}


.author-of-review a{
  text-decoration: underline;
  color: #050c33;
  font-weight: normal;
}

.review-content{
  margin-top: 0;
  width: 980px;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
  position: relative;
}

  .expertise h2{
    font-size: 42px;
    margin-bottom: 65px;
}

  .support h2 {
    font-size: 42px;
  }

  .Cmptn-title{
    font-size: 16px;
}

  .Cmptn h2 {
    font-size: 42px;
}

  .tariffs h2 {
    font-size: 42px;
    padding-top: 160px;
    margin-bottom: 65px
  }

  .tariffs li {
    font-size: 16px;
  }

  .container{
    width: 970px;
}
.main-block-container .col-md-6{
    width: 50%;
    float: left;
    top: 100px;
    left: -18px;
}

.main-block-container .col-lg-6{
    top: 100px;
    left: -18px;
}
.main-block h1{
    font-size: 52px;
    text-align: left;
}

.achivement{
    margin-bottom: 96px;
}

.main-block{
    height: 603px;
}

.druplicon-img img{
    height: auto;
    width: auto;
}
.navbar-logo{
    padding-bottom: 0;
}

.col-md-offset-6 {
    margin-left: 50%;
}

.laptop-block{
    width: 70%;
    position: absolute;
    transform: none;
    left: 0;
    bottom: 0;
}

.review-slick-slider{
  width: 64%;
  float: left;
  padding-right: 60px;
  border-bottom: 0px solid #cdcdcd;
  border-right: 1px solid #cdcdcd;
  padding: 14px 60px;
}

.review-slick{
  display: flex;
  flex-wrap: wrap;
  position: relative;
  z-index: 10;
  background: #fff;
  border: 1px solid rgba(0,0,0,.1);
  box-sizing: border-box;
  box-shadow: 0 4px 60px rgba(162,162,162,.25);
  border-radius: 5px;
  padding: 66px 0 66px 50px;
}

.review-arrow-nav{
  width: 36%;
  display: flex;
  position: relative;
  vertical-align: middle;
  align-items: center;
  justify-content: center;
}

.reviews-title{
  font-size: 42px;
}

.review-content::before{
  content: "";
  display: block;
  background: #fff;
  opacity: .5;
  border: 1px solid rgba(0,0,0,.1);
  box-sizing: border-box;
  box-shadow: 0 4px 60px rgba(162,162,162,.25);
  border-radius: 5px;
  position: absolute;
  top: -40px;
  bottom: 0;
  left: 64px;
  right: 64px;
  z-index: 5;
}
.review-block{
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  position: relative;
  z-index: 10;
  background: #fff;
  border: 1px solid rgba(0, 0, 0, .1);
  box-sizing: border-box;
  box-shadow: 0 4px 60px rgba(162, 162, 162, .25);
  border-radius: 5px;
}
.review-content::after{
  content: "";
  display: block;
  background: #fff;
  opacity: .34;
  border: 1px solid rgba(0,0,0,.1);
  box-sizing: border-box;
  box-shadow: 0 4px 60px rgba(162,162,162,.25);
  border-radius: 5px;
  position: absolute;
  top: -72px;
  bottom: 0;
  left: 128px;
  right: 128px;
  z-index: 4;
}
}
</style>
