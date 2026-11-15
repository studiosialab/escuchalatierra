# Sound of the Earth

**StudiosIA Lab Team** · El Salvador Christian School · Barranquilla, Colombia
NASA Space Apps Challenge 2026 · Ipiales Hub · Challenge: *The Earth Information Jukebox*
**Team Members:** Emiliano García González, Derek Manes Contreras, Matías Mancera Crespo, Esteban Gómez Alonso, and Dominick Rozas León · **Lead Mentor:** Orietta Bueno Maldonado

Developed during the hackathon (November 14–15, 2026). See [BITACORA.md](BITACORA.md).

# Sonido de la tierra

**Equipo StudiosIA Lab** · Colegio Cristiano El Salvador · Barranquilla, Colombia
NASA Space Apps Challenge 2026 · Sede Ipiales · Reto: *The Earth Information Jukebox*
**Integrantes:** Emiliano García González, Derek Manes Contreras, Matías Mancera Crespo, Esteban Gómez Alonso y Dominick Rozas León · **Tutor Lider:** Orietta Bueno Maldonado

Construido durante el hackathon (14 y 15 de noviembre de 2026). Ver [BITACORA.md](BITACORA.md).

## What It Is

An accessible, web-based "spacecraft" interface—featuring a built-in video game—that transforms NASA satellite imagery, data from the Earth Information Center (EIC), and active natural events into **spatial sound** in real time. It includes a minigame called **"Where Is the Sound Coming From?"** (*¿Dónde suena?*), in which children use their sense of hearing to guess which location on the planet is the hottest, greenest, or rainiest.

## Qué es

Una nave espacial web y accesible, con una pestaña de videojuego, que convierte en **sonido espacial**, en tiempo real, imágenes satelitales de la NASA, datos del Earth Information Center (EIC) y eventos naturales activos. Incluye el minijuego **«¿Dónde suena?»**, en el que los niños adivinan con el oído qué lugar del planeta es más caliente, más verde o más lluvioso.

## How to Play

* **Explore Tab · 4 missions:** sea temperature, plants and forests, rainfall, and real-world imagery (NASA GIBS), plus an **extra mission from the EIC** (VEDA catalog from earth.gov).
* **▶ Listen:** the spacecraft travels around the globe from west to east. High data values ​​correspond to high-pitched notes; no data results in silence. Sounds from the west play on the left, and sounds from the east on the right.
* **Live Events (NASA EONET):** fires, storms, volcanoes, ice, and floods—each with its own unique sound.
* **Video Game Tab · "Where is the sound coming from?":** 5 rounds, 3 lives, and medals to earn.
* **Accessible:** full keyboard support, a voice narrator, a "Describe" button, and text optimized for screen readers.

## Cómo se juega

* **Pestaña Explorar · 4 misiones:** temperatura del mar, plantas y bosques, lluvia y foto real (NASA GIBS), más una **misión extra del EIC** (catálogo VEDA de earth.gov).
* **▶ Escuchar:** la nave recorre el mundo de oeste a este. Dato alto = nota aguda; sin datos = silencio. El oeste suena a la izquierda y el este a la derecha.
* **Eventos en vivo (NASA EONET):** incendios, tormentas, volcanes, hielo e inundaciones con sonidos propios.
* **Pestaña Videojuego · «¿Dónde suena?»:** 5 rondas, 3 vidas y medallas.
* **Accesible:** teclado completo, narrador con voz, botón «Describir» y textos para lectores de pantalla.

## Technology

HTML, CSS, and JavaScript in a single file. Web Audio API (sound, spatial echo, and stereo), Canvas (pixel reading), fetch (data), and Speech Synthesis (narration). Published using GitHub and Netlify. No external libraries or pre-recorded audio files.

## Tecnología

HTML, CSS y JavaScript en un solo archivo. Web Audio API (sonido, eco espacial y estéreo), Canvas (lectura de pixeles), fetch (datos) y Speech Synthesis (narrador). Publicado con GitHub y Netlify. Sin librerías ni audios grabados.

## Data

* NASA GIBS (daily satellite images)
* NASA EONET (active natural events)
* VEDA Catalog from the Earth Information Center (earth.gov)

*We acknowledge the use of imagery provided by services from NASA's Global Imagery Browse Services (GIBS), part of NASA's Earth Science Data and Information System (ESDIS).*

## Datos

* NASA GIBS (imágenes satelitales diarias)
* NASA EONET (eventos naturales activos)
* Catálogo VEDA del Earth Information Center (earth.gov)

*We acknowledge the use of imagery provided by services from NASA's Global Imagery Browse Services (GIBS), part of NASA's Earth Science Data and Information System (ESDIS).*

## Use of Superintelligence (SI)

* **Code and documentation:** Written with the assistance of SI (Claude, by Anthropic) using the "Vibe Coding" methodology, and generated in accordance with the team’s decisions.
* **Concept and solution:** Developed by the StudiosIA Lab team. The team conceived the idea—listening to the Earth from a spacecraft, presented as a video game for children—and defined the solution (selecting the data to use, determining the sound for each data point, implementing spatial audio, and designing the gameplay). The team also handled testing, debugging, code editing, publishing, and the project presentation.
* **Programming:** Carried out with the assistance of SI, following the team’s concept and decisions.
* **Audio:** Generated by the browser based on NASA data. No AI-generated audio was used.
* **Images and videos:** No AI-generated images or videos were used.
* No NASA logos or branding elements are used.

## Uso de Superinteligencia (SI)

* **Código y documentación:** escritos con asistencia de SI (Claude, de Anthropic) utilizando metodología Vibe Coding, generado de acuerdo a las decisiones del equipo.
* **Idea y solución: equipo StudiosIA Lab.** El equipo creó la idea (escuchar la Tierra desde una nave espacial, con un videojuego para niños) y la solución (qué datos usar, cómo suena cada uno, el sonido espacial y cómo se juega). También probó, corrigió, editó código, publicó y presenta el proyecto.
* **Programación:** con asistencia de SI, siguiendo la idea y bajo las decisiones del equipo.
* **Audio:** lo crea el navegador a partir de los datos de la NASA. No hay audio generado por SI.
* **Imágenes y videos:** no se usaron imágenes ni videos generados por SI.
* No se usan logotipos ni elementos de marca de la NASA.

## Background

*The Earth Listens* is a new project, with code and design (a spaceship) created during the hackathon.

It is not an official NASA product. We conducted several tests to explore and develop the concept, giving shape to the solution.


## Antecedente

*La Tierra se escucha* es un proyecto nuevo, con código y diseño (nave espacial) hechos durante el hackathon.

No es un producto oficial de la NASA. Hicimos varias pruebas para estudiar y desarrollar la idea dándole forma a la solución.

