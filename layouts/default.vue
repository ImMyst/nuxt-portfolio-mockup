<template>
  <div>
    <SideMenu />
    <main class="main-content">
      <nuxt/>
    </main>
  </div>
</template>

<script>
import SideMenu from '@/components/SideMenu/SideMenu'

export default {
  components: {
    SideMenu: SideMenu
  }
}
</script>


<style lang="scss">
  * {
    box-sizing: border-box;
  }

  body {
    font-family: "Muli", sans-serif;
    margin: 0;
  }

  .main-content {
    margin-left: 20rem;

  }
</style>

