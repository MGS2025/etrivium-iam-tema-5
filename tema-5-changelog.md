# Tema 5 — Changelog

> **Título oficial**: El personal al servicio de la Administración Pública conforme al texto refundido de la Ley del Estatuto Básico del Empleado Público (RDL 5/2015).

---

## v1.6 — 2026-10-06 — Respuestas de la revisión jurídica

**Motivo**: respuestas a las dudas planteadas a la revisión jurídica (06-10-2026).

### Cambios

- **Citas entre corchetes al final del párrafo** (`[CE, art. 14]`) pasan a paréntesis con la ley detrás (`(art. 14 CE)`), el formato de las demás citas de inciso, por decisión de la revisión jurídica (06-10-2026). Se actualiza también la explicación de la convención de citas en Fuentes. Las claves bibliográficas de la tabla de fuentes no cambian.

---

## v1.5 — 2026-10-06 — Revisión de diagramas

**Motivo**: barrido de los diagramas de los 40 temas tras la revisión jurídica y de normas.

### Cambios

- Revisión visual de todos los diagramas, captura a captura (la medición automática no detecta contraste, flechas mal dirigidas ni textos pegados al borde): corregidos textos que se salían de su caja o del lienzo, cajas que se tocaban, flechas que no llegaban a su destino y textos con poco contraste. Sin cambios de contenido.

---

## v1.4 — 2026-10-01 — Revisión jurídica

**Estado**: revisión jurídica aplicada; texto contrastado con el BOE consolidado (TREBEP y Ley 53/1984, consulta 01/10/2026) y con el texto del Acuerdo-Convenio 2019-2022 del Ayuntamiento de Madrid.

### Cambios de la revisión

- §3 y §9: las notas de alcance ya no hacen referencia al origen del material.
- §8.2: «las leyes de cada AP» → «las correspondientes leyes de cada Administración Pública» (literal del art. 24); el resto de usos administrativos del acrónimo AP se sustituyen igualmente (contenido, índice, test, diagramas D5 y D12, título de la página).
- Fuentes: la «Naturaleza de las fuentes» se reescribe sin referencias al material de partida; se elimina la tabla Tier 2 y la fila de trazabilidad asociada; el temario oficial BOAM 10.032 pasa a Tier 1. La Ley 53/1984 y el Acuerdo-Convenio se mantienen (este último identificado con su título completo, periodo 2019-2022, BOAM núm. 8307 de 02/01/2019 y artículos 14.1, 14.7 y 15.l).

### Reglas generales

- **Cajas**: «Dato clave examen» → «Dato clave»; «Cita constitucional» → «Cita normativa»; «Ejemplo Ayto Madrid» → «Ejemplo de aplicación en el Ayto»; «Referencia cruzada» → «Relación con otros temas» (HTML, `.md` y `build_t5.py`). La leyenda ya no promete aparición en el test oficial.
- **Citas de artículos**: «art.» en el paréntesis de inciso y «artículo» cuando la cita forma parte de la oración.
- **Reflexiones y promesas sobre el examen** eliminadas (§9.2, §9.5, §14.2, índice).
- **Correcciones normativas** contra el BOE: art. 1.3 (fundamentos literales); art. 49 (permisos por nacimiento, adopción y del otro progenitor: **19 semanas**, redacción del RDL 9/2025, y permiso parental del art. 49.g); art. 48.a) (accidente o enfermedad graves: 5/4 días hábiles sin distinción de localidad; fallecimiento: 3/5 y 2/4); art. 48.k) (6 días de asuntos particulares) y 48.l); art. 33.1 (principios de la negociación, antes citado como 31.5); art. 36 (materias de la Mesa General de las AAPP); art. 39 (Delegados de Personal: 6 a 49 funcionarios); art. 63.d (separación del servicio, antes citada como art. 66); art. 64.3; art. 67 (sin jubilación «parcial»; añadido el 67.4); art. 68 (rehabilitación: supuestos literales; no aplica a la separación disciplinaria); art. 87.2 (antes 87.3); art. 90.1/90.2; art. 91; art. 95.2.p y 95.3/95.4; art. 96 (tabla de sanciones sin correspondencias que el TREBEP no establece); art. 22.4 (pagas extraordinarias).
- **Test**: 150 preguntas mantenidas; 69 preguntas reescritas o con referencia corregida para ajustarse al texto literal; respuestas correctas reequilibradas en el `.md` (50/50/50). Pedagógicas P4, P5, P7-P10, P15-P19 ajustadas.
- **Casos prácticos** 2, 3, 4, 5 y 6 y **diagramas** D4, D5, D6, D8, D9, D10, D11 y D12 alineados con los cambios anteriores.

---

## v1.3 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~5.000 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 10-12 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.2 — 2026-06-23 — Fix real de diagramas (CSS scoped) + ampliación

**Estado**: Corrige el desbordamiento de texto que María observó en los diagramas.

### Causa raíz encontrada

Los `<style>` embebidos en cada SVG usaban clases genéricas (`.h`, `.t`, `.s`, `.p`) **sin aislar**. Como los 12 SVG conviven en un mismo documento (`index.html`), esas reglas CSS **colisionaban entre sí** y la última definición de cada clase ganaba para todos los SVG. Resultado: en varios diagramas (D3, D7, D9…) el `text-anchor` correcto se sobrescribía y el texto se renderizaba mal anclado, **saliéndose de las cajas**. El fallo NO se veía al abrir un SVG aislado (sin colisión), solo en la página con los 12 juntos — por eso costó localizarlo.

### Cambios

- **Fix**: `build_t5.py` ahora **aísla (scopes) el CSS de cada SVG** a una clase única (`.svdN`), de modo que las reglas de un diagrama no afectan a los demás. Verificado por medición `getBBox` sobre el `index.html` real: **0 textos fuera de su viewBox** (antes, 13).
- **Legibilidad**: la pestaña Diagramas usa además un contenedor más ancho (hasta 1240px) para que los SVG escalen mayor y el texto se lea cómodo al 100%.
- **D2**: el subtítulo de "Personal directivo (art. 13)" era más ancho que su caja → partido en **2 líneas** y caja ensanchada.
- Nota metodológica: la verificación de diagramas pasa a hacerse sobre el `index.html` real (los 12 SVG juntos), no sobre SVG aislados, con medición objetiva por `getBBox` tanto contra el viewBox como **contra la caja contenedora de cada texto**.

---

## v1.1 — 2026-06-23 — Correcciones de María (IAM)

**Estado**: Revisión de María aplicada. Pendiente de validación final.

### Cambios

- **Diagramas (visual)**: corregido el desbordamiento de texto fuera de las cajas en **D12** (mapa-resumen, rediseñado con cajas más anchas y subtítulos a menor tamaño) y ajustados **D10** (caja del Acuerdo-Convenio) y **D5** (última caja). **QA por render (Chrome headless)** para garantizar 0 desbordes en los 12 diagramas.
- **§13 Incompatibilidades**: se retira la etiqueta "pendiente de confirmación". La **Ley 53/1984** se consolida como contenido firme (María confirma que es materia habitual en estas oposiciones).
- **§12.3 Tabla de sanciones**: añadida la columna **"Falta que la origina"** (separación/despido → solo muy graves; suspensión/traslado/demérito → graves o muy graves según ley de FP; apercibimiento → leve).
- **§9.2 Permisos**: la lista del art. 48 se convierte en **tabla**, destacando los días por **grado de parentesco** (1.er grado 3/5 · 2.º grado 2/4), que se confunden en examen.
- **§9.5 (nuevo) Acuerdo-Convenio del Ayuntamiento de Madrid**: nota + referencia cruzada al Tema 9 **y** mini-tabla con datos reales aplicables al IAM (vacaciones por antigüedad: 15/20/25/30 años → +1/+2/+3/+4 días; asuntos particulares: 6 + escala por trienios). Fuente: portal de transparencia del Ayuntamiento de Madrid (arts. 14-15 del Acuerdo-Convenio).
- **Índice y fuentes** actualizados (nueva fuente `[AC-MADRID]`, datos clave de antigüedad y permisos).
- **Acompaña** `informe-correcciones-v1.1.html` con el detalle de los cambios para la revisora.

---

## v1.0 — 2026-06-20 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: **TREBEP (RDL 5/2015)**, versión consolidada del BOE.
- **Material del cliente**: `Tema 5. El Estatuto Básico del Empleado Público.pdf` (resumen del **INSST**, ámbito estatal, feb-2025) + `TEMA_05.docx` (índice oficial).
- **Tratamiento de fuentes**: PDF cliente como base + **contraste con el TREBEP oficial (BOE)**.
- **Tres epígrafes completados desde el BOE** (ausentes en el PDF del cliente pero exigidos por el enunciado oficial):
  1. **Adquisición y pérdida de la relación de servicio** (arts. 55-68).
  2. **Jornada de trabajo, permisos y vacaciones** (arts. 47-51).
  3. **Negociación colectiva, representación y participación institucional** (arts. 31-46).
- **Sección complementaria** de **incompatibilidades** (Ley 53/1984) conservada del PDF, marcada como no exigida literalmente por el enunciado oficial (pendiente de confirmación).
- **Corrección al PDF**: los "principios de conducta" se sitúan en el **art. 54** (el PDF los situaba erróneamente en el art. 53, junto a los principios éticos).
- **Mejora de formato**: se añade la pestaña **Índice** atendiendo al feedback de Jesús sobre el Tema 13.
- **Formato de referencia**: Temas 1-4 (admin): 150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas (+ Índice).

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-5-indice.md` | Índice de 14 secciones + tablas de datos clave |
| `tema-5-fuentes.md` | Registro Tier 1/2/3 + nota sobre el origen INSST del PDF y gaps completados |
| `tema-5-contenido.md` | Contenido teórico (14 secciones, callouts) |
| `tema-5-diagramas.md` | 12 diagramas SVG accesibles |
| `tema-5-test.md` | 150 preguntas + 20 pedagógicas |
| `tema-5-caso-practico.md` | 6 casos prácticos (IAM / Ayto Madrid), 10 pts c/u |
| `tema-5-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, pestañas, motor test 1/3 |

### QA aplicado

- Articulado del PDF cliente contrastado con el texto oficial del TREBEP; epígrafes ausentes completados.
- Datos numéricos sensibles verificados (plazos del interino, excedencias, suspensión, prescripciones, vacaciones).
- Balanceo automático A/B/C de las respuestas del test.
- Refs cruzadas verificadas vs BOAM 10.032 (T1, T4, T9, T10).

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Confirmar tratamiento de la sección complementaria de incompatibilidades.
- Reverificar mínimos de permisos/vacaciones frente al **Acuerdo-Convenio del Ayuntamiento de Madrid** vigente antes de cada convocatoria.
