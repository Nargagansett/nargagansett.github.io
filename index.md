---
layout: page
---

<img src="/assets/testtractor.jpg" height="50%" width="100%" style="margin: 0px 0px 20px 0px; float: center;">

<h3>Books</h3>


<a href="https://google.com"><img src="https://images.squarespace-cdn.com/content/v1/5c71c7d8aadd342945360ba1/1586723509001-E5NQB7VLS1R9NS0EOSOM/Harry+Potter+and+the+Philosopher%27s+Stone+Original+Children%27s+Edition+Cover.jpg" height="25%" width="25%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a good book.
<div style="clear: both;"></div>

try again again

<h3>Other</h3>
<div class="map-responsive">
<iframe src="https://www.google.com/maps/embed?pb=!4v1638641578584!6m8!1m7!1srY9_smxJX6MJfXw_aWmFZQ!2m2!1d51.41198382770721!2d0.01541783592259776!3f205.35260311865295!4f4.794333189591157!5f1.8437470984674964" width="600" height="450" frameborder="0" style="border:0" allowfullscreen="" loading="lazy"></iframe>
</div>
 
 
 text
 
<div class="map-responsive">
 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d69195.39251265253!2d6.470045162882172!3d-71.90335468987807!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xb0a35e27e6cae7fb%3A0xa77c45f11aee610!2sMount%20Kropotkin!5e1!3m2!1sen!2suk!4v1638644592561!5m2!1sen!2suk" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
 </div>
 
 
 text
 
 
 
<a href="https://www.google.com"><img src="/assets/books/testsquare.jpg" height="30%" width="30%" style="margin: 0px 10px 20px 0px; float: left;">
<b>This book</b></a> is a book about x.
<div style="clear: both;"></div>

<h3>Blog</h3>

{% for post in site.posts %}
<span class="date-home">({{ post.date | date: "%Y/%m" }})</span> [{{ post.title }}]({{ post.url }}) <br>
{% endfor %}
