---
layout: page
title: Publications
permalink: /publications/
---

<div class="publications-grid">
  {% assign sorted_publications = site.publications | sort: 'year' | reverse %}
  {% for publication in sorted_publications %}
    {% include publication-card.html publication=publication %}
  {% endfor %}
</div>

## Academic Recognition

- **Schmidt Data Science Residency** - University of Cambridge
- **Apple AI Residency Program** - First cohort participant  
- **Faculty.ai Fellowship** - Applied ML in fintech
- **PhD in Physics** - University of Cambridge

---

For the most up-to-date list of publications, please visit my [Google Scholar profile](https://scholar.google.co.uk/citations?user={{ site.scholar_id }}&hl=en).