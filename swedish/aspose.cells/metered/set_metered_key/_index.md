---
title: set_metered_key metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key {#str-str}
Ställer in mätt offentlig och privat nyckel.
 Om du köper mätlicens, när du startar ansökan, bör denna API kallas, normalt räcker detta.
 Om dock alltid misslyckas med att ladda upp förbrukningsdata och överskrider 24 timmar, kommer licensen att ställas in på utvärderingsstatus,
för att undvika sådana fall bör du regelbundet kontrollera licensstatusen, om det är utvärderingsstatus, ring detta API igen.



```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| public_key | str | offentlig nyckel|
| private_key | str | privat nyckel|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Metered`](/cells/python-net/sv/aspose.cells/metered)
