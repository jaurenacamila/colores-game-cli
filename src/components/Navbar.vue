<template>

  <section class="src-components-navbar">
    <div id="navigator">
      <button id="reset"> New colors</button>
      <span id="message"></span>
      <button id="easy">easy</button>
      <button id="hard" class="selected">hard</button>
    </div>
  </section>

</template>

<script lang="js">

  export default  {
    name: 'src-components-navbar',
    props: [],
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

  .src-components-navbar {
    background: #ffffff;
    height: 30px;
    text-align: center;
    margin: 0;
    margin-top: -30px;
  }

  #message {
    color: #ffffff;
    display: inline-block;
    width: 20%;
  }

  #messageBox {
  }

  .selected {
    background-color: steelblue;
    color: white;
  }

  button {
    border: none;
    background-color: white;
    font-family: "Montserrat", "Avenir";
    text-transform: uppercase;
    height: 100%;
    font-weight: 700;
    letter-spacing: 1px;
    color: steelblue;
    transition: all 0.3s;
    outline: none;
  }

  button:hover {
    color: white;
    background-color: steelblue;
  }

</style>
