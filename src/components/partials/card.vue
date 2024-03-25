<script>
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
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
   
  </div>
</div>
</template>

<script lang="scss" scoped>

</script>