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

    <div class="bg-blue-900">
        <!-- <div class="item">
            <img src="/src/assets/adventist-symbol--white.svg" alt="Утверждённый логотип церкви АСД" class="w-[128px] flex-1"></img>
        </div>
        
        <div>
            <h1 class="text-fuchsia-50 w-[512px] flex-1"><img src="/src/assets/adventist-ru_CH-text--white.svg"></img></h1>
        </div> -->
        
        <div id="header_logo" class="sm:flex text-fuchsia-50 w-[256px] md:flex]">
            <img src="/src/assets/adventist-ru_CH--white.svg" alt="Утверждённый логотип церкви АСД" class="w-[128px] flex-1"></img>
        </div>
    </div>
</section>
</template>

<style>
#header_logo {
    display: flex;
    flex-direction: row;
    justify-content:stretch;
    align-items: center;

    /* flex-wrap: wrap; */
    /* gap: 1rem; */
}
</style>