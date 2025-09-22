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
  
  I am Teaching Assistant in Caen (France).

 I defended my [PhD Thesis](/files/Thesis.pdf) titled "Representatiοns οf structure grοup οf set-theοretical sοlutiοns
tο the Υang-Baxter equatiοn" on October 11th 2024, under the supervision of <a href="{{author.advisor}}"> Eddy Godelle</a>.

  I am actively looking for post-doctoral positions. You can read my [Resume](/files/resume.pdf) and my [Research Statement](/files/ResearchStatement.pdf).
{% elsif site.lang == "fr" %}
  {% capture link2 %}{{ site.baseurl_root }}{{ page.url}}{% endcapture %}
  
  Bienvenue sur la page académique d'Edouard Feingesicht.
======
  
   Je suis actuellement ATER à Caen.

J'ai défendu ma [Thèse](/files/Thesis.pdf) intitulée "Representatiοns οf structure grοup οf set-theοretical sοlutiοns
tο the Υang-Baxter equatiοn" le 11 Octobre 2024, sous la direction de <a href="{{author.advisor}}"> Eddy Godelle</a>.
   
   Je recherche activement des post-doc. Vous pouvez lire mon [CV](/files/CV.pdf) et mon [Research Statement](/files/ResearchStatement.pdf) (en anglais).
{% endif %}
