<template>
  <router-view />
</template>

<style>
@font-face
  font-family: "Exo 2"
  src: url('@/assets/font/exo-2-variable.ttf') format('truetype')

body
  margin: 0

.app
  min-height: 100vh
  font-family: 'Exo 2', sans-serif
  background-image: linear-gradient(to top, #0c2a38, #1c6456 13%, rgba(88, 216, 166, 0.8) 50%, rgba(15, 52, 67, 0.81))
  color: #ffffff

a
  color: #808080
  text-decoration: none

a:hover
  color: #808080
</style>
