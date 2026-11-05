---
permalink: /
title: "Brisa Cruz"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Soy socióloga por la Pontificia Universidad Católica del Perú y asistente de investigación en GRADE (Grupo de Análisis para el Desarrollo). Trabajo con métodos mixtos: de la entrevista y el taller en comunidades altoandinas a la ENDES, los datos geoespaciales y el procesamiento de lenguaje natural. Me interesa producir evidencia rigurosa sobre el Perú y medir mejor lo social.

## Proyectos

{% for post in site.portfolio %}
<div style="display:flex;gap:1.2em;align-items:flex-start;flex-wrap:wrap;margin:1.5em 0;padding-bottom:1.5em;border-bottom:1px solid #e5e5e5">
  {% if post.header.teaser %}<a href="{{ post.url | relative_url }}" style="flex:0 0 200px"><img src="{{ '/images/' | append: post.header.teaser | relative_url }}" alt="" style="width:200px;max-width:100%;border-radius:6px"></a>{% endif %}
  <div style="flex:1 1 260px">
    <h3 style="margin-top:0"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | markdownify | strip_html }}</p>
    <a href="{{ post.url | relative_url }}">Ver proyecto →</a>
  </div>
</div>
{% endfor %}

## Publicaciones

{% for post in site.publications reversed %}
<p><a href="{{ post.url | relative_url }}"><b>{{ post.title }}</b></a><br>{{ post.citation }}</p>
{% endfor %}

## Qué hago

- **Investigación aplicada.** En GRADE integro datos censales, geoespaciales y entrevistas con expertos para analizar la expansión urbana y las brechas de acceso al agua potable en ocho ciudades peruanas.
- **Diseño de mediciones.** Contribuí al rediseño de una encuesta nacional urbana con metodología CAP y capacité a equipos de campo y técnicos para supervisar y replicar mediciones.
- **Trabajo de campo.** Observación participante, entrevistas y talleres sobre estrategias comunales frente a crisis socioambientales en la sierra.
- **Datos y código.** Python y R para microdatos, mapas, NLP y, ahora, agentes de IA que consultan datos oficiales.

## Formación

- **Bachiller en Sociología**, PUCP (2020–2025). Tercer mejor promedio de la carrera. Miembro del Grupo de Investigación en Estado y Sociedad (GIES).
- **Diplomatura en Ciencia de Datos para las Ciencias Sociales y la Gestión Pública**, Q-Lab PUCP (2026–2027), con beca del 50 % por mérito académico.

## Docencia

- Co-diseñé y co-dicté, con Lucía Díaz, el [Taller Introductorio de Python aplicado a Ciencias Sociales](https://github.com/brisacruz22/python-para-ccss) (Q-Lab PUCP, 2024).
- Asistente de docencia en el Diplomado en Ciencia de Datos para las Ciencias Sociales y la Gestión Pública (ediciones 2024 y 2025).

## CV

[Descargar CV en PDF](/files/cv-brisa-cruz.pdf)
