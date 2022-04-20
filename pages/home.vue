<template>
  <div>
    <h1>Home page</h1>
    <nuxt-link to="/about" class="btn btn-primary">About (internal link that belongs to the Nuxt App)</nuxt-link>
    <a href="https://nuxtjs.org">External Link to another page</a>

  </div>
</template>
<script>
export default {
  layout:"corelayout"
}
</script>
