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

You can use the [editor on GitHub](https://github.com/oscarnovillo/oscarnovillo.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image]({{ site.url }}/test/index.html)

[Link](url) and ![Image]({{ site.url }}/assets/img/logo-Jekyll.png)
```

![Image](/assets/img/logo-jekyll.png)

| Tipo de Pienso | Descripción                                            | Marca           |
|----------------|--------------------------------------------------------|---------------------|
| Pienso seco    | Croquetas secas que proporcionan nutrición completa.  | Royal Canin Medium  |
| Pienso húmedo  | Comida enlatada con alto contenido de humedad.        | Hill's Science Diet |
| Pienso natural | Elaborado con ingredientes naturales y sin aditivos.  | Taste of the Wild   |
| Pienso dietético | Formulado para necesidades dietéticas específicas.  | Purina Veterinary Diets |