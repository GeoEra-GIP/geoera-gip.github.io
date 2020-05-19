---
layout: home
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/markus-spiske-unsplash.jpg
  caption: "Photo credit: [Photo by Markus Spiske on Unsplash](https://unsplash.com)"
excerpt: >
  Integrating information and knowledge to support sustainable use of the subsurface.<br />
   
---
Hi

{{ content }}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
