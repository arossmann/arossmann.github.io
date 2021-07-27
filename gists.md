---
layout: default
title: Gists
icon: far fa-file-code
---

# GitHub Gists

<ul>
 {% for gist in site.data.gists %}
 <li>
       <h4>
        <a href="{{ gist.link }}" target="_blank">
         {{ gist.title }}
       </a>
     </h4>
     <p>
       {{ gist.description }}
     </p>
</li>
{% endfor %}

</ul>