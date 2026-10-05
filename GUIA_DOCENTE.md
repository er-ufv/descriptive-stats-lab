# Guía docente · ¿Qué dicen tus datos?

Herramienta interactiva de estadística descriptiva para **Fundamentos de Investigación en Psicología** (1.º, Facultad de Psicología y Educación, Universidad Francisco de Vitoria). Acompaña al **Tema 3: El proceso de análisis descriptivo de los datos**.

- **Autoría:** diseño docente y contenidos de Eduar Ramírez (UFV); código generado con Claude (Anthropic). Contenidos bajo CC BY 4.0 y código bajo MIT (ver `LICENSE-CONTENIDOS.md`).
- **Archivo:** `index.html` (un solo archivo, sin dependencias externas: funciona en GitHub Pages y sin conexión).
- **Duración:** 6 misiones de 10-15 minutos + reto final.
- **Datos:** 120 estudiantes **simulados** (91 mujeres, 25 hombres y 4 personas que marcan «otro / prefiere no decirlo»), con semilla fija: toda la clase ve los mismos números.
- **Privacidad:** la página no registra ni envía nada. Las respuestas solo existen en el navegador del estudiante y se borran al cerrar la pestaña.

---

## Ficha pedagógica

| | |
|---|---|
| **Objetivo** | Al terminar, el estudiante podrá identificar el tipo de variable y elegir medidas y gráficos adecuados; calcular e interpretar media, mediana, moda, percentiles, rango, varianza y desviación típica; describir la forma de una distribución y justificar qué medida la resume mejor. |
| **Procesos que moviliza** | Activación previa (predicción en Inicio, revelada en la Misión 5); generación antes de la revelación (las preguntas y las predicciones desbloquean los laboratorios); ejemplos resueltos con desvanecimiento (ejemplo completo → con huecos → sin ayuda); feedback elaborado con escalera de ayudas (pista → segunda pista → solución); juicio de confianza y calibración final; construcción (reto «construye tu grupo» en la Misión 4); autoexplicación con respuesta modelo (reto final); interacción en parejas. |
| **Uso sugerido** | Una misión por bloque del Tema 3, seguida de 5 min de puesta en común. Reto final y repaso, una semana después. |
| **Cómo saber si funciona** | Ver la sección «Evaluar la herramienta». |
| **Límites** | Datos simulados y más limpios que los reales. La herramienta está *diseñada para movilizar* estos procesos; su efecto en el aprendizaje debe comprobarse. No sustituye la práctica con SPSS o jamovi. |

---

## Uso sugerido en clase

| Momento | Qué | Tiempo |
|---|---|---|
| Antes de clase | Inicio (predicción) + Misión 1 | 15 min |
| Bloque «Frecuencias y contingencia» | Misión 1, paso 4 (modelo de relación × sexo) | 10 min + debate |
| Bloque «Tendencia central» | Misión 2 (proyectar los laboratorios de los pasos 3 y 4) | 15 min |
| Bloque «Posición» | Misión 3 | 10 min |
| Bloque «Dispersión» | Misión 4 (reto «construye tu grupo» en parejas) | 15 min |
| Bloque «Normal, asimetría y curtosis» | Misión 5 | 15 min |
| Bloque «Gráficos» | Misión 6 | 10 min |
| Una semana después | Reto final + «Repaso en una semana» + CSV en jamovi/SPSS | 20-30 min |

**Cierre del docente:** pedir que algunas personas lean su respuesta del reto final y contrastarla en voz alta con la respuesta modelo.

---

## Preguntas para el debrief

1. En el calentamiento, ¿cuántas personas predijeron «50 %»? ¿Por qué es una intuición tan común? *(Se confunde la media con la mediana.)*
2. **Modelo de relación × sexo:** ¿qué diferencia hay entre «el 64 % de los hombres de la clase prefiere pareja monógama» y «a los chicos no les van las relaciones estables»? ¿Qué estereotipos aparecen cuando leemos mal un porcentaje? ¿Puede una tabla descriptiva decirnos *por qué* hay diferencias?
3. En el laboratorio de la Misión 2, ¿por qué la media «se mueve» y la mediana no? Relacionarlo con la idea de la media como punto de equilibrio.
4. ¿Por qué una desviación típica de 0 es posible pero una negativa no?
5. ¿En qué variables de vuestra vida esperáis asimetría positiva? *(Ingresos, seguidores, gasto, tiempo de trayecto, horas de videojuegos.)*
6. ¿Qué información añade la desviación típica a un titular que solo da la media?

---

## Errores frecuentes esperados

| Error | Dónde aparece |
|---|---|
| Tratar códigos numéricos de categorías como cuantitativos | Misión 1, pregunta 3 |
| Calcular porcentajes por fila cuando se comparan grupos en columnas | Misión 1, contingencia |
| Pasar de un porcentaje de grupo a una afirmación sobre cada persona, o a una explicación causal | Misión 1, modelo de relación |
| Interpretar porcentajes de grupos muy pequeños sin dar el n | Misión 1, grupo de n = 4 |
| Usar la media con variables ordinales o nominales | Misión 2, paso 5 |
| Pensar que la media es siempre «lo típico» aunque haya valores extremos | Misión 2, pasos 2-4 y reto final |
| Confundir percentil con nota o con porcentaje de aciertos | Misión 3, pregunta 1 |
| Interpretar dos percentiles de variables distintas como información conjunta | Misión 3, pregunta 3 |
| Leer el signo de la asimetría por el lado donde se amontonan los datos y no por la cola | Misión 5 |
| Mezclar desviación típica poblacional (fórmula de clase, entre N) y muestral (software, entre n − 1) | Misión 4 |

---

## Evaluar la herramienta

La propia página no recoge datos. Propuesta mínima, proporcionada a un aula:

1. **Pregunta:** ¿mejora la transferencia (aplicar a un caso nuevo) frente a la misma actividad en papel?
2. **Comparación honesta:** mismo contenido y mismas preguntas en dos formatos (herramienta frente a ficha en papel o diapositivas), para separar el método del medio.
3. **Asignación:** por grupo-aula o por sesión; si no es aleatoria, usar la nota previa como covariable.
4. **Medida diferida:** 4-6 preguntas de transferencia una semana después (por ejemplo, un caso nuevo con asimetría en el que haya que elegir y justificar media o mediana), más un juicio de confianza por pregunta para estudiar la calibración.
5. **Análisis:** tamaños de efecto con intervalos; con grupos pequeños, evitar conclusiones fuertes.
6. **Ética:** participación voluntaria, sin nota asociada, identificadores seudónimos. Si se quisiera registrar el uso desde la página, haría falta un servidor con autenticación, aviso de tratamiento de datos (RGPD) y seudónimos: no basta con una página estática.

---

## Publicar en GitHub Pages

1. Subir el contenido de la carpeta al repositorio, con `index.html` en la raíz.
2. *Settings → Pages → Deploy from a branch → main / (root).*
3. Compartir el enlace en Canvas. Las páginas de Canvas eliminan los `<script>`, por lo que hay que **enlazar** la herramienta, no pegar su código.

La base de datos simulada también está en `datos/encuesta_genz_simulada.csv` por si se quiere repartir directamente para las prácticas con jamovi o SPSS.

---

## Fuentes de los ejemplos

Los datos de la herramienta son simulados, pero los ejemplos y las cifras de referencia proceden de:

- INJUVE (2025). [*Informe Juventud en España 2024*](https://www.injuve.es/sites/default/files/EJ190/02_INFORME-JUVENTUD-2024_RESUMEN.pdf). Tiempo de conexión (el 59 % se conecta 4 h o más al día), redes más usadas (WhatsApp, Instagram, TikTok), ocio, apuestas online (≈18 %), estudiar y trabajar (23 %).
- Centro Reina Sofía de Fad Juventud (2025). [*Barómetro Juventud y Género 2025*](https://www.pensamientocritico.org/wp-content/uploads/2026_Fad_Barometro.Genero.2025-Informe.pdf). Prefiere pareja monógama el 77,5 % de las mujeres y el 63,1 % de los hombres (15-29 años); tiene pareja actualmente el 60,6 % y el 47,2 %, respectivamente.
- [Spotify Wrapped 2025, España](https://www.infobae.com/espana/cultura/2025/12/03/los-artistas-espanoles-mas-escuchados-del-ano-segun-el-wrapped-2025-de-spotify-del-reinado-de-quevedo-y-aitana-a-la-irrupcion-de-rosalia/): Bad Bunny, Quevedo, Myke Towers, Aitana y KAROL G, entre lo más escuchado.
- [Gasto de jóvenes de 18-24 años en festivales (datos de Revolut, 2026)](https://www.marketingdirecto.com/anunciantes-general/publicaciones/gasto-festivales-espana-generacion-z-revolut-2026).
- [Estudio sobre la «previa» y el ocio de la Generación Z](https://www.vozpopuli.com/bienestar/la-generacion-z-cambia-el-ocio-en-espana-el-74-ya-considera-la-previa-un-plan-en-si-mismo.html).
- [Proyecto «Desconéctate para conectar»](https://www.investigacion.us.es/noticias/el-uso-del-movil-entre-los-jovenes-andaluces-supera-las-cuatro-horas-diarias-en-fin-de-semana) (Universidades de Sevilla, Jaén y Cádiz): tiempo de pantalla de jóvenes.

> Conviene revisar estas cifras antes de usarlas en una publicación o documento formal.
