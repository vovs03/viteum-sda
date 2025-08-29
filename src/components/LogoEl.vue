<script setup lang="ts">
import { onMounted } from 'vue'

{
    // Просто указываем имя компонента вручную
    const componentName = 'LogoEl'

    onMounted(() => {
        console.log(`Компонент 1️⃣ ${componentName} - успешно подключен`)
    })
}
</script>

<template>

<section>

    <div>
        <h1 class="bg-blue-900 text-fuchsia-50"> Logo</h1>
    </div>
</section>
</template>

<style>

</style>