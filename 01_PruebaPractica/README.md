# 01_PruebaPractica

Desarrollo de la prueba práctica de la Unidad IV, transcrito a LaTeX a partir de la
evaluación resuelta a mano en clase.

## Archivos

| Archivo | Descripción |
|---|---|
| `EV4_Practica_FuertesDaniel.tex` | **Archivo principal.** Contiene el instrumento del docente y el desarrollo de las tareas P1–P8. |
| `referencias.bib` | Base bibliográfica (normas ISO/IEC/IEEE, OMG UML, SWEBOK, Pohl, Fagan). |
| `EV4_Practica_FuertesDaniel.pdf` | PDF compilado. |
| `figuras/` | Diagramas UML: clases (P1), actividades (P2) y máquina de estados (P3). |
| `EvidenciasPruebaPracticaDesarrolladaEnClases/` | Fotografías de las hojas resueltas a mano en clase y su transcripción en Word/PDF. |

## Compilación

```bash
pdflatex EV4_Practica_FuertesDaniel
bibtex   EV4_Practica_FuertesDaniel
pdflatex EV4_Practica_FuertesDaniel
pdflatex EV4_Practica_FuertesDaniel
```
