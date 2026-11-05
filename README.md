# R para todos

**EN** — Course material for "R para todos", an introduction to R with RStudio for data analysis, taught by Daniel Villa. It contains two classes written in Quarto, from installing R and RStudio to the basic data structures (vectors, matrices, arrays, data frames and lists), with exercises and solutions. Both classes are published on Quarto Pub.

**ES** — Material del curso "R para todos", una introducción a R desde RStudio para el análisis de datos, a cargo de Daniel Villa. Contiene dos clases escritas en Quarto, desde la instalación de R y RStudio hasta las estructuras de datos básicas (vectores, matrices, arreglos, marcos de datos y listas), con ejercicios resueltos. Las dos clases están publicadas en Quarto Pub.

## A quién va dirigido

A personas que se inician en R y RStudio. No se asume experiencia previa en
programación: la primera clase parte de la instalación del software.

## Clases

| Clase | Tema | Versión publicada | Fuente |
|---|---|---|---|
| 1 | Introducción al R | [dvilla.quarto.pub/introduccion-al-r](https://dvilla.quarto.pub/introduccion-al-r/) | [`Clase 1/Clase1.qmd`](Clase%201/Clase1.qmd) |
| 2 | Tipo de objetos | [dvilla.quarto.pub/tipo-de-objetos](https://dvilla.quarto.pub/tipo-de-objetos/) | [`Clase 2/Clase2.qmd`](Clase%202/Clase2.qmd) |

### Clase 1: Introducción al R

- Qué es R y para qué se usa en estadística, análisis y ciencia de datos.
- Instalación de R y RStudio en Windows y en Linux (Ubuntu).
- Primeros pasos en RStudio: consola, entorno, archivos y gráficos.
- Qué es un IDE y alternativas a RStudio.

### Clase 2: Tipo de objetos

- Variables y tipos de datos.
- Vectores: creación y estadísticas básicas (media, mediana, desviación
  estándar).
- Matrices: creación con nombres de filas y columnas, sumas por fila.
- Arreglos: datos en varias dimensiones y medias por dimensión.
- Marcos de datos (`data.frame`): creación y acceso a columnas.
- Listas: elementos de distinto tipo y acceso a sus componentes.
- Seis ejercicios con solución (`seq()`, `matrix()`, `list()`,
  `data.frame()`, filtrado de vectores y `diag()`).

## Cómo usar el material

1. Lea las clases en línea en los enlaces de la tabla; no requiere instalar
   nada.
2. Para trabajar con el código, clone el repositorio y abra
   `R Para Todos.Rproj` en RStudio.
3. Abra el archivo `.qmd` de cada clase y ejecute los bloques de código, o
   renderícelo con Quarto (botón *Render* en RStudio o
   `quarto render "Clase 1/Clase1.qmd"`). Cada carpeta incluye también el
   HTML ya generado.
4. `Ensayo0.R` es un script de práctica con operaciones básicas, tipos de
   datos, factores, indexación y matrices.

## Estructura

```
Clase 1/      Clase1.qmd, HTML generado y configuración de publicación
Clase 2/      Clase2.qmd, HTML generado, caché y configuración de publicación
Ensayo0.R     Script de práctica
```

## Autor y licencia

Daniel Felipe Villa Rengifo ([@dvillaunal](https://github.com/dvillaunal)),
abril de 2023. Licencia GPL-3 (ver [`LICENSE`](LICENSE)).
