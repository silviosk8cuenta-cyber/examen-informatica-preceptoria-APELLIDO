# Datos base del caso (ficticios)

## El curso
- Curso: 2.º año B, turno mañana
- Estudiantes: **28** (identificados con código E01 a E28)
- Período analizado: **20 días hábiles**

## La tabla `asistencia_2B.csv`
| Columna | Contenido |
|---|---|
| `id_estudiante` | Código del estudiante (E01 a E28) |
| `ausencias_justificadas` | Cantidad de ausencias con justificación |
| `ausencias_injustificadas` | Cantidad de ausencias sin justificación |
| `llegadas_tarde` | Cantidad de llegadas tarde |
| `familia_contactada` | Sí / No: si la preceptoría ya se comunicó con la familia por las ausencias |

## Reglas de clasificación (ficticias, solo para este caso)
Las **ausencias totales** son las justificadas más las injustificadas. Las llegadas tarde no se cuentan como ausencias.

**Porcentaje de asistencia** = (20 − ausencias totales) / 20

| Porcentaje de asistencia | Categoría |
|---|---|
| 90 % o más | Sin alerta |
| De 80 % a menos de 90 % | Seguimiento |
| Menos de 80 % | Intervención |

**Alerta de puntualidad:** 5 o más llegadas tarde en el período.

## Cómo usar estos datos
Usalos tal cual. Si tu investigación te lleva a usar un criterio distinto, justificalo citando la fuente con enlace.
