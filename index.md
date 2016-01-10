---
layout: page
title: CALINYARA
tagline: We live, We learn
---
{% include JB/setup %}
    
## NEWS

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## CONTACT

<ul>
    <li><a href="mailto:mr.dengjie@gmail.com">Email: mr.dengjie@gmail.com</a></li>
</ul>

<!-- UY BEGIN -->
<div id="uyan_frame"></div>
<script type="text/javascript" src="http://v2.uyan.cc/code/uyan.js?uid=2080454"></script>
<!-- UY END -->
