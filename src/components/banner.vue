<script setup></script>

<template>
  <section id="banner" class="slide">
    <div class="color-overlay">
      <article class="ms-5">
        <h1>CODERDOJO HELMOND</h1>
        <p>KINDEREN LEREN PROGRAMMEREN</p>
      </article>
    </div>
  </section>
</template>

<style scoped>
#banner {
  min-height: 500px;
  height: 100%;
  width: 100%;
  max-width: 100%;
  position: relative;
  background: url(@/assets/banner.png) 50% 0 repeat fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  box-shadow: inset 0 0 0 300px rgba(255, 176, 5, 0.3);
}

.color-overlay > article {
  color: #ffffff;
  position: absolute;
  margin-top: 20%;
}

.color-overlay > article > h1 {
  font-size: 4em;
}

.color-overlay > article > p {
  font-size: 1.5em;
}
</style>
