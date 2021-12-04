---
layout: page
---

<img src="/assets/testtractor.jpg" height="50%" width="100%" style="margin: 0px 0px 20px 0px; float: center;">

<h3>Books</h3>

try again

<div class="map-responsive">
<iframe src="https://www.google.com/maps/embed?pb=!4v1638641578584!6m8!1m7!1srY9_smxJX6MJfXw_aWmFZQ!2m2!1d51.41198382770721!2d0.01541783592259776!3f205.35260311865295!4f4.794333189591157!5f1.8437470984674964" width="600" height="450" frameborder="0" style="border:0" allowfullscreen="" loading="lazy"></iframe>
</div>
 
 
 text
 
 
<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="30%" width="30%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
