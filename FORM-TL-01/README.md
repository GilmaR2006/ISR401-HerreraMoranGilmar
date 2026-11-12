# FORM-TL-01 — Taller de identificación y clasificación de tipos de requisitos

**Estudiante:** Herrera Moran Gilmar Javier
**Asignatura:** Ingeniería de Requerimientos (ISR-401) · 4.º nivel, paralelo A · UTEQ
**Docente:** Gleiston Cicerón Guerrero Ulloa, PhD

## Contenido de la carpeta `FORM-TL-01/`

| Archivo | Descripción |
|---|---|
| `main.tex` | **Archivo principal.** Clasificación de los 20 enunciados, 5 requisitos cuantificados y discrepancias |
| `main.pdf` | PDF generado a partir de `main.tex` |
| `portada_sga.tex` | Portada de una sola página con datos informativos y URL del repositorio |
| `portada_sga.pdf` | PDF de una página que se sube al SGA |
| `README.md` | Este archivo |

## Compilador

- **pdfLaTeX**, con TeX Live 2022 o superior, MiKTeX u Overleaf (compilador pdfLaTeX).
- Codificación UTF-8.

## Dependencias (paquetes LaTeX)

`babel` (opciones `spanish`, `es-nodecimaldot`), `inputenc`, `fontenc`, `lmodern`, `geometry`, `tabularx`, `booktabs`, `longtable`, `array`, `enumitem`, `xcolor` (opción `table`), `hyperref`, `fancyhdr`, `microtype`.

La bibliografía está dentro de `main.tex`; **no se usa BibTeX ni Biber**.

## Orden de compilación

Desde la carpeta `FORM-TL-01/`, ejecutar `pdflatex` **dos veces** sobre el archivo principal (la segunda pasada resuelve las citas y referencias):

```bash
pdflatex main.tex
pdflatex main.tex
```

Alternativa equivalente:

```bash
latexmk -pdf main.tex
```

Resultado esperado: `main.pdf` de 5 páginas.

### Portada del SGA

```bash
pdflatex portada_sga.tex
```

Resultado esperado: `portada_sga.pdf` de **una sola página**.

### En Overleaf

Subir `main.tex` (o la carpeta completa), elegir como documento principal `main.tex`, compilador **pdfLaTeX** y pulsar *Recompile*.
