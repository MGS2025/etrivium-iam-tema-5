# Tema 5 — Changelog

> **Título oficial**: El personal al servicio de la Administración Pública conforme al texto refundido de la Ley del Estatuto Básico del Empleado Público (RDL 5/2015).

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
