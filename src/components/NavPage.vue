<script setup lang="ts">
import { onMounted } from 'vue'
{
    // Просто указываем имя компонента вручную
    const componentName = 'NavPage'

    onMounted(() => {
        console.log(`Компонент 2️⃣ ${componentName} - успешно подключен`)
    })
}

</script>

<template>
  <!-- 2️⃣ <NavPage /> -->
  <section>
    <div id="nav_panel" class="bg-blue-800 text-white text-lg px-4 flex hidden sm:block">
      <ul>
        <li>
          <a href="/src/pages/AdventistInfo.vue">Кто такие Адвентисты</a>
        </li>
        <span>|</span>
        <li>
          <a href="/src/pages/ChurchPro">О нашей общине</a>
        </li>
        <span>|</span>
        <li>
          <a href="/src/pages/SermonsInfo.vue">Духовные материалы</a>
        </li>
        <span>|</span>
        <li>
          <a href="/src/pages/MusicInfo.vue">Христианская музыка</a>
        </li>
        <span>|</span>
        <li>
          <a href="/src/pages/VideoLive.vue">Видеотрансляции</a>
        </li>
        <span>|</span>
        <li alt="English version this website. Английская версия сайта.">🇬🇧 English</li>
      </ul>
    </div>
  </section>
</template>

<style>

/* #nav_panel {
    @apply
    fixed
    z-50
} */
span {
  color: rgb(127, 127, 127);
}
ul {
  display: flex;
  justify-content: space-between;
  list-style: none;
  padding: 0;
  margin: 0;

}

li {
  font-size: medium;

  & {
    @apply inline-block px-[8px]
  }
  @media (max-width: 320px) {
    & {
      font-size: small;
    }
  }
  @media (min-width: 320px) {
    & {
      font-size: small;
    }
  }
  @media screen and (min-width: 768px) {
    & {
      font-size: medium;
    }
  }
  @media screen and (min-width: 1024px) {
    & {
      font-size: medium;
    }
  }
  
  @media screen and (min-width: 1024px) {
    & {
      @apply
      flex
      flex-col
      items-center
      justify-center
      /* w-[100px] */
  }
  }

  /* @apply inline-block px-[8px] */
}
</style>
