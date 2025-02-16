---
title: "Document Analysis Group - Publications"
layout: gridlay
excerpt: "Document Analysis Group -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

(For a full list of publications and patents see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.ch/citations?user=TqxYWZsAAAAJ), [ResearcherID](https://www.researcherid.com/rid/D-7763-2012))

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<p><iframe id="" style="overflow-x: hidden;" src="http://refbase.cvc.uab.es/show.php?notes=dag&amp;submit=Cite&amp;citeStyle=J%20Glaciol&amp;citeOrder=year&amp;client=inc-refbase-1.0&amp;showLinks=1&amp;showRows=10"
 name="" width="100%" height="1000px" longdesc="#" frameborder="0" marginwidth="0" marginheight="0" scrolling="auto"></iframe></p>

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


<!-- ## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a> -->

## Full List of publications

<iframe id="" style="overflow-x: hidden;" src="http://refbase.cvc.uab.es/show.php?notes=dag&amp;submit=Cite&amp;citeStyle=J%20Glaciol&amp;citeOrder=year&amp;client=inc-refbase-1.0&amp;showLinks=1&amp;showRows=10" width="100%" height="1000px" longdesc="#" frameborder="0" ></iframe>



  


