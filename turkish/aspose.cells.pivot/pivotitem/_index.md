---
title: PivotItem sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 180
url: /tr/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem sınıfı
PivotField raporundaki bir öğeyi temsil eder.



PivotItem türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_hidden](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_hidden) | Pivot öğesinin gizli olup olmadığını alır ve ayarlar.|
| [position](/cells/python-net/tr/aspose.cells.pivot/pivotitem/position) | Aynı ana düğüm altındaki PivotItems'larda değil, tüm PivotItems'larda konum indeksini belirtmek.|
| [position_in_same_parent_node](/cells/python-net/tr/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Aynı üst düğüm altındaki PivotItems'larda konum indeksini belirtme.|
| [is_hide_detail](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_hide_detail) | Pivot öğesinin ayrıntıyı gizleyip gizlemeyeceğini alır ve ayarlar.|
| [is_detail_hidden](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_detail_hidden) |Bu pivot öğesinin ayrıntısının gizli olup olmadığını alır ve ayarlar.|
| [is_calculated_item](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_calculated_item) | Bu pivot öğesinin hesaplanmış bir formül öğesi olup olmadığını belirtir.|
| [is_formula](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_formula) | Bu pivot öğesinin hesaplanmış bir formül öğesi olup olmadığını belirtir.|
| [is_missing](/cells/python-net/tr/aspose.cells.pivot/pivotitem/is_missing) | Öğenin veri kaynağından kaldırılıp kaldırılmadığını gösterir.|
| [value](/cells/python-net/tr/aspose.cells.pivot/pivotitem/value) | Pivot öğesinin değerini alır|
| [name](/cells/python-net/tr/aspose.cells.pivot/pivotitem/name) | Pivot öğesinin adını alır.|
| [index](/cells/python-net/tr/aspose.cells.pivot/pivotitem/index) | Önbellek alanındaki pivot öğesinin dizinini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/tr/aspose.cells.pivot/pivotitem/move/#int-bool) | Öğeyi yukarı veya aşağı taşır|
| [`get_formula(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotitem/get_formula/#) | Hesaplanan bu öğenin formülünü alır.<br/> Bu öğe yalnızca hesaplanan öğe olduğunda çalışır.|
| [`get_string_value(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotitem/get_string_value/#) | Pivot öğesinin dize değerini alır<br/> Değer null ise "" döndürülür|
| [`get_double_value(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotitem/get_double_value/#) | Pivot öğesinin çift değerini alır<br/> Değer null veya sayı değilse 0 döndürecektir|
| [`get_date_time_value(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Pivot öğesinin tarih/saat değerini alır<br/> Değer null ise DateTime.MinValue değerini döndürecektir.|



###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
