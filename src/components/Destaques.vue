<template>
  <main class="destaques container">
    <section class="destaques-section">
      <div class="destaques-textos">
        <h2 class="destaques-title">Destaques</h2>
        <p class="destaques-text">
          Frete grátis e chinelo de brinde é aqui, aproveite por tempo limitado.
        </p>
      </div>
    </section>
    <Cards />
  </main>
</template>

<script>
import Cards from "./Cards.vue";
export default {
  components: { Cards },
};
</script>

<style scoped>
.destaques-textos {
  padding-left: 1.25rem;
  padding-right: 1.25rem;
}
.destaques-title {
  color: var(--preto-claro);

  display: flex;
  justify-content: center;
  align-items: center;

  font-family: var(--montserrat);
  font-size: 2rem;
  font-weight: 600;
  font-style: normal;

  line-height: 3.92rem;
  padding-top: 2rem;
}

.destaques-text {
  color: var(--cinza);
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;

  font-family: var(--montserrat);
  font-size: 1.12rem;
  font-weight: 500;
  font-style: normal;

  line-height: 2.2rem;
}
@media screen and (max-width: 420px) {
  .destaques-title {
    font-size: 1.75rem;
  }

  .destaques-text {
    font-size: 0.9rem;
    line-height: 1.8rem;
  }
}
</style>
