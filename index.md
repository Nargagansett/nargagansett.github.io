---
layout: page
---

<img src="/assets/testtractor.jpg" height="50%" width="100%" style="margin: 0px 0px 20px 0px; float: center;">

<h3>Books</h3>


 final version?

<div class="map-responsive">
<iframe src="https://www.google.com/maps/embed?pb=!4v1638641412312!6m8!1m7!1srY9_smxJX6MJfXw_aWmFZQ!2m2!1d51.41198382770721!2d0.01541783592259776!3f199.17435489736272!4f11.032650165980854!5f3.325193203789971" width="600" height="450" frameborder="0" style="border:0" allowfullscreen="" loading="lazy"></iframe>
</div>
 
<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="30%" width="30%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
