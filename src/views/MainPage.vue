<template lang="pug">
.main-page
  HeaderBar()
  .main-page__menu
    h1 КОМПЛЕКСНЫЕ СИСТЕМЫ БЕЗОПАСНОСТИ
    ul.main-page__menu-list
      li.main-page__menu-item СИСТЕМЫ КОНТРОЛЯ И УПРАВЛЕНИЕ ДОСТУПОМ
      li.main-page__menu-item ПОЖАРНАЯ СИГНАЛИЗАЦИЯ
      li.main-page__menu-item ЭЛЕКТРОЛАБОРАТОРИЯ
      li.main-page__menu-item ДОМОФОНИЯ
      li.main-page__menu-item ВИДЕОНАБЛЮДЕНИЕ
      li.main-page__menu-item ОХРАННАЯ СИГНАЛИЗАЦИЯ
  .main-page__banner-stretching НАШИ УСЛУГИ
  .main-page__our-projects НАШИ ПРОЕКТЫ
  .main-page__project-counter НАМИ СДЕЛАНО
  .main-page__costomer-reviews ОТЗЫВЫ НАШИХ КЛИЕНТОВ
  .main-page__slider-order-the-service ЗАКАЗАТЬ УСЛУГУ
  .main-page__licenses Лицензированное производство
  .main-page__list-of-partners НАШИ ПАРТНЕРЫ
  .main-page__footer О КОМПАНИИ
</template>

<script setup>
import { reactive } from 'vue'
import HeaderBar from '@/components/HeaderBar.vue'

</script>

<style>
.main-page
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  background: rgba(11, 41, 53, 0.5)

.main-page__menu
  padding: 0px 1ch


.main-page__menu-list
  list-style-type: none

.main-page__menu-item

.main-page__banner-stretching
  height: 80vh

.main-page__our-projects
  height: 80vh

.main-page__project-counter
  height: 80vh

.main-page__costomer-reviews
  height: 80vh

.main-page__slider-order-the-service
  height: 80vh

.main-page__licenses
  height: 80vh

.main-page__list-of-partners
  height: 80vh

.main-page__footer
  height: 80vh
</style>
