# Legislación Paraguaya — Compendio Jurídico Estructurado

Biblioteca documental en formato Markdown (`.md`) de la legislación, la jurisprudencia y la doctrina de la República del Paraguay, organizada por fueros judiciales. El propósito del repositorio es ofrecer una fuente de consulta ágil, de lectura lineal y de referencia normativa para el estudio jurídico, la práctica profesional y la investigación académica, con un sistema uniforme de metadatos que permite localizar, clasificar y citar cada documento de manera consistente.

## Índice de Fueros

| Fuero | Contenido |
|---|---|
| **CIVIL Y COMERCIAL** | Códigos de fondo y de forma, leyes especiales, acordadas y jurisprudencia del fuero civil y comercial. |
| **CONTENCIOSIOSO ADMINISTRATIVO** | Normativa del proceso contencioso administrativo, organización de la jurisdicción y precedentes. |
| **JUSTICIA DE PAZ** | Régimen de la Justicia de Paz, competencias, procedimientos y acordadas aplicables. |
| **LABORAL** | Código del Trabajo, procedimiento laboral, leyes complementarias y precedentes. |
| **NIÑEZ Y ADOLESCENCIA** | Código de la Niñez y la Adolescencia, leyes conexas, tratados y jurisprudencia especializada. |
| **PENAL** | Código Penal, Código Procesal Penal, leyes especiales y órganos jurisdiccionales del fuero. |
| **SALA CONSTITUCIONAL** | Normas y precedentes del control de constitucionalidad, hábeas corpus, amparo y garantías. |
| **TRIBUNAL DE CUENTAS** | Régimen de control y juzgamiento de cuentas, leyes orgánicas y resoluciones. |

## Categorías internas de cada fuero

Cada fuero replica la misma estructura de carpetas, de modo que la ubicación de un documento sea previsible:

| Categoría | Descripción |
|---|---|
| **Codigos** | Códigos de fondo y de forma y sus leyes orgánicas, con estructura articulada y notas de vigencia. |
| **Leyes Vigentes** | Leyes especiales y modificatorias vigentes, ordenadas por número y materia. |
| **Acordadas Judiciales** | Acordadas y resoluciones de la Corte Suprema de Justicia con incidencia procesal. |
| **Jurisprudencia CSJ** | Fallos y precedentes de la Corte Suprema de Justicia y de los tribunales superiores. |
| **Doctrinas Judiciales Paraguay** | Doctrina de autores nacionales y análisis de instituciones jurídicas paraguayas. |
| **Tratados Internacionales** | Instrumentos internacionales ratificados por el Paraguay y su recepción interna. |
| **Otros Relacionados** | Cuadros sinópticos, guías de consulta, índices temáticos y material de apoyo. |

## Estructura del repositorio

```
LESGILACION_PARAGUAYA/
├── CIVIL Y COMERCIAL/
│   ├── Codigos/
│   ├── Leyes Vigentes/
│   ├── Acordadas Judiciales/
│   ├── Jurisprudencia CSJ/
│   ├── Doctrinas Judiciales Paraguay/
│   ├── Tratados Internacionales/
│   └── Otros Relacionados/
├── CONTENCIOSIOSO ADMINISTRATIVO/
├── JUSTICIA DE PAZ/
├── LABORAL/
├── NIÑEZ Y ADOLESCENCIA/
├── PENAL/
├── SALA CONSTITUCIONAL/
└── TRIBUNAL DE CUENTAS/
```

## Formato de los documentos

Todos los archivos se publican en **Markdown (`.md`) codificado en UTF-8** y encabezados por un bloque de **metadatos YAML** estandarizado, con los siguientes campos:

| Campo | Contenido |
|---|---|
| `titulo` | Denominación oficial del documento y su norma de origen. |
| `tipo` | Naturaleza del documento (código, ley, acordada, fallo, doctrina, cuadro). |
| `fuero` | Fuero judicial al que pertenece. |
| `numero_norma` | Número y año de la ley o del instrumento. |
| `fuente` | Repositorio oficial de la fuente utilizada (BACN, CSJ, Gaceta Oficial). |
| `vigencia` | Estado de vigencia y leyes modificatorias registradas. |
| `actualizado` | Fecha de la última revisión del documento (formato ISO `AAAA-MM-DD`). |

Cada documento se organiza, además, con una estructura interna uniforme —resumen, contenido estructurado y artículos o puntos clave— que facilita la lectura progresiva, la cita y la búsqueda por materia. Las transcripciones conservan las grafías del texto oficial publicado; las erratas detectadas en la fuente se señalan expresamente y no se confunden con derogaciones.

## Estado del acervo

| Fuero | Estado | Documentos publicados |
|---|---|---|
| CIVIL Y COMERCIAL | En desarrollo | Código Civil (Ley N° 1183/1985), Código Procesal Civil (Ley N° 1337/1988), Código de Organización Judicial (Ley N° 879/1981) en materia de competencia civil, y cuadro de plazos procesales |
| CONTENCIOSIOSO ADMINISTRATIVO | Estructura creada | — |
| JUSTICIA DE PAZ | Estructura creada | — |
| LABORAL | Estructura creada | — |
| NIÑEZ Y ADOLESCENCIA | Estructura creada | — |
| PENAL | Estructura creada | — |
| SALA CONSTITUCIONAL | Estructura creada | — |
| TRIBUNAL DE CUENTAS | Estructura creada | — |

Las carpetas sin documentos publicados se conservan mediante archivos `.gitkeep` para preservar la estructura del compendio.

## Criterios de cita y control de calidad

1. **Fuente oficial.** Cada documento indica en sus metadatos el repositorio del cual se extrajo el texto (Biblioteca y Archivo del Congreso de la Nación, Corte Suprema de Justicia o Gaceta Oficial).
2. **Transcripción literal.** Los artículos se reproducen tal como están publicados, incluidas las grafías de época y las erratas de la edición digital, que se identifican entre paréntesis cuando afectan la comprensión.
3. **Verificación por artículo.** Los rangos de artículos se controlan por conteo, de modo que no existan omisiones entre el primero y el último de cada cuerpo normativo.
4. **Notas de vigencia.** Se registran las leyes modificatorias y las remisiones a normas derogadas, con indicación de la norma actualmente aplicable.
5. **Cita uniforme.** Se cita la norma por su número y año (por ejemplo, «Ley N° 1337/1988») y el artículo por su número ordinal («art. 234»), con la denominación del cuerpo normativo en la primera mención.

## Autoría y mantenimiento

Este compendio es compilado, estructurado y mantenido por **Zetti Digital PY**.

- Organización: [github.com/FUDAPY](https://github.com/FUDAPY)
- Repositorio: [LESGILACION_PARAGUAYA_ZETTI](https://github.com/FUDAPY/LESGILACION_PARAGUAYA_ZETTI)

Las correcciones, ampliaciones y sugerencias se reciben mediante *issues* y *pull requests* en el repositorio.

## Control de versiones

Toda incorporación o modificación de documentos se registra en la rama `main` con un mensaje de commit normalizado (`feat(docs)`, `fix(docs)`, `docs(...)`), que indica el fuero y el material afectado. Antes de publicar se controla que el índice de archivos no contenga documentos temporales, de configuración local ni credenciales, tarea que asegura el archivo `.gitignore` de la raíz. Cada `push` deja el repositorio sincronizado con la versión revisada del acervo.

## Aviso de uso

Los textos normativos reproducidos son de dominio público. La estructura del compendio, los índices, los cuadros sinópticos y las notas de vigencia son obra de Zetti Digital PY y se publican con fines exclusivamente documentales y de estudio.

Este repositorio **no sustituye la consulta de la fuente oficial**. Antes de invocar una norma en sede judicial o administrativa debe verificarse su texto vigente en la Gaceta Oficial, en la Biblioteca y Archivo del Congreso de la Nación o en el sitio de la Corte Suprema de Justicia, y controlarse la existencia de modificaciones, derogaciones o declaraciones de inconstitucionalidad posteriores a la fecha de actualización indicada en cada documento.

