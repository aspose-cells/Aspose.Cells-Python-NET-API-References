---
title: Cell sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells/cell/
is_root: false
---
##  Cell sınıfı
Tek bir Çalışma Kitabı hücresini temsil eden nesneyi kapsüller.



Cell türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [worksheet](/cells/python-net/tr/aspose.cells/cell/worksheet) |Ana çalışma sayfasını alır.|
| [date_time_value](/cells/python-net/tr/aspose.cells/cell/date_time_value) | Hücrede bulunan DateTime değerini alır.|
| [row](/cells/python-net/tr/aspose.cells/cell/row) | Hücrenin satır numarasını (sıfır tabanlı) alır.|
| [column](/cells/python-net/tr/aspose.cells/cell/column) | Hücrenin sütun numarasını (sıfır tabanlı) alır.|
| [is_formula](/cells/python-net/tr/aspose.cells/cell/is_formula) | Belirtilen hücrenin formül içerip içermediğini temsil eder.|
| [type](/cells/python-net/tr/aspose.cells/cell/type) | Hücre değer türünü temsil eder.|
| [name](/cells/python-net/tr/aspose.cells/cell/name) | Hücrenin adını alır.|
| [is_error_value](/cells/python-net/tr/aspose.cells/cell/is_error_value) | Bu hücrenin değerinin bir hata olup olmadığını kontrol eder.|
| [is_numeric_value](/cells/python-net/tr/aspose.cells/cell/is_numeric_value) | Bu hücrenin değerinin sayısal olup olmadığını belirtir(int, double ve datetime)|
| [string_value](/cells/python-net/tr/aspose.cells/cell/string_value) | Hücrenin içerdiği dize değerini alır. Bu hücrenin türü string ise, string değerinin kendisini döndürün.<br/>Diğer hücre türleri için biçimlendirilmiş dize değeri (bu hücrenin belirtilen stiliyle biçimlendirilmiş) döndürülür.<br/>Biçimlendirilmiş hücre değeri, bir hücreyi metin olarak kopyalarken Excel'den alabileceğiniz değerle aynıdır (örneğin<br/> hücreyi metin düzenleyiciye kopyalamak veya csv'ye aktarmak).|
| [string_value_without_format](/cells/python-net/tr/aspose.cells/cell/string_value_without_format) | Hücrenin değerini herhangi bir format olmadan dize olarak alır.|
| [number_category_type](/cells/python-net/tr/aspose.cells/cell/number_category_type) | Bu hücrenin sayı biçimlendirmesinin kategori türünü temsil eder.|
| [display_string_value](/cells/python-net/tr/aspose.cells/cell/display_string_value) | Bu hücrenin biçimlendirilmiş dize değerini hücrenin görüntüleme stiline göre alır.|
| [int_value](/cells/python-net/tr/aspose.cells/cell/int_value) | Hücrenin içerdiği tamsayı değerini alır.|
| [double_value](/cells/python-net/tr/aspose.cells/cell/double_value) | Hücrenin içerdiği double değerini alır.|
| [float_value](/cells/python-net/tr/aspose.cells/cell/float_value) | Hücrenin içerdiği float değerini alır.|
| [bool_value](/cells/python-net/tr/aspose.cells/cell/bool_value) |Hücrenin içerdiği boole değerini alır.|
| [has_custom_style](/cells/python-net/tr/aspose.cells/cell/has_custom_style) | Bu hücrenin özel stil ayarlarına sahip olup olmadığını belirtir (devralınan varsayılandan farklı)<br/> karşılık gelen satır, sütun veya çalışma kitabından).|
| [shared_style_index](/cells/python-net/tr/aspose.cells/cell/shared_style_index) | Stil havuzunda hücrenin paylaşılan stil dizinini alır.|
| [formula](/cells/python-net/tr/aspose.cells/cell/formula) | [`Cell`](/cells/python-net/tr/aspose.cells/cell)'in formülünü alır veya ayarlar.|
| [formula_local](/cells/python-net/tr/aspose.cells/cell/formula_local) | Hücrenin yerel ayarlı formülünü alın.|
| [r1c1_formula](/cells/python-net/tr/aspose.cells/cell/r1c1_formula) | [`Cell`](/cells/python-net/tr/aspose.cells/cell)'in R1C1 formülünü alır veya ayarlar.|
| [contains_external_link](/cells/python-net/tr/aspose.cells/cell/contains_external_link) | Bu hücrenin harici bir bağlantı içerip içermediğini gösterir.<br/> Yalnızca hücre bir formül hücresi olduğunda geçerlidir.|
| [is_array_header](/cells/python-net/tr/aspose.cells/cell/is_array_header) | Hücrenin formülünün bir dizi formülü olduğunu belirtir<br/> ve dizinin ilk hücresidir.|
| [is_dynamic_array_formula](/cells/python-net/tr/aspose.cells/cell/is_dynamic_array_formula) | Hücrenin formülünün dinamik dizi formülü (doğru) veya eski dizi formülü (yanlış) olup olmadığını belirtir.|
| [is_array_formula](/cells/python-net/tr/aspose.cells/cell/is_array_formula) | Hücre formülünün bir dizi formülü olup olmadığını gösterir.|
| [is_in_array](/cells/python-net/tr/aspose.cells/cell/is_in_array) | Hücre formülünün bir dizi formülü olup olmadığını gösterir.|
| [is_shared_formula](/cells/python-net/tr/aspose.cells/cell/is_shared_formula) | Hücre formülünün paylaşılan formülün parçası olup olmadığını belirtir.|
| [is_table_formula](/cells/python-net/tr/aspose.cells/cell/is_table_formula) | Bu hücrenin tablo formülünün parçası olup olmadığını gösterir.|
| [is_in_table](/cells/python-net/tr/aspose.cells/cell/is_in_table) | Bu hücrenin tablo formülünün parçası olup olmadığını gösterir.|
| [value](/cells/python-net/tr/aspose.cells/cell/value) | Bu hücrede bulunan değeri alır/ayarlar.|
| [is_style_set](/cells/python-net/tr/aspose.cells/cell/is_style_set) |Hücrenin stilinin ayarlanıp ayarlanmadığını gösterir. Yanlış döndürürseniz, bu, bu hücrenin varsayılan hücre biçimine sahip olduğu anlamına gelir.|
| [is_merged](/cells/python-net/tr/aspose.cells/cell/is_merged) | Bir hücrenin birleştirilmiş aralığın parçası olup olmadığını kontrol eder.|
| [comment](/cells/python-net/tr/aspose.cells/cell/comment) | Bu hücrenin yorumunu alır.|
| [html_string](/cells/python-net/tr/aspose.cells/cell/html_string) | Bu hücredeki verileri ve bazı biçimleri içeren html dizesini alır ve ayarlar.|
| [embedded_image](/cells/python-net/tr/aspose.cells/cell/embedded_image) | Hücredeki gömülü görüntüyü alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#bool) | Hücreye bir boole değeri koyar.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#int) | Hücreye bir tam sayı değeri koyar.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#float) | Hücreye çift değer koyar.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#str-bool-bool) | Hücreye bir değer koyar, uygunsa değer başka bir veri tipine dönüştürülür ve hücrenin sayı formatı sıfırlanır.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#str-bool) | Hücreye bir dize değeri koyar ve uygunsa değeri diğer veri türüne dönüştürür.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#str) | Hücreye bir dize değeri koyar.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#DateTime) | Hücreye bir DateTime değeri koyar.|
| [put_value](/cells/python-net/tr/aspose.cells/cell/put_value/#any) | Hücreye bir nesne değeri koyar.|
| [get_display_style](/cells/python-net/tr/aspose.cells/cell/get_display_style/#) | Hücrenin görüntüleme stilini alır.<br/>Bu hücre koşullu biçimlendirme, liste nesneleri vb. gibi diğer ayarlardan da etkileniyorsa,<br/>bu durumda görüntüleme stili cell.GetStyle()'dan farklı olabilir.|
| [get_display_style](/cells/python-net/tr/aspose.cells/cell/get_display_style/#bool) | Hücrenin görüntüleme stilini alır.<br/> Hücre koşullu biçimlendirilmişse görüntüleme stili cell.GetStyle() ile aynı değildir.|
| [get_style](/cells/python-net/tr/aspose.cells/cell/get_style/#) | Hücre stilini alır.|
| [get_style](/cells/python-net/tr/aspose.cells/cell/get_style/#bool) | checkBorders doğruysa, diğer hücrelerin sınırlarının bu hücrenin stilini etkileyip etkilemeyeceğini kontrol edin.|
| [set_style](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.Style) | Hücre stilini ayarlar.|
| [set_style](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | Değiştirilen stil özelliğini hücreye uygulayın.|
| [set_style](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Bayraklara göre hücre stilini uygulayın.|
| [set_formula](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-any) | Formülü ve formülün değerini (hesaplanan sonuç) ayarlayın.|
| [set_formula](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-bool-bool-any) | Formülü ve formülün değerini ayarlayın.|
| [set_formula](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | Formülü ve formülün değerini (hesaplanan sonuç) ayarlayın.|
| [set_array_formula](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [set_array_formula](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int) | Bir dizi formülünü (ms excel'de CTRL+SHIFT+ENTER yoluyla girilen eski dizi formülü) bir hücre aralığına ayarlar.|
| [set_array_formula](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [set_array_formula](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [set_shared_formula](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Bir formül hücre aralığına ayarlar.|
| [set_shared_formula](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [set_shared_formula](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [set_shared_formula](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [get_leafs](/cells/python-net/tr/aspose.cells/cell/get_leafs/#) | Bu hücreye doğrudan başvuran ve bu hücre değiştirildiğinde güncellenmesi gereken tüm hücreleri alın.|
| [get_leafs](/cells/python-net/tr/aspose.cells/cell/get_leafs/#bool) | Bu hücre değiştirildiğinde güncellenecek tüm hücreleri alın.|
| [set_dynamic_array_formula](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [set_dynamic_array_formula](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [set_dynamic_array_formula](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [set_table_formula](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.|
| [set_table_formula](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.|
| [set_table_formula](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.|
| [set_table_formula](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.|
| [get_characters](/cells/python-net/tr/aspose.cells/cell/get_characters/#) | Tüm Karakter nesnelerini döndürür<br/> bu, hücre metni içindeki bir dizi karakteri temsil eder.|
| [get_characters](/cells/python-net/tr/aspose.cells/cell/get_characters/#bool) | Tüm Karakter nesnelerini döndürür<br/> bu, hücre metni içindeki bir dizi karakteri temsil eder.|
| [calculate](/cells/python-net/tr/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | Hücrenin formülünü hesaplar.|
| [get_string_value](/cells/python-net/tr/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | Dize değerini belirli biçimlendirilmiş stratejiye göre alır.|
| [get_width_of_value](/cells/python-net/tr/aspose.cells/cell/get_width_of_value/#) | Değerin genişliğini piksel birimi cinsinden alır.|
| [get_height_of_value](/cells/python-net/tr/aspose.cells/cell/get_height_of_value/#) | Değerin yüksekliğini piksel birimi cinsinden alır.|
| [get_format_conditions](/cells/python-net/tr/aspose.cells/cell/get_format_conditions/#) | Bu hücreye uygulanan biçim koşullarını alır.|
| [get_formula](/cells/python-net/tr/aspose.cells/cell/get_formula/#bool-bool) | Bu hücrenin formülünü bulun.|
| [get_precedents](/cells/python-net/tr/aspose.cells/cell/get_precedents/#) | Bu hücrenin formülünde görünen tüm referansları alır.|
| [get_dependents](/cells/python-net/tr/aspose.cells/cell/get_dependents/#bool) | Formülü doğrudan bu hücreye referans veren tüm hücreleri alın.|
| [get_precedents_in_calculation](/cells/python-net/tr/aspose.cells/cell/get_precedents_in_calculation/#) | Hesaplarken bu hücrenin formülü tarafından kullanılan tüm örnekleri (geçerli çalışma kitabındaki hücrelere referans) alır.|
| [get_dependents_in_calculation](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation/#bool) | Hesaplanan sonucu bu hücreye bağlı olan tüm hücreleri alır.|
| [get_array_range](/cells/python-net/tr/aspose.cells/cell/get_array_range/#) |Hücrenin formülü bir dizi formülü ise dizi aralığını alır.|
| [remove_array_formula](/cells/python-net/tr/aspose.cells/cell/remove_array_formula/#bool) | Dizi formülünü kaldırın.|
| [copy](/cells/python-net/tr/aspose.cells/cell/copy/#aspose.cells.Cell) | Verileri kaynak hücreden kopyalar.|
| [characters](/cells/python-net/tr/aspose.cells/cell/characters/#int-int) | Hücre metni içindeki bir karakter aralığını temsil eden bir Characters nesnesini döndürür.|
| [replace](/cells/python-net/tr/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | Hücrenin metnini seçeneklerle değiştirin.|
| [insert_text](/cells/python-net/tr/aspose.cells/cell/insert_text/#int-str) | Hücreye bazı karakterler ekleyin.<br/> Hücre zengin biçimlendirilmişse bu yöntem orijinal biçimlendirmeyi koruyabilir.|
| [is_rich_text](/cells/python-net/tr/aspose.cells/cell/is_rich_text/#) | Bu hücrenin dize değerinin zengin biçimlendirilmiş bir metin olup olmadığını belirtir.|
| [set_characters](/cells/python-net/tr/aspose.cells/cell/set_characters/#list) | Hücrenin zengin metin biçimini ayarlar.|
| [get_merged_range](/cells/python-net/tr/aspose.cells/cell/get_merged_range/#) | Birleştirilmiş bir aralığı temsil eden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür.|
| [get_html_string](/cells/python-net/tr/aspose.cells/cell/get_html_string/#bool) | Bu hücredeki verileri ve bazı biçimleri içeren html dizesini alır.|
| [to_json](/cells/python-net/tr/aspose.cells/cell/to_json/#) | [`Cell`](/cells/python-net/tr/aspose.cells/cell)'i JSON yapı verilerine dönüştürün.|
| [equals](/cells/python-net/tr/aspose.cells/cell/equals/#aspose.cells.Cell) | Bu nesnenin başka bir hücre nesnesiyle aynı hücreye başvurup başvurmadığını kontrol eder.|
| [get_conditional_formatting_result](/cells/python-net/tr/aspose.cells/cell/get_conditional_formatting_result/#) | Koşullu biçimlendirmenin sonucunu alın.|
| [get_validation](/cells/python-net/tr/aspose.cells/cell/get_validation/#) | Bu hücreye uygulanan doğrulamayı alır.|
| [get_validation_value](/cells/python-net/tr/aspose.cells/cell/get_validation_value/#) | Bu hücreye uygulanan doğrulama değerini alır.|
| [get_table](/cells/python-net/tr/aspose.cells/cell/get_table/#) |Bu hücreyi içeren tabloyu alır.|



###  Örnek

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
