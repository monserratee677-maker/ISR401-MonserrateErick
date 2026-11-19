# Ingeniería de Requerimientos (ISR-401) — UTEQ

## EV-PRAC-01 · Evaluación de la Unidad I (caso FRÍOVAC)

Transcripción fiel de la prueba escrita a mano. Las fotografías originales de las hojas están en `EV-PRAC-01/evidencias/`.

### Estructura

```
EV-PRAC-01/
├── evidencias/
│   ├── hoja-01.jpg
│   ├── hoja-02.jpg
│   └── hoja-03.jpg
├── main.tex      ← archivo principal
└── main.pdf      ← PDF compilado
```

### Compilación

- **Compilador:** `pdflatex` (TeX Live 2022 o posterior, o MiKTeX)
- **Archivo principal:** `EV-PRAC-01/main.tex`
- **Orden de comandos** (desde la raíz del repositorio):

```bash
cd EV-PRAC-01
pdflatex main.tex
pdflatex main.tex
```

  Alternativa: `latexmk -pdf main.tex`

- **Dependencias (paquetes LaTeX):** `inputenc`, `fontenc`, `babel` (idioma `spanish`), `geometry`, `array`, `tabularx`, `graphicx`, `xcolor`, `float`, `hyperref`. Vienen con TeX Live completo y con MiKTeX (este último instala automáticamente los que falten).
- **Imágenes:** `main.tex` carga las fotos desde `evidencias/` con rutas relativas, así que hay que compilar dentro de la carpeta `EV-PRAC-01/`.
