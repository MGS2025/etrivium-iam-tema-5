# Tema 5 — Checklist de Validación

> **Título oficial**: El personal al servicio de la Administración Pública conforme al TREBEP (RDL 5/2015): clases de personal, adquisición y pérdida, situaciones administrativas, derechos, carrera, evaluación, retribuciones, jornada/permisos/vacaciones y régimen disciplinario.
> **Versión**: 1.4 — Revisión jurídica
> **Fecha**: 2026-10-01
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el **TREBEP (RDL 5/2015)** en su versión consolidada.
- [ ] Todos los epígrafes del enunciado oficial se desarrollan desde el texto oficial del BOE.
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[TREBEP, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del TREBEP, de la Ley 53/1984 o del Acuerdo-Convenio del Ayuntamiento de Madrid.

## 2. Estructura del contenido

- [ ] El `tema-5-indice.md` refleja fielmente la estructura de `tema-5-contenido.md`.
- [ ] Las secciones cubren: clases de personal, adquisición y pérdida, situaciones administrativas, derechos (individuales y colectivos), carrera y promoción interna, evaluación del desempeño, retribuciones, jornada/permisos/vacaciones, negociación y representación, deberes/código de conducta y régimen disciplinario.
- [ ] Los conceptos memorizables aparecen en cajas **Dato clave**.
- [ ] Las reproducciones del articulado aparecen en cajas **Cita normativa**.
- [ ] Los ejemplos del Ayto de Madrid / IAM aparecen en cajas **Ejemplo de aplicación en el Ayto**.
- [ ] Los enlaces a otros temas aparecen en cajas **Relación con otros temas**.

## 3. Rigor jurídico (datos sensibles)

- [ ] Funcionario interino: vacante **3 años**, programas temporales **3 años + 12 meses**, exceso de tareas **9 meses/18** [art. 10].
- [ ] Adquisición de la condición: 4 requisitos sucesivos (proceso → nombramiento → acatamiento → toma de posesión) [art. 62].
- [ ] Renuncia **no inhabilita** para el reingreso [art. 64.3]; separación del servicio firme = causa de pérdida [art. 63.d].
- [ ] Jubilación forzosa **65 años**, prolongación como máximo hasta **70** [art. 67.3].
- [ ] Excedencia voluntaria por interés particular: **5 años** previos, no devenga, no computa [art. 89.2].
- [ ] Excedencia por cuidado de familiares: **3 años**, reserva **2 años**, computa [art. 89.4].
- [ ] Suspensión: pierde puesto si **> 6 meses**; firme disciplinaria máx. **6 años** [art. 90].
- [ ] Derechos individuales (art. 14) vs colectivos (art. 15) bien separados.
- [ ] Carrera: horizontal/vertical + promoción interna vertical/horizontal; **2 años** de antigüedad [arts. 16, 18].
- [ ] Retribuciones básicas = **sueldo + trienios** (PGE) [art. 23].
- [ ] Vacaciones: **22 días hábiles**; sábados no hábiles [art. 50].
- [ ] Permisos por nacimiento: **19 semanas** [art. 49, redacción del RDL 9/2025].
- [ ] Juntas de Personal (**≥50**) vs Delegados (**6 a 49**) [art. 39].
- [ ] Código de conducta: principios éticos **art. 53** / de conducta **art. 54**.
- [ ] Prescripción: faltas **3/2 años y 6 meses**; sanciones **3/2 años y 1 año** [art. 97].

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-5-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid / IAM (Técnico Auxiliar TIC).
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se priorizan los datos numéricos memorísticos (plazos, prescripciones, días de vacaciones).

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), con pestañas y motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencia cruzada al **Tema 1** (acceso por igualdad, mérito y capacidad; arts. 23.2 y 103.3 CE) coherente.
- [ ] Referencia al **Tema 4** (personal directivo / coordinador del distrito) coherente.
- [ ] Referencia al **Tema 9** (PRL, representación y Acuerdo-Convenio del Ayto) coherente.
- [ ] Referencia al **Tema 10** (igualdad y no discriminación) coherente.

---

## Observaciones generales

### Correcciones aplicadas en v1.1

1. **Diagramas reajustados** (D5, D10 y, sobre todo, D12 "mapa-resumen"): se eliminó el desbordamiento de texto fuera de las cajas; verificado por render antes de publicar.
2. **§13 Incompatibilidades consolidada**: se retira la etiqueta "pendiente de confirmación"; la Ley 53/1984 pasa a ser contenido firme del tema.
3. **Tabla de sanciones (§12.3)**: añadida la columna **"Falta que la origina"** para relacionar cada sanción con el tipo de falta.
4. **Permisos (§9.2)**: la lista del art. 48 se convierte en **tabla**, con los días por **grado de parentesco** destacados (1.er grado 3/5 · 2.º grado 2/4).
5. **Acuerdo-Convenio del Ayto. de Madrid (§9.5, nuevo)**: añadida nota + referencia cruzada al Tema 9 **y** mini-tabla con datos reales aplicables al IAM (vacaciones por antigüedad y asuntos particulares).

### Decisiones conscientes que conviene confirmar

1. Los epígrafes (a) adquisición y pérdida de la relación de servicio, (b) jornada/permisos/vacaciones, y (c) negociación colectiva, representación y participación se desarrollan desde el texto oficial del TREBEP (BOE). → Confirmar que el alcance es el correcto.
2. **Principios éticos = art. 53** y **principios de conducta = art. 54**.
3. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 8 pestañas (con pestaña Índice)**, replicando el formato de los Temas 1-4 + la mejora de Índice del Tema 13.
4. **Balanceo automático A/B/C** mediante permutación determinista en `build_t5.py`.

### Puntos a vigilar (datos volátiles)

- Los **permisos y vacaciones** y los **órganos de representación** del personal municipal se regulan también en el **Acuerdo-Convenio del Ayuntamiento de Madrid** vigente; reverificar el Acuerdo-Convenio antes de cada convocatoria.
- Las **faltas graves** se establecen por ley (o convenio, para el personal laboral) y las **leves** por las leyes de Función Pública [art. 95.3 y 95.4].

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
