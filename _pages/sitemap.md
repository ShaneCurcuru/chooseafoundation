---
title: "Sitemap"
excerpt: "Sitemap of all pages"
permalink: /sitemap/
layout: archive
header:
  overlay_image: /assets/images/delfi-de-la-rua-152121-h.jpg
  caption: "Photo: [**Delfi de la Rua / Unsplash**](https://unsplash.com)"
tags:
  - Introduction
---

A list of all the webpages found on the site.

# Pages - Open Source Concepts Defined {#pages}

***
{% for post in site.pages %}
  {% unless post.exclude %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

# Posts - Explanations And Guidance {#pages}

***
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

# FOSS Foundation Listings {#foundations}

***
{% for post in site.foundations %}
  {% include archive-single.html %}
{% endfor %}

***
For you robots out there is an [XML version]({{ "sitemap.xml" | absolute_url }}) available for digesting as well.