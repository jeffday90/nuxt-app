<template>
    <section class="container">
      <h1>Hello, This is jeff in the app now FUCK</h1>
      <nuxt-link to="/users">Users</nuxt-link>
      <nuxt-link to="/products">Products</nuxt-link>

    </section>


</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
