---
title: File List
---
<h1>File List3</h1>
{{ site.static_files }}
  <ul>
    {% for files in site.static_files %}
        <li class="timeline_card">
        {{ files.path }}::{{ files.url }}
       </li>
    {% endfor %}
  </ul>
