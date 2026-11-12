# TA-IND-01 — Trabajo individual: IEEE 29148 y tipos de requisitos de un sistema conocido

**Estudiante:** Herrera Morán Gilmar Javier
**Asignatura:** Ingeniería de Requerimientos (ISR-401) · 4.º nivel, paralelo A · UTEQ
**Docente:** Gleiston Cicerón Guerrero Ulloa, PhD

## Contenido de la carpeta `TA-IND-01/`

| Archivo | Descripción |
| --- | --- |
| `main.tex` | **Archivo principal.** Resumen, glosario, requisitos, clasificación, autoevaluación y reflexión |
| `referencias.bib` | Referencias en formato IEEE (los mismos datos de la bibliografía incrustada en `main.tex`) |
| `figuras/` | Capturas propias del sistema elegido |
| `main.pdf` | PDF compilado |
| `portada_sga.tex` / `portada_sga.pdf` | Portada de una página que se sube al SGA |

## Compilador

- **pdfLaTeX**, TeX Live 2022 o superior, MiKTeX u Overleaf.
- Codificación UTF-8. La bibliografía en formato IEEE está dentro de `main.tex`; **no se usa BibTeX ni Biber**.

## Dependencias (paquetes LaTeX)

`babel` (`spanish`, `es-nodecimaldot`), `inputenc`, `fontenc`, `lmodern`, `geometry`, `array`, `booktabs`, `longtable`, `enumitem`, `graphicx`, `xcolor` (opción `table`), `fancyhdr`, `microtype`, `hyperref`, `url`.

## Orden de compilación

Desde la carpeta `TA-IND-01/`:

```
pdflatex main.tex
pdflatex main.tex
```

Alternativa equivalente:

```
latexmk -pdf main.tex
```

Portada del SGA (una sola página):

```
pdflatex portada_sga.tex
```

## En Overleaf

Subir la carpeta completa, elegir `main.tex` como documento principal, compilador **pdfLaTeX** y pulsar *Recompile*.

## Datos personales

No se publican datos personales de terceros en este repositorio.
