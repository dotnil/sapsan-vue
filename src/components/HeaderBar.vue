<template lang="pug">
.header-bar
  .header-bar__menu
    img.header-bar__icon(src='@/assets/icons/menu.svg')
  .header-bar__logo
    img.header-bar__logo-img(src='@/assets/logo-sapsan.png')
  .header-bar__call
    img.header-bar__icon(src='@/assets/icons/call.svg')

</template>

<style>
.header-bar
  width: 100%
  display: flex
  justify-content: space-between
  background-color: rgba(24, 57, 74, 0.5)
  align-items: center
  position: sticky
  top: 0

.header-bar__icon
  min-height: 38px
  margin: 4vw

.header-bar__logo-img
  height: 50px

</style>
