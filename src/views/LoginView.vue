<template>
  <div class="onm-login__page">
  <div class="onm-login">
    <div class="onm-login__wrapper d-flex justify-content-center">
      <div class="onm-login__form--card">
        <div class="onm-login__form--login">
          <a href="/" class="router-link-active">
            <img src="@/assets/img/header-logo.png" height="48px" alt="logo">
            </a>
            </div> <div class="onm-login__form--header"><p>Xush kelibsiz</p> <h3>Tizimga kirish

            </h3></div> <form class="onm-login__form"><div class="onm-login__form--item">
              <label>Login</label> <span><input type="text" placeholder="Киритиш"></span>
              </div> <div class="onm-login__form--item" style="position: relative;"><label>Parol</label> <span>
                <input placeholder="Парол" type="password"> <span class="onm-login__eye">
                  <img src="https://online-mahalla.uz/media/store/img/hide-password.svg" alt="online-mahalla"></span></span>
                  </div> <!----> <div class="onm-login__actions d-flex flex-column align-items-center">
                    <button type="button" class="onm-btn onm-header__list-btn onm-btn--r5 onm-btn--w100p d-flex align-items-center my-3">
                      <RouterLink to="/admin"><span>Tizimga kirish</span> </RouterLink></button> 
                      <button type="button" class="onm-btn onm-btn--dark-blue onm-btn--r5 onm-btn--w100p d-flex align-items-center"><span>ERI bilan kirish</span>
                       </button></div></form></div> <div class="onm-login__banner d-md-flex align-items-center justify-content-center"><div class="onm-login__banner--logo">
                        <img src="@/assets/img/header-logo.png" alt="mahalla"></div>
                         <div class="onm-login__links"><li><a href="https://t.me/onlinemahalla">
                          <img src="@/assets/img/telegram_black.svg" alt="telegram"></a></li> 
                          <li><a href="@">
                            <img src="@/assets/img/instagram_black.svg" alt="instagram"></a></li>
                            </div></div></div></div></div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
