---
title: refresh_dynamic_array_formulas metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 290
url: /sv/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Uppdaterar dynamiska matrisformler (övergår till ett nytt område av angränsande celler enligt aktuell data)
Andra formler i arbetsboken kommer inte att beräknas rekursivt även om de användes av dynamiska matrisformler.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| calculate | bool | Om cellvärden för dessa dynamiska matrisformler beräknas och uppdateras|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Uppdaterar dynamiska matrisformler (övergår till ett nytt område av angränsande celler enligt aktuell data)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| calculate | bool | Om cellvärden för dessa dynamiska matrisformler beräknas och uppdateras|
| copts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativen för att beräkna formler|
###  Anmärkningar

Av prestandaskäl uppdaterar vi inte alla dynamiska matrisformler automatiskt.
när själva formeln eller de data den refererar till ändrades.
Så användaren måste anropa den här metoden manuellt efter de operationer som kan påverka dynamiska arrayformler,
såsom att importera/ställa in cellvärden, infoga/ta bort rader/kolumner/intervall, ...etc.

För de flesta formler med funktioner måste beräkningen av spillintervallet också beräkna formeln,
så i allmänhet är sant värde för flaggan "beräkna" att föredra.
Om formeln är enkel, till exempel en områdesreferens eller array (till exempel "=C1:E5", "={1,2;3,4}", ...),
enkel funktion på ett område eller en array (till exempel "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
och alla formler kommer att beräknas senare (t.ex. med [`Workbook.calculate_formula`](/cells/python-net/sv/aspose.cells/workbook/calculate_formula)),
Genom att använda falskt värde för flaggan "beräkna" kan duplicerad beräkning undvikas, vilket förbättrar prestandan.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
