<script>
export default{
    data() {
        return {
            img : "https://mdbcdn.b-cdn.net/img/new/slides/041.webp"
        }
    }
}

</script>

<template>

<div class="jambotron">
    <img :src="img" alt="">
</div>
</template>

<style scoped>
/* style css */
.jambotron{
    width: 100%;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>
