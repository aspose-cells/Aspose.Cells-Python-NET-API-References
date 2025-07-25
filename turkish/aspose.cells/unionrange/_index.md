---
title: UnionRange sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1510
url: /tr/aspose.cells/unionrange/
is_root: false
---
##  UnionRange sınıfı
Birlik aralığını temsil eder.



UnionRange türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [first_row](/cells/python-net/tr/aspose.cells/unionrange/first_row) | Aralığın ilk satırının indeksini alır.|
| [first_column](/cells/python-net/tr/aspose.cells/unionrange/first_column) | Aralığın ilk sütununun indeksini alır.|
| [row_count](/cells/python-net/tr/aspose.cells/unionrange/row_count) | Aralıktaki satır sayısını alır.|
| [column_count](/cells/python-net/tr/aspose.cells/unionrange/column_count) | Aralıktaki satır sayısını alır.|
| [value](/cells/python-net/tr/aspose.cells/unionrange/value) | Aralığın değerlerini alır ve ayarlar.|
| [name](/cells/python-net/tr/aspose.cells/unionrange/name) | Aralığın adını alır veya ayarlar.|
| [refers_to](/cells/python-net/tr/aspose.cells/unionrange/refers_to) | Aralığın referansını alır.|
| [has_range](/cells/python-net/tr/aspose.cells/unionrange/has_range) | Bunun bir aralığı olup olmadığını gösterir.|
| [hyperlinks](/cells/python-net/tr/aspose.cells/unionrange/hyperlinks) | Aralıktaki tüm hiper bağlantıları alır.|
| [cell_count](/cells/python-net/tr/aspose.cells/unionrange/cell_count) | Aralıktaki tüm hücre sayısını alır.|
| [range_count](/cells/python-net/tr/aspose.cells/unionrange/range_count) |Aralıkların sayısını alır.|
| [ranges](/cells/python-net/tr/aspose.cells/unionrange/ranges) | Tüm birleşim aralıklarını alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/tr/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) | Bir dizi hücrenin etrafına çizgi kenarlıkları koyar.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/tr/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Aynı kenarlık stili ve rengine sahip bir dizi hücrenin etrafına dış hat kenarlıkları ayarlar.|
| [`intersect(self, range)`](/cells/python-net/tr/aspose.cells/unionrange/intersect/#str) | Başka bir aralığı keser.|
| [`intersect(self, union_range)`](/cells/python-net/tr/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) | Başka bir aralığı keser.|
| [`intersect(self, ranges)`](/cells/python-net/tr/aspose.cells/unionrange/intersect/#list) | Başka bir aralığı keser.|
| [`union(self, range)`](/cells/python-net/tr/aspose.cells/unionrange/union/#str) | Bir başka aralık birliği.|
| [`union(self, union_range)`](/cells/python-net/tr/aspose.cells/unionrange/union/#aspose.cells.unionrange) | Bir başka aralık birliği.|
| [`union(self, ranges)`](/cells/python-net/tr/aspose.cells/unionrange/union/#list) | Aralıkları birleştirin.|
| [`merge(self)`](/cells/python-net/tr/aspose.cells/unionrange/merge/#) |Bir dizi hücreyi tek bir hücrede birleştirir.|
| [`un_merge(self)`](/cells/python-net/tr/aspose.cells/unionrange/un_merge/#) | Bu aralıktaki birleştirilmiş hücreleri ayırır.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/tr/aspose.cells/unionrange/put_value/#str-bool-bool) | Aralığa bir değer koyar, uygunsa değer başka bir veri türüne dönüştürülür ve hücrenin sayı biçimi sıfırlanır.|
| [`set_style(self, style)`](/cells/python-net/tr/aspose.cells/unionrange/set_style/#aspose.cells.style) | Aralığın stilini ayarlar.|
| [`apply_style(self, style, flag)`](/cells/python-net/tr/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tüm aralık için biçimleri uygular.|
| [`copy(self, range, options)`](/cells/python-net/tr/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) | Aralığı yapıştırma özel seçenekleriyle kopyalama.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
