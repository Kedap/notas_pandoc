---
title: El café despierta por las mañanas
author: Daniel Arellano Palacios
date: 11 de noviembre de 2020
abstract: Este es un trabajo muy chilo
toc: true
geometry: margin=2cm
---

# Introducción

<!--
Estos son comentarios de HTML pero vale para todo lo que sea pandoc 😜
-->

Lorem ipsum dolor sit amet, officia excepteur ex fugiat reprehenderit enim
labore culpa sint ad nisi Lorem pariatur mollit ex esse exercitation amet. Nisi
anim cupidatat excepteur officia. Reprehenderit nostrud nostrud ipsum Lorem est
aliquip amet voluptate voluptate dolor minim nulla est proident. Nostrud
officia pariatur ut officia. Sit irure elit esse ea nulla sunt ex occaecat
reprehenderit commodo officia dolor Lorem duis laboris cupidatat officia
voluptate. Culpa proident adipisicing id nulla nisi laboris ex in Lorem sunt
duis officia eiusmod. Aliqua reprehenderit commodo ex non excepteur duis sunt
velit enim. Voluptate laboris sint cupidatat ullamco ut ea consectetur et est
culpa et culpa duis.

## Pasos

- Paso 1
- Paso 2
- Paso 3
- Paso 4
- Paso 5

\newpage

Ahora otros en:

1. Hola
2. Hola

**Podemos modificar la tabla de contenidos** con lo siguiente:

```bash
pandoc -Dlatex > plantilla.tex
```

Y así modificar el archivo que fue generado para después ejecutar: `echo
articulo.md | entr pandoc articulo.md --template=plantilla.tex -o paper.pdf`
para después agregar un `\newpage`

# Contexto bibliográfico

# Mi propósito

# Experimentación

# Conclusión

::: notes

Esto no aparece si fuera una presentación, las notas no las agarran
abstract: Es como si fuera un resumen
:::

# Usando bibliografía

Para usar bibliografías debemos tener _citeproc_ instalado para ejecutar lo
siguiente: `echo articulo.md | entr pandoc articulo.md --citeproc
--bibliography=citas.bib -t l atex --template=plantilla.tex -o paper.pdf` Este
trabajo necesitamos cite-proc [@benito1968]
No se si se pueda

# Bibliografías
