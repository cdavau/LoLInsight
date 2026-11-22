# LoLINSIGHT

> Plataforma web que consume las APIs de **League of Legends** para consultar campeones, objetos (items), estadísticas de jugadores y noticias del juego en un solo lugar.

---

## Descripción

LoLINSIGHT es un sitio web informativo sobre League of Legends, el videojuego multijugador de Riot Games. Nace de la necesidad de reunir la enorme cantidad de información del juego (más de 160 campeones y 260 objetos) en una plataforma organizada, rápida y atractiva, donde cualquier usuario —nuevo o veterano— pueda consultar datos de forma sencilla.

El proyecto pone en práctica el **consumo de APIs reales**, el trabajo en equipo y la organización de un proyecto web, integrando información en tiempo real directamente desde los servicios oficiales del juego.

---

## Funcionalidades

- **Inicio:** página principal con banner, menú de navegación y las últimas noticias del juego.
- **Campeones (Champions):** galería de todos los campeones con buscador y filtros por rol/estilo (Asesinos, etc.). Las tarjetas usan un efecto *flip* estilo 3D que, al presionarlas, muestran el lore, habilidades y descripción del campeón.
- **Objetos (Items):** cuadrícula dinámica de los objetos del juego con buscador y filtros, y detalle de cada ítem en un modal.
- **Jugadores (Player):** búsqueda de una cuenta por nombre y región para visualizar el nivel, el rango en clasificatorias y el historial de partidas.
- **Sobre Nosotros:** apartado con la información del equipo desarrollador.

---

## Tecnologías utilizadas

- **HTML5** — estructura de las páginas.
- **CSS3** — identidad visual (colores oscuros inspirados en el juego con detalles dorados), diseño responsive y estilos coherentes en todas las vistas.
- **JavaScript** — lógica de la aplicación, consumo de datos y funciones dinámicas (búsquedas, filtros, modales y tarjetas interactivas).
- **Data Dragon API (Riot Games)** — fuente de datos de campeones e ítems.

---

## Estructura del proyecto

```
LoLINSIGHT/
├── index.html        # Página de inicio + noticias + Sobre Nosotros
├── champions.html    # Galería y detalle de campeones
├── items.html        # Galería y detalle de objetos del juego
├── player.html       # Búsqueda y estadísticas de jugadores
├── styles.css        # Estilos e identidad visual del sitio
└── image/            # Imágenes del equipo, noticias y recursos
```

---


## Equipo de desarrollo

Proyecto desarrollado en equipo para la asignatura **Desarrollo de Software V**:

- Carlos Abadía
- Joss Mendieta
- Aaron Gálvez
- Edwin Jiménez
- Carlos Abraham

> **Mi rol en el proyecto:** 

Lideré la integración de las APIs de League of Legends (Data Dragon), implementando el consumo de datos en tiempo real para los campeones y objetos del juego. Además, fui responsable del diseño y los estilos de la página: definí la identidad visual, maqueté las vistas y aseguré una experiencia coherente y atractiva en todo el sitio.

---

## Contexto académico

- **Universidad:** Universidad Tecnológica de Panamá (UTP)
- **Facultad:** Ingeniería de Sistemas Computacionales (FISC)
- **Carrera:** Licenciatura en Desarrollo y Gestión de Software
- **Asignatura:** Desarrollo de Software V

---
