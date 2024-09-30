<template>
  <div class="weather">
    <div class="container">

      <div class="card weather-form">
        <input type="text" class="weather-form__input" placeholder="введите город">
        <button class="weather-form__btn">Показать</button>
      </div>

      <div class="weather-info">
        <div class="weather-info__text">
          <p class="card">Санкт-Петербург</p>
          <p class="card">15</p>
          <p class="card">Дождь</p>
        </div>
      </div>

    </div>

    <div class="weather-bg">
      <img class="weather-bg__img bg" src="./assets/default.jpg" alt="app background">
      <img class="weather-bg__img sun" src="./assets/sun.jpg" alt="sunny">
      <img class="weather-bg__img rain" src="./assets/rain.jpg" alt="rain">
      <img class="weather-bg__img snow" src="./assets/snow.jpg" alt="snow">
    </div>
  </div>
</template>

<script>

</script>