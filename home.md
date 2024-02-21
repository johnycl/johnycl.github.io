---
title: home
permalink: /
---

## Welcome to {{site.title}} {{page.title}} 
<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>
 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


![Image](/assets/img/perros-personalidad-2.jpg)

| Tipo de Pienso | Descripción                                            | Marca           |
|----------------|--------------------------------------------------------|---------------------|
| Pienso seco    | Croquetas secas que proporcionan nutrición completa.  | Royal Canin Medium  |
| Pienso húmedo  | Comida enlatada con alto contenido de humedad.        | Hill's Science Diet |
| Pienso natural | Elaborado con ingredientes naturales y sin aditivos.  | Taste of the Wild   |
| Pienso dietético | Formulado para necesidades dietéticas específicas.  | Purina Veterinary Diets |