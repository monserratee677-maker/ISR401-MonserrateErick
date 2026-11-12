# ISR401 - Ingeniería de Requerimientos (UTEQ)

Repositorio personal de actividades de Ingeniería de Requerimientos.

## TA-IND-01: IEEE 29148 y tipos de requisitos de un sistema conocido

Sistema analizado: banca móvil del Banco Pichincha (función de transferencias).

### Estructura

```
TA-IND-01/
  main.tex           archivo principal del informe
  referencias.bib    referencias en estilo IEEE
  figuras/           capturas propias del sistema
  main.pdf           PDF compilado
```

### Cómo compilar

- **Compilador:** pdfLaTeX
- **Archivo principal:** `TA-IND-01/main.tex`
- **Orden de comandos** (desde la carpeta `TA-IND-01/`):

```
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

En Overleaf: compilador pdfLaTeX y archivo principal `main.tex`.

### Dependencias

Distribución TeX Live (o MiKTeX) con los paquetes: babel (spanish), geometry, graphicx, booktabs, longtable, array, xcolor, setspace, float, fancyhdr, hyperref e IEEEtran (estilo bibliográfico).
