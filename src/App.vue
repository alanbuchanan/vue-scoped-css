<template>
  <div id="app">
    <foo/>
    <bar/>
    <baz/>
  </div>
</template>

<script>
  import Foo from './components/Foo.vue'
  import Bar from './components/Bar.vue'
  import Baz from './components/Baz.vue'

  export default {
    components: {
      Foo,
      Bar,
      Baz
    }
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Arima+Madurai:900');

div {
  font-family: 'Arima Madurai', cursive;
  text-align: center;
}

</style>
