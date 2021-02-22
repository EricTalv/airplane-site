<template>
  <div class="container-fluid p-0 m-0">
    <nav style="padding: 3rem;" class="navbar navbar-expand-lg navbar-light bg-light">

      <a class="navbar-brand" href="#">
        <fa icon="plane-departure" class="fa-sm"></fa>
        Airship
      </a>

      <!-- visible only on sizing-->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">PRICING</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ABOUT</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">CONTACT</a>
          </li>
        </ul>
      </div>
      <span class="nav-item">
          <fa icon="comment-dots" class="fa-2x"></fa>
        </span>
    </nav>


  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss" scoped>
  .navbar-nav {

    .nav-item {
      font-family: Roboto, sans-serif;
    }

  }
</style>
