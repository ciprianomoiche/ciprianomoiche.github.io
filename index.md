---
layout: defautl

---
# {{site.name}}
### {{site.tittle}}  


## notas


<table>
<tr>
  <th style="border: 1px solid ; padding: 10px;">nombre</th>
  <th style="border: 1px solid ; padding: 10px;">notas</th>
  <th style="border: 1px solid ; padding: 10px;">sexo</th>
  
  </tr>

</table>

<table border="1">

{% for alumno in site.data.alumnos %}

<tr>
   <th>{{ alumno.nombre }}</th>
   <th>{{ alumno.notas }}</th>
   <th>{{ alumno.sexo }}</th>
</tr>
{% endfor %}

</table>