# Mora-IRS401-Prueba_U4

Prueba Práctica — Unidad IV de la asignatura Ingeniería de Requerimientos (ISR-401).

**Caso:** Sistema de Gestión de Pedidos
**Estudiante:** Mora Duarte Alex José
**Universidad:** Universidad Técnica Estatal de Quevedo

## Archivo principal

`Mora_IRS401_Prueba_U4.tex`

## Compilador

`pdflatex`

## Dependencias

Se requiere una distribución LaTeX compatible, como **MiKTeX** o **TeX Live**.

Paquetes utilizados:

* `inputenc`
* `fontenc`
* `babel`
* `graphicx`
* `geometry`
* `hyperref`
* `float`
* `caption`
* `array`
* `tabularx`
* `tikz`

Librerías TikZ utilizadas:

* `arrows.meta`
* `positioning`
* `shapes.geometric`
* `shapes.multipart`
* `calc`

## Orden de compilación

Ejecutar desde la raíz del repositorio:

```bash
pdflatex Mora_IRS401_Prueba_U4.tex
pdflatex Mora_IRS401_Prueba_U4.tex
```

El archivo generado será:

```text
Mora_IRS401_Prueba_U4.pdf
```

## Estructura del repositorio

```text
Mora-IRS401-Prueba_U4/
├── Mora_IRS401_Prueba_U4.tex
├── Mora_IRS401_Prueba_U4.pdf
├── README.md
└── figuras/
    ├── 01_resumen_cuestionario_sga.png
    └── 02_evaluacion_intento_sga.png
```

## Reproducción

1. Clonar el repositorio.
2. Abrir una terminal en la carpeta raíz.
3. Verificar que la carpeta `figuras/` contenga las dos capturas utilizadas en la carátula.
4. Ejecutar dos veces `pdflatex Mora_IRS401_Prueba_U4.tex`.
5. Comprobar que se genere correctamente `Mora_IRS401_Prueba_U4.pdf`.
