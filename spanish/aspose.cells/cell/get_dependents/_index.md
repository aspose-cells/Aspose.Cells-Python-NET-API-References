---
title: método get_dependents
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Obtenga todas las celdas cuya fórmula haga referencia a esta celda directamente.



```python

def get_dependents(self, is_all):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| is_all | bool |Indica si se verifican fórmulas en otras hojas de cálculo|
###  Observaciones

* Si en la fórmula de una celda aparece una referencia que contiene esta celda, esa celda se tomará como

el dependiente de esta celda, sin importar la referencia o si esta celda se usa o no al calcular.
Por ejemplo, aunque la celda A2 en la fórmula "=SI(VERDADERO,A1,A2)" no se utiliza durante el cálculo,
Esta fórmula todavía debe tomarse como dependiente de A2.
Para obtener las fórmulas cuyos resultados calculados dependen de esta celda, utilice [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation). Al rastrear dependientes para una celda, se analizarán y verificarán todas las fórmulas en el libro o la hoja de trabajo.
Por lo tanto, es un proceso que requiere mucho tiempo. Si el usuario necesita rastrear dependencias para muchas celdas, usar este método...
Provocar un rendimiento deficiente. Para mejorar el rendimiento, el usuario debería usar [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation).
O bien, el usuario puede recopilar el mapa de precedentes de todas las celdas mediante [`Cell.get_precedents`](/cells/python-net/es/aspose.cells/cell/get_precedents) en primer lugar.
y luego construir el mapa de dependientes de acuerdo con el mapa de precedentes.

* Si en la fórmula de una celda aparece una referencia que contiene esta celda, esa celda se tomará como
el dependiente de esta celda, sin importar la referencia o si esta celda se usa o no al calcular.
Por ejemplo, aunque la celda A2 en la fórmula "=SI(VERDADERO,A1,A2)" no se utiliza durante el cálculo,
Esta fórmula todavía debe tomarse como dependiente de A2.
Para obtener las fórmulas cuyos resultados calculados dependen de esta celda, utilice [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation). Al rastrear dependientes para una celda, se analizarán y verificarán todas las fórmulas en el libro o la hoja de trabajo.
Por lo tanto, es un proceso que requiere mucho tiempo. Si el usuario necesita rastrear dependencias para muchas celdas, usar este método...
Provocar un rendimiento deficiente. Para mejorar el rendimiento, el usuario debería usar [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation).
O bien, el usuario puede recopilar el mapa de precedentes de todas las celdas mediante [`Cell.get_precedents`](/cells/python-net/es/aspose.cells/cell/get_precedents) en primer lugar.
y luego construir el mapa de dependientes de acuerdo con el mapa de precedentes.

* Si en la fórmula de una celda aparece una referencia que contiene esta celda, esa celda se tomará como
el dependiente de esta celda, sin importar la referencia o si esta celda se usa o no al calcular.
Por ejemplo, aunque la celda A2 en la fórmula "=SI(VERDADERO,A1,A2)" no se utiliza durante el cálculo,
Esta fórmula todavía debe tomarse como dependiente de A2.
Para obtener las fórmulas cuyos resultados calculados dependen de esta celda, utilice [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation). Al rastrear dependientes para una celda, se analizarán y verificarán todas las fórmulas en el libro o la hoja de trabajo.
Por lo tanto, es un proceso que requiere mucho tiempo. Si el usuario necesita rastrear dependencias para muchas celdas, usar este método...
Provocar un rendimiento deficiente. Para mejorar el rendimiento, el usuario debería usar [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation).
O bien, el usuario puede recopilar el mapa de precedentes de todas las celdas mediante [`Cell.get_precedents`](/cells/python-net/es/aspose.cells/cell/get_precedents) en primer lugar.
y luego construir el mapa de dependientes de acuerdo con el mapa de precedentes.
###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
