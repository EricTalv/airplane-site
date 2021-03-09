<template>

  <div
    class="row about p-5 flex-column-reverse flex-md-row"
    :class="{
                 'flex-column-reverse flex-md-row': reorder,
           } ">
    '
    <div class="col-md-6 col-sm-12 about-img-wrapper">
      <img :src="require(`~/assets/images/${image}`)" alt="">
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
export default {
  props: ['title', 'description', 'reorder', 'image'],
  data() {
    return {}
  }
}
</script>
