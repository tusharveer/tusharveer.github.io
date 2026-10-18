---
permalink: /
title: "Tushar Veer Singh"
layout: site
body_class: page-home
redirect_from:
  - /about/
  - /about.html
---

<section class="hero">
  <div class="container hero-inner">
    <div class="hero-text">
      <h1>Tushar Veer Singh</h1>
      <p class="hero-role">MSc in Economics<br>University of Manchester, United Kingdom</p>
      <p class="hero-bio">I am an independent researcher with broad interests in macroeconomics and applied microeconomics.</p>
      <p class="hero-links">
        <a href="mailto:{{ site.author.email }}">Email</a>
        <a href="/resume/">CV</a>
        <a href="https://github.com/tusharveer" target="_blank" rel="noopener">GitHub</a>
      </p>
    </div>
    <figure class="hero-photo"><img class="portrait" src="/images/profile.jpg" alt="Tushar Veer Singh" width="750" height="938"></figure>
  </div>
</section>

<div class="container home-grid">
  <div class="home-papers">
    <section>
      <h2>Research</h2>
{% include working-papers.html %}
      <p class="more"><a href="/research/">All research <span aria-hidden="true">&rarr;</span></a></p>
    </section>
    <section>
      <h2>Beyond research</h2>
      <p>When I am not thinking about economics, I often turn to Hindi music—its rhythm, emotion, and expressive depth. I also enjoy following tennis closely, especially the strategic intensity and drama of the sport. Beyond that, I value the community around both interests: I enjoy attending live music performances and discovering new artists, and on the tennis side, I like playing and watching with friends at local clubs, where the social energy and competitive spirit are just as rewarding as the game itself.</p>
    </section>
  </div>
  <aside class="home-aside">
    <section>
      <h2>Background</h2>
      <ul class="side-list">
        <li>Various research assistantships in economics for professors</li>
        <li>Master's in economics, University of Manchester</li>
        <li>Undergraduate in Business Economics, University of Delhi</li>
      </ul>
    </section>
    <section>
      <h2>Affiliations</h2>
      <ul class="side-list">
        <li>Research Fellow, Centre for Economic Research in Pakistan (CERP)</li>
        <li>Research Fellow, Mehboob ul Haq Research Center, LUMS</li>
      </ul>
    </section>
    <section class="contact">
      <h2>Contact</h2>
      <p><a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br>Independent Scholar<br>Delhi, India</p>
    </section>
  </aside>
</div>
