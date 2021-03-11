<template>
  <v-app>
      <Login/>
  </v-app>
  
</template>

<script>
import Login from './components/Login';

export default {
  name: 'App',

  components: {
    Login
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
