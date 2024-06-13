---
layout: default

---


<table border="1">


<tr>
   <th>nombre</th>
   <th>notas</th>
   <th>sexo</th>
</tr>


{% for alumnos in site.data.alumnos %}
<tr>
   <th>{{ alumnos.nombre }}</th>
   <th>{{ alumnos.notas }}</th>
   <th>{{ alumnos.sexo }}</th>
</tr>
{% endfor %}

</table>