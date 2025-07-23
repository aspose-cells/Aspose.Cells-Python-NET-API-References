---
title: método set_header
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 200
url: /es/aspose.cells/pagesetup/set_header/
is_root: false
---
##  set_header(self, section, header_script) {#int-str}
Establece un script que formatea el encabezado de un archivo Excel.



```python

def set_header(self, section, header_script):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| section | int |0: Sección izquierda, 1: Sección central, 2: Sección derecha.|
| header_script | str | Script de formato de encabezado.|
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

Por ejemplo: "&Arial,Bold&8Header Note"


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`PageSetup`](/cells/python-net/es/aspose.cells/pagesetup)
