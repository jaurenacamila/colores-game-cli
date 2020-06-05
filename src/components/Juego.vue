<template>

  <section class="src-components-juego">
    <Header />
    <Navbar />
    <Cuadrado />
  </section>

</template>

<script lang="js">

  import Header from './Header.vue'
  import Navbar from './Navbar.vue'
  import Cuadrado from './Cuadrado.vue'

  export default  {
    name: 'src-components-juego',
    props: [],
    components: {
      Header,
      Navbar,
      Cuadrado
    },
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="css">

  .src-components-juego {
  }

</style>
