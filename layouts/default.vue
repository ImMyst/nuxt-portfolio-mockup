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
  body {
    font-family: "Muli", sans-serif;
  }
</style>

