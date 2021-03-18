<template>
  <v-card>
   

    <v-tabs vertical>
      <v-tab class="tab">
        <li class="list">
        <img width="30px" src="../assets/users.svg" style="margin: 0px auto; display: block;" alt="">
       Хувь хүн
        </li>
      </v-tab>
      <v-tab>
         <li class="list">
        <img width="30px" src="../assets/corporates.svg" style="margin: 0px auto; display: block" alt="">
       Байгууллага
        </li>
        
      </v-tab>
      <v-tab>
        <li class="list">
        <img width="30px" src="../assets/corporates.svg" style="margin: 0px auto; display: block" alt="">
       Мерчант
        </li>
        
      </v-tab>

      <v-tab-item>
              <Login/>
        
      </v-tab-item>
      <v-tab-item>
       
               <Login/>
      </v-tab-item>
      <v-tab-item>
           <Login/>
          
      </v-tab-item>
    </v-tabs>
   
  </v-card>
 
</template>

<script>
import Vuetify from 'vuetify'
import Login from './Login'
export default {

  vuetify: new Vuetify(),
   components: {
              Login
  },
  
};
</script>

<style scoped>

.list {

  list-style-type: none;
}
.v-tabs--vertical > .v-tabs-bar .v-tab{
  height: 70px;
}
.v-tabs--vertical > .v-tabs-bar .v-tab:active{
  color: green;
}

@media (max-width: 570px) {

}


</style>