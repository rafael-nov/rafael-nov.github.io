---
layout: page
title: Sidequests
permalink: /sidequests/
---

I sometimes share sidequests — things I like to do, in no particular order:

<ul>
{%- for item in site.data.sidequests.interests -%}
  <li>
    {%- if item.url -%}
      <a href="{{ item.url | relative_url }}">{{ item.name }}</a>
    {%- else -%}
      {{ item.name }}
    {%- endif -%}
  </li>
{%- endfor -%}
</ul>
