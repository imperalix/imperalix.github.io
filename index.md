---
layout: default
title: home
---
 <h2>me</h2>
<p>This is a personal web site. The opinions expressed here represent my own and not those of my employer.</p>
<h2>most recent blog post</h2>
<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_title.html %}
</div>
