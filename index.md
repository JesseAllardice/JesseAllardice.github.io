---
layout: default
---

<div class="hero-section">
  <div class="hero-container">
    <div class="hero-photo">
      <img src="img/profile.jpg" alt="Jesse Allardice" class="profile-image">
    </div>
    <div class="hero-text">
      <h1>Jesse Allardice</h1>
      <p class="hero-subtitle">Machine Learning Researcher at Apple</p>
      <p class="hero-description">
        Specializing in multi-modal learning with an interest in image and video generation.
        Background in Physics with a PhD from the University of Cambridge.
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
  <section class="recent-news">
    <h2>Recent News</h2>
    <div class="news-item">
      <span class="news-date">2025</span>
      <span class="news-content">Presenting "FlexTok: Resampling Images into 1D Token Sequences of Flexible Length" at ICML 2025 (July 15, Poster Session 2 East)</span>
    </div>
    <div class="news-item">
      <span class="news-date">2025</span>
      <span class="news-content">Published work on BETR (benchmark-targeted ranking) achieving 1.8–2.8× compute multipliers for language model performance</span>
    </div>
    <div class="news-item">
      <span class="news-date">2025</span>
      <span class="news-content">Apple announces multimodal AI agent research internships in Santa Clara Valley and Zurich</span>
    </div>
  </section>

  <section class="featured-work">
    <h2>Featured Research</h2>
    <div class="work-item">
      <h3>FlexTok: Resampling Images into 1D Token Sequences</h3>
      <p>Latest research on flexible-length image tokenization for multimodal learning, presented at ICML 2025.</p>
      <a href="https://github.com/apple/ml-flextok" target="_blank" class="work-link">View on GitHub</a>
    </div>
    
    <div class="work-item">
      <h3>BETR: Benchmark-Targeted Ranking</h3>
      <p>Novel method for matching pretraining data to benchmarks in language models, achieving significant compute efficiency improvements.</p>
    </div>
  </section>
</div>