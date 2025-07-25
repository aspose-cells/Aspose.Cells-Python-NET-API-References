---
title: Range sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1180
url: /tr/aspose.cells/range/
is_root: false
---
##  Range sınıfı
Bir elektronik tabloda hücre aralığını temsil eden nesneyi kapsüller.



Range türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [current_region](/cells/python-net/tr/aspose.cells/range/current_region) | Geçerli bölgeyi temsil eden bir Range nesnesi döndürür.<br/> Geçerli bölge, boş satırlar ve boş sütunların herhangi bir kombinasyonuyla sınırlanan bir aralıktır.|
| [hyperlinks](/cells/python-net/tr/aspose.cells/range/hyperlinks) | Aralıktaki tüm hiper bağlantıları alır.|
| [row_count](/cells/python-net/tr/aspose.cells/range/row_count) | Aralıktaki satır sayısını alır.|
| [column_count](/cells/python-net/tr/aspose.cells/range/column_count) | Aralıktaki sütun sayısını alır.|
| [name](/cells/python-net/tr/aspose.cells/range/name) | Aralığın adını alır veya ayarlar.|
| [refers_to](/cells/python-net/tr/aspose.cells/range/refers_to) | Aralığın referansını alır.|
| [address](/cells/python-net/tr/aspose.cells/range/address) | Aralığın adresini alır.|
| [left](/cells/python-net/tr/aspose.cells/range/left) | Sütun A'nın sol kenarından aralığın sol kenarına kadar olan mesafeyi puan cinsinden alır.|
| [top](/cells/python-net/tr/aspose.cells/range/top) | 1. satırın üst kenarından aralığın üst kenarına kadar olan mesafeyi puan olarak alır.|
| [width](/cells/python-net/tr/aspose.cells/range/width) | Bir aralığın genişliğini puan cinsinden alır.|
| [height](/cells/python-net/tr/aspose.cells/range/height) | Bir aralığın genişliğini puan cinsinden alır.|
| [first_row](/cells/python-net/tr/aspose.cells/range/first_row) | Aralığın ilk satırının indeksini alır.|
| [first_column](/cells/python-net/tr/aspose.cells/range/first_column) | Aralığın ilk sütununun indeksini alır.|
| [value](/cells/python-net/tr/aspose.cells/range/value) | Aralığın değerini alır ve ayarlar.|
| [column_width](/cells/python-net/tr/aspose.cells/range/column_width) | Bu aralığın sütun genişliğini ayarlar veya alır|
| [row_height](/cells/python-net/tr/aspose.cells/range/row_height) | Bu aralıktaki satırların yüksekliğini ayarlar veya alır|
| [entire_column](/cells/python-net/tr/aspose.cells/range/entire_column) |Belirtilen aralığı içeren tüm sütunu (veya sütunları) temsil eden bir Aralık nesnesi alır.|
| [entire_row](/cells/python-net/tr/aspose.cells/range/entire_row) | Belirtilen aralığı içeren tüm satırı (veya satırları) temsil eden bir Aralık nesnesi alır.|
| [worksheet](/cells/python-net/tr/aspose.cells/range/worksheet) | Bu aralığı içeren [`Range.worksheet`](/cells/python-net/tr/aspose.cells/range#worksheet) nesnesini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/tr/aspose.cells/range/auto_fill/#aspose.cells.range) | Hedef aralığını otomatik olarak doldur.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/tr/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Hedef aralığını otomatik olarak doldur.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/tr/aspose.cells/range/set_style/#aspose.cells.style-bool) | Hücre stilini uygula.|
| [`set_style(self, style)`](/cells/python-net/tr/aspose.cells/range/set_style/#aspose.cells.style) | Aralığın stilini ayarlar.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Aynı kenarlık stili ve rengine sahip bir dizi hücrenin etrafına dış hat kenarlıkları ayarlar.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Aynı kenarlık stili ve rengine sahip bir dizi hücrenin etrafına dış hat kenarlıkları ayarlar.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/tr/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Bir dizi hücrenin etrafına çizgi kenarlıkları koyar.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/tr/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Bir dizi hücrenin etrafına dış kenarlık belirler.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/tr/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Bir dizi hücrenin etrafına dış kenarlık belirler.|
| [`copy(self, range, options)`](/cells/python-net/tr/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Aralığı yapıştırma özel seçenekleriyle kopyalama.|
| [`copy(self, range)`](/cells/python-net/tr/aspose.cells/range/copy/#aspose.cells.range) | Bir kaynak aralığından verileri (formüller dahil), biçimlendirmeyi, çizim nesnelerini vb. kopyalar.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/tr/aspose.cells/range/add_hyperlink/#str-str-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [`is_intersect(self, range)`](/cells/python-net/tr/aspose.cells/range/is_intersect/#aspose.cells.range) | Aralığın kesişip kesişmediğini gösterir.|
| [`intersect(self, range)`](/cells/python-net/tr/aspose.cells/range/intersect/#aspose.cells.range) | İki aralığın dikdörtgen kesişimini temsil eden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür.|
| [`union_rang(self, range)`](/cells/python-net/tr/aspose.cells/range/union_rang/#aspose.cells.range) | İki aralığın birleşim sonucunu döndürür.|
| [`union_ranges(self, ranges)`](/cells/python-net/tr/aspose.cells/range/union_ranges/#list) | İki aralığın birleşim sonucunu döndürür.|
| [`union(self, range)`](/cells/python-net/tr/aspose.cells/range/union/#aspose.cells.range) | İki aralığın birleşimini döndürür.|
| [`is_blank(self)`](/cells/python-net/tr/aspose.cells/range/is_blank/#) | Aralığın değer içerip içermediğini belirtir.|
| [`merge(self)`](/cells/python-net/tr/aspose.cells/range/merge/#) |Bir dizi hücreyi tek bir hücrede birleştirir.|
| [`un_merge(self)`](/cells/python-net/tr/aspose.cells/range/un_merge/#) | Bu aralıktaki birleştirilmiş hücreleri ayırır.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/tr/aspose.cells/range/put_value/#str-bool-bool) | Aralığa bir değer koyar, uygunsa değer başka bir veri türüne dönüştürülür ve hücrenin sayı biçimi sıfırlanır.|
| [`apply_style(self, style, flag)`](/cells/python-net/tr/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tüm aralık için biçimleri uygular.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/tr/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Aralığın sınırları içerisine ayarlayın.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/tr/aspose.cells/range/move_to/#int-int) | Mevcut aralığı hedef aralığa taşı.|
| [`copy_data(self, range)`](/cells/python-net/tr/aspose.cells/range/copy_data/#aspose.cells.range) | Kaynak aralığından hücre verilerini (formüller dahil) kopyalar.|
| [`copy_value(self, range)`](/cells/python-net/tr/aspose.cells/range/copy_value/#aspose.cells.range) | Kaynak aralıktan hücre değerini kopyalar.|
| [`copy_style(self, range)`](/cells/python-net/tr/aspose.cells/range/copy_style/#aspose.cells.range) | Kaynak aralığından stil ayarlarını kopyalar.|
| [`transpose(self)`](/cells/python-net/tr/aspose.cells/range/transpose/#) | Verileri satırlardan sütunlara veya tam tersine aktarın (döndürün).|
| [`get(self, row_offset, column_offset)`](/cells/python-net/tr/aspose.cells/range/get/#int-int) | API for Python'i .Net.since aracılığıyla ekleyin, bu[int, int] desteklenmiyor|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/tr/aspose.cells/range/get_cell_or_null/#int-int) | Bu aralıkta [`Cell`](/cells/python-net/tr/aspose.cells/cell) nesnesini veya null değerini alır.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/tr/aspose.cells/range/get_offset/#int-int) | Ofset ile [`Range`](/cells/python-net/tr/aspose.cells/range) aralığını alır.|
| [`to_image(self, options)`](/cells/python-net/tr/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Aralığı görüntüye dönüştürür.|
| [`to_json(self, options)`](/cells/python-net/tr/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Aralığı JSON değerine dönüştürün.|
| [`to_html(self, save_options)`](/cells/python-net/tr/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Aralığı html'e dönüştürün.|
| [`clear(self)`](/cells/python-net/tr/aspose.cells/range/clear/#) | Bu aralığı temizler.|
| [`clear_contents(self)`](/cells/python-net/tr/aspose.cells/range/clear_contents/#) | Bu aralığın içeriğini temizler.|
| [`clear_formats(self)`](/cells/python-net/tr/aspose.cells/range/clear_formats/#) | Bu aralığın formatlarını temizler.|
| [`clear_comments(self)`](/cells/python-net/tr/aspose.cells/range/clear_comments/#) | Bu aralığın yorumlarını temizler.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/tr/aspose.cells/range/clear_hyperlinks/#bool) | Sadece hiperlinkleri kaldırır.|



###  Notlar

Range sınıfı Excel elektronik tablosunun bir bölgesini belirtir.
Bununla aralığın değerini biçimlendirebilir ve ayarlayabilirsiniz.
Ve Excel aralığını da kolayca kopyalayabilirsiniz.

###  Örnek

Aşağıdaki örnekte Excel'de bir aralık oluşturma ve aralığa değer atama işlemi gösterilmektedir.

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
