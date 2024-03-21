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

Hämtar eller ställer in det beräknade värdet för denna funktion.

###  Anmärkningar

Användaren bör ställa in den här egenskapen i sin anpassade beräkningsmotor för de funktioner som motorn stöder,
och det inställda värdet kommer att returneras när du får den här egenskapen senare.
Det inställda värdet kan vara av möjliga typer av [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value),
eller en uppsättning av sådana värden, eller ett intervall, namn, refererat område.
Om du får den här egenskapen innan du ställer in värdet på den kommer funktionen att beräknas
av standardberäkningsmotorn Aspose.Cells och sedan kommer det beräknade värdet
returneras (i allmänhet ska det vara #NAME? för användardefinierade funktioner).
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
