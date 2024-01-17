<script>
import AppTitle from './components/AppTitle.vue'
export default {
  data() {
    return {
      message:"Hello World! Questo dato è preso dall'app vue"
    };
  },
  components: {
    AppTitle
  }

}
</script>

<template>
  <div>
    <AppTitle/>
    <main>
      <h1>{{ message }}</h1>
    </main>
  </div>
</template>
 

<style scoped>
  main{
    width: 100%;
    text-align: center;
  }
</style>
