---
permalink: /
title: "Brisa Cruz"
author_profile: true
header:
  image: hero-laguna.jpg
redirect_from:
  - /about/
  - /about.html
---

Soy socióloga por la Pontificia Universidad Católica del Perú y asistente de investigación en GRADE (Grupo de Análisis para el Desarrollo). Trabajo con métodos mixtos: de la entrevista y el taller en comunidades altoandinas a la ENDES, los datos geoespaciales y el procesamiento de lenguaje natural. Me interesa producir evidencia rigurosa sobre el Perú y medir mejor lo social.

## Formación

- **Bachiller en Sociología**, PUCP (2020–2025). Tercer mejor promedio de la carrera. Miembro del Grupo de Investigación en Estado y Sociedad (GIES).
- **Diplomatura en Ciencia de Datos para las Ciencias Sociales y la Gestión Pública**, Q-Lab PUCP (2026–2027), con beca del 50 % por mérito académico.

## Qué hago

- **Investigación aplicada.** En GRADE integro datos censales, geoespaciales y entrevistas con expertos para analizar la expansión urbana y las brechas de acceso al agua potable en ocho ciudades peruanas.
- **Diseño de mediciones.** Contribuí al rediseño de una encuesta nacional urbana con metodología CAP y capacité a equipos de campo y técnicos para supervisar y replicar mediciones.
- **Trabajo de campo.** Observación participante, entrevistas y talleres sobre estrategias comunales frente a crisis socioambientales en la sierra.
- **Datos y código.** Python y R para microdatos, mapas, NLP y, ahora, agentes de IA que consultan datos oficiales.

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

## Trabajo de campo

<div class="campo">

<h3>Expansión urbana y acceso al agua en ocho ciudades</h3>
<p class="campo-meta">GRADE, por encargo de la Confederación de Desarrolladores Inmobiliarios del Perú (CODIP) · 2026 · Asistente de investigación</p>
<div class="campo-fotos"><figure><a href="/images/campo-urbano-proceso.jpg" target="_blank" rel="noopener"><img src="/images/campo-urbano-proceso.jpg" alt="Polígono informal_20 trazado a mano sobre imagen satelital"></a><figcaption>Proceso: clasificación manual de la expansión. Imagen satelital: Google Earth.</figcaption></figure><figure><a href="/images/campo-urbano-arequipa.jpg" target="_blank" rel="noopener"><img src="/images/campo-urbano-arequipa.jpg" alt="Mapa de expansión urbana formal e informal en Arequipa, 2017–2024" style="object-fit:contain;background:#fff"></a><figcaption>Resultado: expansión formal e informal en Arequipa, 2017–2024.</figcaption></figure></div>
<p>Colaboré en la estimación de cuántas de las nuevas edificaciones levantadas entre 2017 y 2024 en Arequipa, Chiclayo, Huancayo, Ica, Lima, Piura, Tarapoto y Trujillo acceden a agua potable. Combiné la cartografía oficial de manzanas, Open Buildings y datos de SUNASS, y clasifiqué a mano la expansión formal e informal con imágenes satelitales y Street View.</p>
<p>Resultados preliminares en El Comercio: <a href="https://elcomercio.pe/economia/obras-de-saneamiento-demoraron-casi-dos-anos-en-pasar-de-las-inmobiliarias-a-las-empresas-de-agua-segun-grade-noticia/" target="_blank" rel="noopener">nota 1</a> · <a href="https://elcomercio.pe/lima/sucesos/la-ciudad-crece-mas-rapido-que-las-redes-de-agua-por-que-la-brecha-sigue-aumentando-pese-a-la-inversion-apuesplan-noticia/" target="_blank" rel="noopener">nota 2</a></p>

<h3>Familias ganaderas frente a crisis en Tanta, Yauyos</h3>
<p class="campo-meta">GRADE · noviembre–diciembre 2024 · Asistente de investigación en campo</p>
<div class="campo-fotos"><img src="/images/campo-yauyos-alpacas.jpg" alt="Alpacas en un corral de piedra en la puna de Yauyos"><img src="/images/campo-yauyos-mapa.jpg" alt="Mapa parlante elaborado en un taller"><img src="/images/campo-yauyos-taller.jpg" alt="Taller con madres de familia ganaderas"></div>
<p>Tres semanas en campo para una investigación ganadora de CONCYTEC-PROCIENCIA. Entrevisté a actores de tres niveles: familias ganaderas, organizaciones comunales y de base, e instituciones públicas presentes en el territorio. Con madres ganaderas facilité talleres de mapa parlante y línea de tiempo, y con adolescentes, uno sobre proyectos de vida. También visité estancias de pastoreo.</p>
<p><a href="https://doi.org/10.18800/kawsaypacha.202602.A018" target="_blank" rel="noopener">Leer el artículo en Kawsaypacha</a></p>

<h3>El Fenómeno del Niño y la escuela peruana</h3>
<p class="campo-meta">PUCP-CISE · enero 2024 · Asistencia de investigación documental</p>
<div class="campo-fotos"><img src="/images/campo-fen-2.jpg" alt="Diario de 1998 sobre escolares afectados por el Fenómeno del Niño"><img src="/images/campo-fen-1.jpg" alt="Diario sobre el regreso a clases tras el Fenómeno del Niño"></div>
<p>En la Biblioteca Central de la PUCP fotografié y sistematicé prensa de los episodios de 1982-1983, 1997-1998 y 2016-2017 para reconstruir cómo respondió el Estado ante el impacto del Niño en las escuelas. El trabajo alimentó el libro de Manuel Etesse (PUCP, 2025).</p>
<p><a href="http://hdl.handle.net/20.500.14657/206922" target="_blank" rel="noopener">Ver la publicación</a></p>

<h3>Cacao y cambio climático en Chazuta, San Martín</h3>
<p class="campo-meta">Curso de trabajo de campo, PUCP · octubre 2023 · Co-investigadora, en un equipo de tres</p>
<div class="campo-fotos"><img src="/images/campo-chazuta-2.jpg" alt="Mazorcas de cacao en Chazuta"><img src="/images/campo-chazuta-1.jpg" alt="Atardecer en Chazuta"></div>
<p>Entrevisté a familias cacaoteras de tres generaciones, a ingenieros de una cooperativa y de una ONG, y a la lideresa de una organización local de mujeres. Facilité un taller de mapa parlante para ubicar zonas protegidas, de avistamiento de fauna y donde más se nota el cambio climático. Encontramos una nueva ruralidad con economías familiares diversificadas: cacao, piscicultura, chocolate, ropa, caucho y hotelería.</p>

</div>

<style>
.campo h3 { margin-top: 2em; }
.campo-meta { color: #6b6b6b; font-size: .9em; margin-top: -.6em; }
.campo-fotos { display: flex; gap: .6em; flex-wrap: wrap; margin: .8em 0; }
.campo-fotos figure { margin: 0; flex: 1 1 220px; max-width: 340px; }
.campo-fotos figure img { width: 100%; max-width: none; }
.campo-fotos figcaption { font-size: .75em; color: #6b6b6b; margin-top: .3em; }
.campo-fotos img { flex: 1 1 180px; max-width: 260px; height: 200px; object-fit: cover; border-radius: 6px; }
</style>

## Publicaciones

{% for post in site.publications reversed %}
<p><a href="{{ post.url | relative_url }}"><b>{{ post.title }}</b></a><br>{{ post.citation }}</p>
{% endfor %}

## Docencia

- Co-diseñé y co-dicté, con Lucía Díaz, el [Taller Introductorio de Python aplicado a Ciencias Sociales](https://github.com/brisacruz22/python-para-ccss) (Q-Lab PUCP, 2024).
- Asistente de docencia en el Diplomado en Ciencia de Datos para las Ciencias Sociales y la Gestión Pública (ediciones 2024 y 2025).

## CV

<a href="/files/cv-brisa-cruz.pdf" target="_blank" rel="noopener">Visualizar el CV en PDF</a>
