---
title: add_area metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Tillämpar valideringen på området.



```python

def add_area(self, cell_area):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) | Området.|
###  Anmärkningar

Det motsvarar att använda [`Validation.add_area`](/cells/python-net/sv/aspose.cells/validation/add_area)
med kontroll av korsning och kant.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Tillämpar valideringen på området.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) | Området.|
| check_intersection | bool | Om skärningspunkten mellan ett givet område och befintliga valideringsområden ska kontrolleras.<br/>Om en validering har tillämpats i ett givet område (eller en del av det),<br/>då bör den befintliga valideringen först tas bort från det givna området.<br/>Annars kan de genererade valideringar bli skadade.<br/>Om användaren är säker på att det tillagda området inte korsar något befintligt område,<br/> Den här parametern kan ställas in som falsk av prestandahänsyn.|
| check_edge | bool | Om kanten av denna validerings tillämpade områden ska kontrolleras.<br/>Valideringens interna inställningar beror på det övre vänstra av dess tillämpade intervall,<br/>så om ett givet område blir det nya övre vänstra av de tillämpade områdena,<br/>De interna inställningarna bör ändras och byggas om, annars kan oväntade resultat uppstå.<br/>Om användaren är säker på att det tillagda området inte är det övre vänstra,<br/> Den här parametern kan ställas in som falsk av prestandahänsyn.|
###  Anmärkningar

Med den här metoden tar vi bort alla gamla valideringar i ett givet område.
För det övre vänstra av Validations tillämpade områden är för det första dess StartRow minst,
för det andra är dess Startkolumn det minsta av de områden som har samma minsta Startrad.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Validation`](/cells/python-net/sv/aspose.cells/validation)
