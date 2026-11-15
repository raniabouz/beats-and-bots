---
layout: default
title: Beats & Bots
---

<section class="hero">
  <div class="wrap hero-grid">
    <div>
      <h1>Pull up a chair.<br><span class="SOMETHING">Let's talk tech law!</span></h1>
      <p class="sub">I'm Rania, and I write about copyright, platforms, AI and the legal questions that change faster than you can say “Ctrl+C”.</p>
      <div class="hero-cta">
        <a class="btn btn-solid" href="#posts">Read the latest</a>
        <a class="btn btn-ghost" href="#about">About the blog</a>
      </div>
    </div>
        <div class="hero-art">
      <div class="hero-photo-wrap">
        <div class="headshot">
          <img src="{{ '/assets/images/headshot.png' | relative_url }}" alt="Rania, author of Beats and Bots">
        </div>
      </div>
    </div>
  </div>
</section>

<section id="posts">
  <div class="wrap">
  <div class="section-head">
   <h2>Latest posts</h2>
  </div>
    <div class="posts">
      {% for post in site.posts %}
      {% assign words = post.content | strip_html | number_of_words %}
      {% assign mins = words | divided_by: 200 | at_least: 1 %}
      <article class="card">
        <div class="card-thumb">
          {% if forloop.first %}<span class="new-badge" data-date="{{ post.date | date_to_xmlschema }}">New</span>{% endif %}
          {% if post.thumbnail %}
            <img src="{{ post.thumbnail | relative_url }}" alt="" style="object-position: 50% 20%;">
          {% else %}
            <div class="placeholder">
              <svg width="36" height="36" viewBox="0 0 24 24" fill="none" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="3" stroke="currentColor" stroke-width="1.6"/><circle cx="8.5" cy="8.5" r="1.6" fill="currentColor"/><path d="M21 15l-5.5-5.5L3 21" stroke="currentColor" stroke-width="1.6"/></svg>
            </div>
          {% endif %}
          <button class="card-share" type="button" data-url="{{ post.url | absolute_url }}" data-title="{{ post.title | escape }}" aria-label="Share this post">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 3v12"/><path d="M8 7l4-4 4 4"/><path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-7"/></svg>
          </button>
        </div>
        <div class="card-body">
          <div class="card-meta">
            {% if post.tag %}<span class="tag-pill {{ post.tag_color | default: 'c1' }}">{{ post.tag }}</span>{% endif %}
            <span class="card-date">{{ post.date | date: "%-d %b %Y" }}</span>
          </div>
          <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
          <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
          <span class="card-foot">{{ mins }} min read</span>
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
  <li class="t1"><span class="num">1.</span><div><h4>AI &amp; regulation</h4><p>How the law is racing to catch up with generative AI.</p></div></li>
  <li class="t2"><span class="num">2.</span><div><h4>Platforms &amp; speech</h4><p>The rules platforms set, and the ones governments do.</p></div></li>
  <li class="t3"><span class="num">3.</span><div><h4>Data &amp; privacy</h4><p>Who owns your information, and what happens when it moves.</p></div></li>
  <li class="t4"><span class="num">4.</span><div><h4>Media &amp; IP</h4><p>Ownership, authorship, and the business of content.</p></div></li>
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
    <p>I'm Rania, a First Class LLB graduate (University of Sussex) specialising in IP, technology, and platform law. Before law, I spent years in music and documentary photography which is where the questions behind this blog started.</p>
    <p>My research on generative AI and music ownership, funded through a Junior Research Associate project, was presented at the British Conference of Undergraduate Research 2025. I've since worked across ad policy and platform compliance during a placement year at TikTok, alongside experience at The Guardian and Hogan Lovells, and I write here to keep pulling on that thread.</p>
      <div class="credentials">
        <span class="pill">Best Essay Prize, Internet Law & Regulation</span>
        <span class="pill">TikTok Ad Policy placement</span>
        <span class="pill">BCUR 2025 presenter</span>
        <span class="pill">Sussex Law School</span>
      </div>
    </div>
  </div>
</section>
