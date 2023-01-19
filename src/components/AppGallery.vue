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
            const url = new URL(`../assets/img/${image}`,
                import.meta.url);
            return url.href;
        }
    }
}
</script>



<template>
    <figure>
        <img :src="buildImagePath(image)" alt="">
    </figure>
</template>


<style scoped>
figure {
    margin-top: 4rem;
    width: 100vw;
    text-align: center;
}

img {
    height: 500px;
    margin: 0 auto;
}
</style>