<template>
  <div class="container">
    <div>
      <h1>this all user page</h1>
      <input type="text" v-model="userId" placeholder="Enter User ID">
      <button @click="onLoadUser">Show User</button>
    </div>
  </div>
</template>

<script>
  export default {
    name: "user",
    data(){
      return {
       userId: ""
      }
    },
    methods: {
      onLoadUser(){
        this.$router.push("/user/"+this.userId);
      }
    }
  }
</script>

<style scoped>
  h1 {
    text-align: center;
  }
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
  }
</style>