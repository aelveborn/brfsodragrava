---
layout: map
title: Kontakta oss
permalink: /kontakta/
---

<p>
    Du är välkommen att kontakta styrelsen på mail med frågor eller önskemål.
</p>
<ul class="contact-list">
    {%- if site.email -%}
    <li><a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a></li>
    {%- endif -%}
</ul>