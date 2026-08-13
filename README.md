# Evaluación Unidad IV — Ingeniería de Requisitos (ISR-401)

Prueba Práctica Unidad IV, Paralelo B — caso **Sistema de Reserva de Citas Médicas**.
Universidad Técnica Estatal de Quevedo · Carrera de Ingeniería de Software.

El documento reproduce el instrumento entregado por el docente e incorpora el desarrollo
de las actividades **P1 a P5**, cada una inmediatamente debajo de su enunciado.

## Estructura

```
.
├── main.tex          # archivo principal (único .tex que se compila)
├── referencias.bib   # bibliografía (natbib / plainnat)
├── figuras/
│   └── P3-maquina-estados-cita_drawio.png
├── main.pdf          # PDF compilado
└── README.md
```

## Compilación

Compilador: **pdflatex**. Archivo principal: **main.tex**.

```bash
pdflatex main.tex
bibtex   main
pdflatex main.tex
pdflatex main.tex
```

Salida esperada: `main.pdf`.

## Dependencias (paquetes LaTeX)

`inputenc`, `fontenc`, `helvet`, `textcomp`, `geometry`, `amsmath`, `amssymb`, `graphicx`,
`xcolor`, `array`, `tabularx`, `multirow`, `colortbl`, `booktabs`, `enumitem`, `microtype`,
`parskip`, `titlesec`, `fancyhdr`, `caption`, `pdflscape`, `natbib`, `hyperref`, `tcolorbox`,
`float`, `tikz` (librerías `shapes.geometric`, `shapes.multipart`, `arrows.meta`, `positioning`,
`calc`, `fit`, `backgrounds`).

Instalación en Debian/Ubuntu:

```bash
sudo apt install texlive-latex-base texlive-latex-extra texlive-fonts-recommended \
                 texlive-pictures texlive-bibtex-extra
```

En Windows (MiKTeX o TeX Live) los paquetes se instalan bajo demanda en la primera compilación.

## Pendiente antes de entregar

1. ~~Completar los campos **Estudiante** y **Fecha** de la cabecera.~~ Hecho.
2. Agregar la carátula con la URL del repositorio en una sola línea.
3. Insertar las capturas del resumen y del intento del cuestionario del SGA.
