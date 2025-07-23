---
title: calculation_id fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells/formulasettings/calculation_id/
is_root: false
---
##  calculation_id fastighet

Anger vilken version av beräkningsmotorn som används för att beräkna värden i arbetsboken.

###  Anmärkningar

Den här egenskapen är endast till för att spara inställningarna till den resulterande kalkylbladsfilen.
så att andra program (som MS Excel) kan agera därefter när de laddar och manipulerar den resulterande filen.
fallet med MS Excel, om värdet på den här egenskapen är mindre än den associerade omberäkningsmotoridentifieraren
Med programmet som öppnar den resulterande filen kommer programmet att beräkna om resultaten av alla formler
i den här arbetsboken direkt efter att filen har laddats.
Av prestandaskäl för de flesta användares applikationer beräknar vi inte någon formler automatiskt i arbetsboken,
oavsett vilket värde som har satts för denna egendom.
###  Definition:
```python
@property
def calculation_id(self):
    ...
@calculation_id.setter
def calculation_id(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`FormulaSettings`](/cells/python-net/sv/aspose.cells/formulasettings)
