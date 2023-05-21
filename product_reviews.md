---
layout: default
title: Product Reviews
permalink: /product_reviews/
---

<h1>Product Reviews</h1>

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'product' %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.date | date: "%B %d, %Y" }}</p>
      </li>
    {% endif %}
  {% endfor %}
</ul>
