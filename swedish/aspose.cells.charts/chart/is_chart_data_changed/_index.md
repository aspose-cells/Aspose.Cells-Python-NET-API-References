---
title: is_chart_data_changed metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Upptäcker om ett diagrams datakälla har ändrats.


###  Returnerar

Returnerar sant om diagrammet har ändrats, annars returnerar falskt


```python

def is_chart_data_changed(self):
    ...
```


###  Anmärkningar

Metoden detekterar ändringarna i diagrammets datakälla innan diagrammet renderas till bildformat.
Vid första Chart.toImage-anropet kommer diagrammets källdata (t.ex. XValuesParseData, ValuesParseData) att registreras.
Innan du anropar Chart.toImage-metoden igen, anropa IsChartDataChanged-metoden för att kontrollera om Chart behöver renderas om.


###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`Chart`](/cells/python-net/sv/aspose.cells.charts/chart)
