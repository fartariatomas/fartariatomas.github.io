---
layout: default
title: Tomas Fartaria
---    		
## Hi there, I'm Tomas Fartaria!

[This is me now](/now)

<ul class="posts">
    {% for post in site.posts %}
        <li><p><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></p></li>
    {% endfor %}
</ul>

