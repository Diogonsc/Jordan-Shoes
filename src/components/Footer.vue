<template>
  <footer class="footer">
    <p class="footer-text">Todos os direitos reservados.</p>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  width: 100%;
  height: 3.75rem;

  display: flex;
  justify-content: center;
  align-items: center;

  background-color: var(--preto-claro);
}

.footer-text {
  color: var(--branco);
  text-align: center;
  font-family: var(--montserrat);
  font-size: 1.12rem;
  font-weight: 500;
  font-style: normal;

  line-height: 2.2rem;
  margin: 0;
}
</style>
