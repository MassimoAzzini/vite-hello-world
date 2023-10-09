  <script>
  export default {
    name: 'AppTitle',
    data() {
      return {
        title: 'HELLO VITE'

      }
    },
  
  }

  </script>


<template>

<div class="bg">
  
  <h1>{{ title }}</h1>

</div>

</template>


<style scoped>
h1 {
  font-size: 3rem;
  color: red;
  text-align: center;
}

.bg {
  background-color: #255ee9;

}

</style>