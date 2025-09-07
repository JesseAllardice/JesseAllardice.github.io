---
layout: page
title: Experience
permalink: /experience/
---

# Professional Experience

<div class="experience-grid">
  {% assign sorted_experience = site.experience | sort: 'start_date' | reverse %}
  {% for experience in sorted_experience %}
    {% include experience-card.html experience=experience %}
  {% endfor %}
</div>

## Skills & Expertise

**Research Areas:**
- Multi-modal machine learning
- Computer vision and image/video generation
- Natural language processing
- Quantum physics applications
- Solar energy technology

**Technical Skills:**
- Large language models and fine-tuning
- Deep learning frameworks (PyTorch, TensorFlow)
- Production ML systems
- Data augmentation techniques
- Statistical modeling and analysis

**Leadership & Communication:**
- Corporate training and education
- Cross-functional team collaboration
- Research publication and presentation
- Patent development and commercialization