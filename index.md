

<table border="1">

{% for alumno in site.data.alumnos %}
<tr>
   <th>{{alumno.nombre }}</th>
   <th>{{alumno.notas }}</th>
   <th>{{alumno.sexo }}</th>
</tr>
{% endfor %}

</table>