<template>
  <section class="about">
    <h1>Clarence <span class="text-primary">Taylor</span></h1>
    <h3>3542 Berry Street · Cheweyenne Wells, CO 80810 · (317) 585-8469 · <nuxt-link to=":mailto:name@email.com" target="_blank" class="text-primary">name@email.com</nuxt-link></h3>
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .about {
    margin: auto 0 auto 0;
    margin-top: 18.5rem;
    h1 {
      margin: 0;
      text-transform: uppercase;
      font-size: 6rem;
      font-weight: 700;
      line-height: 5.5rem;
    }
    h3 {
      margin: 0;
      color: #868e96;
      text-transform: uppercase;
      font-size: 1.5rem;
      font-weight: 500;
    }
  }
</style>
