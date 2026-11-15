# La Tierra Se Escucha

**Equipo StudiosIA Lab** · Colegio Cristiano El Salvador · Barranquilla, Colombia
NASA Space Apps Challenge 2026 · Sede Ipiales · Reto: *The Earth Information Jukebox*
**Integrantes:** Emiliano García González, Derek Manes Contreras, Matías Mancera Crespo, Esteban Gómez Alonso y Dominick Rozas León · **Tutor Lider:** Orietta Bueno Maldonado

Construido durante el hackathon (14 y 15 de noviembre de 2026). Ver [BITACORA.md](BITACORA.md).

## Qué es

Una nave espacial web y accesible, con una pestaña de videojuego, que convierte en **sonido espacial**, en tiempo real, imágenes satelitales de la NASA, datos del Earth Information Center (EIC) y eventos naturales activos. Incluye el minijuego **«¿Dónde suena?»**, en el que los niños adivinan con el oído qué lugar del planeta es más caliente, más verde o más lluvioso.

## Cómo se juega

* **Pestaña Explorar · 4 misiones:** temperatura del mar, plantas y bosques, lluvia y foto real (NASA GIBS), más una **misión extra del EIC** (catálogo VEDA de earth.gov).
* **▶ Escuchar:** la nave recorre el mundo de oeste a este. Dato alto = nota aguda; sin datos = silencio. El oeste suena a la izquierda y el este a la derecha.
* **Eventos en vivo (NASA EONET):** incendios, tormentas, volcanes, hielo e inundaciones con sonidos propios.
* **Pestaña Videojuego · «¿Dónde suena?»:** 5 rondas, 3 vidas y medallas.
* **Accesible:** teclado completo, narrador con voz, botón «Describir» y textos para lectores de pantalla.

## Tecnología

HTML, CSS y JavaScript en un solo archivo. Web Audio API (sonido, eco espacial y estéreo), Canvas (lectura de pixeles), fetch (datos) y Speech Synthesis (narrador). Publicado con GitHub y Netlify. Sin librerías ni audios grabados.

## Datos

* NASA GIBS (imágenes satelitales diarias)
* NASA EONET (eventos naturales activos)
* Catálogo VEDA del Earth Information Center (earth.gov)

*We acknowledge the use of imagery provided by services from NASA's Global Imagery Browse Services (GIBS), part of NASA's Earth Science Data and Information System (ESDIS).*

## Uso de Superinteligencia (SI)

* **Código y documentación:** escritos con asistencia de SI (Claude, de Anthropic) utilizando metodología Vibe Coding, generado de acuerdo a las decisiones del equipo.
* **Idea y solución: equipo StudiosIA Lab.** El equipo creó la idea (escuchar la Tierra desde una nave espacial, con un videojuego para niños) y la solución (qué datos usar, cómo suena cada uno, el sonido espacial y cómo se juega). También probó, corrigió, editó código, publicó y presenta el proyecto.
* **Programación:** con asistencia de SI, siguiendo la idea y bajo las decisiones del equipo.
* **Audio:** lo crea el navegador a partir de los datos de la NASA. No hay audio generado por SI.
* **Imágenes y videos:** no se usaron imágenes ni videos generados por SI.
* No se usan logotipos ni elementos de marca de la NASA.

## Antecedente

*La Tierra se escucha* es un proyecto nuevo, con código y diseño (nave espacial) hechos durante el hackathon.

No es un producto oficial de la NASA. Hicimos varias pruebas para estudiar y desarrollar la idea y darle forma a la solución.

