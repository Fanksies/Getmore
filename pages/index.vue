<template>
  <section id="root">

    <section id="hero">
      <div class="aside">
        <div class="aside__ball text-center pt-lg-4">
          <img alt="ball" src="/fill-2.png">
        </div>
      </div>

      <div class="title container">
      
        <b-navbar>
          <b-navbar-nav>
            <b-nav-item class="active" href="#"> <strong>Inicio</strong></b-nav-item>
            <b-nav-item href="#">Acerca de nosotros</b-nav-item>
            <b-nav-item href="#">Historia</b-nav-item>
            <b-nav-item href="#">Contacto</b-nav-item>
          </b-navbar-nav>
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#"> ES <span class="ml-1"> EN </span></b-nav-item>
          </b-navbar-nav>
        </b-navbar>  

        <!-- <ul class="ml-auto">
          <li>Es</li>
          <li>En</li>          
        </ul> -->

      <div class="flex-2 pl-3">
        <h1>Las mejores raquetas para <br> jugar <span class="title__highlight">Tennis</span> </h1>
        <div>
          <button class="text-white mt-4">Acerca de Nosotros ⟶</button>
        </div>
      </div>

      </div>
      
    </section>

    <section id="history">
      <div class="history__wrapper">
        <div class="history__aside mr-5 mt-2">
          Tennis
        </div>
        <div class="history__main">
          <h2 class="mb-4">Raquetas.Accesorios.<br>Pelotas.</h2>
          <p class="history__main--description p-desc">Conoce nuestras raquetas y aprende a jugar <br> Tennis cómo un profesional.</p>      
        </div>
        <button class="history__btn ml-5 mb-3">Historia 	&#160; 	&#160; 	&#160; 	&#160; 	 ⟶</button>
      </div>
    </section>

    <section id="showcase">
      <div class="showcase__aside">
        <div class="showcase__aside--content">
          <h2>Nuestras <br> <strong>Raquetas</strong></h2>
          <p class="showcase__aside--description p-desc">
            Conoce nuestras raquetas y <br> aprende a jugar Tennis cómo un <br> profesional 
          </p>
          <div>
            <img src="/oval.png" alt="">
            <img class="ml-3" src="/oval_2.png" alt="">
            <img class="ml-3" src="/oval_2.png" alt="">
            <img class="ml-3" src="/oval_2.png" alt="">
          </div>
          <div class="showcase__aside--prev-next">
            <div>
              <img class="showcase-btn mr-3 test-btn" src="/test.png" alt="">
            </div>
            <div class="prev-next--highlighted">
              <img class="showcase-btn" src="/group-copy-2.png" alt="">
            </div>
          </div>
        </div>
      </div>
      <div class="showcase">
        <div class="showcase__carousel">
          <div class="showcase__carousel--item">
            <img class="relative" src="/group-10.png" alt="">
            <img class="absolute--unit" src="/oval@3x.png" alt="">
            <div class="absolute--unit__num">1</div>
          </div>
          <div class="showcase__carousel--item">
            <img class="relative" src="/group-10.png" alt="">
            <img class="absolute--unit" src="/oval@3x.png" alt="">     
            <div class="absolute--unit__num">2</div>
                  
          </div>
          <div class="showcase__carousel--item">
            <img class="relative" src="/group-10.png" alt="">
            <img class="absolute--unit" src="/oval@3x.png" alt="">
            <div class="absolute--unit__num">3</div>

          </div>
        </div>
      </div>
    </section>

    <section id="background"></section>

    <section id="footer">
      <div class="footer__main p-4">
        <b-navbar >
          <b-navbar-nav>
            <b-nav-item class="active dark" href="#"> <strong>Inicio</strong></b-nav-item>
            <b-nav-item class="dark" href="#">Acerca de nosotros</b-nav-item>
            <b-nav-item class="dark" href="#">Historia</b-nav-item>
            <b-nav-item class="dark" href="#">Contacto</b-nav-item>
          </b-navbar-nav>
          
        </b-navbar>  
        <div class="social pl-4">
          <img class="social__icon mr-1" src="/group-23@3x.png" alt="">
          <img class="social__icon mr-1" src="/group-24@3x.png" alt="">
          <img class="social__icon mr-1" src="/group-25@3x.png" alt="">
          <img class="social__icon mr-1" src="/group-22@3x.png" alt="">
          <img class="social__icon mr-1" src="/group-26@3x.png" alt="">
        </div>
      </div>
      <div class="footer__aside">
        <img src="/fill-2@3x.png" alt="">
      </div>
    </section>

  </section>
  
 
  
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style lang="scss">

// Variables

$green: #cbe346;

// Generals

html, body {
  font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 
}

.container {
    max-width: 1560px;
}

.relative {
  position:inherit;
}

.absolute--unit {
  position: absolute;
  left: 8%;
  top: 5%;
  position:absolute;
}

.absolute--unit__num {
  position: absolute;
  top: 5%;
  right: 87%;
  color: white;
  margin: 0px -1px;
  font-size: 0.9em;
}

button {
  all: unset;
  border-radius: 26.5px;
  border: solid 1px #ffffff;
  display: inline-block;
  text-transform: uppercase;
  padding: 1.15em 2.5em;
  font-weight: bold;
  letter-spacing: 1px;
  font-size:13px;
  text-align:center;
}

.flex-2 {
  flex:2;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

// Sections

// Hero 

#hero {
  display: grid;
  grid-template-columns: 110px 1fr;
  h1 {
    font-size:3.31em;
    line-height: 1.28;
    color:white;
    letter-spacing: -0.05px;
  }
  .title {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
}

.aside {
  border-right: 2px solid white;
}

.title__highlight {
  font-weight:bold;
  color: $green !important;
}

//Navbar 
.nav-link  {
    color:white !important;
    letter-spacing: 1.1px;
}

.nav-link-dark {
  color:#2b3049 !important;
}

.nav-item {
  margin:1.5em;  
}

.nav-item.active {
  margin-left:0 !important;
}

#hero {
  background-size: cover;
  background-position:center center;
  background-image: url('/group@2x.png');
  min-height: 785px;
}
#history {
  min-height: 392px;
  background-color: #f3f4f8;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.history__main {
  h2 {
    font-size:2.5rem;
  }
}

.history__wrapper {
  display: flex;
  margin: 0 auto;
}

.history__aside {
  color:$green;
  letter-spacing: 1.5px;
  font-weight:bold;
  text-transform: uppercase;
  align-self: baseline;
}

.history__btn {
  border:1px solid #282e47;
  color: #282e47;
  align-self: end;
}

.history__main--description {
  line-height: 1.78;
  letter-spacing: 0.5px;
  color: #787878;
}

#showcase {
  min-height: 468px;
  display: flex;
}

.showcase__aside {
  background:url('/ball-color-court-1405355.png');
  background-size: cover;
  background-position: 35%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.showcase__aside--content {
  color: white;
  margin: 0em 1.5em 0em 10em;
  h2 {
    font-size:2.5em;
  }
}

.showcase {
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex: 2;
  overflow: hidden;
}

.showcase__aside--prev-next {
  display: flex;
}

.showcase-btn {
  width: 54px;
  margin: 1em 0 1em -0.5em;
}

.test-btn {
  width: 45px;
  margin-top: 19px;
}

.showcase__carousel {
  display: flex;
}

.showcase__carousel--item {
  width: 288px;
  height:344px;
  margin: 0 1em;
  position: relative;
}

#background {
  background-image: url('/action-athlete-ball-342361.png'); 
  background-size: cover; 
  min-height:586px;
}
#footer {
  display: flex;
  background-color: #cbe346;
  min-height:203px;
}

.social__icon {
  width:2.25em;
}


.footer__aside {
  display: flex;
  flex-direction: column;
  justify-content: center;
  img {
    width:50%;
  }
}

.footer__main {
  flex:2;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.dark {
  margin-bottom: 0.5em;
  a {
    color: #2b3049 !important;
  }
}
</style>


