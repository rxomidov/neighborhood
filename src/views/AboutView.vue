<template>
  <div class="onm-top-header">
    <div class="container mt-2 d-flex align-items-center justify-content-between">
      <div class="onm-top-header__left d-flex">
        <div class="d-flex"><span>
          <img src="@/assets/img/Phone.svg" alt="telegram">
        </span> <a href="https://t.me/online_mahalla_help_bot" target="_blank">
          <span> +998 (00) 000-00-00</span>
        </a></div> <div class="d-flex"><span>
          <img src="@/assets/img/svg-users.svg" alt="telegram">
        </span> <a href="https://t.me/mahalla" target="_blank">
          <span> Rasmiy kanal</span></a></div> <div class="d-flex"><span>
            <img src="@/assets/img/email.svg" alt="email"></span> 
            <a href="mailto:info@mahalla.uz"><span> info@mahalla.uz</span></a>
          </div></div> 
          <div class="onm-top-header__right d-flex">
            <ul class="d-flex onm-socials m-0 pl-3"><li>
              <a href="#">
                <img src="@/assets/img/facebook_black.svg" alt="facebook">
              </a></li> <li><a href="#">
                <img src="@/assets/img/telegram_black.svg" alt="telegram">
              </a></li> <li><a href="#">
                <img src="@/assets/img/instagram_black.svg" alt="instagram">
              </a></li></ul></div></div></div>
  <div class="onm-header onscroll">
    <div class="container d-flex justify-content-between">
      <div class="onm-header--logo">
        <a href="/" aria-current="page" class="router-link-exact-active router-link-active">
          <img src="@/assets/img/header-logo.png" height="64px" alt="logo">
          </a>
          </div>
          <div class="onm-header__list d-flex justify-content-between align-items-center">
            <ul class="list-group d-flex flex-row list-style-none align-items-center justify-content-between"><li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Bosh sahifa</a></li> <li><RouterLink to="/about" class="router-link-exact-active router-link-active" href="/public/pages/about">Tizim haqida</RouterLink>
            </li>
            <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Onlayn axborotnoma</a></li> <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Savol-javob</a></li> <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Bog‘lanish</a></li>
            </ul>
            <RouterLink to="/login"><button type="button" class="onm-btn onm-header__list-btn onm-btn-197 d-flex align-items-center justify-content-between" style="backdrop-filter: blur(20px);">
            <img src="@/assets/img/log-in-blue.svg" alt="login icon">
            <span>Tizimga kirish</span> </button></RouterLink>
      </div>
    </div>
  </div>
    <section><div class="onm-about__banner"><div class="container"><div class="onm-about__banner-wrapper"><h1> Tizim haqida </h1> <p><span>Bosh sahifa </span> <span>» Tizim haqida</span></p></div></div></div> <div class="container"><div class="onm-about__info"><img src="@/assets/img/about-info-icon.svg" alt="exclamation mark"> <p>
      O‘zbekiston Respublikasi Prezidentining “Iqtisodiy taraqqiyot va kambag‘allikni qisqartirish vazirligi huzuridagi Mahallabay ishlash va tadbirkorlikni rivojlantirish agentligi faoliyatini tashkil etish chora-tadbirlari to‘g‘risida” 2021-yil 24-dekabrdagi PQ-62-son qaroriga muvofiq ishlab chiqilgan.<br>Mazkur elektron platforma respublika miqyosidagi barcha hokim yordamchilari, respublika vakillari, tuman markazlari va tuman hokimliklari, hududiy boshqarma va viloyat hokimliklarning faoliyatini to‘liq raqamlashtirish vazifasini bajaradi.
          <button type="button" class="btn btn btn-primary btn-primary">Batafsil</button></p></div></div></section>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.onm-about__banner {
    display: flex;
    justify-content: center;
    margin: 85px 0 45px;
    height: 25vh;
    position: relative;
    background-size: cover;
    background-repeat: no-repeat;
    background-image: url(https://online-mahalla.uz/media/store//img/svg/onm-about-banner2.png);
}
.onm-about__banner-wrapper {
    display: flex;
    z-index: 10;
    position: relative;
    height: 100%;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-family: 'Montserrat', sans-serif;
    color: #FFFFFF;
}
.onm-about__info {
    gap: 17px;
    display: flex;
    align-items: center;
    padding: 15px 17px;
    border-radius: 10px;
    margin-bottom: 63px;
    background: rgba(0, 96, 254, 0.07);
    cursor: pointer;
}
.onm-about__info p {
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    font-weight: bold;
    font-size: 16px;
    line-height: 32px;
    color: #000000;
}
</style>
