---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Group Members

We are a diverse group of researchers interested in understanding speciation, adaptation and biological processes using genomics and ecological approaches. Click on group member profiles to learn more about us! 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We use ecology, evolutionary biology and genomics to understand adaptation and speciation in a changing world. In particular, we are interested in how human activity is able to shape and alter these processes. The group works on a wide variety of organisms but our main focus is on Passer sparrows, particularly the remarkable house sparrow.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
