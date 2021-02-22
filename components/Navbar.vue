<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">

    <!-- visible only SM size-->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <a class="navbar-brand" style="color: #505050" href="#">
      <fa icon="plane-departure" class="fa-sm"></fa>
      <b>Airship</b>
    </a>

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
    <span class="action-btn nav-item d-none d-sm-block">
          <a href="">
            <fa icon="comment-alt" class="fa-2x"></fa>
          </a>
      </span>
  </nav>

</template>

<style lang="scss" scoped>

  $brand-color: #505050;

  nav {

    padding: 3rem;

    .navbar-brand {
      font-size: 2rem;
      color: $brand-color;
    }
    .navbar-nav {
      font-size: 1.3rem;

      .nav-item {
        font-family: Roboto, sans-serif;
      }
    }
    .action-btn {
      a {
        color: $brand-color;
      }
    }
  }
</style>
