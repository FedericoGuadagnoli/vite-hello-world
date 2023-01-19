<script>
export default {
    name: 'AppGallery',
    data() {
        return {
            image: 'elden-ring-ranni.jpg'
        }
    },

    methods: {
        buildImagePath(image) {
            const url = new URL(`../assets/img/${image}`, url);
            return url.href;
        }
    }
}
</script>



<template>
    <img :src="buildImagePath(image)" alt="">
</template>


<style>

</style>