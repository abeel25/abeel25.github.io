---
title: Personajes series

---

# Peronajes series


{% for personaje in data.personajes %}
  ## {{ personaje.name }} - {{ personaje.position }}
  {{ personaje.content | markdownify }}
{% endfor %}


{% for personaje in site.data.personajes %}
  ## {{ personajes.nombre }} - {{ personajes.serie }}
{% endfor %}