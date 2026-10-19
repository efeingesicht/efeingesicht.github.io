---
permalink: /contact/
---

{% if site.lang == "en" %}
  {% capture link1 %}{{ site.baseurl_root }}/fr{{ page.url}}{% endcapture %}
  <u>eMail:</u> firstname.lastname@univ-reims.fr <i>(replace firstname and lastname)</i> <br>
  
  <u>Address:</u><br>
&nbsp;&nbsp;&nbsp;Laboratoire de Mathématiques de Reims.<br>
&nbsp;&nbsp;&nbsp;U.F.R. Sciences Exactes et Naturelles.<br>
&nbsp;&nbsp;&nbsp;Moulin de la Housse - BP 1039.<br>
&nbsp;&nbsp;&nbsp;51687 Reims Cedex 2 FRANCE.<br>
&nbsp;&nbsp;&nbsp;Office : 3R50
{% elsif site.lang == "fr" %}
  {% capture link2 %}{{ site.baseurl_root }}{{ page.url}}{% endcapture %} 
  <u>eMail :</u> prénom.nom@univ-reims.fr <i>(remplacer prénom et nom)</i><br>
  
  <u>Adresse :</u><br>
&nbsp;&nbsp;&nbsp;Laboratoire de Mathématiques de Reims.<br>
&nbsp;&nbsp;&nbsp;U.F.R. Sciences Exactes et Naturelles.<br> 
&nbsp;&nbsp;&nbsp;Moulin de la Housse - BP 1039.<br>
&nbsp;&nbsp;&nbsp;51687 Reims Cedex 2 FRANCE.<br>
&nbsp;&nbsp;&nbsp;Bureau : 3R50.
{% endif %}
