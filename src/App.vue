<template>
  <v-app>
      <Tab/>
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
        items: [
          {  icon: 'mdi-view-dashboard' },
          {  icon: 'mdi-forum' },
        ],
      }
    },
};
</script>
