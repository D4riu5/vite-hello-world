<script>
export default {
    data() {
        return {
            logo: 'https://uploads.sitepoint.com/wp-content/uploads/2021/04/1618197067vitejs.png',
        }
    }
}
</script>

<template>
    <img class="my-2" :src="logo" alt="">
</template>

<style scoped>
img{
    width: 400px;
    aspect-ratio: 1.5/1;
}
</style>


