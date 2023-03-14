---
title: CellArea sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells/cellarea/
is_root: false
---
##  CellArea sınıfı
Bir hücre alanını temsil eder.



CellArea türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [CellArea()](/cells/python-net/tr/aspose.cells/cellarea/__init__/#) | CellArea'nın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [start_row](/cells/python-net/tr/aspose.cells/cellarea/start_row) | Bu alanın başlangıç satırını alır veya ayarlar.|
| [end_row](/cells/python-net/tr/aspose.cells/cellarea/end_row) | Bu alanın bitiş satırını alır veya ayarlar.|
| [start_column](/cells/python-net/tr/aspose.cells/cellarea/start_column) |Bu alanın başlangıç sütununu alır veya ayarlar.|
| [end_column](/cells/python-net/tr/aspose.cells/cellarea/end_column) | Bu alanın bitiş sütununu alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [create_cell_area(start_row, start_column, end_row, end_column)](/cells/python-net/tr/aspose.cells/cellarea/create_cell_area/#int-int-int-int) | Bir hücre alanı oluşturur.|
| [create_cell_area(start_cell_name, end_cell_name)](/cells/python-net/tr/aspose.cells/cellarea/create_cell_area/#str-str) | Bir hücre alanı oluşturur.|
| [compare_to(obj)](/cells/python-net/tr/aspose.cells/cellarea/compare_to/#any) | İki CellArea nesnesini sol üst köşelerine göre karşılaştırın.|



###  Örnek

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

###  Ayrıca bakınız
* modül [aspose.cells](..)
