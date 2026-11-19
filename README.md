# ISR-401 — Ingeniería de Requerimientos

**Estudiante:** Herrera Moran Gilmar Javier
**Asignatura:** Ingeniería de Requerimientos (ISR-401) · 4.º nivel, paralelo A · UTEQ
**Docente:** Gleiston Cicerón Guerrero Ulloa, PhD

Repositorio personal con las actividades de la asignatura. Cada actividad está en su propia carpeta, con su propio `README.md` que explica cómo compilar.

## Actividades

| Carpeta | Actividad | Contenido principal |
|---|---|---|
| [FORM-TL-01/](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/tree/main/FORM-TL-01) | Taller de identificación y clasificación de tipos de requisitos (formativa) | `main.tex`, `main.pdf`, `portada_sga.tex`, `portada_sga.pdf` |
| [TA-IND-01/](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/tree/main/TA-IND-01) | Trabajo individual: IEEE 29148 y tipos de requisitos de un sistema conocido (sumativa) | `main.tex`, `main.pdf`, `referencias.bib`, `figuras/`, `portada_sga_TA-IND-01.tex`, `portada_sga_TA-IND-01.pdf` |
| [EV-PRAC-01/](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/tree/main/EV-PRAC-01) | Evaluación de la Unidad I, caso FRÍOVAC: transcripción fiel de la prueba escrita a mano (sumativa) | `main.tex`, `main.pdf`, `referencias.bib`, `logoband.png`, `evidencias/`, `portada_EV-PRAC-01_1pag.tex`, `portada_EV-PRAC-01_1pag.pdf` |

## Compilación

Todos los documentos se compilan con pdfLaTeX (TeX Live 2022 o superior, MiKTeX u Overleaf), codificación UTF-8. Las instrucciones exactas, el orden de comandos y las dependencias de cada actividad están en el `README.md` de su carpeta:

- [FORM-TL-01/README.md](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/blob/main/FORM-TL-01/README.md)
- [TA-IND-01/README.md](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/blob/main/TA-IND-01/README.md)
- [EV-PRAC-01/README.md](https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar/blob/main/EV-PRAC-01/README.md)

### Resumen para EV-PRAC-01

```bash
git clone https://github.com/GilmaR2006/ISR401-HerreraMoranGilmar.git
cd ISR401-HerreraMoranGilmar/EV-PRAC-01
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

- Compilador: `pdflatex`
- Archivo principal: `EV-PRAC-01/main.tex`
- Dependencias: `referencias.bib`, `logoband.png` y las fotografías de `evidencias/` (`hoja-01.jpg`, `hoja-02.jpg`, `hoja-03.jpg`)

## Datos personales

No se publican datos personales de terceros en este repositorio.
