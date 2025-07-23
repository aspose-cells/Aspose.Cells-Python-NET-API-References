---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Data för den nya pivottabellcachen.|
| dest_cell_name | str | Cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
Lägger till en ny pivottabell baserad på en annan pivottabell.


###  Returnerar

Det nya tillagda pivottabellindexet.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/sv/aspose.cells.pivot/pivottable) | Källpivottabellen.|
| dest_cell_name | str | Cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Data för den nya pivottabellcachen.|
| dest_cell_name | str | Cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|
| use_same_source | bool | Anger om samma datakälla används när en annan befintlig pivottabell har använt denna datakälla.<br/> Om egenskapen är sann sparar den minne.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Datacellsområdet för den nya pivottabellen. Exempel: Sheet1!A1:C8|
| row | int |Radindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Lägger till en ny pivottabell baserad på en annan pivottabell.


###  Returnerar

Det nya tillagda pivottabellindexet.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/sv/aspose.cells.pivot/pivottable) | Källpivottabellen.|
| row | int |Radindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Datacellsområdet för den nya pivottabellen. Exempel: Sheet1!A1:C8|
| row | int |Radindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|
| use_same_source | bool | Anger om samma datakälla används när en annan befintlig pivottabell har använt denna datakälla.<br/> Om egenskapen är sann sparar den minne.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Datacellsområdet för den nya pivottabellen. Exempel: Sheet1!A1:C8|
| cell | str | Cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|
| use_same_source | bool | Anger om samma datakälla används när en annan befintlig pivottabell har använt denna datakälla.<br/> Om egenskapen är sann sparar den minne.|
| is_xls_classic | bool | Anger om den klassiska pivottabellen från Excel 97-2003 ska läggas till.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
Lägger till ett nytt pivottabellobjekt i samlingen med flera konsolideringsområden som datakälla.


###  Returnerar

Det nya tillagda pivottabellindexet.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | list | De flera konsolideringsområdena, såsom {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Om ett fält på en enda sida ska skapas automatiskt.<br/> Om värdet är sant kommer följande parameter pageFields att ignoreras.|
| page_fields | [`PivotPageFields`](/cells/python-net/sv/aspose.cells.pivot/pivotpagefields) | Fältobjekten på pivotsidan.|
| dest_cell_name | str | destCellName Namnet på den nya pivottabellrapporten.|
| table_name | str | namnet på den nya pivottabellrapporten.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
Lägger till en ny pivottabell.


###  Returnerar

Det nya tillagda cacheindexet.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | str | Datacellsområdet för den nya pivottabellen. Exempel: Sheet1!A1:C8|
| row | int |Radindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|
| use_same_source | bool | Anger om samma datakälla används när en annan befintlig pivottabell har använt denna datakälla.<br/> Om egenskapen är sann sparar den minne.|
| is_xls_classic | bool | Anger om den klassiska pivottabellen från Excel 97-2003 ska läggas till.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
Lägger till ett nytt pivottabellobjekt i samlingen med flera konsolideringsområden som datakälla.


###  Returnerar

Det nya tillagda pivottabellindexet.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_data | list | De flera konsolideringsområdena, såsom {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Om ett fält på en enda sida ska skapas automatiskt.<br/> Om sant kommer följande parameter pageFields att ignoreras|
| page_fields | [`PivotPageFields`](/cells/python-net/sv/aspose.cells.pivot/pivotpagefields) | Fältobjekten på pivotsidan.|
| row | int |Radindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av pivottabellrapportens målområde.|
| table_name | str | Namnet på den nya pivottabellrapporten.|



###  Se även
* modul [`aspose.cells.pivot`](../../)
* klass [`PivotTableCollection`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection)
