---


---
# {{site.name}}
### {{site.tittle}}  


## notas

<table border="1">
{% for nota in site.data.notas %}

<tr>
   <th>{{ nota.nombre }}</th>
   <th>{{ nota.notas }}</th>
   <th>{{ nota.sexo }}</th>
</tr>

{% endfor %}
</table>