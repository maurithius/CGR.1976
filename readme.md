# Base de Conocimiento Normativa SIAPER

## Descripción

Este repositorio contiene una colección de documentos normativos en formato Markdown (`.md`) destinados a ser utilizados como fuente de consulta por agentes de inteligencia artificial, asistentes virtuales y sistemas de apoyo a la gestión administrativa.

El contenido está orientado principalmente a materias relacionadas con:

- SIAPER
- Gestión de personal en la Administración Pública
- Estatuto Administrativo
- Dictámenes de la Contraloría General de la República
- Leyes y reglamentos aplicables
- Instructivos y manuales de procedimiento
- Normativa complementaria

## Objetivo

Permitir que un agente de IA pueda:

1. Leer el contenido de los documentos normativos.
2. Recuperar información relevante mediante búsqueda semántica.
3. Responder consultas citando la fuente documental correspondiente.
4. Reducir la generación de respuestas sin respaldo normativo.
5. Mantener trazabilidad de la información utilizada.

## Estructura del Repositorio

```text
/
├── README.md
├── leyes/
│   ├── ley_10336_LEY DE ORGANIZACION Y ATRIBUCIONES DE LA CONTRALORIA GENERAL DE LA REPUBLICA.md
│   ├── ley_19880_procedimiento_administrativo.md
│   └── ...
│
├── dictamenes/
│   ├── dictamen_001_2024.md
│   ├── dictamen_002_2024.md
│   └── ...
│
├── manuales/
│   ├── manual_siaper.md
│   └── ...
│
└── instructivos/
    ├── instructivo_registro.md
    └── ...
```

## Reglas para los Documentos

Cada archivo debe contener:

### Metadatos recomendados

```markdown
# Ley N° 18.834

## Fuente
Biblioteca del Congreso Nacional de Chile

## Fecha de Publicación
1989-09-23

## Nombre
LEY DE ORGANIZACION Y ATRIBUCIONES DE LA CONTRALORIA GENERAL DE LA REPUBLICA

## Materia
Estatuto Administrativo

## Palabras Clave
funcionarios públicos, nombramiento, contrata, planta

## Contenido
...
```

### Recomendaciones

- Mantener títulos claros.
- Utilizar encabezados Markdown (`#`, `##`, `###`).
- Conservar numeración de artículos.
- No modificar el texto legal original.
- Registrar la fuente oficial.
- Incorporar fecha de actualización cuando corresponda.

## Instrucciones para el Agente de IA

Al consultar este repositorio, el agente deberá:

### Prioridad de fuentes

1. Leyes vigentes.
2. Reglamentos.
3. Dictámenes aplicables.
4. Manuales e instructivos.
5. Otros documentos de apoyo.

### Comportamiento esperado

- Responder únicamente con información contenida en los documentos.
- Citar el archivo utilizado.
- Indicar artículo, numeral o sección cuando exista.
- Explicitar cuando no exista información suficiente para responder.
- Evitar interpretaciones jurídicas sin respaldo documental.

### Formato sugerido de respuesta

```text
Fuente:
- ley_18834_estatuto_administrativo.md

Referencia:
- Artículo 10

Extracto relevante:
"Texto aplicable..."

Conclusión:
Respuesta elaborada a partir del texto normativo.
```

## Convención de Nombres

Utilizar nombres descriptivos y consistentes.

Ejemplos:

```text
ley_18834_estatuto_administrativo.md
ley_19880_procedimiento_administrativo.md
dictamen_12345_2024.md
manual_siaper_ingreso.md
instructivo_declaracion_intereses.md
```

## Control de Versiones

Toda modificación debe:

- Mantener historial en Git.
- Indicar fecha de actualización.
- Registrar fuente de origen.
- Verificar vigencia del documento.

## Calidad de la Información

Antes de incorporar un documento:

- Verificar que provenga de una fuente oficial.
- Confirmar que el texto esté completo.
- Revisar la vigencia normativa.
- Eliminar duplicados.
- Corregir errores de conversión desde PDF.

## Limitaciones

Este repositorio constituye una base documental de consulta y no reemplaza:

- Interpretaciones jurídicas oficiales.
- Pronunciamientos de la Contraloría General de la República.
- Dictámenes vinculantes.
- Asesoría legal especializada.

## Licencia

Los documentos conservan las condiciones establecidas por sus fuentes oficiales. El uso de este repositorio debe respetar la normativa vigente sobre acceso y reutilización de la información pública.

---

**Última actualización:** YYYY-MM-DD
