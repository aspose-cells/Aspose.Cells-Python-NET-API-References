---
title: add_areas metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/validation/add_areas/
is_root: false
---
##  add_areas(self, areas, check_intersection, check_edge) {#list-bool-bool}
Tillämpar valideringen på givna områden.



```python

def add_areas(self, areas, check_intersection, check_edge):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| areas | list | Områdena.|
| check_intersection | bool | Om skärningspunkten mellan ett givet område och befintliga valideringsområden ska kontrolleras.<br/>Om en validering har tillämpats i ett givet område (eller en del av det),<br/>då bör den befintliga valideringen först tas bort från det givna området.<br/>Annars kan de genererade valideringar bli skadade.<br/>Om användaren är säker på att alla tillagda områden inte korsar något befintligt område,<br/> Den här parametern kan ställas in som falsk av prestandahänsyn.|
| check_edge | bool | Om kanten av denna validerings tillämpade områden ska kontrolleras.<br/>Valideringens interna inställningar beror på det övre vänstra av dess tillämpade intervall,<br/>så om ett av de givna områdena blir det nya övre vänstra av de tillämpade områdena,<br/>De interna inställningarna bör ändras och byggas om, annars kan oväntade resultat uppstå.<br/>Om användaren är säker på att inget av de tillagda områdena är det övre vänstra,<br/> Den här parametern kan ställas in som falsk av prestandahänsyn.|
###  Anmärkningar

Med den här metoden tar vi bort alla gamla valideringar i ett givet område.
För det övre vänstra av Validations tillämpade områden är för det första dess StartRow minst,
för det andra är dess Startkolumn det minsta av de områden som har samma minsta Startrad.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Validation`](/cells/python-net/sv/aspose.cells/validation)
