---
title: método set_footer
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells/pagesetup/set_footer/
is_root: false
---
##  set_footer(self, section, footer_script) {#int-str}
Establece un script que formatea el pie de página de un archivo de Excel.



```python

def set_footer(self, section, footer_script):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| section | int |0: Sección izquierda, 1: Sección central, 2: Sección derecha.|
| footer_script | str | Script de formato de pie de página.|
###  Observaciones

Comandos de script:

| Dominio| Descripción|
| :- | :- |
| &PAG| Número de página actual|
| &NORTE| Número de páginas|
| &D| Fecha actual|
| &T| Hora actual|
| &A| Nombre de la hoja|
| &F| Nombre de archivo sin ruta|
| &"<FontName>"|Nombre de la fuente, por ejemplo: &"Arial"|
| &"<FontName>, <FontStyle>"| Nombre y estilo de fuente, por ejemplo: &"Arial,Bold"|
| &<FontSize>| Tamaño de fuente. Si este comando va seguido de un número simple para imprimir en el encabezado, se separará de la altura de la fuente con un espacio.|
| &K<RRGGBB>| Color de fuente, por ejemplo (ROJO): &KFF0000|
| &GRAMO| Guión de imagen|

Por ejemplo: "&Arial,Bold&8Nota al pie"


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`PageSetup`](/cells/python-net/es/aspose.cells/pagesetup)
