---
title: Range sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1290
url: /tr/aspose.cells/range/
is_root: false
---
##  Range sınıfı
Bir elektronik tablodaki bir hücre aralığını temsil eden nesneyi kapsüller.



Range türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [current_region](/cells/python-net/tr/aspose.cells/range/current_region) |Geçerli bölgeyi temsil eden bir Range nesnesi döndürür.<br/> Geçerli bölge, boş satırların ve boş sütunların herhangi bir birleşimiyle sınırlanan bir aralıktır.|
| [hyperlinks](/cells/python-net/tr/aspose.cells/range/hyperlinks) | Aralıktaki tüm köprüleri alır.|
| [row_count](/cells/python-net/tr/aspose.cells/range/row_count) | Aralıktaki satır sayısını alır.|
| [column_count](/cells/python-net/tr/aspose.cells/range/column_count) | Aralıktaki sütunların sayısını alır.|
| [name](/cells/python-net/tr/aspose.cells/range/name) | Aralığın adını alır veya ayarlar.|
| [refers_to](/cells/python-net/tr/aspose.cells/range/refers_to) | Aralığın referanslarını alır.|
| [address](/cells/python-net/tr/aspose.cells/range/address) | Aralığın adresini alır.|
| [left](/cells/python-net/tr/aspose.cells/range/left) | A sütununun sol kenarından aralığın sol kenarına kadar olan mesafeyi nokta cinsinden alır.|
| [top](/cells/python-net/tr/aspose.cells/range/top) | 1. satırın üst kenarından aralığın üst kenarına kadar olan mesafeyi nokta cinsinden alır.|
| [width](/cells/python-net/tr/aspose.cells/range/width) | Bir aralığın genişliğini nokta cinsinden alır.|
| [height](/cells/python-net/tr/aspose.cells/range/height) | Bir aralığın genişliğini nokta cinsinden alır.|
| [first_row](/cells/python-net/tr/aspose.cells/range/first_row) | Aralığın ilk satırının indeksini alır.|
| [first_column](/cells/python-net/tr/aspose.cells/range/first_column) | Aralığın ilk sütununun dizinini alır.|
| [value](/cells/python-net/tr/aspose.cells/range/value) | Aralığın değerini alır ve ayarlar.|
| [column_width](/cells/python-net/tr/aspose.cells/range/column_width) | Bu aralığın sütun genişliğini ayarlar veya alır|
| [row_height](/cells/python-net/tr/aspose.cells/range/row_height) | Bu aralıktaki satırların yüksekliğini ayarlar veya alır|
| [entire_column](/cells/python-net/tr/aspose.cells/range/entire_column) | Belirtilen aralığı içeren sütunun (veya sütunların) tamamını temsil eden bir Range nesnesi alır.|
| [entire_row](/cells/python-net/tr/aspose.cells/range/entire_row) |Belirtilen aralığı içeren satırın tamamını (veya satırları) temsil eden bir Range nesnesi alır.|
| [worksheet](/cells/python-net/tr/aspose.cells/range/worksheet) | Bu aralığı içeren [`Range.worksheet`](/cells/python-net/tr/aspose.cells/range#worksheet) nesnesini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [auto_fill](/cells/python-net/tr/aspose.cells/range/auto_fill/#aspose.cells.Range) | Hedef aralığı otomatik olarak doldurun.|
| [auto_fill](/cells/python-net/tr/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Hedef aralığı otomatik olarak doldurun.|
| [set_style](/cells/python-net/tr/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Hücre stilini uygulayın.|
| [set_style](/cells/python-net/tr/aspose.cells/range/set_style/#aspose.cells.Style) | Aralığın stilini ayarlar.|
| [set_outline_borders](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Aynı kenarlık stiline ve rengine sahip bir hücre aralığının etrafındaki anahat kenarlıklarını ayarlar.|
| [set_outline_borders](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Aynı kenarlık stiline ve rengine sahip bir hücre aralığının etrafındaki anahat kenarlıklarını ayarlar.|
| [set_outline_borders](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Bir hücre aralığının etrafındaki çizgi kenarlıklarını belirler.|
| [set_outline_border](/cells/python-net/tr/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Bir hücre aralığının etrafındaki ana hat kenarlığını ayarlar.|
| [set_outline_border](/cells/python-net/tr/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Bir hücre aralığının etrafındaki ana hat kenarlığını ayarlar.|
| [copy](/cells/python-net/tr/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Aralığın özel yapıştırma seçenekleriyle kopyalanması.|
| [copy](/cells/python-net/tr/aspose.cells/range/copy/#aspose.cells.Range) | Kaynak aralığından verileri (formüller dahil), biçimlendirmeyi, çizim nesnelerini vb. kopyalar.|
| [add_hyperlink](/cells/python-net/tr/aspose.cells/range/add_hyperlink/#str-str-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [get_enumerator](/cells/python-net/tr/aspose.cells/range/get_enumerator/#) | Bu Aralıktaki hücrelerin numaralandırıcısını alır.|
| [is_intersect](/cells/python-net/tr/aspose.cells/range/is_intersect/#aspose.cells.Range) | Aralığın kesişip kesişmediğini belirtir.|
| [intersect](/cells/python-net/tr/aspose.cells/range/intersect/#aspose.cells.Range) | İki aralığın dikdörtgen kesişimini temsil eden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür.|
| [union_rang](/cells/python-net/tr/aspose.cells/range/union_rang/#aspose.cells.Range) | İki aralığın birleşme sonucunu döndürür.|
| [union](/cells/python-net/tr/aspose.cells/range/union/#aspose.cells.Range) | İki aralığın birleşimini döndürür.|
| [is_blank](/cells/python-net/tr/aspose.cells/range/is_blank/#) | Aralığın değerler içerip içermediğini gösterir.|
| [merge](/cells/python-net/tr/aspose.cells/range/merge/#) | Bir dizi hücreyi tek bir hücrede birleştirir.|
| [un_merge](/cells/python-net/tr/aspose.cells/range/un_merge/#) |Bu aralıktaki birleştirilmiş hücreleri ayırır.|
| [put_value](/cells/python-net/tr/aspose.cells/range/put_value/#str-bool-bool) | Aralığa bir değer koyar, uygunsa değer başka bir veri türüne dönüştürülür ve hücrenin sayı formatı sıfırlanır.|
| [apply_style](/cells/python-net/tr/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Tüm aralık için formatları uygular.|
| [set_inside_borders](/cells/python-net/tr/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Aralığın sınırlarının içine ayarlayın.|
| [move_to](/cells/python-net/tr/aspose.cells/range/move_to/#int-int) | Geçerli aralığı hedef aralığa taşıyın.|
| [copy_data](/cells/python-net/tr/aspose.cells/range/copy_data/#aspose.cells.Range) | Bir kaynak aralığından hücre verilerini (formüller dahil) kopyalar.|
| [copy_value](/cells/python-net/tr/aspose.cells/range/copy_value/#aspose.cells.Range) | Kaynak aralığından hücre değerini kopyalar.|
| [copy_style](/cells/python-net/tr/aspose.cells/range/copy_style/#aspose.cells.Range) | Stil ayarlarını bir kaynak aralığından kopyalar.|
| [get_cell_or_null](/cells/python-net/tr/aspose.cells/range/get_cell_or_null/#int-int) | Bu aralıkta [`Cell`](/cells/python-net/tr/aspose.cells/cell) nesnesini veya null değerini alır.|
| [get_offset](/cells/python-net/tr/aspose.cells/range/get_offset/#int-int) | Uzaklığa göre [`Range`](/cells/python-net/tr/aspose.cells/range) aralığını alır.|



###  Notlar

Range sınıfı, Excel elektronik tablosunun bir bölgesini belirtir.
Bununla aralığın değerini biçimlendirebilir ve ayarlayabilirsiniz.
Ayrıca Excel aralığını da kolayca kopyalayabilirsiniz.

###  Örnek

Aşağıdaki örnek, bir aralığın nasıl oluşturulacağını ve Excel aralığının değerini nasıl ayarlayacağınızı gösterir.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
