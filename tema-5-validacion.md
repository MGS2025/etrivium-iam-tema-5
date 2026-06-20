# Tema 5 — Checklist de Validación

> **Título oficial**: El personal al servicio de la Administración Pública conforme al TREBEP (RDL 5/2015): clases de personal, adquisición y pérdida, situaciones administrativas, derechos, carrera, evaluación, retribuciones, jornada/permisos/vacaciones y régimen disciplinario.
> **Versión**: 1.0
> **Fecha**: 2026-06-20
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el **TREBEP (RDL 5/2015)** en su versión consolidada.
- [ ] El PDF aportado por el cliente (INSST) se ha usado como base y **se han completado los epígrafes ausentes** desde el texto oficial del BOE.
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[TREBEP, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del TREBEP o a la Ley 53/1984.

## 2. Estructura del contenido

- [ ] El `tema-5-indice.md` refleja fielmente la estructura de `tema-5-contenido.md`.
- [ ] Las secciones cubren: clases de personal, adquisición y pérdida, situaciones administrativas, derechos (individuales y colectivos), carrera y promoción interna, evaluación del desempeño, retribuciones, jornada/permisos/vacaciones, negociación y representación, deberes/código de conducta y régimen disciplinario.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayto de Madrid / IAM están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico (datos sensibles)

- [ ] Funcionario interino: vacante **3 años**, programas temporales **3 años + 12 meses**, exceso de tareas **9 meses/18** [art. 10].
- [ ] Adquisición de la condición: 4 requisitos sucesivos (proceso → nombramiento → acatamiento → toma de posesión) [art. 62].
- [ ] Renuncia **no inhabilita**; separación del servicio **sí** [arts. 64, 66].
- [ ] Jubilación forzosa **65 años**, prorrogable hasta **70** [art. 67].
- [ ] Excedencia voluntaria por interés particular: **5 años** previos, no devenga, no computa [art. 89.2].
- [ ] Excedencia por cuidado de familiares: **3 años**, reserva **2 años**, computa [art. 89.4].
- [ ] Suspensión: pierde puesto si **> 6 meses**; firme disciplinaria máx. **6 años** [art. 90].
- [ ] Derechos individuales (art. 14) vs colectivos (art. 15) bien separados.
- [ ] Carrera: horizontal/vertical + promoción interna vertical/horizontal; **2 años** de antigüedad [arts. 16, 18].
- [ ] Retribuciones básicas = **sueldo + trienios** (PGE) [art. 23].
- [ ] Vacaciones: **22 días hábiles**; sábados no hábiles [art. 50].
- [ ] Permisos por nacimiento: **16 semanas** [art. 49].
- [ ] Juntas de Personal (**≥50**) vs Delegados (**<50**) [art. 39].
- [ ] Código de conducta: principios éticos **art. 53** / de conducta **art. 54** (corrige el error del PDF, que situaba ambos en el art. 53).
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

### Decisiones conscientes que conviene confirmar

1. **El PDF del cliente es del INSST (ámbito estatal), no de Madrid**, y **omite tres epígrafes** del enunciado oficial del Tema 5: (a) adquisición y pérdida de la relación de servicio, (b) jornada/permisos/vacaciones, y (c) negociación colectiva, representación y participación. **Se han completado desde el texto oficial del TREBEP (BOE)**. → Confirmar que el alcance es el correcto.
2. **El PDF añade un epígrafe de incompatibilidades (Ley 53/1984)** que **no figura** en el enunciado oficial del Tema 5. Se ha conservado como **sección complementaria marcada** (§13). → Confirmar si se mantiene o se retira.
3. **Corrección detectada en el PDF**: situaba los "principios éticos" y los "principios de conducta" **ambos en el art. 53**. Lo correcto es **principios éticos = art. 53** y **principios de conducta = art. 54**. Se ha corregido.
4. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas (+ pestaña Índice)**, replicando el formato de los Temas 1-4. Se ha **añadido la pestaña Índice** atendiendo al feedback de Jesús sobre el Tema 13.
5. **Balanceo automático A/B/C** mediante permutación determinista en `build_t5.py`.

### Puntos a vigilar (datos volátiles)

- Los **permisos y vacaciones** y los **órganos de representación** pueden estar mejorados por el **Acuerdo-Convenio del Ayuntamiento de Madrid** vigente. Los mínimos del TREBEP son el suelo; reverificar el Acuerdo-Convenio antes de cada convocatoria.
- Las **faltas graves y leves** dependen de la legislación de Función Pública aplicable.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
