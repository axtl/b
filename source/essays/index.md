---
layout: default
heading: The Essay Archive
title: Essay Archive
---


<h2 id="intro">{{ site.posts.size }} essays.</h2>

<div class="posts">
    <ul>
        {% for post in site.posts %}
            <li>
                {{ post.date | date: "%b %d, %Y"  }} &mdash; <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
        {% endfor %}
    </ul>
</div>
