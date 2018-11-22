<template>
  <div class="container">
    <h1>Single User {{ $route.params.id }}</h1>
    <a href="javascript:history.back()">Go Back</a>
  </div>
</template>


<script>
  export default {
    name: "_id"
  }
</script>

<style scoped>
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
  }
</style>