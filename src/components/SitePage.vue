<script setup lang="ts">
    import AddressInfo from './AddressEl.vue';
    import { onMounted } from 'vue';
    import SabbathShedule from './SabbathShedule.vue';

    
{
    // Просто указываем имя компонента вручную
    const componentName = 'SitePage'

    onMounted(() => {
        console.log(`Компонент 4️⃣ ${componentName} - успешно подключен`)
    })
}
</script>

<template>

<section class="flex col-3">
    <!-- Left block on Desktop :-->
    <AddressInfo class="col-1 w-[15%]"/>

    <!-- Central block on Desktop :-->
     <main>
        <div class="flex-row flex-2 h-155">
            <h1 class="bg-lime-300"> Site Page!</h1>
            <div>
                Hello words!
            </div>
            <!-- Carousel Slider -->
            <div>
                Slider
            </div>
        </div>
     </main>


    <!-- Right block on Desktop :-->
    <div class="flex-row flex-1 h-85">
        <div>
            <div>
                <SabbathShedule />
            </div>
        </div>
    </div>
</section>
</template>

<style>

</style>