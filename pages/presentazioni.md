---
layout: page
title: Keynote
---

<div class="home-posts">
  {% for post in site.tags.slide %}
  <ul class="home">
    <li class="home"><a href="{{ slide.link }}"></a> {{ post.date | date_to_string }} &raquo; <a href="{{ slide.url }}">&raquo; {{ post.title }}   </a></li>
	  <li class="home">
	    <p class="home-tags"> 
	      {% if post.tags != empty %}<br/><i class="fa fa-tags"></i>
	        {% for tag in post.tags %}
	          <a href="{{ '-ref' | prepend: tag | replace: ' ','-' | prepend: 'tags/#' | prepend: site.baseurl }}">{{ tag }}</a>{% unless forloop.last %}, {% endunless %}
	        {% endfor %}
	      {% endif %}
	    </p>
	  </li>
  </ul>
  {% endfor %}
</div>