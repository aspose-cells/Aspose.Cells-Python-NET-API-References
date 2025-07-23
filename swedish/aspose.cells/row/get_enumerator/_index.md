---
title: get_enumerator metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/row/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Hämtar en uppräknare som itererar celler genom den här raden.


###  Returnerar

Celluppräknaren


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| reversed | bool |om cellerna ska räknas upp i omvänd ordning|
| sync | bool | om den returnerade uppräknaren ska kontrollera modifieringen av cellerna i den här raden<br/> och hålla sig synkroniserad med den.|
###  Anmärkningar

Om raden kommer att ändras (genom operationer som kan orsaka att nya Cell instansieras eller
befintlig Cell tas bort) under genomgången med uppräknaren,
En synkroniserad uppräknare bör användas istället för en vanlig uppräknare så att genomgången kan fortsätta.
från positionen precis efter att den har passerats av den sista MoveNext().
Men tillsammans med fördelen att inget element behöver hoppas över eller gås igenom upprepade gånger,
Nackdelen med synkroniserad uppräknare är att prestandan försämras något.
vid jämförelse med en vanlig uppräknare.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Row`](/cells/python-net/sv/aspose.cells/row)
