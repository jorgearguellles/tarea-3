# Tarea 3 — Línea de tiempo comparativa: Carl Jung y Fritz/Laura Perls

**Curso:** Enfoques Clásicos de la Psicología  
**Institución:** Universidad Nacional Abierta y a Distancia (UNAD)  
**Código del curso:** 402537619  
**Año:** 2026

Este repositorio contiene la entrega de la **Tarea 3**, orientada a los principios teóricos y metodológicos del **Psicoanálisis** y la **Gestalt**. El producto principal es una página web que presenta una **línea de tiempo comparativa** entre **Carl Jung** (Psicoanálisis Analítico) y **Fritz y Laura Perls** (Terapia Gestalt), articulando hitos biográficos, conceptos centrales y puntos de convergencia y divergencia respecto al psicoanálisis freudiano.

---

## Cómo visualizar el trabajo

1. Abra el archivo [`index.html`](index.html) en cualquier navegador web (Chrome, Firefox, Safari, Edge, etc.).
2. Puede hacer doble clic sobre el archivo o arrastrarlo a una ventana del navegador.
3. No se requiere servidor ni instalación de programas. La visualización funciona sin internet; la **descarga automática de PDF** requiere conexión la primera vez (carga la librería html2pdf.js). Sin internet, el botón abre el diálogo de impresión para guardar como PDF.

Al abrir la página verá la línea de tiempo, podrá hacer clic en cada hito para ampliar la información y, al final, consultar una tabla comparativa de ambos enfoques.

### Descargar PDF

En la parte superior de la página hay un botón **Descargar PDF** que exporta la línea de tiempo **completa** (los 12 hitos con su texto ampliado y la tabla comparativa).

1. Haga clic en **Descargar PDF**.
2. Si hay conexión a internet, el navegador generará y descargará automáticamente el archivo `linea-de-tiempo-jung-perls-tarea3.pdf`.
3. Si no hay conexión o falla la descarga automática, se abrirá el **diálogo de impresión** del navegador: elija **Guardar como PDF** como destino y confirme.

La exportación expande temporalmente todos los hitos para incluir el detalle completo en el documento.

---

## Contenido de `index.html`

La página se organiza en cuatro bloques principales:

1. **Encabezado** — Identificación de la tarea, el curso y los autores comparados.
2. **Leyenda** — Convención de colores para distinguir hitos de Jung, de los Perls y de relación entre enfoques.
3. **Línea de tiempo** — Doce hitos cronológicos con tarjetas expandibles.
4. **Tabla comparativa** — Síntesis en cinco dimensiones teóricas más una fila sobre el origen común freudiano.

### Convención de colores

| Color / posición | Autor(es) | Cantidad |
|------------------|-----------|----------|
| Índigo (izquierda) | Carl Jung — Psicoanálisis Analítico | 5 hitos |
| Verde (derecha) | Fritz y Laura Perls — Terapia Gestalt | 5 hitos |
| Ámbar (centro) | Relación o comparación entre enfoques | 2 hitos |

### Hitos cronológicos (12 en total)

#### Carl Jung (5 hitos)

| Año | Título | Etiqueta |
|-----|--------|----------|
| 1875 | Nacimiento e infancia espiritual | Contexto biográfico |
| 1900–1910 | Formación y encuentro con Freud | Hito teórico |
| 1921 | Inconsciente colectivo y arquetipos (*Tipos Psicológicos*) | Concepto central |
| 1930s–1950s | Proceso de individuación | Método terapéutico |
| 1948–1961 | Instituto C.G. Jung y legado | Legado |

#### Fritz y Laura Perls (5 hitos)

| Año | Título | Etiqueta |
|-----|--------|----------|
| 1893 · 1905 | Nacimientos: Fritz y Laura | Contexto biográfico |
| 1920s–1930s | Formación psicoanalítica y primeras divergencias | Hito teórico |
| 1942 | Primera obra: ruptura con el psicoanálisis (*El Yo, el Hambre y la Agresión*) | Obra clave |
| 1951 | Fundación formal de la Terapia Gestalt (*Gestalt Therapy*) | Obra clave |
| 1960s–1990 | Expansión, silla vacía y legado | Legado |

#### Relación entre enfoques (2 hitos)

| Año | Título | Etiqueta |
|-----|--------|----------|
| ~1913–1935 | Ruptura con Freud: dos caminos distintos | Influencia compartida |
| ~1950s | Inconsciente simbólico vs. experiencia presente | Comparación teórica |

### Tabla comparativa final

Al cierre de la página se incluye una tabla que contrasta ambos enfoques en estas dimensiones:

- **Objeto de estudio** — Psique profunda e inconsciente colectivo (Jung) vs. experiencia presente y contacto organismo-entorno (Perls).
- **Método** — Análisis de sueños, imaginación activa, amplificación simbólica vs. awareness, silla vacía, experimentación corporal.
- **Temporalidad** — Pasado, símbolos y arquetipos vs. presente (“aquí y ahora”).
- **Visión del ser humano** — Individuación y totalidad psíquica vs. contacto auténtico y autorregulación.
- **Origen** — Ambos parten del psicoanálisis freudiano y lo critican y superan desde perspectivas distintas.

---

## Interactividad y forma de presentación

- Cada hito se muestra como una **tarjeta** con un resumen breve visible de inmediato.
- Al **hacer clic** en la tarjeta (o activarla con teclado), se despliega un **detalle ampliado** con mayor profundidad conceptual o biográfica.
- El botón **Descargar PDF** genera un documento con todo el contenido expandido (ver sección anterior).
- La línea de tiempo usa un diseño **vertical**: los hitos de Jung aparecen a la izquierda, los de los Perls a la derecha, y los hitos compartidos quedan **centrados**.
- En pantallas pequeñas (móvil), el diseño se adapta a **una sola columna** para facilitar la lectura.

---

## Ideas conceptuales que articula la entrega

**Carl Jung:** inconsciente colectivo, arquetipos (Sombra, Ánima/Ánimus, Self), individuación, análisis de sueños e imaginación activa. El cambio terapéutico se vincula a integrar contenidos simbólicos del inconsciente.

**Fritz y Laura Perls:** awareness (darse cuenta), contacto, figura-fondo, ciclo de la experiencia y énfasis en el presente terapéutico. El cambio se vincula a recuperar el contacto auténtico con el entorno en el “aquí y ahora”.

Ambos autores **parten del psicoanálisis freudiano** y lo **superan** por caminos distintos: Jung amplía el inconsciente hacia lo transpersonal y simbólico; los Perls desplazan el foco hacia la experiencia consciente y corporal del presente.

---

## Aspectos técnicos de la entrega

- Archivo único (`index.html`) con HTML, CSS y JavaScript integrados; sin dependencias externas ni frameworks.
- Idioma de la interfaz: español.
- Accesibilidad básica: roles ARIA, estados `aria-expanded` en tarjetas expandibles, contraste de color pensado para legibilidad (criterios WCAG documentados en el código).
- Diseño **responsive** para lectura en computador y dispositivos móviles.

---

## Archivos del repositorio

```
tarea-3/
├── index.html   ← Entrega principal (abrir en navegador)
└── README.md    ← Este documento (guía para la evaluación)
```

---

## Nota para la evaluación

Este README describe el contenido y la estructura de la entrega para facilitar su revisión. La evidencia completa del trabajo — textos ampliados, citas de obras y desarrollo argumentativo — se encuentra en [`index.html`](index.html), que puede consultarse directamente en el navegador sin necesidad de revisar el código fuente.
