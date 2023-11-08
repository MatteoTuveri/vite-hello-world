<template>
  <div class="jumbotron">
    <h1>{{ title }}</h1>      
    <p>{{ paragraph }}</p>
  </div>
</template>

<script>
export default {
    name: 'AppHero',
    data() {
        return {
            title : 'La mia prima app con Vite!',
            paragraph : 'Hello Vite'
        }
    }
}
</script>


<style scoped>
.jumbotron{
    margin: auto;
    width: 40vw;
    height: 40vh;
    border-radius: 5px;
    background-image: url(/images/1_C8xdSMN_IkeXDsTLt6EACA.png);
    background-size: cover;
    background-position: center;
    text-align: center;
}

h1{
    font-size: 2em;
    text-transform: uppercase;
    color: antiquewhite;
}
p{
    font-size: 2em;
    text-transform: uppercase;
    color: antiquewhite;
}

</style>