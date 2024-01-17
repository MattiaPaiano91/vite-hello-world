<script>
  export default {
    data() {
      return {
        message: "La mia prima app con Vite!"
      };
    },
  }
</script>

<template>
  <div>
    <header>
      <h1>{{ message }}</h1>
    </header>
  </div>
 
</template>

<style scoped>
    header{
      height: 200px;
      width: 100%;
      background-color: darkgray;
      text-align: center;
      line-height: 200px;
    }
</style>
    

