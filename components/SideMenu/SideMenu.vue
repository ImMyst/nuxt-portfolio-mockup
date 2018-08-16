<template>
  <aside>
    <nuxt-link class="avatar" to="/" tag="a">
      <div class="avatar-image" :style="{backgroundImage: 'url(' + image + ')'}"></div>
    </nuxt-link>
    <nav>
      <ul>
        <nuxt-link to="/" tag="li">
          <a>About</a>
        </nuxt-link>
        <nuxt-link to="/experience" tag="li">
          <a>Experience</a>
        </nuxt-link>
        <nuxt-link to="/education" tag="li">
          <a>Education</a>
        </nuxt-link>
        <nuxt-link to="/skills" tag="li">
          <a>Skills</a>
        </nuxt-link>
        <nuxt-link to="/interests" tag="li">
          <a>Interests</a>
        </nuxt-link>
        <nuxt-link to="/awards" tag="li">
          <a>Awards</a>
        </nuxt-link>
      </ul>
    </nav>
  </aside>
</template>

<script>
  module.exports = {
    data: function () {
      return {
        image: "https://images.pexels.com/photos/247885/pexels-photo-247885.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
      }
    }
  }

</script>


<style lang="scss" scoped>
  aside {
    position: fixed;
    height: 100vh;
    width: 17rem;
    top: 0;
    left: 0;
    float: left;
    background-color: #e3593f;

    .avatar {
      margin-top: 15rem;
      display: flex;
      justify-content: center;
      padding: 1.5rem;
      border-radius: 50%;
    }

    .avatar-image {
      width: 150px;
      height: 158px;
      object-fit: cover;
      background-size: cover;
      background-position: center;
      border-radius: 50%;
      border: 8px solid #e97f6b;
    }

    ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      li {
        height: 100%;
        display: flex;
        align-items: center;
        text-align: center;
        width: 87%;

        a {
          width: 100%;
          text-transform: uppercase;
          text-decoration: none;
          font-weight: 800;
          line-height: 1.5;
          letter-spacing: .05rem;
          color: rgba(255, 255, 255, .5);
          padding: 0.5rem 1rem;
          &:hover,
          &:active {
            color: rgba(255, 255, 255, .7)
        }
        }
      }
      .nuxt-link-exact-active a {
        color: white;
      }
    }
  }

</style>
