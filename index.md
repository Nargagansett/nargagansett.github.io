---
layout: page
---

<img src="/assets/testtractor.jpg" height="50%" width="100%" style="margin: 0px 0px 20px 0px; float: center;">

<h3>Books</h3>

<iframe src="https://www.google.com/maps/embed?pb=!4v1637532890392!6m8!1m7!1sCAoSLEFGMVFpcE13cjJpLWlmdENVbmNKSEc5RWZNMHJFNi1oTVlWR2ZWUk5SZzVO!2m2!1d51.5226617!2d-0.1556945!3f91.25740436702097!4f6.05873327267922!5f0.7820865974627469" width="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="30%" width="30%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
