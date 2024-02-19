---
title: members

---

# Members


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }} {{ member.position2 }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for perro in site.data.perros %}
  ## {{ perro.raza }} - {{ perro.edad_dueno }} {{ perro.sexo_perro}}
{% endfor %}