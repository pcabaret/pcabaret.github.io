---
title: "Graphic design"
excerpt: "Selection of posters and logos designed over the years <br/><img width=500px src='/images/portfolio/portfolio-teaser.jpg'>"
collection: portfolio
---

Here you'll find a selection of posters and illustrations I've produced for INSA Rennes associations such as B.I.I.P. (student newspaper) or InsaLan (e-sport tournaments), as well as illustrations or logos created for other occasions. 


<div class="gallery-container" id="gallery">
  <div class="gallery-grid">

{% for i in site.gallery %}
  <div class="card">
    <a href="/images/portfolio/{{i[1].file}}">
    <img src="/images/portfolio/{{i[1].file}}" alt="" class="card-img">
    </a>
    <div class="card-body">
    <h5 class="card-title">{{i[1].title}}</h5>
    <span class="card-text">{{i[1].date}}</span>
    </div>
</div>
{% endfor %}


  </div>
</div>