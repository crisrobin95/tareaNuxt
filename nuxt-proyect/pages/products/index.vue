
<script setup lang="ts">
import { useRouter } from 'nuxt/app';
import { onMounted } from 'vue';

const router = useRouter();

onMounted(() => {
  router.push('/');
});
</script>

<template>
  <div>
    <p>Redirigiendo a la página de inicio...</p>
  </div>
</template>