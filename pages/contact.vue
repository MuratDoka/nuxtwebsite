<template>
<div>

  <div class="py-4 bg-warning">
    <div class="container text-center">
      <h3>Contact Us</h3>
    </div>
  </div>

  <!-- Contact Start -->
  <div class="py-5">
    <div class="container">
      <div class="row">

        <div class="col-md-8">
          <h1 class="main-heading">If you have any questions?</h1>
          <h4>Please reach out us at contact"example.com</h4>
        </div>

        <div class="col-md-4 text-center my-auto">
          <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary">Contact Us</NuxtLink>
        </div>

      </div>
    </div>
  </div>
  <!-- Contact End -->
</div>
</template>

<script>
export default {
  name: 'ContactPage',
  head() {
    return {
      title: 'Contact Page',
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
