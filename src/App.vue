<script>
import AppTitle from "./components/AppTitle.vue"
import Jumbotron from "./components/Jumbotron.vue"
export default {
  components:{
    AppTitle,
    Jumbotron
  },
  data(){
        return{

        }
      }
}
     
</script>

<template>
<AppTitle/>
<Jumbotron/>
</template>

<style>
.container{
  width: 100%;
}
</style>