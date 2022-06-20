<template>
  <div>
    <FirstPageVueCli></FirstPageVueCli>
  </div>
</template>

<script>
import FirstPageVueCli from './components/FirstPageVueCli.vue'


export default {
    data() {
        return {
            message: "HELLO VUE CLI!"
        };
    },
    components: { 
      FirstPageVueCli
   }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
