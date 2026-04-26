# Claude.md — Instrucciones del Proyecto: El Estado del Ser

## Contexto del Proyecto

**"El Estado del Ser"** es un álbum de música de meditación y relajación basado en las enseñanzas del Ho'oponopono, la antigua técnica hawaiana de reconciliación y sanación interior.

## Rol Asignado a Claude

Psicólogo con experiencia en terapias holísticas (especialmente Ho'oponopono), con habilidades artísticas y de desarrollo web.

## Tareas Realizadas

### 1. Revisión y Mejora del Documento Word
- Lectura del archivo `El_Estado_del_Ser.docx`
- Revisión del texto de la historia, frases principales, palabras gatillo y beneficios
- Mejora del lenguaje: positivo, liberador, motivador, de aceptación y amor

### 2. Mejora de Letras de Canciones
- Se revisaron y mejoraron las 10 letras originales con lenguaje más positivo, liberador y motivador
- Se expandieron las letras cortas para una duración estimada de 5 a 8 minutos
- Se mantuvo la coherencia temática con el Ho'oponopono

### 3. Tres Canciones Adicionales
Se agregaron 3 canciones adicionales con el mismo estilo, y se reordenó el cierre:
- **Canción 10: Fuego que Sana** — Liberación de la Ira
- **Canción 11: El Abrazo del Perdón** — Liberación de la Culpa
- **Canción 12: Más Allá del Umbral** — Liberación del Miedo
- **Canción 13: Retorno al Puerto** — Cierre y Protección *(canción de cierre del álbum, originalmente la 10)*

Para cada canción adicional se generó:
- Imagen representativa (descripción en `/images/`)
- Descripción breve para la "Guía del Viajero"
- Letra completa al estilo del álbum
- Instrucciones para producción en Suno AI

### 4. Documentación
- `README.md`: Versión mejorada y completa del documento original con todas las canciones
- `Claude.md`: Este archivo con instrucciones del proyecto

### 5. Página Web
- `index.html`: Sitio web completo con tema espiritual y de sanación
- Paleta de colores: `#EEFABD`, `#A0D585`, `#6984A9`, `#263B6A`
- Secciones: Historia, Beneficios, Frases, Palabras Gatillo, Guía del Viajero, Letras
- Links temporales de YouTube (inactivos hasta tener la lista real)

### 6. Repositorio GitHub
- Repositorio: `https://github.com/jlomeli71/el_estado_del_ser`
- Todos los archivos generados subidos al repositorio

## Estructura de Archivos

```
el_estado_del_ser/
├── Claude.md           ← Este archivo
├── README.md           ← Documento principal del proyecto
├── index.html          ← Página web
└── images/
    ├── README.md               ← Descripción e instrucciones de imágenes
    ├── cancion_01_mantra.jpg
    ├── cancion_02_lluvia.jpg
    ├── cancion_03_hielo.jpg
    ├── cancion_04_hojas.jpg
    ├── cancion_05_luz.jpg
    ├── cancion_06_paz.jpg
    ├── cancion_07_vinculos.jpg
    ├── cancion_08_memoria.jpg
    ├── cancion_09_aliento.jpg
    ├── cancion_10_ira.jpg
    ├── cancion_11_culpa.jpg
    ├── cancion_12_miedo.jpg
    └── cancion_13_retorno.jpg
```

## Tecnologías Usadas

- **Pandoc**: Lectura del archivo .docx
- **HTML5 / CSS3 / JavaScript**: Página web
- **Google Fonts**: Tipografía espiritual (Cormorant Garamond + Nunito)
- **Suno AI**: Producción musical (instrucciones incluidas en README.md)
- **Git / GitHub**: Control de versiones y repositorio público

## Fuentes de Referencia

- NotebookLM: https://notebooklm.google.com/notebook/b25d2e2e-9224-4ea4-b7a8-2a1c5369485f/
- Paleta de colores: https://colorhunt.co/palette/eefabda0d5856984a9263b6a

## Notas

- Las instrucciones de Suno AI están incluidas en cada sección de canción en el README.md (en la web solo se eliminan conforme se publican los videos reales)
- Los links de YouTube se activan progresivamente conforme se suben los videos
- Las imágenes decorativas del .docx original no se incluyeron en el markdown (solo descripciones de prompt)
- Canción 1 ya tiene link real de YouTube: https://youtu.be/PaUH2Qn-Brc?si=L3zllZRjOD8BAj-u
- Canción 2 ya tiene link real de YouTube: https://youtu.be/lVFkq6GPEgo
- Álbum completo (playlist): https://www.youtube.com/playlist?list=PLhHPSBekmq--K6s-AqKRwjCdmfcQsmBWN

---

## Tareas Siguientes

### 7. Publicación del Sitio Web (Despliegue Automático desde GitHub)

El sitio es HTML/CSS/JS puro — no requiere servidor ni proceso de compilación. Las tres mejores opciones para publicarlo con despliegue automático al hacer `git push` son:

---

#### Opción A: GitHub Pages ⭐ (Recomendada — más simple)

**Ventajas:** Gratuito, sin cuenta adicional, URL directa desde el repositorio actual.

**Pasos:**
1. Ir a: `https://github.com/jlomeli71/el_estado_del_ser/settings/pages`
2. En **Source** seleccionar: `Deploy from a branch`
3. En **Branch** seleccionar: `main` / `/ (root)`
4. Guardar — en 1-2 minutos el sitio estará en:
   `https://jlomeli71.github.io/el_estado_del_ser/`
5. Cada `git push` a `main` actualiza el sitio automáticamente.

**Limitación:** La URL incluye el nombre del repositorio (a menos que uses dominio propio).

---

#### Opción B: Netlify

**Ventajas:** URL personalizable, dominio propio gratuito (`tudominio.netlify.app`), más fácil conectar dominio propio.

**Pasos:**
1. Crear cuenta en https://netlify.com (gratis)
2. "Add new site" → "Import an existing project" → GitHub
3. Seleccionar repositorio `el_estado_del_ser`
4. En **Build settings** dejar todo en blanco (no hay proceso de build)
5. Deploy — URL tipo: `https://el-estado-del-ser.netlify.app`
6. Cada `git push` a `main` actualiza el sitio automáticamente.

---

### 8. Agregar las Imágenes a la Página Web

Actualmente las imágenes JPG están en el repositorio pero no se muestran en `index.html`.
Pendiente: integrarlas en la sección de la Guía del Viajero o en cada panel de letras.

### 9. Links de YouTube Pendientes

Activar los links de YouTube conforme se suban los videos de las canciones 3-13.
Para cada canción: cambiar `href="#"` por el link real y quitar `(próximamente)`.

## Tareas Completadas (Sesión Anterior)

- ✅ "Outro" → "Final" en index.html (13 ocurrencias)
- ✅ Secciones "Intro" eliminadas de la página web (mantenidas en README.md)
- ✅ Bloques de instrucciones Suno AI eliminados de la página web (mantenidos en README.md)
- ✅ Link YouTube Canción 1 actualizado: https://youtu.be/PaUH2Qn-Brc?si=L3zllZRjOD8BAj-u
- ✅ Modal YouTube embebido: al dar clic muestra imagen, título y reproductor en la misma página
- ✅ Imágenes de canciones integradas en la Guía del Viajero (thumbnails 72×72px)
- ✅ Datos (data-song, data-yt, data-img) en los 13 track-items y 13 lyric-panels
- ✅ 3 colores nuevos agregados: --amethyst #9B7EC8, --amber #E8A83A, --mist #D6EAE0
- ✅ Mejoras de diseño CSS (hero gradient, section-label, track hover, lyric header, bridge)
- ✅ Notas de Ceeport y Unihipili agregadas en README.md (primeras menciones relevantes)
