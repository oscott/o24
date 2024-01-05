---
layout: home
---
{% for page in site.pages %}  
    <li>
        <a href="{{ page.url }}"> {{ page.title }}</a>
    </li>  
{% endfor %}
<sub><sup>Agree to T&C before looking</sup></sub>
