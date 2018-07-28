<template>
  <div class="container h-100">
    <div class="row align-items-center h-100">
      <div class="col-12 mx-auto">
        <div class="jumbotron text-center">
          <app-logo/>
          <h1 class="display-4">nuxt-bootstrap-boilerplate</h1>
          <p class="lead">Nuxt.js project + Bootstrap CSS Framework</p>
          <p class="lead">
            <a
              href="https://getbootstrap.com/"
              role="button"
              target="_blank"
              class="btn btn-primary btn-lg">Bootstrap Documentation</a>
            <a
              href="https://github.com/twbs/bootstrap"
              role="button"
              target="_blank"
              class="btn btn-primary btn-lg">Bootstrap GitHub</a>
          </p>
          <p class="lead">
            <a
              href="https://nuxtjs.org/"
              role="button"
              target="_blank"
              class="btn btn-success btn-lg">Nuxt.js Documentation</a>
            <a
              href="https://github.com/nuxt/nuxt.js"
              role="button"
              target="_blank"
              class="btn btn-success btn-lg">Nuxt.js GitHub</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>
<style>
#__layout {
  height: 100vh;
}
.jumbotron {
  background-color: #fff;
}
</style>

