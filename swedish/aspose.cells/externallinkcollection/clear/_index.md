---
title: clear metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Tar bort alla externa länkar.



```python

def clear(self):
    ...
```


###  Anmärkningar

När du tar bort externa länkar kommer även alla formler som refererar till dem att tas bort eftersom
referenserna blir ogiltiga.

##  clear(self, update_references_as_local) {#bool}
Tar bort alla externa länkar.



```python

def clear(self, update_references_as_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| update_references_as_local | bool |Om alla referenser till externa länkar i formler ska uppdateras till referenser i den aktuella arbetsboken.|
###  Anmärkningar

Om referenser behöver uppdateras, dessa referenser till externa länkar i formler
kommer att ändras till aktuell arbetsbok när det är möjligt.
Till exempel är en cells ursprungliga formel "='externalsource.xlam'!customfunction()",
efter att externa länkar tagits bort blir formeln "=customfunction()";
När den ursprungliga formeln är "='[externalsource.xlam]Sheet1'!$A$1",
beroende på om det finns ett ark med namnet "Ark1" i den aktuella arbetsboken:
om det är sant blir formeln "=Sheet1!$A$1";
Om det är falskt blir formeln "=#REF!$A$1".

Om referenser inte behöver uppdateras, alla formler med referenser till externa länkar
kommer också att tas bort eftersom dessa referenser blir ogiltiga.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`ExternalLinkCollection`](/cells/python-net/sv/aspose.cells/externallinkcollection)
