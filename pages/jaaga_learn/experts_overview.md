---
layout: page
title: "Overview of our Experts"
meta_title: "experts overview"
subheadline: ""
teaser: ""
permalink: "/experts_overview/"
---
<ul>
% for member in site.data.workshop_expert %}
  <li>
   {{ workshop_expert.name }}
      {{ workshop_expert.expert }}
  </li>
{% endfor %}
</ul>

<div class="row">
  <div class="large-6 columns">
  	<a href="https://thiemowa.github.io/experts2/" target="_blank"><img src="{{ site.url }}{{ site.baseurl }}/images/tej.png" width="200"  alt="Tej"></a>
  </div>
  <div class="large-6 columns" align="center">
    	<h2><a href="https://thiemowa.github.io/experts2/ ">Tej</a></h2>
      <br>
      <subheadline><em> Sales and Marketing</em></subheadline>
      <br>
  </div>
</div>

<br>

<div class="row">
  <div class="large-6 columns">
  		<a href="https://thiemowa.github.io/experts2/" target="_blank"><img href="https://thiemowa.github.io/experts2/" src="{{ site.url }}{{ site.baseurl }}/images/dharmesh.jpg" width="200" alt="Dharmesh"></a>
  </div>
  <div class="large-6 columns" align="center">
    	<h2><a href="https://thiemowa.github.io/experts2/">Dharmesh</a></h2>
      <br>
      <subheadline><em> UX Design</em></subheadline>
      <br>

  </div>
</div>

<br>
