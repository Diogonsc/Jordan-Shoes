<template>
  <div>
    <header class="container">
      <p class="p-text-header">Ganhe R$ 10,00 de desconto no frete</p>
      <h2 class="h2-title-header">JordanShoes</h2>
      <figure class="figure-header">
        <div class="figure-texto">
          <h1 class="h1-title-banner-header">A melhor loja de Jordan</h1>
          <p class="p-text-banner-header">
            O tênis Jordan é fruto de uma velha e forte parceria entre a Nike e
            o jogador Michael Jordan.
          </p>
        </div>
      </figure>
    </header>
    <Destaques />
    <Footer />
  </div>
</template>

<script>
import Destaques from "src/components/Destaques.vue";
import Footer from "src/components/Footer.vue";
export default {
  components: { Destaques, Footer },
};
</script>
<style scoped>
.p-text-header {
  width: 100%;
  height: 3.75rem;

  color: var(--branco-200);
  background-color: var(--preto-claro);

  display: flex;
  align-items: center;
  justify-content: center;

  margin-bottom: 0;

  font-family: var(--montserrat);
  font-weight: 500;
  font-size: 1rem;
  font-style: normal;

  line-height: 1.96rem;
}
.h2-title-header {
  width: 100%;
  height: 3.75rem;

  color: var(--preto-claro);
  background-color: var(--branco);

  display: flex;
  align-items: center;
  justify-content: center;

  font-family: var(--montserrat);
  font-weight: 600;
  font-size: 1.5rem;
  font-style: normal;

  line-height: 2.94rem;

  margin-top: 0;
}
.figure-header {
  width: 100%;
  height: 23.62rem;

  background: linear-gradient(360deg, #13131f 0%, rgba(18, 18, 18, 0.6) 100%),
    url(../assets/img/Air-Jordan-1-Retro.png);
  position: relative;
}

.figure-texto {
  padding-top: 7.5rem;
  padding-left: 5.5rem;
}

.h1-title-banner-header {
  color: var(--branco);

  font-family: var(--montserrat);
  font-size: 2rem;
  font-weight: 700;
  font-style: normal;

  line-height: 2.43rem;

  position: relative;
}

.p-text-banner-header {
  width: 28.75rem;
  height: 4.37rem;
  color: var(--branco);

  font-family: var(--montserrat);
  font-size: 1.12rem;
  font-weight: 600;
  font-style: normal;

  line-height: 2.2rem;

  position: relative;
}

@media screen and (max-width: 420px) {
  .figure-header {
    background: linear-gradient(
        360deg,
        #13131f 0%,
        rgba(18, 18, 18, 0.008) 100%
      ),
      url(../assets/img/Air-Jordan-1-Retro-mobile.png);
  }
  .figure-texto {
    padding-top: 7.5rem;
    padding-left: 1.25rem;
    padding-right: 1.25rem;
  }

  .h1-title-banner-header {
    font-size: 1.65rem;
  }

  .p-text-banner-header {
    width: 22.31rem;
    height: 5.43rem;

    padding-top: 0.5rem;
    font-size: 0.9rem;
    line-height: 1.8rem;
  }
}
</style>
