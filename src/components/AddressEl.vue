<script setup lang="ts">
import { onMounted } from 'vue'
{
    // Просто указываем имя компонента вручную
    const componentName = 'AddressEl'

    onMounted(() => {
        console.log(`Компонент 3️⃣ ${componentName} - успешно подключен`)
    })
}
</script>

<template>

<section id="Address_item" class="">

    <div class="bg-blue-300">
        <h1 class="bg-blue-300"> Address:</h1>
        <div class="">
            <!-- <ul class="">
                <li>Адрес молитвенного дома:</li>
                <li>Московская обл., го. Серпухов, г. Протвино,</li>
                <li>ул. Южная, д. 4, помещение 3</li>
                <li>Подробнее: тут</li>

            </ul> -->

            <p>Адрес молитвенного дома:</p>
            <p>Московская обл., го. Серпухов, г. Протвино,</p>
            <p>ул. Южная, д. 4, помещение 3</p>
            <p>Подробнее: тут</p>
        </div>
    </div>
</section>
</template>

<style>
#Address_item {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    align-content: center;
}
#Address_item p {
    font-size: x-small;
    display: flex;
    flex-direction: column;
    align-items: center;
    align-content: center;
    align-self: center;
    margin: 0px;
    padding: 0px;
    text-align: center;
    text-justify: center;
    text-align-last: center;
    flex-wrap: wrap;

    @media screen and (max-width: 320px) {
        & {
            font-size: x-small;
            display: flex;
            flex-direction: row;
            align-items: center;
            align-content: center;
    }
        
    }
}

li  {
    list-style: none;
    font-size: x-small;
    display: flex;
    flex-direction: column;
}
</style>