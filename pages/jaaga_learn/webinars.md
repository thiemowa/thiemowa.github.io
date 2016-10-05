---
layout: page
title: "Upcoming Webinars"
meta_title: "Upcoming Webinars"
subheadline: ""
teaser: ""
permalink: "/webinars/"
---
{% for webinars in site.data.webinars %}

<div class="container" align= "left">
		<h2>{{ webinars.title }} </h2>
		<p class="subheadline"><em>{{ webinars.date }} </em><p>

  
<div class="row">
 <div class="small-3 columns">
  	 <a href="https://thiemowa.github.io/{{ webinars.profil_url}}/" target="_blank"> <img src="{{ site.url }}{{ site.baseurl }}/images/{{ webinars.image }}" width="200" alt="{{ webinars.name }}"></a>
  </div>
  <div class="small-6 columns">
  	<h5><a href="https://thiemowa.github.io/{{ webinars.profil_url}}/" algin="center" target="_blank">With: {{ webinars.name}}</a></h5>
	<h6><em>{{ webinars.expert}}</em></h6>
  </div>
   <div class="small-3 columns">
  	    <a class="button small radius alert" href="{{ webinars.link}}" align= "center" width="250">Join now</a>
  </div>
</div>

<br>
<hr />
<br>
{% endfor %}
