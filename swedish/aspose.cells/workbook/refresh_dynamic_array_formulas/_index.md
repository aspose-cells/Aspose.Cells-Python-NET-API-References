---
title: refresh_dynamic_array_formulas metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Uppdaterar dynamiska matrisformler (spill in i ett nytt intervall av närliggande celler enligt aktuella data)
Andra formler i arbetsboken kommer inte att beräknas rekursivt även om de användes av dynamiska matrisformler.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| calculate | bool | Om beräknar och uppdaterar cellvärden för dessa dynamiska matrisformler|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Uppdaterar dynamiska matrisformler (spill in i ett nytt intervall av närliggande celler enligt aktuella data)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| calculate | bool | Om beräknar och uppdaterar cellvärden för dessa dynamiska matrisformler|
| copts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativen för att beräkna formler|
###  Anmärkningar

För prestandaöverväganden uppdaterar vi inte alla dynamiska matrisformler automatiskt
när själva formeln eller data den refererar till ändrades.
Så användaren måste anropa den här metoden manuellt efter de operationer som kan påverka dynamiska matrisformler,
som att importera/ställa in cellvärden, infoga/ta bort rader/kolumner/intervall, ...etc.

För de flesta formler med funktioner måste beräkningen av spillintervallet också beräknas formeln,
så i allmänhet är sant värde för "beräkna" flagga att föredra.
Om formeln är enkel, till exempel en intervallreferens eller matris (till exempel "=C1:E5", "={1,2;3,4}", ...),
enkel funktion på ett område eller array(till exempel "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
och alla formler kommer att beräknas senare (t.ex. av [`Workbook.calculate_formula`](/cells/python-net/sv/aspose.cells/workbook/calculate_formula)),
att sedan använda falsk vlaue för "beräkna"-flaggan kan undvika den duplicerade beräkningen till förmån för prestanda.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
