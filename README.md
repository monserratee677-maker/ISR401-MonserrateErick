# ISR401-MonserrateErick

Repositorio personal de Ingeniería de Requerimientos (ISR-401), UTEQ.

## FORM-TL-01: Taller de tipos de requisitos

- **Archivo principal:** `FORM-TL-01/main.tex`
- **PDF compilado:** `FORM-TL-01/main.pdf`

## Cómo compilar

**Compilador:** pdfLaTeX (TeX Live o MiKTeX), o Overleaf con compilador pdfLaTeX.

```
cd FORM-TL-01
pdflatex main.tex
pdflatex main.tex
```

Se ejecuta dos veces para resolver las referencias cruzadas y las tablas largas. No se usa BibTeX: las referencias están dentro del propio `main.tex`.

## Dependencias

Paquetes de LaTeX: `inputenc`, `geometry`, `booktabs`, `longtable`, `array`, `amsmath`, `hyperref`. Todos vienen incluidos en TeX Live y MiKTeX completos.
