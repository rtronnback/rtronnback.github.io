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

<h3>Debug: Latest Publication</h3>
<p>Count: {{ site.publications | size }}</p>
<p>Latest Title: {{ latest_publication.title }}</p>
<p>Latest Date: {{ latest_publication.date }}</p>
<p>Latest URL: {{ latest_publication.url }}</p>


{% assign latest_publication = site.publications | sort: 'date' | reverse | first %}

{% if latest_publication %}
  <h3>Latest Publication</h3>
  {% assign post = latest_publication %}
  {% include archive-single.html %}
{% else %}
  <p><em>No publications listed yet.</em></p>
{% endif %}
