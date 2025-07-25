---
title: get_dependents metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Hämta alla celler vars formel refererar direkt till den här cellen.



```python

def get_dependents(self, is_all):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_all | bool |Anger om kontroll av formler i andra kalkylblad|
###  Anmärkningar

* Om en referens som innehåller den här cellen förekommer i en cells formel, kommer den cellen att tas som

den här cellens beroende, oavsett om referensen eller cellen används eller inte under beräkningen.
Till exempel, även om cell A2 i formeln "=OM(SANT;A1;A2)" inte används vid beräkning,
Denna formel kan fortfarande tas som A2:s beroende.
För att hämta de formler vars beräknade resultat är beroende av den här cellen, använd [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation). När man spårar beroenden för en cell kommer alla formler i arbetsboken eller kalkylbladet att analyseras och kontrolleras.
Så det är en tidskrävande process. Om användaren behöver spåra beroenden för många celler, kommer den här metoden att...
orsaka dålig prestanda. Av prestandaskäl bör användaren använda [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation) istället.
Eller så kan användaren först samla in en prejudikatkarta över alla celler med [`Cell.get_precedents`](/cells/python-net/sv/aspose.cells/cell/get_precedents),
och sedan bygga kartan över anhöriga enligt den tidigare kartan.

* Om en referens som innehåller den här cellen förekommer i en cells formel, kommer den cellen att tas som
den här cellens beroende, oavsett om referensen eller cellen används eller inte under beräkningen.
Till exempel, även om cell A2 i formeln "=OM(SANT;A1;A2)" inte används vid beräkning,
Denna formel kan fortfarande tas som A2:s beroende.
För att hämta de formler vars beräknade resultat är beroende av den här cellen, använd [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation). När man spårar beroenden för en cell kommer alla formler i arbetsboken eller kalkylbladet att analyseras och kontrolleras.
Så det är en tidskrävande process. Om användaren behöver spåra beroenden för många celler, kommer den här metoden att...
orsaka dålig prestanda. Av prestandaskäl bör användaren använda [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation) istället.
Eller så kan användaren först samla in en prejudikatkarta över alla celler med [`Cell.get_precedents`](/cells/python-net/sv/aspose.cells/cell/get_precedents),
och sedan bygga kartan över anhöriga enligt den tidigare kartan.

* Om en referens som innehåller den här cellen förekommer i en cells formel, kommer den cellen att tas som
den här cellens beroende, oavsett om referensen eller cellen används eller inte under beräkningen.
Till exempel, även om cell A2 i formeln "=OM(SANT;A1;A2)" inte används vid beräkning,
Denna formel kan fortfarande tas som A2:s beroende.
För att hämta de formler vars beräknade resultat är beroende av den här cellen, använd [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation). När man spårar beroenden för en cell kommer alla formler i arbetsboken eller kalkylbladet att analyseras och kontrolleras.
Så det är en tidskrävande process. Om användaren behöver spåra beroenden för många celler, kommer den här metoden att...
orsaka dålig prestanda. Av prestandaskäl bör användaren använda [`Cell.get_dependents_in_calculation`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation) istället.
Eller så kan användaren först samla in en prejudikatkarta över alla celler med [`Cell.get_precedents`](/cells/python-net/sv/aspose.cells/cell/get_precedents),
och sedan bygga kartan över anhöriga enligt den tidigare kartan.
###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
