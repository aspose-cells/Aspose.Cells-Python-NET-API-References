---
title: auto_fit_row metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/worksheet/auto_fit_row/
is_root: false
---
##  auto_fit_row(self, row_index) {#int}
Anpassar radhöjden automatiskt.



```python

def auto_fit_row(self, row_index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Radindex.|
###  Anmärkningar

AutoFitRow är en oprecis funktion.

##  auto_fit_row(self, row_index, first_column, last_column) {#int-int-int}

Anpassar radhöjden automatiskt.



```python

def auto_fit_row(self, row_index, first_column, last_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Radindex.|
| first_column | int | Första kolumnens index.|
| last_column | int | Index för sista kolumnen.|
###  Anmärkningar

Den här metoden anpassar automatiskt en rad baserat på innehållet i ett cellområde inom raden.

##  auto_fit_row(self, row_index, first_column, last_column, options) {#int-int-int-aspose.cells.AutoFitterOptions}

Anpassar radhöjden automatiskt.



```python

def auto_fit_row(self, row_index, first_column, last_column, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Radindex.|
| first_column | int | Första kolumnens index.|
| last_column | int | Index för sista kolumnen.|
| options | [`AutoFitterOptions`](/cells/python-net/sv/aspose.cells/autofitteroptions) | Alternativen för automatisk montör|
###  Anmärkningar

Den här metoden anpassar automatiskt en rad baserat på innehållet i ett cellområde inom raden.

##  auto_fit_row(self, start_row, end_row, start_column, end_column) {#int-int-int-int}

Anpassar automatiskt radhöjden i ett rektangulärt område.



```python

def auto_fit_row(self, start_row, end_row, start_column, end_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start_row | int | Index för startrad.|
| end_row | int | Index för slutrad.|
| start_column | int |Starta kolumnindex.|
| end_column | int | Index för slutkolumn.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
