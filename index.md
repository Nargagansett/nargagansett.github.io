---
layout: page
---

<img src="/assets/testtractor.jpg" height="50%" width="100%" style="margin: 0px 0px 20px 0px; float: center;">

<h3>Books</h3>

<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="30%" width="30%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
