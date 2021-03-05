<template>

  <div class="row about p-5 flex-column-reverse flex-md-row">

    <div class="col-md-6 col-sm-12 about-img-wrapper">
      <img :src="'./../assets/images/' +  imgUrl " alt="">
    </div>

    <div class="col-md-6 col-sm-12 about-text-center">
      <h2 class="about-title ">{{ title }}</h2>
      <p class="about-p text-muted">
        {{ description }}
      </p>
    </div>

  </div>

</template>
<script>
 export default  {

 }
</script>
