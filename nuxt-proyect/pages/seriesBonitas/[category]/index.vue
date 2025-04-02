<script setup>
    const route = useRoute();
    const category = route.params.category;
   
</script>
<template>
   <h1>Categoria: {{ category }}</h1>
   <h3>Lista de episodios:</h3>
    <ul>
        <li>
            <NuxtLink :to="`/seriesBonitas/${category}/spiderman`">Episodio 1</NuxtLink>
        </li>
    </ul>
</template>


<style lang="scss" scoped>

</style>