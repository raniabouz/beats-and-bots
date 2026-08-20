---
layout: default
title: Home
---

<section class="hero">
  <div class="wrap hero-grid">
    <div>
      <p class="eyebrow"><span class="docket">NO. 01</span><span class="divider"></span><span class="label">Law for tech and media</span></p>
      <h1>Where IP, platforms,<br>and AI meet the<br><span class="pop">law that governs them.</span></h1>
      <p class="sub">Notes on copyright, platform regulation, and the legal questions technology and media keep raising faster than the law can answer.</p>
      <div class="hero-cta">
        <a class="btn btn-solid" href="#posts">Read the latest</a>
        <a class="btn btn-ghost" href="#about">About the blog</a>
      </div>
    </div>
    <div class="hero-art">
      <div class="headshot">
        <img src="{{ '/assets/images/headshot.png' | relative_url }}" alt="Rania, author of Beats and Bots">
      </div>
    </div>
  </div>
</section>

<section id="posts">
  <div class="wrap">
    <div class="section-head">
      <h2>Latest posts</h2>
      <span class="label">Recently published</span>
    </div>
    <div class="posts">
      {% for post in site.posts %}
      <article class="card">
        <div class="card-thumb">
          {% if post.thumbnail %}
            <img src="{{ post.thumbnail | relative_url }}" alt="{{ post.title }}" style="object-position: 50% 20%;">
          {% else %}
            <div class="placeholder">
              <svg width="36" height="36" viewBox="0 0 24 24" fill="none" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="3" stroke="currentColor" stroke-width="1.6"/><circle cx="8.5" cy="8.5" r="1.6" fill="currentColor"/><path d="M21 15l-5.5-5.5L3 21" stroke="currentColor" stroke-width="1.6"/></svg>
            </div>
          {% endif %}
        </div>
        <div class="card-body">
          {% if post.tag %}
            <span class="tag-pill {{ post.tag_color | default: 'c1' }}">{{ post.tag }}</span>
          {% endif %}
          <span class="label" style="margin-left:8px;">{{ post.date | date: "%b %-d, %Y" }}</span>
          <h3>{{ post.title }}</h3>
          <p>{{ post.excerpt | strip_html | truncatewords: 24 }}</p>
          <a class="read" href="{{ post.url | relative_url }}">Read the post</a>
        </div>
      </article>
      {% endfor %}
    </div>
  </div>
</section>

<section id="topics">
  <div class="wrap">
    <div class="section-head"><h2>What this blog covers</h2></div>
    <ul class="topic-list">
  <li><span class="dot" style="background:var(--navy)"></span><div><h4>AI &amp; regulation</h4><p>How the law is racing to catch up with generative AI.</p></div></li>
  <li><span class="dot" style="background:var(--rose)"></span><div><h4>Platforms &amp; speech</h4><p>The rules platforms set, and the ones governments do.</p></div></li>
  <li><span class="dot" style="background:var(--mustard)"></span><div><h4>Data &amp; privacy</h4><p>Who owns your information, and what happens when it moves.</p></div></li>
  <li><span class="dot" style="background:var(--navy)"></span><div><h4>Media &amp; IP</h4><p>Ownership, authorship, and the business of content.</p></div></li>
</ul>
  </div>
</section>

<section id="about">
  <div class="wrap about">
    <div class="about-mark">
      <img src="{{ '/assets/images/mylogo.png' | relative_url }}" alt="Beats and Bots logo" style="width:100%; height:auto; display:block;">
    </div>
    <div>
    <h2>Written by a law and tech nerd with a music habit</h2>
    <p>I'm Rania, a First Class LLB graduate (University of Sussex) specialising in IP, technology, and platform law. Before law, I spent years in music and documentary photography — which is where the questions behind this blog started.</p>
    <p>My research on generative AI and music ownership, funded through a Junior Research Associate project, was presented at the British Conference of Undergraduate Research 2025. I've since worked across ad policy and platform compliance during a placement year at TikTok, alongside experience at The Guardian and Hogan Lovells, and I write here to keep pulling that thread.</p>
      <div class="credentials">
        <span class="pill">Best Essay Prize, Internet Law & Regulation</span>
        <span class="pill">TikTok Ad Policy placement</span>
        <span class="pill">BCUR 2025 presenter</span>
        <span class="pill">Sussex Law School</span>
      </div>
    </div>
  </div>
</section>
