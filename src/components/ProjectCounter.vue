<template lang="pug">
.project-counter
  .project-counter__title НАМИ СДЕЛАНО

  ul.project-counter__list
    li.project-counter__item
      .project-counter__oval-frame
        .project-counter__oval
          .project-counter__oval-quantity 500
      .project-counter__item-name ПРОЕКТНЫХ И МОНТАЖНЫХ РАБОТ

    li.project-counter__item
      .project-counter__oval-frame
        .project-counter__oval
          .project-counter__oval-quantity 1234
      .project-counter__item-name ТЕХНИЧЕСКИХ ОБСЛУЖИВАНИЙ ОБЪЕКТОВ

    li.project-counter__item
      .project-counter__oval-frame
        .project-counter__oval
          .project-counter__oval-quantity 678
      .project-counter__item-name ИЗГОТОВЛЕНЫХ ПЛАНОВ ЭВАКУАЦИИ

    li.project-counter__item
      .project-counter__oval-frame
        .project-counter__oval
          .project-counter__oval-quantity 987
      .project-counter__item-name РАБОТ ПО ПОЖАРНОМУ ОБОРУДОВАНИЮ

</template>

<style>
.project-counter
  background-color: #ffffff
  display: flex
  flex-direction: column
  align-items: center
  width: 90vw
  padding-bottom: 40px

.project-counter__title
  font-size: 8vw
  font-weight: 600
  color: #0f3443
  padding: 40px 0

.project-counter__list
  list-style-type: none
  margin: 0
  padding: 0

.project-counter__item
  font-size: 4vw
  font-weight: 600
  color: #0f3443
  padding: 12px 2px
  cursor: pointer
  display: flex
  flex-direction: column
  align-items: center

.project-counter__oval-frame
  padding: 3px
  width: 50vw
  height: 50vw
  background-image: linear-gradient(to bottom, #32e59a, #0f3443)
  -webkit-border-radius: 50%

.project-counter__oval
  padding: 5vw
  width: 40vw
  height: 40vw
  background-color: #ffffff
  -webkit-border-radius: 50%

.project-counter__oval-quantity
  height: 14vw
  width: 30vw
  text-align: center
  padding: 13vw 5vw 13vw 5vw
  border-radius: 20vw
  font-size: 13vw
  font-weight: 400
  color: #344251
  background-color: #ffffff
  -webkit-box-shadow: 0 6px 15px 1px rgba(0, 0, 0, 0.2)
  -webkit-transition: 0.3s

.project-counter__item-name
  padding-top: 20px
  text-align: center
  font-size: 1.1em

</style>
