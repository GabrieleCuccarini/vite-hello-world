<script>
export default {
     data() {
       return {
            data: {
            img: "./jumbotron.jpg"
            }
        }
     }
}
</script>

<template>
    <img src="./jumbotron.jpg" alt="test">
</template>

<style>

    img {
    position: absolute;
    top: 10vh;
    left: calc(50% - 40vw);
    width: 80vw;
    height: 80vh;
    }
    
</style>
