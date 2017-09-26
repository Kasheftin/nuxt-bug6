<template>
  <div class="container">
    <h1>Home page</h1>
    <p><nuxt-link to="/a/about">About page</nuxt-link></p>
    <p><nuxt-link to="/a/users">Lists of users</nuxt-link></p>
  </div>
</template>

<script>
export default {
  transition: 'slide-left'
}
</script>
