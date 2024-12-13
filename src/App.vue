<template>
  <div id="app">
    <!-- Banner Section -->
    <div class="banner-container">
      <h1>Floricultura Japonesa</h1>
    </div>

    <!-- Section: Lycoris radiata -->
    <section class="content-section">
      <div class="text">
        <h2>Lycoris radiata: a flor mágica</h2>
        <p>
          A Lycoris radiata é uma flor famosa no Japão, associada a significados
          profundos e à temporada de outono. Suas pétalas delicadas e vibrantes
          são um símbolo de beleza e mistério.
        </p>
      </div>
      <div class="image">
        <img src="./assets/image/juuzou.jpg" alt="Lycoris radiata">
      </div>
    </section>

    <!-- Footer Section -->
    <footer>
      <p>© 2024 Floricultura Japonesa. Todos os direitos reservados.</p>
    </footer>
  </div>
</template>

<style scoped>
/********** BANNER **********/
.banner-container {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #fdf6f0;
  padding: 2rem;
  height: 50vh;
  background: url('./assets/image/juuzou_banner.jpg') no-repeat center center;
  background-size: cover;
}

.banner-container h1 {
  font-size: 3rem;
  color: #b93160;
}

/********** SEÇÃO DE CONTEÚDO **********/
.content-section {
  padding: 2rem;
  text-align: center;
}

.content-section .text {
  margin-bottom: 1.5rem;
  font-size: 1.2rem;
  line-height: 1.6;
  color: #333;
}

.content-section .text h2 {
  font-size: 2rem;
  color: #b93160;
  margin-bottom: 1rem;
}

.content-section .image img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/********** RODAPÉ **********/
footer {
  text-align: center;
  padding: 1rem;
  background-color: #f1f1f1;
  font-size: 0.9rem;
  color: #666;
  margin-top: 2rem;
}
</style>
