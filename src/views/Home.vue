<template>
  <div>
    <section class="hero is-white has-text-centered is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered">
            <div class="column">
              <h1
                class="title is-spaced is-size-1-desktop is-size-2-tablet is-size-3-mobile"
              >Entrepreneur, Developer &amp; Data Geek</h1>
              <h2 class="subtitle is-size-4-desktop">I build things for fun, and love doing it.</h2>
              <img class="avatar" src="@/assets/avataaars.svg">
            </div>
          </div>
        </div>
      </div>
    </section>

    <Blurb/>
    <Media/>
  </div>
</template>

<script>
import Media from "@/components/Media.vue";
import Blurb from "@/components/Blurb.vue";

export default {
  components: {
    Media,
    Blurb
  }
};
</script>

<style>
</style>
