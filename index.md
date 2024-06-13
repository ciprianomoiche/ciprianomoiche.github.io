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

{% for alumnos in site.data.alumnos %}

<tr>
   <th>{{ alumnos.nombre }}</th>
   <th>{{ alumnos.notas }}</th>
   <th>{{ alumnos.sexo }}</th>
</tr>
{% endfor %}

</table>