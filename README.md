# Evaluación Unidad IV — Prueba Práctica

**Asignatura:** Ingeniería de Requisitos (ISR-401)
**Docente:** Ing. Gleiston Cicerón Guerrero Ulloa, PhD
**Estudiante:** Fuertes Arraes Edson Daniel — CI: 0929115087 — efuertesa2@uteq.edu.ec
**Curso:** Cuarto semestre, Paralelo "B"
**Universidad:** Universidad Técnica Estatal de Quevedo — Facultad de Ciencias de la Ingeniería
**Caso:** Sistema de Reserva de Citas Médicas

---

## Documento principal a compilar

El archivo que debe compilarse para reproducir el desarrollo de la prueba es:

```
01_PruebaPractica/EV4_Practica_FuertesDaniel.tex
```

### Instrucciones de compilación

Compilador: **pdfLaTeX**. Bibliografía: **BibTeX** (paquete `natbib`, estilo `plainnat`).

Desde la carpeta `01_PruebaPractica/`, ejecutar en este orden:

```bash
pdflatex EV4_Practica_FuertesDaniel
bibtex   EV4_Practica_FuertesDaniel
pdflatex EV4_Practica_FuertesDaniel
pdflatex EV4_Practica_FuertesDaniel
```

Notas importantes:

- El comando `bibtex` se ejecuta **sin extensión** (`bibtex EV4_Practica_FuertesDaniel`, no `.tex`).
- Las dos pasadas finales de `pdflatex` son necesarias para resolver las citas y las referencias cruzadas.
- No se usa `biber`; el documento emplea `natbib`, que requiere `bibtex`.

Salida esperada: `EV4_Practica_FuertesDaniel.pdf`

### Dependencias

Todos los paquetes vienen incluidos en una distribución LaTeX estándar (TeX Live o MiKTeX completos):

`inputenc`, `fontenc`, `helvet`, `textcomp`, `geometry`, `amsmath`, `amssymb`, `graphicx`, `xcolor`, `array`, `tabularx`, `multirow`, `colortbl`, `booktabs`, `enumitem`, `microtype`, `parskip`, `titlesec`, `fancyhdr`, `caption`, `pdflscape`, `natbib`, `hyperref`, `tcolorbox`.

No se requiere `babel-spanish`.

---

## Documento entregado al SGA

```
03_DocumentoEntregable/Entregable_EV4_FuertesDaniel.tex
```

Contiene la carátula con los datos de identificación, la URL del repositorio y las capturas del cuestionario del SGA. Se compila con **una sola pasada** de `pdfLaTeX` (no usa bibliografía):

```bash
pdflatex Entregable_EV4_FuertesDaniel
```

---

## Estructura del repositorio

| Carpeta | Contenido |
|---|---|
| `01_PruebaPractica/` | Documento principal en LaTeX, `referencias.bib`, figuras de los modelos UML y PDF compilado. Incluye las evidencias fotográficas de la prueba resuelta a mano en clase y su transcripción. |
| `02_EvaluacionSumativa/` | Resumen y revisión del intento del cuestionario rendido en el LMS (SGA). |
| `03_DocumentoEntregable/` | Carátula con identificación, URL del repositorio y capturas del SGA. Es el PDF que se sube al LMS. |

```
.
├── 01_PruebaPractica/
│   ├── EV4_Practica_FuertesDaniel.tex      <- archivo principal
│   ├── referencias.bib
│   ├── figuras/                            <- diagramas UML (P1, P2, P3)
│   └── EvidenciasPruebaPracticaDesarrolladaEnClases/
├── 02_EvaluacionSumativa/
├── 03_DocumentoEntregable/
│   ├── Entregable_EV4_FuertesDaniel.tex
│   └── evidencias/                         <- capturas del SGA
└── README.md
```

---

## Contenido del desarrollo

| Tarea | Descripción |
|---|---|
| P1 | Modelo de datos — Diagrama de clases UML |
| P2 | Modelo funcional — Diagrama de actividades UML |
| P3 | Modelo de comportamiento — Máquina de estados UML |
| P4 | Consistencia entre las tres perspectivas |
| P5 | Especificación de requisitos con esquema de atributos |
| P6 | Priorización MoSCoW |
| P7 | Validación por inspección (lista de comprobación 29148) |
| P8 | Pruebas de aceptación trazadas |
