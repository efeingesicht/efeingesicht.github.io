---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if site.lang == "en" %}
  {% capture link1 %}{{ site.baseurl_root }}/fr{{ page.url}}{% endcapture %}
  Welcome on Edouard Feingesicht's academic website.
======
  
  I am 3rd year PhD student in Caen (France) under the supervision of <a href="{{author.advisor}}"> Eddy Godelle</a>, working on "Structure group of set-theoretical solutions of the Yang-Baxter equation".
  
  I am actively looking for post-doctoral positions. You can read my [Resume](/files/Resume.pdf) and my [Research Statement](/files/ResearchStatement.pdf)
{% elsif site.lang == "fr" %}
  {% capture link2 %}{{ site.baseurl_root }}{{ page.url}}{% endcapture %}
  
  Bienvenue sur la page académique d'Edouard Feingesicht.
======
  
   Je suis doctorant en 3è année à Caen, sous la direction de <a href="{{author.advisor}}"> Eddy Godelle</a>, travaillant sur le sujet "Groupe de structure des solutions ensemblistes de l'équation de Yang-Baxter".
   
   Je recherche activement des post-doc. Vous pouvez lire mon [CV](/files/CV.pdf) et mon [Research Statement](/files/ResearchStatement.pdf) (en anglais).
{% endif %}
