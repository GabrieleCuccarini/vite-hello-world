<script>
export default {
     data() {
       return {
            title: "La mia prima app con Vite"
        }
     }
}
</script>

<template>
  <h1>{{title}}</h1>
</template>

<style scoped>

h1 {
    color: mediumvioletred;
    position: absolute;
    top: 100px;
    left: 20vw;
    z-index: 2;
    font-size: 3.2em;
    line-height: 1.1;
  }  
</style>
