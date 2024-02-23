---
title: Personajes series

---

# Peronajes series

{% for personaje in site.data.personajes %}
  ## {{ personaje.nombre }} - {{ personaje.serie }}
{% endfor %}