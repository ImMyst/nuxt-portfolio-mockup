<template>
  <div>
    <SideMenu />
    <div class="main-content">
      <nuxt/>
    </div>
  </div>
</template>

<script>
import SideMenu from "@/components/SideMenu/SideMenu";

export default {
  components: {
    SideMenu: SideMenu
  }
};
</script>


<style lang="scss">
* {
  box-sizing: border-box;
}

body {
  font-family: "Muli", sans-serif;
  margin: 0;
}

h1,
h2,
h3,
.sub-heading {
  font-family: "Saira Extra Condensed", sans-serif;
  color: #343a40;
}

h1 {
  font-weight: 700;
}

p {
  color: #868e96;
}

a {
  text-decoration: none;
  color: white;
}

.text-primary {
  background: -webkit-linear-gradient(#ff4b2b, #ff416c);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.main-content {
  margin-left: 20rem;
  height: 100vh;
  max-width: 70rem;
  overflow: hidden;
  display: flex;
}
</style>

