<script>
import {store} from '../../data/store'
export default {
  props:{
    name: String,
    status: String,
    gender: String,
    image: String
  }
 
}
</script>

<template>
  <div class="card mb-4 " style="width: 18rem;">
  <img :src="image" class="card-img-top" :alt="name">
  <div class="card-body">
    <h5 class="card-title">{{ name }}</h5>
    <p class="card-text">{{ gender }}</p>
    <p class="card-text">{{ status }}</p>
   
  </div>
</div>
</template>

<script lang="scss" scoped>

</script>