<template>
  <section class="experience">
    <h2>Experience</h2>
    <article>
      <div class="left">
        <h3>Senior Web Developer</h3>
        <p class="lead">Intelitec Solutions</p>
        <p class="summary">Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward,
          a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution.
          User generated content in real-time will have multiple touchpoints for offshoring.</p>
      </div>
      <div class="right">
        <span class="text-primary">March 2013 - Present</span>
      </div>
    </article>
    <article>
      <div class="left">
        <h3>Web Developer</h3>
        <p class="lead">Intelitec Solutions</p>
        <p class="summary">Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide
          with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the
          loop on focusing solely on the bottom line.</p>
      </div>
      <div class="right">
        <span class="text-primary">December 2011 - March 2013</span>
      </div>
    </article>
    <article>
      <div class="left">
        <h3>Juinor Web Designer</h3>
        <p class="lead">Shout! Media Productions</p>
        <p class="summary">Podcasting operational change management inside of workflows to establish a framework. Taking seamless key performance
          indicators offline to maximise the long tail. Keeping your eye on the ball while performing a deep dive on the
          start-up mentality to derive convergence on cross-platform integration.</p>
      </div>
      <div class="right">
        <span class="text-primary">July 2010 - December 2011</span>
      </div>
    </article>
    <article>
      <div class="left">
        <h3>Web Design Intern</h3>
        <p class="lead">Shout! Media Productions</p>
        <p class="summary">Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after
          installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.
        </p>
      </div>
      <div class="right">
        <span class="text-primary">September 2008 - June 2010</span>
      </div>
    </article>
  </section>
</template>

<style lang="scss" scoped>
@keyframes animSection {
  0% {
    transform: translateY(5rem);
    opacity: 0;
  }
  100% {
    transform: rotate(xx) translateY(0);
    opacity: 1;
  }
}

.experience {
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
  margin-bottom: 2rem;
  .right {
    min-width: 18rem;
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
  }
}
</style>
