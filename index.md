---


---
# {{site.name}}
### {{site.tittle}}  






## JSON
### INFORMACION DE LOS ESTUDIANTES
<table border="1">
{% for nota in site.data.notas %}

<tr>
   <th>{{ nota.nombre }}</th>
   <th>{{ nota.notas }}</th>
   <th>{{ nota.sexo }}</th>
</tr>

{% endfor %}
</table>