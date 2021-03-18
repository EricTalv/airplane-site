<template>
  <div class="container-fluid p-0 m-0">

    <!--  nav  -->
    <navbar></navbar>
    <!-- nav end -->

    <!--  intro  -->
    <intro-section></intro-section>
    <!-- intro end -->

    <!-- about -->
    <section class="about-section">

      <row-text-img
        title="What we do"
        description="We enterprise level flight services and solutions for your business.
            Starting from simple pilot and crew recruitment to having your flying business lift off the ground."
        image="what-we-do.svg"
        contentRight

      ></row-text-img>

      <row-text-img
        title="Our background"
        description=" Since 1985 we have build and curated small businesses with state of the art
            solutions tailored to their needs and wishes.
            <br>
            <br>
            We believe in four-dimensional management mobility,
            our upgraded model now offers 21st Century logistical paradigm shifts."
        image="our-background.svg"

      ></row-text-img>

      <row-text-img
        title="The team"
        description="Our Team is comprised of 10 top level fight experts and enthusiasts.
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto, consequuntur doloribus est provident
            qui voluptatibus?"
        image="the-team.svg"
        contentRight

      ></row-text-img>

    </section>
    <!-- about end -->

    <!-- pricing -->
    <section>
      <div class="row d-flex flex-column justify-content-center align-items-center">
        <h1 class="pricing-title mb-5">Sign up Today!</h1>
        <div class="card-deck mb-3 text-center" style="width: 75%">
          <div class="card mb-4 box-shadow">
            <div class="card-header">
              <h4 class="my-0 font-weight-normal">Free</h4>
            </div>
            <div class="card-body">
              <h1 class="card-title pricing-card-title">$0 <small class="text-muted">/ mo</small></h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>10 users included</li>
                <li>2 GB of storage</li>
                <li>Email support</li>
                <li>Help center access</li>
              </ul>
              <button type="button" class="btn btn-lg btn-block btn-outline-primary">Sign up for free</button>
            </div>
          </div>
          <div class="card mb-4 box-shadow">
            <div class="card-header">
              <h4 class="my-0 font-weight-normal">Pro</h4>
            </div>
            <div class="card-body">
              <h1 class="card-title pricing-card-title">$15 <small class="text-muted">/ mo</small></h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>20 users included</li>
                <li>10 GB of storage</li>
                <li>Priority email support</li>
                <li>Help center access</li>
              </ul>
              <button type="button" class="btn btn-lg btn-block btn-primary">Get started</button>
            </div>
          </div>
          <div class="card mb-4 box-shadow">
            <div class="card-header">
              <h4 class="my-0 font-weight-normal">Enterprise</h4>
            </div>
            <div class="card-body">
              <h1 class="card-title pricing-card-title">$29 <small class="text-muted">/ mo</small></h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>30 users included</li>
                <li>15 GB of storage</li>
                <li>Phone and email support</li>
                <li>Help center access</li>
              </ul>
              <button type="button" class="btn btn-lg btn-block btn-primary">Contact us</button>
            </div>
          </div>
        </div>
      </div>

    </section>
    <!-- pricing end -->

    <!-- footer  -->
    <section></section>
    <!-- footer end -->


  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">


</style>

