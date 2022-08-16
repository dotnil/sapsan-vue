<template lang="pug">
.costomer-reviews
  .costomer-reviews__title ОТЗЫВЫ НАШИХ КЛИЕНТОВ
  .costomer-reviews__slider
    .costomer-reviews__slider-text Сработали быстро и профессионально. Бесплатно провели консультацию по недостаткам системы безопасности. Разрабатывали для нас план эвакуации.
    .costomer-reviews__slider-name Балиж Александр
    .costomer-reviews__slider-nav
      .costomer-reviews__slider-nav-button
      .costomer-reviews__slider-nav-button
      .costomer-reviews__slider-nav-button

</template>

<style>
.costomer-reviews
  height: 100%
  background-color: #ffffff
  display: flex
  flex-direction: column
  align-items: center
  width: 90vw
  padding-bottom: 40px

.costomer-reviews__title
  font-size: 8vw
  font-weight: 600
  color: #0f3443
  padding: 40px 0
  text-align: center

.costomer-reviews__slider
  font-size: 4.1vw
  font-weight: 400
  font-style: italic
  text-align: center
  color: #333b4d

.costomer-reviews__slider-name
  height: initial
  font-size: 1.3em
  text-align: center
  color: #bcbcbc
  margin-top: 24px
  font-style: initial

.costomer-reviews__slider-nav
  width: 100%
  margin: 6% auto 0 auto
  text-align: center
  padding: 5px
  display: inline-block

.costomer-reviews__slider-nav-button
  border: solid 2px
  color: rgb(100,100,100)
  padding: 0.2em
  -webkit-border-radius: 0.4em
  display: inline-block
  text-decoration: none
  cursor: pointer
  margin: 0 6px
  padding: 0.2em

.costomer-reviews__slider-nav-button:hover
  border: solid 2px #34e89e

</style>
