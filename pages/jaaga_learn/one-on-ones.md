---
layout: page
title: "One-on-One Offers"
meta_title: "one-on-Ooe"
subheadline: ""
teaser: ""
permalink: "/one-on-ones/"
---

{% for events in site.data.events %}
{% if events.one-on-ones %}

<div class="container" align= "left">
		<h2>{{ events.title }} </h2>
		<p class="subheadline"><em>{{ events.date }} </em><p>

  
<div class="row">
 <div class="small-3 columns">
  	 <a href="https://thiemowa.github.io/{{ events.profil_url}}/" target="_blank"> <img src="{{ site.url }}{{ site.baseurl }}/images/{{ events.image }}" width="200" alt="{{ events.name }}"></a>
  </div>
  <div class="small-6 columns">
  	<h5><a href="https://thiemowa.github.io/{{ events.profil_url}}/" algin="center" target="_blank">With: {{ events.name}}</a></h5>
	<h6><em>{{ events.expert}}</em></h6>
  </div>
   <div class="small-3 columns">
  	    <a class="button small radius alert" href="{{ events.link}}" align= "center" width="250">Join now</a>
  </div>
</div>

<br>
<hr />
<br>
{% endif %}
{% endfor %}

