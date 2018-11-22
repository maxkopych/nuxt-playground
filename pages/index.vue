<template>
  <section class="container">
    <h1>Hello I'm first Nuxt app</h1>
    <nuxt-link to="/user">USER</nuxt-link>
  </section>
</template>

<script>

export default {
  name: "app"
}
</script>

<style>

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}
</style>
