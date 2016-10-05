---
layout: page
title: "Overview of our Experts"
meta_title: "Jaaga Experts"
subheadline: ""
teaser: ""
permalink: "/experts_overview/"
---

{% for workshop_expert in site.data.workshop_expert %}
<div class="row">
  <div class="large-6 columns">
  	<a href="https://thiemowa.github.io/{{ workshop_expert.profil_url }}/" target="_blank"><img src="{{ site.url }}{{ site.baseurl }}/images/{{ workshop_expert.image }}" width="200"  alt="{{ workshop_expert.name }}"></a>
  </div>
  <div class="large-6 columns" align="center">
    	<h2><a href="https://thiemowa.github.io/{{ workshop_expert.profil_url }}/">{{ workshop_expert.name }}</a></h2>
      <br>
      <subheadline><em> {{ workshop_expert.expert }}</em></subheadline>
      <br>
  </div>
</div>

<br>
{% endfor %}
