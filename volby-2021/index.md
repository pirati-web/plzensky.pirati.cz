---
layout: elections-2021
title: Parlamentní volby 2021
heroBgImg: volby2020.jpg
campaignGroupUid: volby2021
campaignCategoryUid: psp2021
candidateListUid: psp2021
customizeHeader: true
heroBgImg: kampan20/zahajenikampan.jpg
---

{% assign candidates = site.candidatelists | where: "uid", page.candidateListUid | first %}

{% capture mainContent %}
  <h1 class="head-alt-lg md:head-alt-xl text-center">Parlamentní volby 2021</h1>
{% endcapture %}

{% capture subContent %}
  <h2 class="head-xs md:head-base mt-2 text-center">Vraťme <strong>zemi budoucnost</strong></h2>
{% endcapture %}

{% include elections-header.html img=page.img bgImg=page.heroBgImg mainContent=mainContent subContent=subContent candidateListNumber=candidates.number %}

