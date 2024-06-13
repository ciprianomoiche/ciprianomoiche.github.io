---


---
# {{site.name}}
### {{site.tittle}}  


## notas


{% for nota in site.data.alumnos %}

   {{ nota.nombre }}
   {{ nota.notas }}
   {{ nota.sexo }}

{% endfor %}
