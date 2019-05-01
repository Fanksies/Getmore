<template>
  <section id="root">

    <section id="hero">
      <div class="aside">
        <div class="aside__ball">
          <div>ball</div>
        </div>
      </div>
      <nav class="container">
        <ul>
          <li>Inicio</li>
          <li>Acerca de nosotros</li>
          <li>Historia</li>
          <li>Contacto</li>
        </ul>
        <ul class="ml-auto">
          <li>Es</li>
          <li>En</li>          
        </ul>
      </nav>
      <div class="title">
        <h1>Las mejores raquetas para <br> jugar <span class="title__highlight">Tennis</span> </h1>
        <button>Acerca de Nosotros</button>
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

    <section id="background">
      <div>background image</div>
    </section>

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

</style>


