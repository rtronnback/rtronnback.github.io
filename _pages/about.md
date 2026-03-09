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

{% assign latest_publication = site.publications | sort: 'date' | reverse | first %}

{% if latest_publication %}
  {% assign post = latest_publication %}
  {% include archive-single.html %}
{% else %}
  <p><em>No publications listed yet.</em></p>
{% endif %}
