<script setup lang="ts">
import { onMounted } from 'vue'
{
    // Просто указываем имя компонента вручную
    const componentName = 'FooterInfo'

    onMounted(() => {
        console.log(`Компонент 6️⃣ ${componentName} - успешно подключен`)
    })
}
</script>

<template>
<!-- 6️⃣ <FooterInfo /> -->
<section id="footer_id">

    <div>
        <h1 class="bg-blue-300"> Footer</h1>
    </div>
</section>
</template>

<style>
/* #footer_id {
    background-color: #000000;
    color: #ffffff;
    font-family: Arial, sans-serif;
    padding: 20px;
    text-align: center;
    font-size: 16px;
    margin: 0;
    width: 100%;
    height: 100%;
    @media (max-width: 320px) {
        font-size: 1.2rem;
        font-weight: 300;
        margin: 0;
        color: #ffffff;
        text-align: center;
    }
} */
</style>