<template>
  <section class="about">
    <h1>Clarence
      <span class="text-primary">Taylor</span>
    </h1>
    <h3>3542 Berry Street · Cheyenne Wells, CO 80810 · (317) 585-8468 ·
      <nuxt-link to=":mailto:name@email.com" target="_blank" class="text-primary">name@email.com</nuxt-link>
    </h3>
    <p>I am experienced in leveraging agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches
      to corporate strategy foster collaborative thinking to further the overall value proposition.</p>
    <div class="social-icons">
      <nuxt-link class="social" to="/">
        <i class="fab fa-linkedin-in"></i>
      </nuxt-link>
      <nuxt-link class="social" to="/">
        <i class="fab fa-github"></i>
      </nuxt-link>
      <nuxt-link class="social" to="/">
        <i class="fab fa-twitter"></i>
      </nuxt-link>
      <nuxt-link class="social" to="/">
        <i class="fab fa-facebook-f"></i>
      </nuxt-link>
    </div>
  </section>
</template>

<script>
  export default {

  }

</script>

<style lang="scss" scoped>
  .about {
    margin: auto 0 auto 0;
    margin-top: 20rem;
    animation: animSection .8s forwards 0s ease-in-out;

    @keyframes animSection{
    0%{
        transform: translateY(-5rem);
        opacity: 0;
        }
    100%{
        transform: rotate(xx) translateY(0);
        opacity: 1;
        }
    }
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
      margin-bottom: 3rem;
    }
    p {
      font-size: 1.15rem;
      line-height: 1.5rem;
      margin-bottom: 3rem;
    }
    .social {
      display: inline-block;
      height: 3.5rem;
      width: 3.5rem;
      border-radius: 50%;
      background-color: #495057;
      text-align: center;
      margin-right: 1.5rem;
      line-height: 3.9rem;
      &:hover {
        background-color: #e3593f;
      }
      i {
        font-size: 1.5rem;
      }

    }
  }

</style>
