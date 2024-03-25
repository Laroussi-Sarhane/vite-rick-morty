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

    <div class="row row-cols-4 ">

      <card v-for=" card in this.store.cardsList" 
      :key="card.id"
      :name="card.name"
      :status="card.status"
      :gender="card.gender"
      :image="card.image"
      
      />
      
       
    </div>

  </div>
  
</template>

<script lang="scss" scoped>

</script>