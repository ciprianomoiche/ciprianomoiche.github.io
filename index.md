---
layout: default

---
# {{site.name}}
### {{site.tittle}}  


## students




<table border="1">


<tr>
   <th>nombre</th>
   <th>notas</th>
   <th>sexo</th>
</tr>


{% for alumno in site.data.alumnos %}
<tr>
   <th>{{ alumno.nombre }}</th>
   <th>{{ alumno.notas }}</th>
   <th>{{ alumno.sexo }}</th>
</tr>
{% endfor %}

</table>