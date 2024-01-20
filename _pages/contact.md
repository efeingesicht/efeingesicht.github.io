---
permalink: /contact/
---

{% if site.lang == "en" %}
  {% capture link1 %}{{ site.baseurl_root }}/fr{{ page.url}}{% endcapture %}
  <u>eMail:</u> firstname.lastname@unicaen.fr <i>(replace firstname and lastname)</i> <br>
  <u>Address:</u><br>
&nbsp;&nbsp;&nbsp;Université de Caen, UFR des sciences.<br>
&nbsp;&nbsp;&nbsp;Laboratoire LMNO.<br>
&nbsp;&nbsp;&nbsp;Campus II, 14032 Caen cedex, France.<br>
&nbsp;&nbsp;&nbsp;Office : S3 111
{% elsif site.lang == "fr" %}
  {% capture link2 %}{{ site.baseurl_root }}{{ page.url}}{% endcapture %} 
  <u>eMail :</u> prénom.nom@unicaen.fr <i>(remplacer prénom et nom)</i><br>
  <u>Adresse :</u><br>
&nbsp;&nbsp;&nbsp;Université de Caen, UFR des sciences.<br>
&nbsp;&nbsp;&nbsp;Laboratoire LMNO.<br> 
&nbsp;&nbsp;&nbsp;Campus II, 14032 Caen cedex, France.<br>
&nbsp;&nbsp;&nbsp;Bureau : S3 111
{% endif %}
