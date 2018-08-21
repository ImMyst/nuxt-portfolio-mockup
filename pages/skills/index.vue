<template>
<section class="skills">
  <h2>Skills</h2>
  <p class="lead">Programming Languages & Tools</p>
  <div class="icons">
    <i class="fab fa-html5 fa-3x"></i>
    <i class="fab fa-css3-alt fa-3x"></i>
    <i class="fab fa-js-square fa-3x"></i>
    <i class="fab fa-angular fa-3x"></i>
    <i class="fab fa-react fa-3x"></i>
    <i class="fab fa-node-js fa-3x"></i>
    <i class="fab fa-sass fa-3x"></i>
    <i class="fab fa-less fa-3x"></i>
    <i class="fab fa-wordpress fa-3x"></i>
    <i class="fab fa-gulp fa-3x"></i>
    <i class="fab fa-grunt fa-3x"></i>
    <i class="fab fa-npm fa-3x"></i>
  </div>
  <p class="lead">Workflow</p>
  <ul>
    <li><i class="fas fa-check"></i>Mobile-First, Responsive Design</li>
    <li><i class="fas fa-check"></i>Cross Browser Testing & Debugging</li>
    <li><i class="fas fa-check"></i>Cross Functional Teams</li>
    <li><i class="fas fa-check"></i>Agile Development & Scrum</li>
  </ul>
</section>
</template>

<style lang="scss" scoped>
.skills {
  margin: auto 0 auto 0;
  margin-top: 15rem;
  animation: animSection 0.8s forwards 0s ease-in-out;
}
@keyframes animSection {
  0% {
    transform: translateY(-5rem);
    opacity: 0;
  }
  100% {
    transform: rotate(xx) translateY(0);
    opacity: 1;
  }
}
h2 {
  text-transform: uppercase;
  margin-top: 2rem;
  font-size: 3.5rem;
}

.lead {
  text-transform: uppercase;
  margin-top: 2.5rem;
}

.icons {
  color: #868e96;
  i {
    margin-right: 1.5rem;
    &:hover {
      background: linear-gradient(to top, #ff4b2b, #ff416c);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  }
}

ul {
  margin: 0;
  padding: 0;
  li {
    list-style: none;
    color: #868e96;
    line-height: 1.5rem;
    i {
      margin-right: 0.5rem;
      margin-left: 1rem;
    }
  }
}
</style>
