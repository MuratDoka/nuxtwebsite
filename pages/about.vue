<template>
<div>

  <div class="py-4 bg-warning">
    <div class="container text-center">
      <h3>About Us</h3>
    </div>
  </div>

  <AboutUs />

</div>
</template>

<script>
import AboutUs from '~/components/AboutUs.vue';

export default {
  name: 'AboutPage',
  components: {AboutUs},
  head() {
    return {
      title: 'About page',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'NUXTJS Website'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Vue, nuxt, JavaScript'
        }
      ]
    }
  }
}
</script>
