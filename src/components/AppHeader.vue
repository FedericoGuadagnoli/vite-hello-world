<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            title: 'La mia prima app con Vite'
        }
    }
}
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
    </header>

</template>


<style scoped>
h1 {
    text-align: center;
    color: rgba(228, 12, 12, 0.767);
    font-size: 4rem;
    text-shadow: 2px 2px black
}
</style>