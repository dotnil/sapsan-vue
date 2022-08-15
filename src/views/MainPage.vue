<template lang="pug">
.main-page
  HeaderBar
  .main-page__services
    h1.main-page__title КОМПЛЕКСНЫЕ СИСТЕМЫ БЕЗОПАСНОСТИ
    ListOfServices
  OurProjects
  ProjectCounter
  .main-page__costomer-reviews ОТЗЫВЫ НАШИХ КЛИЕНТОВ
  .main-page__slider-order-the-service ЗАКАЗАТЬ УСЛУГУ
  .main-page__licenses Лицензированное производство
  .main-page__list-of-partners НАШИ ПАРТНЕРЫ
  .main-page__footer О КОМПАНИИ
</template>

<script setup>
import { reactive } from 'vue'
import HeaderBar from '@/components/HeaderBar.vue'
import ListOfServices from '@/components/ListOfServices.vue'
import OurProjects from '@/components/OurProjects.vue'
import ProjectCounter from '@/components/ProjectCounter.vue'

</script>

<style>
.main-page
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  background: rgba(11, 41, 53, 0.5)

.main-page__services
  max-width: 100vw
  height: 100%

.main-page__title
  font-weight: 300
  text-align: center
  font-size: 10vw

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
