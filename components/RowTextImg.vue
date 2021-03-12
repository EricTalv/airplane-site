<template>

  <div
    class="row m-5 flex-column-reverse"
    :class="[ contentRight ? 'flex-md-row' : 'flex-md-row-reverse' ]

    ">
    <div class="col-md-6 col-sm-12 about-img-wrapper">
      <img :src="require(`~/assets/images/${image}`)" alt="">
    </div>

    <div class="col-md-6 col-sm-12 about-text-center">
      <h2 class="about-title ">{{ title }}</h2>
      <p class="about-p text-muted" v-html="description">
      </p>
    </div>

  </div>

</template>

<!--
 If True - Images will be below on SM screen and on the RIGHT of text on MD screen
-->

<script>
export default {
  props: {
    title: String,
    description: String,
    image: String,
    contentRight: Boolean,
  },
}
</script>
