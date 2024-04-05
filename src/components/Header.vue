<script>
import { store } from '../data/store'
export default {
  data(){
    return{
      store
    }
  }
 
}
</script>

<template >

  <div class=" container  d-flex  justify-content-between ">
    <div>
      <h1 class=" text-center  mb-3 "> vite rick & morty</h1>
    </div>
    
    <div>
      <div class="input-group mb-3">
    <input v-model="store.nameToSerach" 
    type="text" class="form-control" 
    placeholder="cerca personaggio "
     aria-label="Recipient's username" 
     aria-describedby="basic-addon2">
    <button @click="$emit('startSearch')" class="input-group-text  btn btn-warning" id="basic-addon2">cerca</button>
  </div>
    </div>
  </div>

  
</template>

<script lang="scss" scoped>

</script>