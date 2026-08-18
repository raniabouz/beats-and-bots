---
layout: default
title: Home
---

<section class="hero">
  <div class="wrap hero-grid">
    <div>
      <p class="eyebrow"><span class="dot"></span><span class="label">Law for tech and media</span></p>
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
      <li><span class="dot" style="background:var(--navy)"></span><div><h4>Training data &amp; infringement</h4><p>What "input" means legally when a model learns from copyrighted work.</p></div></li>
      <li><span class="dot" style="background:var(--rose)"></span><div><h4>Ownership &amp; authorship</h4><p>Where the law draws the line between a tool and a co-creator.</p></div></li>
      <li><span class="dot" style="background:var(--mustard)"></span><div><h4>Platform policy</h4><p>How platforms' own rules shape what's actually enforceable.</p></div></li>
      <li><span class="dot" style="background:var(--navy)"></span><div><h4>Personality &amp; voice rights</h4><p>Passing off, likeness, and what happens when an AI sounds like someone real.</p></div></li>
    </ul>
  </div>
</section>

<section id="about">
  <div class="wrap about">
    <div class="about-mark">
      <img src="{{ '/assets/images/mylogo.png' | relative_url }}" alt="Beats and Bots logo" style="width:100%; height:auto; display:block;">
    </div>
    <div>
      <h2>Written by a music-and-law crossbreed</h2>
      <p>Beats and Bots is written by Rania, a First Class LLB graduate (University of Sussex) specialising in IP, technology, and platform law. Before law, she spent years in music and documentary photography — which is where the questions behind this blog started.</p>
      <p>Her research on generative AI and music ownership, funded through a Junior Research Associate project, was presented at BCUR 2025. She's since worked across ad policy, platform compliance, and IP research, and writes here to keep pulling that thread.</p>
      <div class="credentials">
        <span class="pill">WIPO ADR Young</span>
        <span class="pill">The Copyright Society</span>
        <span class="pill">BCUR 2025 presenter</span>
        <span class="pill">Sussex Law School</span>
      </div>
    </div>
  </div>
</section>
