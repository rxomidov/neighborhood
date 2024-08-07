<template>
  <nav class="menu" tabindex="0">
	<div class="smartphone-menu-trigger"></div>
  <header class="avatar">
		<img src="https://s3.amazonaws.com/uifaces/faces/twitter/kolage/128.jpg" />
    <h2>John D.</h2>
  </header>
	<ul>
    <li tabindex="0" class="icon-dashboard"><span>Dashboard</span></li>
    <li tabindex="0" class="icon-customers"><span>Customers</span></li>
    <li tabindex="0" class="icon-users"><span>Users</span></li>
    <li tabindex="0" class="icon-settings"><span>Settings</span></li>
  </ul>
</nav>

<main>
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
  <div class="helper">
    Bosh sahifa
		<span>Breakpoints on 900px and 400px</span>
  </div>
</main>
</template>

<style lang="css">
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
body {
	 background: #383f64;
	 margin: 0;
	 font-family: "Open Sans", Helvetica Neue, Helvetica, Arial, sans-serif;
	 color: #fff;
	 padding-left: 240px;
}
 main {
	 position: relative;
	 height: 100vh;
}
 main .helper {
	 background: rgba(0,0,0,0.2);
	 color:rgb(255, 255, 255)4;
	 position: absolute;
	 top: 50%;
	 left: 50%;
	 transform: translate3d(-50%,-50%,0);
	 padding: 1.2em 2em;
	 text-align: center;
	 border-radius: 20px;
	 font-size: 2em;
	 font-weight: bold;
}
 main .helper span {
	 color: rgba(255, 255, 255, 0.8);
	 font-size: 0.4em;
	 display: block;
}
 .menu {
	 background: #1b2347;
	 height: 100vh;
	 width: 240px;
	 position: fixed;
	 top: 0;
	 left: 0;
	 z-index: 5;
	 outline: none;
}
 .menu .avatar {
	 background: rgba(0,0,0,0.1);
	 padding: 2em 0.5em;
	 text-align: center;
}
 .menu .avatar img {
	 width: 100px;
	 border-radius: 50%;
	 overflow: hidden;
	 border: 4px solid #383f64;
	 box-shadow: 0 0 0 4px rgba(255,255,255,0.2);
}
 .menu .avatar h2 {
	 font-weight: normal;
	 margin-bottom: 0;
}
 .menu ul {
	 list-style: none;
	 padding: 0.5em 0;
	 margin: 0;
}
 .menu ul li {
	 padding: 0.5em 1em 0.5em 3em;
	 font-size: 0.95em;
	 font-weight: regular;
	 background-repeat: no-repeat;
	 background-position: left 15px center;
	 background-size: auto 20px;
	 transition: all 0.15s linear;
	 cursor: pointer;
}
 .menu ul li.icon-dashboard {
	 background-image: url("http://www.entypo.com/images//gauge.svg");
}
 .menu ul li.icon-customers {
	 background-image: url("http://www.entypo.com/images//briefcase.svg");
}
 .menu ul li.icon-users {
	 background-image: url("http://www.entypo.com/images//users.svg");
}
 .menu ul li.icon-settings {
	 background-image: url("http://www.entypo.com/images//tools.svg");
}
 .menu ul li:hover {
	 background-color: rgba(0,0,0,0.1);
}
 .menu ul li:focus {
	 outline: none;
}
 @media screen and (max-width: 900px) and (min-width: 400px) {
	 body {
		 padding-left: 90px;
	}
	 .menu {
		 width: 90px;
	}
	 .menu .avatar {
		 padding: 0.5em;
		 position: relative;
	}
	 .menu .avatar img {
		 width: 60px;
	}
	 .menu .avatar h2 {
		 opacity: 0;
		 position: absolute;
		 top: 50%;
		 left: 100px;
		 margin: 0;
		 min-width: 200px;
		 border-radius: 4px;
		 background: rgba(0,0,0,0.4);
		 transform: translate3d(-20px,-50%,0);
		 transition: all 0.15s ease-in-out;
	}
	 .menu .avatar:hover h2 {
		 opacity: 1;
		 transform: translate3d(0px,-50%,0);
	}
	 .menu ul li {
		 height: 60px;
		 background-position: center center;
		 background-size: 30px auto;
		 position: relative;
	}
	 .menu ul li span {
		 opacity: 0;
		 position: absolute;
		 background: rgba(0,0,0,0.5);
		 padding: 0.2em 0.5em;
		 border-radius: 4px;
		 top: 50%;
		 left: 80px;
		 transform: translate3d(-15px,-50%,0);
		 transition: all 0.15s ease-in-out;
	}
	 .menu ul li span:before {
		 content: '';
		 width: 0;
		 height: 0;
		 position: absolute;
		 top: 50%;
		 left: -5px;
		 border-top: 5px solid transparent;
		 border-bottom: 5px solid transparent;
		 border-right: 5px solid rgba(0,0,0,0.5);
		 transform: translateY(-50%);
	}
	 .menu ul li:hover span {
		 opacity: 1;
		 transform: translate3d(0px,-50%,0);
	}
}
 @media screen and (max-width: 400px) {
	 body {
		 padding-left: 0;
	}
	 .menu {
		 width: 230px;
		 box-shadow: 0 0 0 100em rgba(0,0,0,0);
		 transform: translate3d(-230px,0,0);
		 transition: all 0.3s ease-in-out;
	}
	 .menu .smartphone-menu-trigger {
		 width: 40px;
		 height: 40px;
		 position: absolute;
		 left: 100%;
		 background: #5bc995;
	}
	 .menu .smartphone-menu-trigger:before, .menu .smartphone-menu-trigger:after {
		 content: '';
		 width: 50%;
		 height: 2px;
		 background: #fff;
		 border-radius: 10px;
		 position: absolute;
		 top: 45%;
		 left: 50%;
		 transform: translate3d(-50%,-50%,0);
	}
	 .menu .smartphone-menu-trigger:after {
		 top: 55%;
		 transform: translate3d(-50%,-50%,0);
	}
	 .menu ul li {
		 padding: 1em 1em 1em 3em;
		 font-size: 1.2em;
	}
	 .menu:focus {
		 transform: translate3d(0,0,0);
		 box-shadow: 0 0 0 100em rgba(0,0,0,0.6);
	}
	 .menu:focus .smartphone-menu-trigger {
		 pointer-events: none;
	}
}
 
</style>
