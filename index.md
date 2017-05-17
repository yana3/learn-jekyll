---
layout: page
title: Home
---

# Vytajte na našom webe!

Tento web vznikol, ako experimentálny projekt, za účelom vzdelávania sa. Téma webu je zameraná na Českých a Slovenských fanúšikov Kpopu. Keďže na vytváraní spolupracujeme dve češky a slovenka, pridávané posty nebudú v jednotnom jazyku. Dúfame, že informácie tu publikované budú pre vás užitočné.

## Videjko na privítanie 

<iframe width="570" height="320" src="https://www.youtube.com/embed/jp2emtZWc_k" frameborder="0" allowfullscreen></iframe>"

## Príspevky

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Navigácia


<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
