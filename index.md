---
layout: default

---
# {{site.name}}
### {{site.tittle}}  


## notas




<table border="1">

{% for alumnos in site.data.alumnos %}

<tr>
   <th>{{ alumnos.nombre }}</th>
   <th>{{ alumnos.notas }}</th>
   <th>{{ alumnos.sexo }}</th>
</tr>
{% endfor %}

</table>