---
title: remove_at metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Tar bort den angivna externa länken från arbetsboken.



```python

def remove_at(self, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | indexet för den externa länken som ska tas bort.|
###  Anmärkningar

När du tar bort den externa länken kommer även alla formler som refererar till den att tas bort eftersom
referenserna blir ogiltiga.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Tar bort den angivna externa länken från arbetsboken.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | indexet för den externa länken som ska tas bort.|
| update_references_as_local | bool | Om alla referenser till den givna externa länken ska uppdateras till referensen till den aktuella arbetsboken.<br/> Kontrollera [`ExternalLinkCollection.clear`](/cells/python-net/sv/aspose.cells/externallinkcollection/clear) för mer information om den här parametern.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`ExternalLinkCollection`](/cells/python-net/sv/aspose.cells/externallinkcollection)
