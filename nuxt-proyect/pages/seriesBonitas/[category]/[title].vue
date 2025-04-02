<script setup>
    const route = useRoute();
    const title = route.params.title;
    const category = route.params.category;
</script>

<template>
    <h1>La categoria es: {{ category }}</h1>
    <h3>Episodios de: {{ title }}</h3>
    <p>Episodio 1</p>
    <p>Episodio 2</p>
</template>

<style lang="scss" scoped>

</style>