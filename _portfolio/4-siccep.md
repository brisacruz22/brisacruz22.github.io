---
title: "Los 564 continuos poblados oficiales del Perú, listos para descargar"
excerpt: "Extraje la base geográfica detrás del geovisor SICCEP del Ministerio de Vivienda, que no ofrece descarga directa."
collection: portfolio
---

**Pregunta.** ¿Cómo trabajar con las ciudades del Perú según cómo crecen de verdad, y no según límites distritales?

**Qué hice.** El Ministerio de Vivienda publicó una tipología oficial de ciudades basada en continuos poblados, pero su geovisor (SICCEP) no permite descargar las capas. Identifiqué el servicio ArcGIS REST que alimenta el visor y reconstruí una consulta estable para descargar la capa completa desde R con `sf`.

**Resultado.** Una base de 564 continuos poblados con sus geometrías, categoría y población al 2025. Los conteos por categoría coinciden exactamente con el geovisor. Se puede descargar en GeoPackage y RDS.

[Código y datos en GitHub](https://github.com/brisacruz22/webscrapeando-geovisor-SICCEP)
