---
layout: default
---

<div class="hero-section">
  <div class="hero-container">
    <div class="hero-photo">
      <img src="img/profile.jpg" alt="Jesse Allardice" class="profile-image">
    </div>
    <div class="hero-text">
      <p class="hero-description">
        I'm a machine learning researcher at <a href="https://machinelearning.apple.com/" target="_blank">Apple</a>, formerly <a href="https://www.cam.ac.uk/" target="_blank">Cambridge</a> Physics PhD. I work on multimodal foundation models, image and video generation, and pretraining science for large language models.
      </p>
      
      <div class="social-links">
        <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank" class="social-link">
          <img src="img/linkedin-light.svg" alt="LinkedIn" class="social-icon">
        </a>
        <a href="https://x.com/{{ site.twitter_username }}" target="_blank" class="social-link">
          <img src="img/twitter-light.svg" alt="Twitter" class="social-icon">
        </a>
        <a href="https://github.com/{{ site.github_username }}" target="_blank" class="social-link">
          <img src="img/github-light.svg" alt="GitHub" class="social-icon">
        </a>
        <a href="https://scholar.google.co.uk/citations?user={{ site.scholar_id }}&hl=en" target="_blank" class="social-link">
          Google Scholar
        </a>
      </div>
    </div>
  </div>
</div>

<div class="home-content">
  <section class="featured-work">
    <h2>Featured Research</h2>
    <div class="publications-grid">
      {% assign recent_publications = site.publications | sort: 'year' | reverse %}
      {% for publication in recent_publications limit: 3 %}
        {% include publication-card.html publication=publication %}
      {% endfor %}
    </div>
    <div style="text-align: center; margin-top: 1.5rem;">
      <a href="/publications/" class="work-link">View All Publications →</a>
    </div>
  </section>

  <section class="recent-news">
    <h2>Recent News</h2>
    <div class="news-grid">
      {% assign recent_news = site.news | sort: 'date' | reverse %}
      {% for news_item in recent_news limit: 3 %}
        {% include news-card.html news_item=news_item %}
      {% endfor %}
    </div>
    <div style="text-align: center; margin-top: 1.5rem;">
      <a href="/news/" class="work-link">View All News →</a>
    </div>
  </section>
</div>