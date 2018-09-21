<template>
  <div id="app">
    <router-view />

    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: [
    Footer
  ]
}
</script>

<style lang="sass">
  body
    margin: 0

  .container
    padding-right: 15px
    padding-left: 15px
    margin-right: auto
    margin-left: auto

  .row
    display: flex
    .col-2-4
      width: 20%
    .col-3
      width: 25%
    .col-4
      width: 33.33%
    .col-6
      width: 50%

  .img-circle
    border-radius: 50%

  .btn
    border: none
    padding: 10px 20px
    color: #fff

    &.btn-green
      background: green

    &:hover
      background: #000

  @media (min-width: 768px)
    .container 
      width: 750px

  @media (min-width: 992px)
    .container 
      width: 970px

  @media (min-width: 1200px)
    .container
      width: 1170px
</style>
