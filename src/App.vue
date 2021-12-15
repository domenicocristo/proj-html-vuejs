<template>
  <div id="app">
    <MyHeader :items="items"/>

    <MyMain/>

    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
  },
  data() {
    return {
      items: [
        {
          name: "HOME"
        },

        {
          name: "ABOUT"
        },

        {
          name: "PROJECTS"
        },

        {
          name: "PROCESS"
        },

        {
          name: "TESTIMONIALS"
        }
      ]
    }
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Avenir, Helvetica;
}
</style>