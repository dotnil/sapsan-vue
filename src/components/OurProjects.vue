<template lang="pug">
.our-projects
  .our-projects__title НАШИ ПРОЕКТЫ

  .our-projects__customer
    .our-projects__customer-logo
      img.our-projects__customer-logo-img(src='/src/assets/customer-logo-vedogon-teatr.png')
    .our-projects__customer-name Ведогонь-театр
    .our-projects__customer-underlining

  .our-projects__customer
    .our-projects__customer-logo
      img.our-projects__customer-logo-img(src='/src/assets/customer-logo-kim.png')
    .our-projects__customer-name Делтэк (магазин 'КиМ')
    .our-projects__customer-underlining

  .our-projects__customer
    .our-projects__customer-logo
      img.our-projects__customer-logo-img(src='/src/assets/customer-logo-medial-apteka.jpg')
    .our-projects__customer-name Аптеки 'МЕДИАЛ'
    .our-projects__customer-underlining


  .our-projects__all-projects
    .our-projects__all-projects-link ПОСМОТРЕТЬ ВСЕ
    img.our-projects__all-projects-icon-arrow(src='/src/assets/icons/arrow-right.svg')

</template>

<style>
.our-projects
  height: 100%
  background-color: #ffffff
  display: flex
  flex-direction: column
  align-items: center
  width: 90vw

.our-projects__title
  font-size: 8vw
  font-weight: 600
  color: #0f3443
  padding: 40px 0

.our-projects__customer
  padding-bottom: 10vw

.our-projects__customer-logo-img
  width: 80vw

.our-projects__customer-name
  font-size: 4vw
  font-weight: 600
  color: #0f3443
  padding: 12px 2px
  cursor: pointer

.our-projects__customer-underlining
  width: 120px
  border-style: solid
  border-width: 2px 0 0 0
  border-image-source: linear-gradient(to right, rgba(255, 255, 255, 0), #33e79e 49%, rgba(255, 255, 255, 0))
  border-image-slice: 1

.our-projects__all-projects
  display: flex
  align-items: center
  font-size: 5vw
  padding: 10vw 0
  cursor: pointer

.our-projects__all-projects :hover
  color: #33e79e

.our-projects__all-projects-link
  color: #0f3443

.our-projects__all-projects-icon-arrow
  height: 6vw
  margin-left: 20px

</style>
