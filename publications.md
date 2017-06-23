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
  
  <p style="border: 1px solid steelblue; width: 50px; text-align: center; height: 30px; line-height: 30px; border-radius: 10px; color: steelblue; display: inline-block; font-size:70%">
  <a href="{{publi.url}}">
    PDF 
  </a>
  </p>
  
  {% if publi.project != "" and publi.project != nil %}
  <p style="border: 1px solid steelblue; width: 70px; text-align: center; height: 30px; line-height: 30px; border-radius: 10px; color: steelblue; display: inline-block; font-size:70%">
  <a href="{{publi.baseurl}}{{publi.project}}">
    Project
  </a>
  </p>
  {% endif %}

  {% if publi.code != "" and publi.code != nil %}
  <p style="border: 1px solid steelblue; width: 60px; text-align: center; height: 30px; line-height: 30px; border-radius: 10px; color: steelblue; display: inline-block; font-size:70%">
  <a href="{{publi.baseurl}}{{publi.code}}">
    Code
  </a>
  </p>
  {% endif %}

{% endfor %}

