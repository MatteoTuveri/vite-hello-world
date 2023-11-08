
<template>
    <div>
        {{ msg }}
    </div>
</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            msg : 'La mia prima app con Vite!'
        }
    }
}
</script>


<style scoped>
div{
    text-align: center;
    margin: 20px;
    font-size: 2em;
}
</style>