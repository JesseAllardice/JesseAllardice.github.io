---
layout: page
title: News
permalink: /news/
---

# News & Updates

<div class="news-grid">
  {% assign sorted_news = site.news | sort: 'date' | reverse %}
  {% for news_item in sorted_news %}
    {% include news-card.html news_item=news_item %}
  {% endfor %}
</div>

---

*For the latest updates on my research and professional activities, connect with me on [LinkedIn](https://www.linkedin.com/in/{{ site.linkedin_username }}) or follow me on [X/Twitter](https://x.com/{{ site.twitter_username }}).*