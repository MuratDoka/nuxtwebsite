<template>
<div>

  <div class="py-4 bg-warning">
    <div class="container text-center">
      <h3>Our Services</h3>
    </div>
  </div>

  <OurServices />
</div>

</template>

<script>
import OurServices from '~/components/OurServices.vue';

export default {
  name: 'ServicesPage',
  components: {OurServices},
  head() {
    return {
      title: 'Services Page',
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
