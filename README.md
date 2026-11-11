# Examen final piloto – Informática
## Tecnicatura Superior en Preceptoría

**Instituto Alfa · Duración: 80 minutos · Modalidad: presencial, en laboratorio, individual**

---

## 1. Qué tenés que lograr

Construir, dentro de este repositorio, un **dossier de seguimiento de asistencia** para el curso del caso *2.º B – Escuela Secundaria "Tres Fronteras"*: una investigación, una planilla, un informe, una presentación para las familias, tu registro de uso de IA y la aplicación de las herramientas a tu rol de preceptor/a.

**Se evalúa únicamente lo que quede en tu repositorio al terminar los 80 minutos.** Si algo no está en el repo (o el enlace no abre), no se evalúa.

## 2. Antes de empezar (1 minuto de lectura)

1. Leé el caso: [`caso/enunciado.md`](caso/enunciado.md)
2. Los datos están en [`caso/datos_base.md`](caso/datos_base.md) y en la tabla [`caso/asistencia_2B.csv`](caso/asistencia_2B.csv).
3. Tu consigna completa está en [`caso/consigna.md`](caso/consigna.md).

**Herramientas permitidas:** GitHub, Perplexity, NotebookLM (Gemini), Claude, Google Sheets, Google Docs, Gamma, Word y Excel.

**Reglas:**
- **Datos personales:** todos los datos del caso son ficticios. No cargues nombres ni datos reales de estudiantes, familias o escuelas en el repositorio ni en ninguna herramienta de IA. Tu repositorio es público.
- Todo dato que no venga de `datos_base.md` debe tener fuente citada (con enlace).
- Podés usar IA en cualquier etapa, pero tenés que **registrar tus prompts** en `05-ia/prompts.md` y explicar qué corregiste vos.
- Todos los enlaces (Google Sheets, Google Docs, Gamma) deben estar en modo **"cualquier persona con el enlace puede ver"**. Probalos en una pestaña de incógnito.

## 3. Cronograma sugerido

| Etapa | Minutos | Acumulado | Herramienta | Entregable en el repo |
|---|---|---|---|---|
| 0. Preparación | 5 | 0–5 | GitHub | `00-estudiante.md` completo |
| 1. Investigación | 12 | 5–17 | Perplexity | `01-investigacion/fuentes.md` |
| 2. Síntesis | 8 | 17–25 | NotebookLM | `01-investigacion/sintesis.md` |
| 3. Planilla | 18 | 25–43 | Google Sheets / Excel | `02-datos/planilla.xlsx` + `enlace-planilla.md` |
| 4. Informe | 15 | 43–58 | Google Docs / Word | `03-informe/informe.pdf` + `enlace-informe.md` |
| 5. Presentación | 10 | 58–68 | Gamma | `04-presentacion/enlace-gamma.md` |
| 6. Rol de preceptor y revisión con IA | 8 | 68–76 | Claude | `06-rol-preceptor/aplicacion.md` y `05-ia/prompts.md` |
| 7. Cierre | 4 | 76–80 | GitHub | README verificado y entrega |

## 4. Paso a paso

### Etapa 0 · Preparación (0–5 min)
1. Hacé clic en **Use this template → Create a new repository**. Nombre: `examen-informatica-preceptoria-APELLIDO`. Visibilidad: **Public**.
2. Completá `00-estudiante.md` (nombre, cohorte, fecha).
3. **Commit 1:** `etapa 0: datos del estudiante`

### Etapa 1 · Investigación con Perplexity (5–17 min)
1. Con la consigna, hacé al menos **3 búsquedas** distintas en Perplexity.
2. Por cada una, anotá en `01-investigacion/fuentes.md`: la pregunta, el dato obtenido y el enlace de la fuente.
3. **Commit 2:** `etapa 1: fuentes de investigación`

### Etapa 2 · Síntesis con NotebookLM (17–25 min)
1. Cargá en NotebookLM los enlaces de tus fuentes.
2. Pedí una síntesis orientada a la pregunta del caso y copiá el resultado a `01-investigacion/sintesis.md`.
3. Marcá con **[VERIFICADO]** lo que contrastaste con la fuente original y **[REVISAR]** lo que no pudiste verificar.
4. **Commit 3:** `etapa 2: síntesis`

### Etapa 3 · Planilla (25–43 min)
1. Importá `caso/asistencia_2B.csv` a Google Sheets (**Archivo → Importar**) y armá las hojas que pide la consigna, con **fórmulas** (no valores escritos a mano) y **al menos un gráfico**.
2. Descargala como `.xlsx` y subila a `02-datos/` con el nombre `planilla.xlsx` (**Add file → Upload files**).
3. Pegá el enlace de la hoja de Google en `02-datos/enlace-planilla.md`.
4. **Commit 4:** `etapa 3: planilla de asistencia`

### Etapa 4 · Informe (43–58 min)
1. Redactá el informe en Google Docs (1 a 2 páginas) con la estructura de `03-informe/enlace-informe.md`.
2. Insertá al menos **1 tabla y 1 gráfico** traídos de tu planilla.
3. Descargalo como PDF, subilo como `03-informe/informe.pdf` y pegá el enlace del Doc en `enlace-informe.md`.
4. **Commit 5:** `etapa 4: informe`

### Etapa 5 · Presentación para las familias en Gamma (58–68 min)
1. Generá la presentación a partir de tu informe (6 láminas, estructura en `04-presentacion/enlace-gamma.md`).
2. La presentación es para una **reunión de familias**: usá solo datos del curso en conjunto, nunca datos de un estudiante en particular.
3. Pegá el enlace público en `04-presentacion/enlace-gamma.md`.
4. **Commit 6:** `etapa 5: presentación para familias`

### Etapa 6 · Rol de preceptor y revisión con Claude (68–76 min)
1. Completá `06-rol-preceptor/aplicacion.md`: tres usos de lo que aprendiste en tu trabajo diario como preceptor/a y una nota de traspaso para un colega.
2. Pedile a Claude que revise tu informe (coherencia, errores, claridad).
3. Completá `05-ia/prompts.md` con **todos** los prompts que usaste durante el examen y qué aceptaste o corregiste.
4. **Commit 7:** `etapa 6: rol de preceptor y registro de IA`

### Etapa 7 · Cierre (76–80 min)
1. Abrí cada enlace en incógnito y confirmá que funciona.
2. Verificá la lista de la sección 6.
3. **Commit final:** `entrega final` y entregá al docente la URL de tu repositorio, como se indique en el aula.

## 5. Estructura final esperada del repositorio

```
examen-informatica-preceptoria-APELLIDO/
├── README.md
├── 00-estudiante.md
├── caso/
│   ├── enunciado.md
│   ├── datos_base.md
│   ├── asistencia_2B.csv
│   └── consigna.md
├── 01-investigacion/
│   ├── fuentes.md
│   └── sintesis.md
├── 02-datos/
│   ├── planilla.xlsx
│   └── enlace-planilla.md
├── 03-informe/
│   ├── informe.pdf
│   └── enlace-informe.md
├── 04-presentacion/
│   └── enlace-gamma.md
├── 05-ia/
│   └── prompts.md
└── 06-rol-preceptor/
    └── aplicacion.md
```

## 6. Lista de verificación antes de entregar

- [ ] `00-estudiante.md` completo
- [ ] Mínimo 3 fuentes con enlace en `fuentes.md`
- [ ] `sintesis.md` con marcas [VERIFICADO] / [REVISAR]
- [ ] `planilla.xlsx` subida, con fórmulas y 1 gráfico
- [ ] `informe.pdf` subido, con 1 tabla y 1 gráfico
- [ ] Presentación sin datos individuales de estudiantes
- [ ] Los 3 enlaces (Sheets, Docs, Gamma) abren en incógnito
- [ ] `aplicacion.md` con 3 usos en el rol de preceptor y la nota de traspaso
- [ ] `prompts.md` con todos los prompts usados
- [ ] Mínimo **6 commits** hechos durante el examen, con mensajes descriptivos
- [ ] URL del repositorio entregada al docente

## 7. Cómo se evalúa

Se aplica la rúbrica de Informática de la Tecnicatura Superior en Preceptoría, que recibiste al inicio del curso. Cada criterio se valora en 4 niveles (Excelente, Bueno, Regular, Deficiente) y la nota final es el promedio ponderado.

| Criterio | Peso | Dónde se evidencia en este examen |
|---|---|---|
| 1. Conocimientos técnicos y aplicación práctica | 40 % | Planilla, uso de GitHub (estructura y commits), integración entre herramientas |
| 2. Comunicación y uso de macro habilidades | 30 % | Informe, síntesis, presentación, fuentes y comprensión de la consigna |
| 3. Trabajo colaborativo y actitud profesional | 20 % | Gestión del tiempo, honestidad en el uso de IA, cuidado de datos personales, nota de traspaso a un colega |
| 4. Aplicación en el rol de preceptor | 10 % | `06-rol-preceptor/aplicacion.md` y pertinencia del plan de acción |
