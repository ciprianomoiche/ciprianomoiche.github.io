---


---
# {{site.name}}
### {{site.tittle}}  


## notas

<table border="1">
{% for nota in site.data.alumnos %}

<tr>
   <th>{{ nota.nombre }}</th>
   <th>{{ nota.notas }}</th>
   <th>{{ nota.sexo }}</th>
</tr>

{% endfor %}
</table>