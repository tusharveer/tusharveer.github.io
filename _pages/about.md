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
      <p class="hero-role">Msc in Economics <br>University of Manchester, United Kingdom</p>
      <p class="hero-bio">I am an independent researcher, with broad research interests in Macroeconomics and applied microeconomics. </p>
      <p class="hero-links"><a href="mailto:{{ iamtusharvs@gmail.com }}">Email</a><a href="/resume/">CV</a><a href="https://github.com/{{ https://github.com/tusharveer }}" target="_blank" rel="noopener">GitHub</a></p>
    </div>
    <figure class="hero-photo"><img class="portrait" src="/images/profile.jpg" alt="Muhammad Bashir" width="750" height="938"></figure>
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
      <p>When I am not thinking about economics, I often turn to Hindi music—its rhythm, emotion, and expressive depth. I also enjoy following tennis closely, especially the strategic intensity and </p>
    </section>
  </div>
  <aside class="home-aside">
    <section>
      <h2>Background</h2>
      <ul class="side-list">
        <li>Predoctoral researcher in economics, Columbia University, for professors <a href="https://michaelcbest.github.io/">Michael Best</a> and <a href="https://sites.google.com/view/jwillis/">Jac[...]
        <li>Master's in economics, University of Manchester (advisor: <a href="https://mazharwaseem.com">Mazhar Waseem</a>)</li>
        <li>Undergraduate in Economics and Mathematics, Lahore University of Management Sciences (LUMS), funded by the <a href="https://nop.lums.edu.pk/">National Outreach Program</a> scholarship</li>
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
      <p><a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br>Department of Economics<br>UC Berkeley</p>
    </section>
  </aside>
</div>
