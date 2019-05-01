<template>
  <section id="root">

    <section id="hero">
      <div class="aside">
        <div class="aside__ball">
          <div>ball</div>
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
        </b-navbar>  

        <!-- <ul class="ml-auto">
          <li>Es</li>
          <li>En</li>          
        </ul> -->

      <div class="flex-2 pl-3">
        <h1>Las mejores raquetas para <br> jugar <span class="title__highlight">Tennis</span> </h1>
        <button>Acerca de Nosotros</button>
      </div>

      </div>
      
    </section>

    <section id="history">
      <div class="history__aside">
        Tennis
      </div>
      <div class="history__main">
        <h2>Raquetas.Accesorios.<br>Pelotas.</h2>
        <p class="history__main--description p-desc">Conoce nuestras raquetas y aprende a jugar <br> Tennis cómo un profesional.</p>
        <button>Historia</button>
      </div>
    </section>

    <section id="showcase">
      <div class="showcase__aside">
        <div class="showcase__aside--content">
          <h2>Nuestras <br> <strong>Raquetas</strong></h2>
          <p class="showcase__aside--description p-desc">
            Conoce nuestras raquetas y <br> aprende a jugar Tennis cómo un profesional <br>
          </p>
          <div>dots</div>
          <div class="showcase__aside--prev-next">
            <div>prev</div>
            <div class="prev-next--highlighted">next</div>
          </div>
        </div>
      </div>
      <div class="showcase">
        <div class="showcase__carousel">
          <div class="showcase__carousel--item">
            raketa
          </div>
          <div class="showcase__carousel--item">
            raketa
          </div>
          <div class="showcase__carousel--item">
            raketa
          </div>
        </div>
      </div>
    </section>

    <section id="background"></section>

    <section id="footer">
      <div class="footer__main">
        <ul>
          <li>Inicio</li>
          <li>Acerca de nosotros</li>
          <li>Historia</li>
          <li>Contacto</li>
        </ul>
        <div class="social">
          <div>LinkedIn</div>
          <div>Vimeo</div>
          <div>Instagram</div>
          <div>Twitter</div>
          <div>Facebook</div>
        </div>
      </div>
      <div class="footer__aside">
        <div>Be the ball</div>
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
  font-family: Arial, Helvetica, sans-serif;
}

button {
  all: unset;
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
  grid-template-columns: 100px 1fr;
  h1 {
    font-size:3.31em;
    line-height: 1.28;
    color:white;
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
  color: $green !important;
}

//Navbar 
.nav-link  {
    color:white !important;
    letter-spacing: 1.5px;
}

.nav-item {
  margin:0 1.5em;  
}

.nav-item.active {
  margin-left:0 !important;
}

#hero {
  background-image: url('/group.png');
  min-height: 785px;
}
#history {
  min-height: 392px;
  background-color: #f3f4f8;
}
#showcase {
  min-height: 468px;
}
#background {
  background-image: url('/action-athlete-ball-342361.png');  
  min-height:586px;
}
#footer {
  background-color: #cbe346;
  min-height:203px;
}
</style>


