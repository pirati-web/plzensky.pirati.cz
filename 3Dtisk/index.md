---
layout: default
title: 3D tisk
description: Vše o 3D tisku
keywords: 3D tisk
---


<div class="row">
  <div class="columns">
    <div class="o-section">
      <div class="o-section-inner">
          <header class="c-page-header">
            <h1 itemprop="headline" class="c-page-title">Zde budou soubory ke stažení pro 3D tisk</h1>
            <div class="large-6 column">
  <div class="media-object">
      <div class="media-object-section">
        <div class="thumbnail">
          <img style="height: 65px;" src= "{{ '/assets/img/people/kosik.jpg' }}" alt="Mince do košíku">
        </div>
      </div>
      <div class="media-object-section main-section">
        <h6><a href="{{ '/lide/miroslav-masek/'}}">Odkaz</a></h6>
        <p>výrobek je z 3D tiskárny</p>
      </div>
    </div>
    <div class="media-object">
      <div class="media-object-section">
        <div class="thumbnail" >
          <img style="height: 65px;" src= "{{ '/assets/img/pistalka.jpg' }}" alt="Píšťalka">
        </div>
       </div>
      <div class="media-object-section main-section">
        <h6><a href="{{ '/lide/lukas-barton/'  }}">Odkaz</a></h6>
        <p>výrobek je z 3D tiskárny</p>
                 </header>
          {% assign posts = site.posts | where_exp: "item", "item.tags contains 'susice'"%}
          {% include articles/list-responsive.html posts=posts %}
      </div>
    </div>
  </div>
</div>

