---
layout: page
---

<h3>Books</h3>

<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="20%" width="20%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
