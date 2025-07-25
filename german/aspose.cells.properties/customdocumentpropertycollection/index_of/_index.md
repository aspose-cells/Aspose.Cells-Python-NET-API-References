---
title: index_of Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.properties/customdocumentpropertycollection/index_of/
is_root: false
---
##  index_of(self, name) {#str}




```python

def index_of(self, name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| name | str |  |


##  index_of(self, item, index) {#aspose.cells.properties.DocumentProperty-int}
Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.


###  Kehrt zurück

Der nullbasierte Index des ersten Vorkommens von „value“ innerhalb des Elementbereichs in der Array-Liste, der sich vom Startindex bis zum letzten Element erstreckt, sofern gefunden; andernfalls -1.


```python

def index_of(self, item, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| item | [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty) | Das in der Array-Liste zu suchende Objekt. Der Wert kann null sein.|
| index | int | Der nullbasierte Startindex der Suche. 0 (Null) ist in einer leeren Liste gültig.|


##  index_of(self, item, index, count) {#aspose.cells.properties.DocumentProperty-int-int}
Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.


###  Kehrt zurück

Der nullbasierte Index des ersten Vorkommens von „value“ innerhalb des Elementbereichs in der Array-Liste, die bei „startIndex“ beginnt und die Anzahl der Elemente enthält (sofern gefunden); andernfalls –1.


```python

def index_of(self, item, index, count):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| item | [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty) | Das in der Array-Liste zu suchende Objekt. Der Wert kann null sein.|
| index | int | Der nullbasierte Startindex der Suche. 0 (Null) ist in einer leeren Liste gültig.|
| count | int | Die Anzahl der Elemente im zu durchsuchenden Abschnitt.|



###  Siehe auch
* Modul [`aspose.cells.properties`](../../)
* Klasse [`CustomDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection)
