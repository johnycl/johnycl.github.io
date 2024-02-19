---
title: Perros

---

<h1>Raza de perro, edad y sexo </h1>
<table>
  <thead>
    <tr>
      <th>Raza</th>
      <th>Edad del Dueño</th>
      <th>Sexo del Perro</th>
    </tr>
  </thead>
  <tbody>
    {% for perro in site.data.perros %}
      <tr>
        <td>{{ perro.raza }}</td>
        <td>{{ perro.edad_dueno }}</td>
        <td>{{ perro.sexo_perro }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>