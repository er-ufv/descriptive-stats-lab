# ¿Qué dicen tus datos? · Estadística descriptiva interactiva

Aplicación web interactiva para aprender **estadística descriptiva** en 1.º de **Fundamentos de Investigación en Psicología** (Facultad de Psicología y Educación, Universidad Francisco de Vitoria). Acompaña al **Tema 3: El proceso de análisis descriptivo de los datos**.

Funciona como una *Shiny app* de estadística: el estudiante mueve deslizadores, cambia los datos y ve al momento cómo cambian las medidas y los gráficos. Pero es una sola página HTML: funciona en el navegador y en el móvil, sin instalar R ni ningún programa, y se puede publicar gratis con GitHub Pages.

**Abrir la aplicación:** `https://<tu-usuario>.github.io/descriptive-stats-lab/` *(sustituye `<tu-usuario>` por tu usuario de GitHub cuando actives GitHub Pages)*.

> **In English:** *Descriptive Stats Lab* is an interactive, Shiny-style web app for learning descriptive statistics in first-year Psychology (Universidad Francisco de Vitoria, Spain). Students move sliders, change the data and instantly see how the mean, median, mode, percentiles, spread and shape respond. It runs entirely in the browser (single HTML file, no installation, mobile-friendly) and is grounded in learning-science principles (prediction before feedback, hint ladders, confidence ratings, faded worked examples). The interface and content are in Spanish. Code: MIT; content: CC BY 4.0.

---

## Contenido

| Sección | Qué practica el estudiante |
|---|---|
| Inicio | Objetivos y una predicción de calentamiento (se revela en la Misión 5) |
| 1 · Variables | Tipos de variables, tablas de frecuencias, tablas de contingencia (modelo de relación preferido × sexo) |
| 2 · Tendencia central | Media, mediana y moda, con laboratorios: la media como punto de equilibrio, valores extremos, asimetría y mediana con categorías ordenadas |
| 3 · Posición | Cuartiles, percentiles y diagrama de caja con la posición del propio estudiante |
| 4 · Dispersión | Rango, varianza y desviación típica; reto «construye tu grupo» |
| 5 · Forma | Asimetría, curtosis, curva normal y puntuaciones z |
| 6 · Gráficos | Elegir el gráfico adecuado y detectar gráficos engañosos |
| Reto final | Caso nuevo (apuestas online) con autoexplicación y respuesta modelo |
| Cierre | Ideas clave, calibración de la confianza, repaso espaciado y descarga de los datos en CSV |
| Acerca de | Descripción de la herramienta y autoría |

## Cómo está diseñada

La herramienta se apoya en principios de la psicología del aprendizaje:

- **Predecir o responder antes de ver la solución.** Los laboratorios se desbloquean al resolver la pregunta previa.
- **Escalera de ayudas:** pista → segunda pista → solución explicada.
- **Juicio de confianza** en cada pregunta y resumen de calibración al final.
- **Ejemplos resueltos que se van retirando:** ejemplo completo → con huecos → sin ayuda.
- **Preguntas de transferencia** (casos nuevos) y **tareas en parejas**.
- **Lenguaje cercano:** recuadros «Dicho fácil» al inicio de cada misión.

La guía para el profesorado está en [`GUIA_DOCENTE.md`](GUIA_DOCENTE.md).

## Estructura del repositorio

```
.
├── index.html                          # La aplicación (un solo archivo, sin dependencias externas)
├── README.md                           # Este archivo
├── GUIA_DOCENTE.md                     # Uso en clase, debrief, errores frecuentes, evaluación y fuentes
├── LICENSE                             # Licencia MIT (código)
├── LICENSE-CONTENIDOS.md               # Licencia CC BY 4.0 (contenidos) y cómo citar
└── datos/
    └── encuesta_genz_simulada.csv      # Base de datos simulada para practicar en jamovi o SPSS
```

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a un repositorio de GitHub (con `index.html` en la raíz).
2. En el repositorio: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**.
3. En uno o dos minutos la aplicación estará en `https://<tu-usuario>.github.io/descriptive-stats-lab/`.
4. Comparte ese enlace en Canvas. Las páginas de Canvas eliminan el código JavaScript, así que hay que **enlazar** la aplicación, no pegar su código.

Para probarla en local, basta con abrir `index.html` en el navegador.

## Datos y privacidad

- Los datos son **simulados** (120 estudiantes ficticios: 91 mujeres, 25 hombres y 4 personas que marcan «otro / prefiere no decirlo»), con una semilla fija para que toda la clase vea los mismos números.
- Están inspirados en fuentes reales sobre jóvenes en España: *Informe Juventud en España 2024* (INJUVE), *Barómetro Juventud y Género 2025* (Fad Juventud), Spotify Wrapped 2025 y estudios sobre ocio y uso del móvil. Las referencias completas están en la guía docente.
- La aplicación **no recoge, guarda ni envía** ninguna respuesta. Todo ocurre en el navegador del estudiante y se borra al cerrar la página.

## Autoría

- **Diseño docente y contenidos:** Eduar Ramírez, profesor de Fundamentos de Investigación en Psicología, Facultad de Psicología y Educación, Universidad Francisco de Vitoria.
- **Código:** generado con [Claude](https://www.anthropic.com/claude) (Anthropic), a partir de las indicaciones y la revisión del docente.

El logotipo y la identidad visual de la Universidad Francisco de Vitoria pertenecen a la universidad y se usan con fines docentes, en el marco de la actividad del profesorado de la institución.

## Licencia

- **Código** (HTML, CSS y JavaScript): [MIT](LICENSE).
- **Contenidos didácticos** (textos, ejercicios, guía docente y datos simulados): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Se pueden reutilizar y adaptar citando la autoría.
- **Logotipo de la UFV:** excluido de ambas licencias. Si reutilizas la aplicación fuera de la UFV, retíralo.

Detalles y forma de citar en [`LICENSE-CONTENIDOS.md`](LICENSE-CONTENIDOS.md).
