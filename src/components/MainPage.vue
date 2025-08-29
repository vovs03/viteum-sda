<script setup lang="ts">
    import SitePage from './SitePage.vue';
    import NavPage from './NavPage.vue';
    import FooterInfo from './FooterInfo.vue';
    import LogoEl from './LogoEl.vue';

</script>

<template>
    <LogoEl />
    <NavPage class="nav_page"/>
    <SitePage />
    <FooterInfo />

    <section>
        <!-- <div class="grid">Grid-контейнер</div>
        <div class="grid-cols-3">Сетка с 3 колонками
            <div class="bg-amber-600">Элемент в 3 колонках</div>
            <div class="bg-blue-400">Элемент в 3 колонках</div>
            <div class="bg-green-400">Элемент в 3 колонках</div>

        </div>
        <div class="grid-cols-12">Сетка с 12 колонками
            <div class="grid col-span-6 bg-amber-600">Элемент в 6 колонках</div>
            <div class="col-span-6 bg-blue-400">Элемент в 6 колонках</div>

        </div>
        <div class="grid-rows-4">Сетка с 4 строками</div> -->
    </section>
</template>

<style>
/* .nav_page {
    background-color: #000000;
    color: #ffffff;
    padding: 0px;
    font-size: 20px;
    @apply text-center;
    /* @media (max-width: 320px) {
    
        font-size: 1rem;
        font-weight: 300;
        margin: 0;
        color: #ffffff;
    } */
/* } 
*/
</style>