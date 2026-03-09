---
permalink: /
title: About
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

---

I am a PhD student currently specializing in Algorithmic Monitoring of the World Wide Web. I have had the opportunity to work internationally in research, government, and business environments. Specialized in Machine Learning, Data Analysis, and Web Scraping, I have a keen interest in applying these digital skills to current societal challenges.

Interested in my latest publication? Read it here:

<h3>Debug: Publications Count = {{ site.publications | size }}</h3>

{% for pub in site.publications %}
  <p>{{ pub.title }} - {{ pub.date }}</p>
{% endfor %}


{% assign latest_publication = site.publications | sort: 'date' | reverse | first %}

{% if latest_publication %}
  <h3>Latest Publication</h3>
  {% include archive-single.html post=latest_publication %}
{% endif %}
