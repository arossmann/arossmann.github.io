---
layout: default
title: Slides
icon: fab fa-slideshare
---

# GitHub Gists

<ul>
 {% for gist in site.data.gists %}
 <li>
       <a href="{{ pres.link }}" target="_blank">
         {{ pres.title }}
       </a>
     </h4>
     <p>
       {{ pres.description }}
     </p>
</li>
{% endfor %}

</ul>