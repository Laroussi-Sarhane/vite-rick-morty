<script>
import card from './partials/card.vue';
import {store} from '../data/store'
export default {
  components:{
   card
  },
  data(){
    return{
      store 
    }
  }
 
}
</script>

<template>
  <div class="container">
    <card />

  </div>
  
</template>

<script lang="scss" scoped>

</script>