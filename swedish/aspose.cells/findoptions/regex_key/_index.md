---
title: regex_key fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key fastighet

Anger om den sökta nyckeln är regex.
Om värdet är sant kommer den sökta nyckeln att tas som regex och parsas.
Annars kommer nyckeln att analyseras enligt reglerna i MS Excel.

###  Anmärkningar

Även om söknyckeln har angetts som regex,
Den kan omstruktureras enligt specificerad [`FindOptions.look_at_type`](/cells/python-net/sv/aspose.cells/findoptions#look_at_type).
Till exempel, när typen är [`LookAtType.CONTAINS`](/cells/python-net/sv/aspose.cells/lookattype#CONTAINS) (detta är standardvärdet för dessa alternativ),
Jokertecken läggs automatiskt till i början och slutet av söknyckeln för att säkerställa att matchningen blir
markerad som "innehåller". I det här fallet blir de reguljära uttrycken mer komplexa.
och prestandan kommer också att minska.
Så, av prestandaskäl, om användaren har angett den exakta regeln för regexen, finns det inget behov av att
använd [`FindOptions.look_at_type`](/cells/python-net/sv/aspose.cells/findoptions#look_at_type) som ytterligare begränsning och användaren kan ställa in den som [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/sv/aspose.cells/lookattype#ENTIRE_CONTENT)
för att få bättre prestanda.
###  Definition:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`FindOptions`](/cells/python-net/sv/aspose.cells/findoptions)
