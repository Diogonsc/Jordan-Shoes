<template>
  <div class="cards">
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-1.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-2.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-3.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-4.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-5.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-6.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-7.png" alt="Air Jordan 1" />
    </q-card>
    <q-card flat class="destaques-cards">
      <img src="../assets/img/Tenis-air-jordan-8.png" alt="Air Jordan 1" />
    </q-card>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.cards {
  padding: 2.25rem;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.destaques-cards {
  margin: 15px 0.5rem;
  width: 18.75rem;
  height: 18.87rem;

  display: flex;
  justify-content: center;
  align-items: center;

  background-color: var(--branco-200);
}

@media screen and (max-width: 420px) {
  .cards {
    padding: 1.25rem 0;
  }
  .destaques-cards {
    margin: 10px 1.25rem;
    width: 23.37rem;
    background-color: var(--branco-200);
  }
}
</style>
