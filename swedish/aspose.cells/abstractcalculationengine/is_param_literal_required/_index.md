---
title: is_param_literal_required fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required fastighet

Indikerar om denna motor behöver den bokstavliga texten av parametern när den gör beräkningar. Standardvärdet är falskt.

###  Anmärkningar

Om den här anpassade beräkningsmotorn behöver parameterns bokstavliga text,
fler stackar kommer att krävas för att cachelagra den bokstavliga texten för parametrar
och metoden Calculate() kan anropas rekursivt för att beräkna parameterns värde.
I allmänhet behövs inte den bokstavliga texten för att beräkna formler
och den här egenskapen bör hållas som falsk för de flesta implementeringar för att få bättre prestanda.
###  Definition:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`AbstractCalculationEngine`](/cells/python-net/sv/aspose.cells/abstractcalculationengine)
