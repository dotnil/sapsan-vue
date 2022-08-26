<template lang="pug">
.service-order
  .service-order__title ЗАКАЗАТЬ УСЛУГУ

  form.service-order__contact
    .service-order__contact-title НАПИСАТЬ НАМ
    .service-order__contact-description
      | У вас остались вопросы?
      br
      | Мы вам поможем!

    span.service-order__contact-name
      label.service-order__contact-name-label(for='name') Имя
      input#name.service-order__contact-name-input(type='text')
    span.service-order__contact-address
      label.service-order__contact-address-label(for='address') Почтовый адрес
      input#address.service-order__contact-address-input(type='text')
    span.service-order__contact-message
      label.service-order__contact-message-label(for='message') Сообщение
      input#message.service-order__contact-message-input(type='text')

    .service-order__contact-button Отправить

    .service-order__nav
      .service-order__nav-button
      .service-order__nav-button
</template>

<style>
.service-order
  height: 100%
  background-color: #ffffff
  display: flex
  flex-direction: column
  align-items: center
  width: 90vw
  padding-bottom: 40px

.service-order__title
  font-size: 8vw
  font-weight: 600
  color: #0f3443
  padding: 40px 0

.service-order__contact
  background:  radial-gradient(circle at 85% -18%, #3bdb98, #20594a 25%, #034140 41%, #1a3844 56%, #21474b 73%, #4c7a7a 91%, #518581)
  display: flex
  flex-direction: column
  width: 82vw
  padding-bottom: 40px

.service-order__contact-button
  margin: 23% auto 0 25%
  width: initial
  padding: 7% 10%
  border: solid 1px #34e89e
  cursor: pointer
  font-weight: 300
  color: #0f3443
  background-color: #ffffff
  -webkit-box-shadow: 0 2px 15px 0 #34e89e
  height: auto
  -webkit-border-radius: 100px
  outline: none

.service-order__nav
  display: block
  margin: 10% auto 0 auto

.service-order__nav-button
  padding: 0
  width: 14px
  height: 14px
  border: solid 2px #ffffff
  background: none
  border-radius: 25.5px
  -webkit-box-shadow: 0 2px 15px 0 rgba(0, 0, 0, 0.5)
  cursor: pointer
</style>
