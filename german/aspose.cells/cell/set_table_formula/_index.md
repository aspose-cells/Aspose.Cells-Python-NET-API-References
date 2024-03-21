---
title: set_table_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 370
url: /de/aspose.cells/cell/set_table_formula/
is_root: false
---
##  set_table_formula {#int-int-str-str-list}
Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit zwei Variablen für einen bestimmten Bereich.



```python
def set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Auffüllen der Formel.|
| row_input_cell | str | die Zeileneingabezelle|
| column_input_cell | str | die Spalte Eingabezelle|
| values | list | Werte für Zellen im Tabellenformelbereich|


##  set_table_formula {#int-int-str-bool-list}
Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit einer Variablen für einen bestimmten Bereich.



```python
def set_table_formula(self, row_number, column_number, input_cell, is_row_input, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Auffüllen der Formel.|
| input_cell | str | die Eingabezelle|
| is_row_input | bool | Gibt an, ob die Eingabezelle eine Zeileneingabezelle (wahr) oder eine Spalteneingabezelle (falsch) ist.|
| values | list | Werte für Zellen im Tabellenformelbereich|


##  set_table_formula {#int-int-int-int-bool-list}
Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit einer Variablen für einen bestimmten Bereich.



```python
def set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Auffüllen der Formel.|
| row_index_of_input_cell | int | Zeilenindex der Eingabezelle|
| column_index_of_input_cell | int | Spaltenindex der Eingabezelle|
| is_row_input | bool | Gibt an, ob die Eingabezelle eine Zeileneingabezelle (wahr) oder eine Spalteneingabezelle (falsch) ist.|
| values | list | Werte für Zellen im Tabellenformelbereich|


##  set_table_formula {#int-int-int-int-int-int-list}
Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit zwei Variablen für einen bestimmten Bereich.



```python
def set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Auffüllen der Formel.|
| row_index_of_row_input_cell | int | Zeilenindex der Zeileneingabezelle|
| column_index_of_row_input_cell | int | Spaltenindex der Zeileneingabezelle|
| row_index_of_column_input_cell | int | Zeilenindex der Spalteneingabezelle|
| column_index_of_column_input_cell | int | Spaltenindex der Spalteneingabezelle|
| values | list | Werte für Zellen im Tabellenformelbereich|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
