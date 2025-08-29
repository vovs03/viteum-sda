<script setup lang="ts">
    import SitePage from './SitePage.vue';
    import NavPage from './NavPage.vue';
    import FooterInfo from './FooterInfo.vue';
    import LogoEl from './LogoEl.vue';

</script>

<template>
<div id="main_page">
  <header>
    <div>
      <LogoEl />
    </div>
  </header>

  <nav>
    <div>
      <NavPage />
    </div>
  </nav>

  <main>
    <!-- <div>This is the main content.</div> -->
    <!-- <section>
      <div>This is a section.</div>
    </section> -->
    <article>
      <div>
        <SitePage />
      </div>
    </article>
    <!-- <aside>
      <div>This is an aside.</div>
    </aside> -->
  </main>
  
  <footer>
    <div>
      <FooterInfo />
    </div>
  </footer>

</div>
</template>

<style>
header {
  background-color: var(--color-blue-900);
  width: 100%;
  & {
    @apply
    flex
    flex-col
    justify-center
    items-center
  }
}

nav {
  width: 100%;
  & {
    @apply
    flex
    flex-col
    justify-center
    items-center
  }
}

#main_page {
    display: flex;
    flex-direction: column;
    /* justify-content: space-between; */
    align-items: center;
}

</style>