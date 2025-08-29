<script setup lang="ts">

</script>

<template>
  <div id="first_world" class="rounded-[8px] shadow-2xs ">
    <p>Сердечно приветствуем вас <br />на сайте общины <br/>христиан Адвентистов седьмого дня <br/>города Протвино!</p>
  </div>

</template>

<style scoped>
  #first_world {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: #202690;
    text-align: center;
    color: aliceblue;
    font-size: medium;
    width: 66%;

    @media screen and (max-width: 320px) {
      & {
        width: 100%;
      }
    }

    @media screen and (min-width: 320px) {
      & {
        flex-direction: column;
        height: max-content;
        
        
        width: 100%;
        padding: 4px 12px 4px 12px;
      }
    }

    @media screen and (min-width: 768px) {
      & {
        width: 66%;
      }
    }

    @media screen and (min-width: 1024px) {
      & {
        width: 100%;
        height: max-content;
        margin: 24px 24px 24px 24px;
        padding: 32px 48px 32px 48px;
      }
    }
  }

  p {
    @media screen and (max-width: 320px) {
      & {
        font-size: small;
      }
    }
    @media screen and (min-width: 320px) {
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
        font-size: large;
      }
    }
  }
</style>
