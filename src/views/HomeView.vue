<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <!-- <TheWelcome /> -->
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
          <span> Расмий канал</span></a></div> <div class="d-flex"><span>
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
            <ul class="list-group d-flex flex-row list-style-none align-items-center justify-content-between"><li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Бош саҳифа</a></li> <li><a href="/public/pages/about" class="">Тизим ҳақида</a>
            </li>
            <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Онлайн ахборотнома</a></li> <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Савол-жавоб</a></li> <li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Боғланиш</a></li>
            </ul>
            <RouterLink to="/login"><button type="button" class="onm-btn onm-header__list-btn onm-btn-197 d-flex align-items-center justify-content-between" style="backdrop-filter: blur(20px);">
            <img src="@/assets/img/log-in-blue.svg" alt="login icon">
            <span>Тизимга кириш</span> </button></RouterLink>
      </div>
    </div>
  </div>
  <section id="main" class="main-section"><div class="main-section__wrapper"><div class="container"><h1>
          «Mahalla» - elektron platformasi
        </h1> <p>
          Mahallabay ishlash markazi va mahalla fuqarolar yig‘ini faoliyatini
          o‘zaro bog‘liq holda raqamlashtirishni nazarda tutuvchi elektron platforma
        </p> <div class="main-section__buttons"><button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://online-mahalla.uz@/assets/docs/hy_info.pdf" target="_blank"><span name="title"> Қўлланма </span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://online-mahalla.uz/public/forms/study_nntt_direction" target="_blank"><span name="title"> Ўқишга йўналтириш <br> (ННТ/НТТ)</span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://online-mahalla.uz/public/forms/subsidy" target="_blank"><span name="title"> Субсидияга ариза </span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://murojaat.gov.uz" target="_blank"><span name="title"> Онлайн мурожаатнома</span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://online-mahalla.uz/public/pages/reestr" target="_blank"><span name="title" alt="reestr"> Электрон реестр </span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://my.chamber.uz/" target="_blank"><span name="title"> 20 минг тадбиркор </span></a> </button> <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center"><a href="https://online-mahalla.uz/public/forms/subsidy_craftsman" target="_blank"><span name="title"> Ҳунармандчилик <br> субсидияси </span></a> </button></div> <br></div></div></section>
        <section class="business-plans container-fluid"><div class="container business-plans"><div class="business-plans-heading-wrapper"><h1 class="business-plans-heading">Biznesga yo'naltiruv</h1></div> <a href="/public/pages/growthpoints-page" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/house.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          O‘sish nuqtalari
          </h4> <p class="business-plans__card--desc">
            Mahalladagi ijtimoiy-iqtisodiy holatnii xonadonbay o‘rganish
          </p> <div class="business-plans__card--more">
            Batafsil
            <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/business_plans-page" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/growth.svg" alt="icon"> <div><h4 class="business-plans__card--title">
              Biznes-reja loyihasi va hujjatlar to‘plami
          </h4> <p class="business-plans__card--desc">
            Mavjud biznes rejalar
          </p> <div class="business-plans__card--more">
            Batafsil
            <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/preferences-new" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/work-from-home.svg" alt="icon"> <div><h4 class="business-plans__card--title">
              Imtiyoz va preferensiyalar to‘g‘risida ma’lumot
          </h4> <p class="business-plans__card--desc">
            Mavjud imtiyoz va preferensiyalar va ularni olish uchun zarur bo‘lgan xujjatlar to‘plami
          </p> <div class="business-plans__card--more">
            Batafsil
            <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/new_auctionpage?index=1&amp;page=1&amp;order=0" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/headhunting.svg" alt="icon"> <div><h4 class="business-plans__card--title">
              Tadbirkorlik faoliyatini amalga oshirish uchun ko‘chmas mulk obyektlari
          </h4> <p class="business-plans__card--desc">
            Bo‘sh turgan ko‘chmas mulk to‘g‘risidagi ma’lumotlar
          </p> <div class="business-plans__card--more">
            Batafsil
            <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a></div></section>      




<section class="business-plans bs__bg container-fluid"><div class="container business-plans"><div class="business-plans-heading-wrapper-heading-wrapper"><h1 class="business-plans-heading">Аҳоли ва тадбиркорлар учун хизматлар соҳасидаги имкониятлар</h1></div> <div class="business-cards-modal-wrapper"><a href="/public/pages/profitable-services" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img1.svg" alt="icon"> <div><h4 class="business-plans__card--title">
  Daromadli xizmatlar
			 </h4> <p class="business-plans__card--desc">
        Aholi va tadbirkorlik subyektlariga faoliyatini tashkil etish mumkin bo‘lgan daromadli xizmatlar
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/project-offices" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img2.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          Loyiha ofislari
			 </h4> <p class="business-plans__card--desc">
        Xizmat ko‘rsatish sohasida yangi loyihalarni amalga oshirish uchun tayyor biznes g‘oyalar, loyiha takliflari va boshqa maslahat xizmatlarini ko‘rsatuvchi loyiha ofislari
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/auction-sales" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img3.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          Auksion savdolar
			 </h4> <p class="business-plans__card--desc">
        Xizmat ko‘rsatish obyektlarini tashkil etish maqsadlari uchun auksion savdolarga chiqarilgan yer maydonlari va bino-inshoatlar
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/benefits-amenities" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img4.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          Imtiyozlar va qulayliklar
			 </h4> <p class="business-plans__card--desc">
        Xizmat ko‘rsatish sohasidagi imtiyozlar va qulayliklar
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/prefential-credits" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img5.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          Imtiyozli kreditlar
			 </h4> <p class="business-plans__card--desc">
          Xizmat ko‘rsatish sohasi uchun imtiyozli kreditlar
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="https://simyogoch.uz" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img66.svg" alt="icon"> <div><h4 class="business-plans__card--title">
			   Simyog’och platformasi
			 </h4> <p class="business-plans__card--desc">
        O‘zingizga kerak bo‘lgan ishni yoxud ishchini topish uchun qulay platforma.
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a><a href="/public/pages/map" class="business-plans__card"><div class="business-plans__card--item"><img src="@/assets/img/card-img5.svg" alt="icon"> <div><h4 class="business-plans__card--title">
          Mahallalar reytingi
			 </h4> <p class="business-plans__card--desc">
        O‘zbekiston Respublikasi mahallalar reytingi
			 </p> <div class="business-plans__card--more">
			   Batafsil
			   <img src="@/assets/img/arrow-right.svg" alt="icon" class="main-more-icon"></div></div></div></a></div></div></section>



         <section class="main-gallery">
          <div class="container">
            <div class="main-gallery__header mb-5">
              <h1 class="text-center">Galereya</h1> 
              <p class="text-center">«Hokim yordamchi»lari faoliyatidan foto va video lavhalar</p></div>
               <div class="d-flex">
                <div class="col-6">
                  <div class="bg-gallery pic mb-3" style="width: calc(100% - 15px);">
                  <img src="@/assets/img/image15.jpg" alt="gallery1" class="bg-gallery--main">
                  </div>
                   <div class="d-flex" style="gap: 15px;">
                   <div class="bg-gallery pic col-6 p-0">
                    <img src="@/assets/img/image34.jpg" alt="gallery2">
                    </div> <div class="bg-gallery pic col-6 p-0">
                      <img src="@/assets/img/image96.jpg" alt="gallery3" style="width: calc(100% - 30px);">
                      </div></div></div> <div class="col-6">
                        <div class="d-flex mb-3" style="gap: 15px;"><div class="bg-gallery pic col-6 p-0">
                          <img src="@/assets/img/image43.jpg" alt="gallery4"
                          ></div> <div class="bg-gallery pic col-6 p-0">
                            <img src="@/assets/img/image38.jpg" alt="gallery5">
                            </div></div> <div class="bg-gallery pic" style="width: calc(100% + 15px);">
                            <img src="@/assets/img/image18.jpg" alt="gallery6" class="bg-gallery--main">
                            </div></div></div> <a href="/public/pages/page_gallery" class="">
                              <div class="onm-btn-more d-flex justify-content-center align-items-center">
                                <button type="button" class="onm-btn onm-btn--blue d-flex align-items-center">
                                  <span name="title">Ko‘proq yuklash</span> </button>
                      </div></a>
                </div>
            </section>



            <footer><div class="main-footer"><div class="container"><div class="row justify-content-between"><div class="col-md-5 col-sm-12 main-footer__logo-line"><a href="/" aria-current="page" class="router-link-exact-active router-link-active"><img src="@/assets/img/header-logo.png" alt="footer"></a> <p>
              Yunusobod tumani, Amir Temur shox ko‘chasi
            </p> <a href="mailto:info@mahalla.uz"><p class="ml-2">info@mahalla.uz</p></a> <a class="m-0">www.mahalla.uz</a></div> <div class="col-lg-2 col-sm-12 col-md-3 main-footer__list"><h2>
              Menyular
            </h2> <ul><li><a href="/" aria-current="page" class="router-link-exact-active router-link-active">Бош саҳифа</a></li> <li><a href="/public/pages/about" class="">Тизим ҳақида</a></li> <li><a href="#" class="">Янгиликлар</a></li> <li><a href="/#faq">Савол-жавоб</a></li> <li><a href="#" target="_blank">Боғланиш</a></li></ul></div> <div class="col-md-4 col-sm-12 main-footer__list"><h2>
              Mobil ilovalar
            </h2> <ul class="footer-socials"><li class="mb-2"><div class="google-play-icon cursor-pointer"><a href="#" target="_blank"><img src="@/assets/img/google-play.svg"></a></div></li> <li><a href="#" class="main-footer__mobilelink"><button type="button" class="onm-btn onm-header__list-btn onm-btn-197 d-flex align-items-center justify-content-between" style="backdrop-filter: blur(20px);"><span>E-IMZO Mobile</span> <img src="@/assets/img/log-in-blue.svg" alt="login icon"> </button></a></li></ul></div></div></div></div> <div class="main-footer2"><div class="container"><div class="d-flex justify-content-between"><div class="main-footer2--left">
          © «Mahalla». Barcha huquqlar himoyalangan
        </div> <div class="main-footer2--right d-flex"><div class="d-flex"><p class="mr-3"><a href="#"><img src="@/assets/img/telegram_black.svg" alt="footer" class="pointer"></a></p> <p><a href="#"><img src="@/assets/img/instagram_black.svg" alt="footer" class="pointer"></a></p></div> <div class="ml-5"><a href="#" target="_top"></a></div></div></div></div></div></footer>
  </main>
</template>
