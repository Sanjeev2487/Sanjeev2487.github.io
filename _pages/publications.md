---
title: "Publications"
permalink: /publications/
author_profile: true
---

These days it makes little sense to create publications lists by hand. There are so many great tools !

Here is a list of sites where you can find my publications:

<ul>
<li>The great classic, with statistics and various (questionable) metrics: <a href="https://scholar.google.fr/citations?user=8f23q-4AAAAJ&hl=en">Google Scholar</a></li>
<li>A CV-like page where you can download all my articles: <a href="https://cv.archives-ouvertes.fr/hugues-talbot">CV-HAL</a></li>
<li>A site that some have described as the facebook for scientists: <a href="https://www.researchgate.net/profile/Hugues_Talbot">Researchgate</a></li>
<li>Various other links are available in the left-hand side column</li> 
</ul>

{% comment %}
Other than that, here is a recent publication 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
