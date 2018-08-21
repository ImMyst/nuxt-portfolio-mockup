<template>
<section class="awards">
  <h2>Awards & Certifications</h2>
  <ul>
    <li><i class="fa fa-trophy"></i>Google Analytics Certified Developer</li>
    <li><i class="fa fa-trophy"></i>Mobile Web Specialist - Google Certification</li>
    <li><i class="fa fa-trophy"></i>1<sup>st</sup> Place - University of Colorado Boulder - Emerging Tech Competition 2009</li>
    <li><i class="fa fa-trophy"></i>1<sup>st</sup> Place - University of Colorado Boulder - Adobe Creative Jam 2008 (UI Design Category)</li>
    <li><i class="fa fa-trophy"></i>2<sup>nd</sup> Place - University of Colorado Boulder - Emerging Tech Competition 2008</li>
    <li><i class="fa fa-trophy"></i>1<sup>st</sup> Place - James Buchanan High School - Hackathon 2006</li>
    <li><i class="fa fa-trophy"></i>3<sup>rd</sup> Place - James Buchanan High School - Hackathon 2005</li>
  </ul>
</section>
</template>

<style lang="scss" scoped>
.awards {
  margin: auto 0 auto 0;
  margin-top: 18rem;
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

ul {
  padding: 0;
  margin: 0;
  li {
    color: #868e96;
    list-style: none;
    line-height: 1.35rem;
    i {
      color: #ffc107;
      margin-right: 0.5rem;
      margin-left: 1rem;
    }
  }
}
</style>
