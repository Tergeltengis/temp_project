<template>
  <v-app>
      <Tab class="tab"/>
  </v-app>
  
</template>

<script>
// import Login from './components/Login';
import Tab from './components/Tab'
export default {
  name: 'App',

  components: {
    Tab
  },

     data () {
      return {
      
      }
    },
};
</script>

<style lang="scss" scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  padding: 3% 2% 3% 2%;
  text-align: center;

  box-sizing: border-box;
  height: 100%;
  .tab {
    box-shadow: 5px 5px 50px 50px rgba(0,0,0,0.2);
    height: 100vh;
    background: white;

  }
  
}

</style>