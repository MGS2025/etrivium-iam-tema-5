# Tema 5 — Catálogo de Diagramas

> **Título oficial**: El personal al servicio de la Administración Pública conforme al TREBEP (RDL 5/2015).
>
> **Versión**: 1.2 — tipografía ampliada y cajas más holgadas (legibilidad al 100%)
> **Fecha**: 2026-06-23
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                                  | Sección | Tipo |
|-----|---------------------------------------------------------|---------|------|
| D1  | El TREBEP: objeto, ámbito y estructura                  | § 1     | Esquema |
| D2  | Clases de personal al servicio de las AAPP             | § 2     | Árbol |
| D3  | Funcionario interino: supuestos y plazos               | § 2     | Lista |
| D4  | Adquisición y pérdida de la relación de servicio       | § 3     | Flujo |
| D5  | Las cinco situaciones administrativas                  | § 4     | Mapa |
| D6  | Modalidades de excedencia y sus efectos                | § 4     | Comparativa |
| D7  | Derechos individuales (art. 14) vs colectivos (art. 15)| § 5     | Comparativa |
| D8  | Carrera profesional y promoción interna                | § 6     | Árbol |
| D9  | Retribuciones: básicas vs complementarias              | § 8     | Comparativa |
| D10 | Jornada, permisos y vacaciones                         | § 9     | Esquema |
| D11 | Régimen disciplinario: faltas, sanciones y prescripción| § 12    | Flujo |
| D12 | Mapa-resumen del Tema 5                                 | § 14    | Mapa conceptual |

---

## D1 · El TREBEP: objeto, ámbito y estructura

**Sección**: § 1 — El TREBEP
**Propósito**: Situar la norma (RDL 5/2015) y a quién se aplica.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="El TREBEP, aprobado por el Real Decreto Legislativo 5/2015, establece las bases del régimen estatutario y se aplica a la Administración del Estado, comunidades autónomas, entidades locales, organismos públicos y universidades públicas">
  <style>
    .h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:13px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="180" y="20" width="340" height="56" rx="8" fill="#003d75"/>
  <text x="350" y="44" class="h">TREBEP · RDL 5/2015, de 30 de octubre</text>
  <text x="350" y="63" class="h" style="font-weight:400;font-size:11px">Bases del régimen estatutario de los funcionarios</text>
  <line x1="350" y1="76" x2="350" y2="100" stroke="#0055a0" stroke-width="1.5"/>
  <text x="350" y="116" class="s" style="font-weight:700;fill:#0055a0">ÁMBITO DE APLICACIÓN (art. 2)</text>
  <rect x="20" y="135" width="125" height="70" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="82" y="165" class="t">Admón. Gral.</text>
  <text x="82" y="183" class="t">del Estado</text>
  <rect x="160" y="135" width="125" height="70" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="222" y="165" class="t">CCAA y</text>
  <text x="222" y="183" class="t">Ceuta/Melilla</text>
  <rect x="300" y="135" width="125" height="70" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="362" y="165" class="t" style="font-weight:700">Entidades</text>
  <text x="362" y="183" class="t" style="font-weight:700">Locales</text>
  <rect x="440" y="135" width="125" height="70" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="502" y="158" class="t">Organismos</text>
  <text x="502" y="176" class="t">públicos y</text>
  <text x="502" y="194" class="t">agencias</text>
  <rect x="580" y="135" width="100" height="70" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="630" y="165" class="t">Univ.</text>
  <text x="630" y="183" class="t">Públicas</text>
  <rect x="160" y="230" width="380" height="62" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="350" y="255" class="s" style="font-weight:700;fill:#b5740f">Ayuntamiento de Madrid = Entidad Local</text>
  <text x="350" y="276" class="s">su personal se rige por el TREBEP como norma básica</text>
</svg>
```

---

## D2 · Clases de personal al servicio de las AAPP

**Sección**: § 2 — Clases de personal
**Propósito**: Distinguir las cuatro clases de empleados públicos más el personal directivo.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="Los empleados públicos se clasifican en funcionarios de carrera, funcionarios interinos, personal laboral y personal eventual; el personal directivo se regula aparte en el artículo 13">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="16" width="220" height="46" rx="8" fill="#003d75"/>
  <text x="360" y="37" class="h">EMPLEADOS PÚBLICOS</text>
  <text x="360" y="54" class="h" style="font-weight:400;font-size:10.5px">art. 8 TREBEP</text>
  <line x1="360" y1="62" x2="360" y2="78" stroke="#0055a0"/>
  <line x1="90" y1="95" x2="630" y2="95" stroke="#0055a0"/>
  <line x1="90" y1="95" x2="90" y2="110" stroke="#0055a0"/>
  <line x1="270" y1="95" x2="270" y2="110" stroke="#0055a0"/>
  <line x1="450" y1="95" x2="450" y2="110" stroke="#0055a0"/>
  <line x1="630" y1="95" x2="630" y2="110" stroke="#0055a0"/>
  <rect x="20" y="110" width="140" height="92" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="90" y="132" class="t" style="font-weight:700">Funcionario</text>
  <text x="90" y="149" class="t" style="font-weight:700">de carrera</text>
  <text x="90" y="170" class="s">relación estatutaria</text>
  <text x="90" y="186" class="s">permanente (art. 9)</text>
  <rect x="200" y="110" width="140" height="92" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="270" y="132" class="t" style="font-weight:700">Funcionario</text>
  <text x="270" y="149" class="t" style="font-weight:700">interino</text>
  <text x="270" y="170" class="s">temporal, por</text>
  <text x="270" y="186" class="s">necesidad/urgencia (10)</text>
  <rect x="380" y="110" width="140" height="92" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="450" y="132" class="t" style="font-weight:700">Personal</text>
  <text x="450" y="149" class="t" style="font-weight:700">laboral</text>
  <text x="450" y="170" class="s">contrato de trabajo</text>
  <text x="450" y="186" class="s">fijo/indef./temp. (11)</text>
  <rect x="560" y="110" width="140" height="92" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="630" y="132" class="t" style="font-weight:700">Personal</text>
  <text x="630" y="149" class="t" style="font-weight:700">eventual</text>
  <text x="630" y="170" class="s">confianza/asesor.;</text>
  <text x="630" y="186" class="s">libre cese (art. 12)</text>
  <rect x="110" y="236" width="500" height="82" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="262" class="t" style="font-weight:700;fill:#b5740f">Personal directivo (art. 13)</text>
  <text x="360" y="284" class="s">funciones directivas profesionales ·</text>
  <text x="360" y="301" class="s">designación por mérito e idoneidad · sujeto a evaluación</text>
</svg>
```

---

## D3 · Funcionario interino: supuestos y plazos

**Sección**: § 2 — Clases de personal
**Propósito**: Memorizar los cuatro supuestos del art. 10 y sus plazos.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Los cuatro supuestos del funcionario interino: vacante máximo tres años, sustitución transitoria el tiempo necesario, programas temporales tres años más doce meses, y exceso o acumulación de tareas nueve meses en dieciocho">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a}
    .p{font:700 13px system-ui,sans-serif;fill:#d13c3c;text-anchor:end}
  </style>
  <rect x="190" y="16" width="320" height="40" rx="8" fill="#003d75"/>
  <text x="350" y="41" class="h">FUNCIONARIO INTERINO · art. 10</text>
  <rect x="40" y="76" width="620" height="44" rx="6" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="56" y="103" class="t">a) Plazas vacantes sin cobertura por funcionario de carrera</text>
  <text x="644" y="103" class="p">máx. 3 años</text>
  <rect x="40" y="128" width="620" height="44" rx="6" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="56" y="155" class="t">b) Sustitución transitoria de los titulares</text>
  <text x="644" y="155" class="p">tiempo necesario</text>
  <rect x="40" y="180" width="620" height="44" rx="6" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="56" y="207" class="t">c) Ejecución de programas de carácter temporal</text>
  <text x="644" y="207" class="p">3 años + 12 meses</text>
  <rect x="40" y="232" width="620" height="44" rx="6" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="56" y="259" class="t">d) Exceso o acumulación de tareas</text>
  <text x="644" y="259" class="p">9 meses / 18 meses</text>
</svg>
```

---

## D4 · Adquisición y pérdida de la relación de servicio

**Sección**: § 3 — Adquisición y pérdida
**Propósito**: Los cuatro requisitos de adquisición (art. 62) y las causas de pérdida (art. 63).

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 320" role="img" aria-label="La condición de funcionario se adquiere por superación del proceso, nombramiento, acatamiento de la Constitución y toma de posesión; se pierde por renuncia, pérdida de nacionalidad, jubilación, separación del servicio o inhabilitación">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:11px system-ui,sans-serif;fill:#555;text-anchor:start}
  </style>
  <rect x="40" y="16" width="300" height="38" rx="8" fill="#2d8659"/>
  <text x="190" y="40" class="h">ADQUISICIÓN (art. 62)</text>
  <rect x="380" y="16" width="300" height="38" rx="8" fill="#d13c3c"/>
  <text x="530" y="40" class="h">PÉRDIDA (art. 63)</text>
  <rect x="40" y="70" width="300" height="34" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="92" class="t">1. Superación del proceso selectivo</text>
  <rect x="40" y="110" width="300" height="34" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="132" class="t">2. Nombramiento (diario oficial)</text>
  <rect x="40" y="150" width="300" height="34" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="172" class="t">3. Acatamiento de la Constitución</text>
  <rect x="40" y="190" width="300" height="34" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="212" class="t">4. Toma de posesión</text>
  <text x="190" y="250" class="t" style="font-size:11px;fill:#1f5e3f">requisitos sucesivos y acumulativos</text>
  <rect x="380" y="70" width="300" height="26" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="396" y="88" class="s">a) Renuncia (no inhabilita · art. 64)</text>
  <rect x="380" y="100" width="300" height="26" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="396" y="118" class="s">b) Pérdida de la nacionalidad (art. 65)</text>
  <rect x="380" y="130" width="300" height="26" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="396" y="148" class="s">c) Jubilación (art. 67)</text>
  <rect x="380" y="160" width="300" height="26" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="396" y="178" class="s">d) Separación del servicio (sanción · 66)</text>
  <rect x="380" y="190" width="300" height="26" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="396" y="208" class="s">e) Inhabilitación absoluta o especial (66)</text>
  <rect x="380" y="228" width="300" height="40" rx="6" fill="#fff5e6" stroke="#e89822"/>
  <text x="530" y="246" class="t" style="font-size:11px;fill:#b5740f">Jubilación forzosa: 65 años</text>
  <text x="530" y="262" class="t" style="font-size:11px;fill:#b5740f">(prorrogable hasta los 70)</text>
</svg>
```

---

## D5 · Las cinco situaciones administrativas

**Sección**: § 4 — Situaciones administrativas
**Propósito**: Visualizar las cinco situaciones del art. 85.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Las cinco situaciones administrativas del funcionario: servicio activo, servicios especiales, servicio en otras administraciones públicas, excedencia y suspensión de funciones">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="230" y="16" width="240" height="40" rx="8" fill="#003d75"/>
  <text x="350" y="41" class="h">SITUACIONES (art. 85)</text>
  <rect x="30" y="90" width="120" height="80" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="90" y="120" class="t" style="font-weight:700">Servicio</text>
  <text x="90" y="138" class="t" style="font-weight:700">activo</text>
  <text x="90" y="158" class="s">todos los derechos</text>
  <rect x="166" y="90" width="120" height="80" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="226" y="116" class="t" style="font-weight:700">Servicios</text>
  <text x="226" y="134" class="t" style="font-weight:700">especiales</text>
  <text x="226" y="156" class="s">conserva trienios</text>
  <rect x="302" y="90" width="120" height="80" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="362" y="116" class="t" style="font-weight:700">Servicio en</text>
  <text x="362" y="134" class="t" style="font-weight:700">otras AAPP</text>
  <text x="362" y="156" class="s">destino en otra AP</text>
  <rect x="438" y="90" width="120" height="80" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="498" y="124" class="t" style="font-weight:700">Excedencia</text>
  <text x="498" y="150" class="s">5 modalidades</text>
  <rect x="574" y="90" width="110" height="80" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="629" y="116" class="t" style="font-weight:700">Suspensión</text>
  <text x="629" y="134" class="t" style="font-weight:700">de funciones</text>
  <text x="629" y="156" class="s" style="font-size:9.5px">pierde puesto si >6 m.</text>
  <rect x="120" y="210" width="460" height="44" rx="6" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="350" y="237" class="s" style="font-weight:700;fill:#0055a0">El reingreso al servicio activo se regula en el art. 91</text>
</svg>
```

---

## D6 · Modalidades de excedencia y sus efectos

**Sección**: § 4 — Situaciones administrativas
**Propósito**: Comparar las excedencias por requisito, retribución y reserva de puesto.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="Comparativa de excedencias: voluntaria por interés particular exige cinco años y no retribuye; por cuidado de familiares dura tres años con reserva de puesto dos años; por violencia de género no exige tiempo previo y reserva el puesto seis meses">
  <style>
    .h{font:700 12px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:11.5px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="180" y="14" width="360" height="34" rx="8" fill="#003d75"/>
  <text x="360" y="36" class="h">EXCEDENCIA · art. 89</text>
  <rect x="20" y="62" width="220" height="240" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="130" y="86" class="t" style="font-weight:700">Interés particular</text>
  <text x="130" y="118" class="s">Requisito:</text>
  <text x="130" y="134" class="t" style="font-weight:700;fill:#d13c3c">5 años previos</text>
  <text x="130" y="166" class="s">Retribución:</text>
  <text x="130" y="182" class="t">NO devenga</text>
  <text x="130" y="214" class="s">Cómputo:</text>
  <text x="130" y="230" class="t">NO computa</text>
  <text x="130" y="262" class="s">Reserva puesto:</text>
  <text x="130" y="278" class="t">NO</text>
  <rect x="250" y="62" width="220" height="240" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="360" y="86" class="t" style="font-weight:700">Cuidado familiares/hijos</text>
  <text x="360" y="118" class="s">Duración:</text>
  <text x="360" y="134" class="t" style="font-weight:700;fill:#1f5e3f">máx. 3 años</text>
  <text x="360" y="166" class="s">Cómputo:</text>
  <text x="360" y="182" class="t">SÍ (trienios/carrera)</text>
  <text x="360" y="214" class="s">Reserva puesto:</text>
  <text x="360" y="230" class="t" style="font-weight:700">2 años</text>
  <text x="360" y="262" class="s">luego misma localidad</text>
  <text x="360" y="278" class="s">e igual retribución</text>
  <rect x="480" y="62" width="220" height="240" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="590" y="86" class="t" style="font-weight:700">Violencia de género</text>
  <text x="590" y="118" class="s">Requisito:</text>
  <text x="590" y="134" class="t" style="font-weight:700;fill:#b5740f">sin tiempo previo</text>
  <text x="590" y="166" class="s">Retribución:</text>
  <text x="590" y="182" class="t">2 meses íntegras</text>
  <text x="590" y="214" class="s">Reserva puesto:</text>
  <text x="590" y="230" class="t" style="font-weight:700">6 meses</text>
  <text x="590" y="262" class="s">prorrogable hasta 18</text>
  <text x="590" y="278" class="s">computa antigüedad</text>
</svg>
```

---

## D7 · Derechos individuales (art. 14) vs colectivos (art. 15)

**Sección**: § 5 — Derechos
**Propósito**: No confundir los derechos individuales con los de ejercicio colectivo.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Los derechos individuales del artículo 14 incluyen inamovilidad, carrera, retribuciones, formación e intimidad; los derechos de ejercicio colectivo del artículo 15 incluyen libertad sindical, negociación colectiva, huelga, conflicto colectivo y reunión">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:11.5px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
  </style>
  <rect x="30" y="20" width="300" height="38" rx="8" fill="#0055a0"/>
  <text x="180" y="44" class="h">INDIVIDUALES · art. 14</text>
  <rect x="370" y="20" width="300" height="38" rx="8" fill="#2d8659"/>
  <text x="520" y="44" class="h">COLECTIVOS · art. 15</text>
  <rect x="30" y="70" width="300" height="210" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="48" y="98" class="t">• Inamovilidad (carrera)</text>
  <text x="48" y="124" class="t">• Carrera y promoción interna</text>
  <text x="48" y="150" class="t">• Retribuciones e indemnizaciones</text>
  <text x="48" y="176" class="t">• Formación continua</text>
  <text x="48" y="202" class="t">• Intimidad y desconexión digital</text>
  <text x="48" y="228" class="t">• No discriminación / conciliación</text>
  <text x="48" y="254" class="t">• Vacaciones, permisos y licencias</text>
  <rect x="370" y="70" width="300" height="210" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="388" y="104" class="t">• Libertad sindical</text>
  <text x="388" y="138" class="t">• Negociación colectiva</text>
  <text x="388" y="172" class="t" style="font-weight:700;fill:#1f5e3f">• Huelga (servicios esenciales)</text>
  <text x="388" y="206" class="t">• Conflicto colectivo</text>
  <text x="388" y="240" class="t">• Reunión (art. 46)</text>
</svg>
```

---

## D8 · Carrera profesional y promoción interna

**Sección**: § 6 — Carrera profesional
**Propósito**: Las cuatro modalidades de carrera del art. 16.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 290" role="img" aria-label="La carrera profesional comprende carrera horizontal sin cambio de puesto, carrera vertical con ascenso de puesto, y la promoción interna vertical a un subgrupo superior u horizontal al mismo subgrupo">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="220" y="16" width="260" height="40" rx="8" fill="#003d75"/>
  <text x="350" y="41" class="h">CARRERA PROFESIONAL · art. 16</text>
  <rect x="30" y="80" width="150" height="110" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="105" y="108" class="t" style="font-weight:700">Horizontal</text>
  <text x="105" y="138" class="s">progresión de grado</text>
  <text x="105" y="156" class="s">o categoría</text>
  <text x="105" y="178" class="s" style="font-weight:700;fill:#0055a0">sin cambiar de puesto</text>
  <rect x="195" y="80" width="150" height="110" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="270" y="108" class="t" style="font-weight:700">Vertical</text>
  <text x="270" y="138" class="s">ascenso en la</text>
  <text x="270" y="156" class="s">estructura de puestos</text>
  <text x="270" y="178" class="s" style="font-weight:700;fill:#0055a0">cambio de puesto</text>
  <rect x="360" y="80" width="150" height="110" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="435" y="104" class="t" style="font-weight:700">Promoción interna</text>
  <text x="435" y="120" class="t" style="font-weight:700">vertical</text>
  <text x="435" y="150" class="s">a un Subgrupo</text>
  <text x="435" y="168" class="s" style="font-weight:700;fill:#1f5e3f">superior (art. 18)</text>
  <rect x="525" y="80" width="150" height="110" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="600" y="104" class="t" style="font-weight:700">Promoción interna</text>
  <text x="600" y="120" class="t" style="font-weight:700">horizontal</text>
  <text x="600" y="150" class="s">al mismo Subgrupo</text>
  <text x="600" y="168" class="s" style="font-weight:700;fill:#1f5e3f">(art. 18)</text>
  <rect x="150" y="218" width="400" height="50" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="350" y="240" class="s" style="font-weight:700;fill:#b5740f">Promoción interna: titulación + 2 años de antigüedad</text>
  <text x="350" y="258" class="s">igualdad · mérito · capacidad</text>
</svg>
```

---

## D9 · Retribuciones: básicas vs complementarias

**Sección**: § 8 — Retribuciones
**Propósito**: Distinguir las retribuciones básicas (PGE) de las complementarias.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Las retribuciones básicas son el sueldo y los trienios, fijados en los Presupuestos Generales del Estado; las complementarias dependen del puesto y del desempeño y las fija cada Administración">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="220" y="16" width="260" height="38" rx="8" fill="#003d75"/>
  <text x="350" y="40" class="h">RETRIBUCIONES · art. 22</text>
  <rect x="40" y="74" width="290" height="170" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="185" y="100" class="s" style="font-weight:700;fill:#1f5e3f;font-size:13px">BÁSICAS (art. 23)</text>
  <text x="60" y="134" class="t">• Sueldo (por Subgrupo/Grupo)</text>
  <text x="60" y="166" class="t">• Trienios (cada 3 años)</text>
  <rect x="60" y="190" width="250" height="40" rx="6" fill="#fff" stroke="#2d8659"/>
  <text x="185" y="215" class="s" style="font-weight:700">Se fijan en los PGE · iguales por Subgrupo</text>
  <rect x="370" y="74" width="290" height="170" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="515" y="100" class="s" style="font-weight:700;fill:#0055a0;font-size:13px">COMPLEMENTARIAS (art. 24)</text>
  <text x="390" y="128" class="t">• Progresión en la carrera</text>
  <text x="390" y="152" class="t">• Dificultad / responsabilidad</text>
  <text x="390" y="176" class="t">• Rendimiento y resultados</text>
  <text x="390" y="200" class="t">• Servicios extraordinarios</text>
  <rect x="390" y="212" width="250" height="22" rx="5" fill="#fff" stroke="#0055a0"/>
  <text x="515" y="227" class="s" style="font-weight:700">Las fija cada Administración</text>
</svg>
```

---

## D10 · Jornada, permisos y vacaciones

**Sección**: § 9 — Jornada, permisos y vacaciones
**Propósito**: Resumir jornada/teletrabajo, permisos y vacaciones.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 270" role="img" aria-label="Jornada general y teletrabajo en el artículo 47, permisos en el artículo 48, permisos de conciliación de dieciséis semanas en el artículo 49 y vacaciones de veintidós días hábiles en el artículo 50">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="170" y="16" width="360" height="38" rx="8" fill="#003d75"/>
  <text x="350" y="40" class="h">JORNADA · PERMISOS · VACACIONES</text>
  <rect x="30" y="78" width="150" height="120" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="105" y="104" class="t" style="font-weight:700">Jornada</text>
  <text x="105" y="122" class="s">art. 47</text>
  <text x="105" y="152" class="s">general y especiales</text>
  <text x="105" y="174" class="s" style="font-weight:700;fill:#0055a0">+ teletrabajo (47 bis)</text>
  <rect x="196" y="78" width="150" height="120" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="271" y="104" class="t" style="font-weight:700">Permisos</text>
  <text x="271" y="122" class="s">art. 48</text>
  <text x="271" y="150" class="s">familiares, traslado,</text>
  <text x="271" y="168" class="s">exámenes, lactancia,</text>
  <text x="271" y="186" class="s">asuntos particulares</text>
  <rect x="362" y="78" width="150" height="120" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="437" y="104" class="t" style="font-weight:700">Conciliación</text>
  <text x="437" y="122" class="s">art. 49</text>
  <text x="437" y="154" class="t" style="font-weight:700;fill:#1f5e3f">16 semanas</text>
  <text x="437" y="176" class="s">nacimiento/adopción</text>
  <rect x="528" y="78" width="150" height="120" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="603" y="104" class="t" style="font-weight:700">Vacaciones</text>
  <text x="603" y="122" class="s">art. 50</text>
  <text x="603" y="156" class="t" style="font-weight:700;fill:#b5740f">22 días hábiles</text>
  <text x="603" y="178" class="s">(o proporcional)</text>
  <rect x="40" y="216" width="620" height="38" rx="6" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="350" y="240" class="s" style="font-weight:700;fill:#0055a0;font-size:10px">El Acuerdo-Convenio del Ayto. de Madrid puede mejorar, nunca empeorar, estos mínimos</text>
</svg>
```

---

## D11 · Régimen disciplinario: faltas, sanciones y prescripción

**Sección**: § 12 — Régimen disciplinario
**Propósito**: La cascada faltas → sanciones → prescripción.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="Las faltas se clasifican en muy graves, graves y leves; las sanciones van de la separación del servicio al apercibimiento; la prescripción de las faltas es de tres años, dos años y seis meses respectivamente">
  <style>
    .h{font:700 12px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:11.5px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="40" y="16" width="200" height="34" rx="8" fill="#003d75"/>
  <text x="140" y="38" class="h">FALTAS (art. 95)</text>
  <rect x="260" y="16" width="200" height="34" rx="8" fill="#003d75"/>
  <text x="360" y="38" class="h">SANCIONES (art. 96)</text>
  <rect x="480" y="16" width="200" height="34" rx="8" fill="#003d75"/>
  <text x="580" y="38" class="h">PRESCRIPCIÓN (art. 97)</text>
  <rect x="40" y="66" width="200" height="50" rx="6" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="140" y="88" class="t" style="font-weight:700">Muy graves</text>
  <text x="140" y="106" class="s">lista cerrada art. 95.2</text>
  <rect x="40" y="124" width="200" height="50" rx="6" fill="#fff5e6" stroke="#e89822"/>
  <text x="140" y="146" class="t" style="font-weight:700">Graves</text>
  <text x="140" y="164" class="s">por ley de FP / convenio</text>
  <rect x="40" y="182" width="200" height="50" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="140" y="204" class="t" style="font-weight:700">Leves</text>
  <text x="140" y="222" class="s">por ley de FP / convenio</text>
  <rect x="260" y="66" width="200" height="30" rx="5" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="360" y="86" class="s" style="font-weight:700">Separación del servicio</text>
  <rect x="260" y="100" width="200" height="26" rx="5" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="360" y="118" class="s">Despido (laboral)</text>
  <rect x="260" y="130" width="200" height="26" rx="5" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="360" y="148" class="s">Suspensión ≤ 6 años</text>
  <rect x="260" y="160" width="200" height="26" rx="5" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="360" y="178" class="s">Traslado forzoso</text>
  <rect x="260" y="190" width="200" height="26" rx="5" fill="#f4f6f9" stroke="#0055a0"/>
  <text x="360" y="208" class="s">Demérito</text>
  <rect x="260" y="220" width="200" height="26" rx="5" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="360" y="238" class="s">Apercibimiento (la más leve)</text>
  <rect x="480" y="66" width="200" height="50" rx="6" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="580" y="88" class="t" style="font-weight:700">Muy graves: 3 años</text>
  <text x="580" y="106" class="s">sanción: 3 años</text>
  <rect x="480" y="124" width="200" height="50" rx="6" fill="#fff5e6" stroke="#e89822"/>
  <text x="580" y="146" class="t" style="font-weight:700">Graves: 2 años</text>
  <text x="580" y="164" class="s">sanción: 2 años</text>
  <rect x="480" y="182" width="200" height="50" rx="6" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="580" y="204" class="t" style="font-weight:700">Leves: 6 meses</text>
  <text x="580" y="222" class="s">sanción: 1 año</text>
  <rect x="120" y="262" width="480" height="44" rx="6" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="360" y="282" class="s" style="font-weight:700;fill:#0055a0">Principios (art. 94): legalidad y tipicidad · proporcionalidad ·</text>
  <text x="360" y="298" class="s" style="font-weight:700;fill:#0055a0">culpabilidad · presunción de inocencia · irretroactividad desfavorable</text>
</svg>
```

---

## D12 · Mapa-resumen del Tema 5

**Sección**: § 14 — Esquema resumen
**Propósito**: Visión global del personal al servicio de la AP según el TREBEP.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 760 360" role="img" aria-label="Mapa resumen del Tema 5: el TREBEP regula clases de personal, acceso y pérdida, situaciones administrativas, derechos, carrera, retribuciones, jornada y permisos, negociación, deberes y régimen disciplinario">
  <style>
    .h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:700 11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:9.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <line x1="380" y1="181" x2="122" y2="46" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="380" y2="46" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="638" y2="46" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="122" y2="112" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="638" y2="112" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="122" y2="256" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="638" y2="256" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="122" y2="322" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="380" y2="322" stroke="#cdd6e0"/>
  <line x1="380" y1="181" x2="638" y2="322" stroke="#cdd6e0"/>
  <rect x="305" y="152" width="150" height="58" rx="10" fill="#003d75"/>
  <text x="380" y="178" class="h">TREBEP</text>
  <text x="380" y="196" class="h" style="font-weight:400;font-size:11px">RDL 5/2015</text>
  <rect x="15" y="20" width="215" height="52" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="122" y="42" class="t">Clases de personal</text>
  <text x="122" y="59" class="s">carrera/interino/laboral/eventual</text>
  <rect x="272" y="20" width="216" height="52" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="380" y="42" class="t">Acceso y pérdida</text>
  <text x="380" y="59" class="s">igualdad · mérito · capacidad</text>
  <rect x="530" y="20" width="215" height="52" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="638" y="42" class="t">Situaciones</text>
  <text x="638" y="59" class="s">activo · excedencia · suspensión</text>
  <rect x="15" y="86" width="215" height="52" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="122" y="108" class="t">Derechos</text>
  <text x="122" y="125" class="s">individuales (14) / colectivos (15)</text>
  <rect x="530" y="86" width="215" height="52" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="638" y="108" class="t">Carrera + evaluación</text>
  <text x="638" y="125" class="s">horizontal/vertical · prom. interna</text>
  <rect x="15" y="230" width="215" height="52" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="122" y="252" class="t">Retribuciones</text>
  <text x="122" y="269" class="s">básicas / complementarias</text>
  <rect x="530" y="230" width="215" height="52" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="638" y="252" class="t">Jornada / permisos</text>
  <text x="638" y="269" class="s">vacaciones 22 días</text>
  <rect x="15" y="296" width="215" height="52" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="122" y="318" class="t">Negociación</text>
  <text x="122" y="335" class="s">mesas · delegados / juntas</text>
  <rect x="272" y="296" width="216" height="52" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="380" y="318" class="t">Deberes</text>
  <text x="380" y="335" class="s">código de conducta (53/54)</text>
  <rect x="530" y="296" width="215" height="52" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="638" y="318" class="t">Disciplinario</text>
  <text x="638" y="335" class="s">faltas · sanciones · prescripción</text>
</svg>
```
