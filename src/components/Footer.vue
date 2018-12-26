<template>
  <div>
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.6.3/css/all.css"
      integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/"
      crossorigin="anonymous"
    >
    <footer class="footer">
      <div class="columns is-centered">
        <div class="column is-one-third">
          <h1 class="is-size-4-touch footer-title">Reach out to me below</h1>
        </div>
      </div>
      <div class="social-icons">
        <p class="field">
          <a class="button is-medium" href="https://twitter.com/davielee" target="_blank">
            <span class="icon is-small">
              <i class="fab fa-twitter fa-2x"></i>
            </span>
          </a>
          <a class="button is-medium" href="https://www.linkedin.com/in/davielee" target="_blank">
            <span class="icon is-small">
              <i class="fab fa-linkedin-in fa-2x"></i>
            </span>
          </a>
          <a class="button is-medium" href="https://github.com/davie-lee" target="_blank">
            <span class="icon is-small">
              <i class="fab fa-github fa-2x"></i>
            </span>
          </a>
          <a
            class="button is-medium"
            href="https://www.quora.com/profile/Davie-Lee-2"
            target="_blank"
          >
            <span class="icon is-small">
              <i class="fab fa-quora fa-2x"></i>
            </span>
          </a>
          <a class="button is-medium" href="https://www.instagram.com/davie.lee/" target="_blank">
            <span class="icon is-small">
              <i class="fab fa-instagram fa-2x"></i>
            </span>
          </a>
          <a class="button is-medium" href="mailto:davie@townfolio.ca">
            <span class="icon is-small">
              <i class="far fa-envelope fa-2x"></i>
            </span>
          </a>
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background-color: #ee5253;
}

.button {
  margin-left: 10px;
  margin-right: 10px;
  background-color: transparent;
  border: none;
}

.footer-title {
  color: #ffffff;
  font-size: 20px;
}

.fab {
  color: #ffffff;
}

.far {
  color: #ffffff;
}
</style>
