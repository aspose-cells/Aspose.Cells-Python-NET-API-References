---
title: calculated_value fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value fastighet

Hämtar eller ställer in det beräknade värdet för den här funktionen.

###  Anmärkningar

Användaren bör ställa in den här egenskapen i sin anpassade beräkningsmotor för de funktioner som motorn stöder,
och det inställda värdet returneras när den här egenskapen hämtas senare.
Det inställda värdet kan vara av möjliga typer av [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value),
eller en array av sådana värden, eller ett intervall, namn, refererat område.
Om man hämtar den här egenskapen innan man anger ett värde för den beräknas funktionen.
av standardberäkningsmotorn Aspose.Cells och sedan kommer det beräknade värdet att
returneras (generellt sett bör det vara #NAMN? för användardefinierade funktioner).
###  Definition:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata)
