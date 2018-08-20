<template>
<section class="education">
  <h2>Education</h2>
  <article>
    <div class="left">
      <h3>University of Colorado Boulder</h3>
      <p class="lead">Bachelor of Science</p>
      <p class="summary">Computer Science - Web Development Track</p>
      <p class="score">GPA: 3.23</p>
    </div>
    <div class="right">
      <span class="text-primary">August 2006 - May 2010</span>
    </div>
  </article>
  <article>
    <div class="left">
      <h3>James Buchanan High School</h3>
      <p class="lead">Technology Magnet Program</p>
      <p class="score">GPA: 3.56</p>
    </div>
    <div class="right">
      <span class="text-primary">August 2002 - May 2006</span>
    </div>
  </article>
</section>
</template>

<style lang="scss" scoped>
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

.education {
  margin: auto 0 auto 0;
  animation: animSection 0.8s forwards 0s ease-in-out;
}

h2 {
  text-transform: uppercase;
  margin-top: 2rem;
  font-size: 3.5rem;
}
article {
  display: flex;
  margin-bottom: 3rem;
  .right {
    margin-left: 30rem;
    min-width: 18rem;
    text-align: right;
  }

  h3 {
    text-transform: uppercase;
    font-size: 2rem;
    margin: 0;
    line-height: 1.2;
  }
  .lead {
    text-transform: uppercase;
    margin: 0;
  }
  .summary {
    line-height: 1.5;
    margin-bottom: -1rem;
  }
}
</style>
