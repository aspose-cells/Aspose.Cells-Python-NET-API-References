---
title: get_equation_paragraph metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.drawing/textbox/get_equation_paragraph/
is_root: false
---
##  get_equation_paragraph(self) {#}
Hämtar det första matematiska stycket från TextBody-egenskapen för TextBox-objektet.


###  Returnerar

Om det finns ett matematiskt stycke returneras det första, annars returneras null.


```python

def get_equation_paragraph(self):
    ...
```




##  get_equation_paragraph(self, index) {#int}
Hämta det angivna matematiska stycket från TextBody-egenskapen för TextBox-objektet.
Varsel:
(1) Returnerar NULL när indexet är utanför gränserna eller inte hittas.
(2) Returnerar även NULL om den angivna indexpositionen inte är ett matematiskt stycke.


###  Returnerar

Returnerar det matematiska stycket som anges av index.


```python

def get_equation_paragraph(self, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Positionens index för matematikstycket, med början från 0.|



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox)
