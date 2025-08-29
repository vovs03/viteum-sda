<script setup lang="ts">
import { onMounted } from 'vue'
{
    // Просто указываем имя компонента вручную
    const componentName = 'SabbathShedule'

    onMounted(() => {
        console.log(`Компонент 5️⃣ ${componentName} - успешно подключен`)
    })
}
</script>

<template>

<section class="flex">

    <div class="m-0 ">
        <h1 class="bg-blue-300"> Sabbath Shedule:</h1>
    </div>
</section>
</template>

<style>

</style>