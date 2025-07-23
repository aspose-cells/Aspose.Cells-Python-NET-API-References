---
title: enable_calculation_chain fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain fastighet

Om beräkningskedjan för formler ska aktiveras. Standardvärdet är falskt.

###  Anmärkningar

När det finns många formler i arbetsboken och användaren behöver beräkna dem upprepade gånger
Genom att endast modifiera en liten del av dem kan det vara bra för prestandan att aktivera beräkningskedjan.
Å andra sidan, om kedjan är aktiverad, kräver underhåll av kedjemodellen extra minne,
och det kräver också lite mer processortid för vissa andra operationer, som att ändra cellers värde eller formler.
Efter att denna egenskap ändrats från falskt till sant kommer beräkningskedjan att analyseras och byggas
vid tidpunkten för den första beräkningen för arbetsboken, så den tid som krävs för den första beräkningen
kan vara mer än normal beräkning utan kedja.
###  Definition:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`FormulaSettings`](/cells/python-net/sv/aspose.cells/formulasettings)
