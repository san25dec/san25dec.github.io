---
title: "Publications"
layout: gridlay
permalink: /publications/
---


# Publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <span style="color:green; font-size:70%"><em>{{ publi.authors }} </em></span> 
  <span style="color:darkcyan; font-size:70%"><br />{{ publi.venue}}</span>
  <br /><a href="{{publi.link.url }}">
          <i class="fa fa-file-pdf-o"></i>
        </a>

{% endfor %}

