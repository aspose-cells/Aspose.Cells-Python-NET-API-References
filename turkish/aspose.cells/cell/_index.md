---
title: Cell sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells/cell/
is_root: false
---
##  Cell sınıfı
Tek bir Çalışma Kitabı hücresini temsil eden nesneyi kapsüller.



Cell türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [worksheet](/cells/python-net/tr/aspose.cells/cell/worksheet) | Ebeveyn çalışma sayfasını alır.|
| [date_time_value](/cells/python-net/tr/aspose.cells/cell/date_time_value) | Hücrede bulunan DateTime değerini alır.|
| [row](/cells/python-net/tr/aspose.cells/cell/row) | Hücrenin satır numarasını (sıfırdan başlayarak) alır.|
| [column](/cells/python-net/tr/aspose.cells/cell/column) | Hücrenin sütun numarasını (sıfırdan başlayarak) alır.|
| [is_formula](/cells/python-net/tr/aspose.cells/cell/is_formula) | Belirtilen hücrenin formül içerip içermediğini gösterir.|
| [has_custom_function](/cells/python-net/tr/aspose.cells/cell/has_custom_function) |Bu hücrenin formülünde özel bir fonksiyon(desteklenmeyen fonksiyon) olup olmadığını kontrol eder.|
| [type](/cells/python-net/tr/aspose.cells/cell/type) | Hücre değer türünü temsil eder.|
| [name](/cells/python-net/tr/aspose.cells/cell/name) | Hücrenin adını alır.|
| [is_error_value](/cells/python-net/tr/aspose.cells/cell/is_error_value) | Bu hücrenin değerinin hatalı olup olmadığını kontrol eder.|
| [is_numeric_value](/cells/python-net/tr/aspose.cells/cell/is_numeric_value) | Bu hücrenin değerinin numeric(int, double ve datetime) olup olmadığını gösterir|
| [string_value](/cells/python-net/tr/aspose.cells/cell/string_value) | Hücrede bulunan dize değerini alır. Eğer bu hücrenin türü dize ise, dize değerinin kendisini döndürür.<br/>Diğer hücre tipleri için biçimlendirilmiş dize değeri (bu hücrenin belirtilen stiliyle biçimlendirilmiş) döndürülecektir.<br/>Biçimlendirilmiş hücre değeri, bir hücreyi metin olarak kopyaladığınızda Excel'den alabileceğiniz değerle aynıdır (örneğin<br/> (hücreyi metin düzenleyicisine kopyalama veya csv'ye aktarma).|
| [string_value_without_format](/cells/python-net/tr/aspose.cells/cell/string_value_without_format) | Hücrenin değerini herhangi bir formata tabi tutmadan string olarak alır.|
| [number_category_type](/cells/python-net/tr/aspose.cells/cell/number_category_type) | Bu hücrenin sayı biçimlendirmesinin kategori türünü temsil eder.|
| [display_string_value](/cells/python-net/tr/aspose.cells/cell/display_string_value) | Bu hücrenin biçimlendirilmiş dize değerini hücrenin görüntüleme stiline göre alır.|
| [int_value](/cells/python-net/tr/aspose.cells/cell/int_value) | Hücrede bulunan tam sayı değerini alır.|
| [double_value](/cells/python-net/tr/aspose.cells/cell/double_value) | Hücrede bulunan double değerini alır.|
| [float_value](/cells/python-net/tr/aspose.cells/cell/float_value) | Hücrede bulunan float değerini alır.|
| [bool_value](/cells/python-net/tr/aspose.cells/cell/bool_value) | Hücrede bulunan boolean değerini alır.|
| [has_custom_style](/cells/python-net/tr/aspose.cells/cell/has_custom_style) | Bu hücrenin özel stil ayarlarına sahip olup olmadığını gösterir (devralınan varsayılan ayarlardan farklı)<br/>(ilgili satırdan, sütundan veya çalışma kitabından).|
| [shared_style_index](/cells/python-net/tr/aspose.cells/cell/shared_style_index) | Stil havuzundaki hücrenin paylaşılan stil indeksini alır.|
| [formula](/cells/python-net/tr/aspose.cells/cell/formula) | [`Cell`](/cells/python-net/tr/aspose.cells/cell) formülünü alır veya ayarlar.|
| [formula_local](/cells/python-net/tr/aspose.cells/cell/formula_local) | Hücrenin yerel biçimlendirilmiş formülünü alın.|
| [r1c1_formula](/cells/python-net/tr/aspose.cells/cell/r1c1_formula) | [`Cell`](/cells/python-net/tr/aspose.cells/cell)'in R1C1 formülünü alır veya ayarlar.|
| [contains_external_link](/cells/python-net/tr/aspose.cells/cell/contains_external_link) | Bu hücrenin harici bir bağlantı içerip içermediğini belirtir.<br/> Yalnızca hücre bir formül hücresi olduğunda geçerlidir.|
| [is_array_header](/cells/python-net/tr/aspose.cells/cell/is_array_header) | Hücrenin formülünün bir dizi formülü olduğunu gösterir<br/> ve dizinin ilk hücresidir.|
| [is_dynamic_array_formula](/cells/python-net/tr/aspose.cells/cell/is_dynamic_array_formula) | Hücrenin formülünün dinamik dizi formülü (doğru) veya eski dizi formülü (yanlış) olduğunu gösterir.|
| [is_array_formula](/cells/python-net/tr/aspose.cells/cell/is_array_formula) | Hücre formülünün bir dizi formülü olup olmadığını gösterir.|
| [is_in_array](/cells/python-net/tr/aspose.cells/cell/is_in_array) | Hücre formülünün bir dizi formülü olup olmadığını gösterir.|
| [is_shared_formula](/cells/python-net/tr/aspose.cells/cell/is_shared_formula) | Hücre formülünün paylaşılan formülün parçası olup olmadığını gösterir.|
| [is_table_formula](/cells/python-net/tr/aspose.cells/cell/is_table_formula) | Bu hücrenin tablo formülünün parçası olup olmadığını gösterir.|
| [is_in_table](/cells/python-net/tr/aspose.cells/cell/is_in_table) | Bu hücrenin tablo formülünün parçası olup olmadığını gösterir.|
| [value](/cells/python-net/tr/aspose.cells/cell/value) | Bu hücrede bulunan değeri alır/ayarlar.|
| [is_style_set](/cells/python-net/tr/aspose.cells/cell/is_style_set) | Hücrenin stilinin ayarlanıp ayarlanmadığını gösterir. Eğer false döndürülürse, bu hücrenin varsayılan bir hücre biçimine sahip olduğu anlamına gelir.|
| [is_merged](/cells/python-net/tr/aspose.cells/cell/is_merged) | Bir hücrenin birleştirilmiş aralığın parçası olup olmadığını kontrol eder.|
| [comment](/cells/python-net/tr/aspose.cells/cell/comment) |Bu hücrenin yorumunu alır.|
| [html_string](/cells/python-net/tr/aspose.cells/cell/html_string) | Bu hücrede veri ve bazı formatları içeren html dizesini alır ve ayarlar.|
| [is_check_box_style](/cells/python-net/tr/aspose.cells/cell/is_check_box_style) | Bu hücrenin onay kutusu olarak ayarlanıp ayarlanmadığını belirtir.|
| [embedded_image](/cells/python-net/tr/aspose.cells/cell/embedded_image) | Hücredeki gömülü resmi alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/tr/aspose.cells/cell/put_value/#bool) | Hücreye bir Boole değeri koyar.|
| [`put_value(self, int_value)`](/cells/python-net/tr/aspose.cells/cell/put_value/#int) | Hücreye tam sayı değeri koyar.|
| [`put_value(self, double_value)`](/cells/python-net/tr/aspose.cells/cell/put_value/#float) | Hücreye çift değer koyar.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/tr/aspose.cells/cell/put_value/#str-bool-bool) | Hücreye bir değer koyar, uygunsa değer başka bir veri türüne dönüştürülür ve hücrenin sayı biçimi sıfırlanır.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/tr/aspose.cells/cell/put_value/#str-bool) | Hücreye bir dize değeri koyar ve uygunsa değeri başka bir veri türüne dönüştürür.|
| [`put_value(self, string_value)`](/cells/python-net/tr/aspose.cells/cell/put_value/#str) | Hücreye bir dize değeri koyar.|
| [`put_value(self, date_time)`](/cells/python-net/tr/aspose.cells/cell/put_value/#datetime) | Hücreye bir DateTime değeri koyar.|
| [`put_value(self, object_value)`](/cells/python-net/tr/aspose.cells/cell/put_value/#any) | Hücreye bir nesne değeri koyar.|
| [`get_display_style(self)`](/cells/python-net/tr/aspose.cells/cell/get_display_style/#) | Bu hücrenin görüntüleme stilini alır.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/tr/aspose.cells/cell/get_display_style/#bool) | Bu hücrenin görüntüleme stilini alır.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/tr/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Bu hücrenin görüntüleme stilini alır.|
| [`get_style(self)`](/cells/python-net/tr/aspose.cells/cell/get_style/#) | Hücre stilini alır.|
| [`get_style(self, check_borders)`](/cells/python-net/tr/aspose.cells/cell/get_style/#bool) | checkBorders true ise, diğer hücrelerin kenarlıklarının bu hücrenin stilini etkileyip etkilemeyeceğini kontrol edin.|
| [`set_style(self, style)`](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.style) | Hücre stilini ayarlar.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Hücreye style'ın değiştirilen özelliğini uygula.|
| [`set_style(self, style, flag)`](/cells/python-net/tr/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Bayraklara dayalı hücre stilini uygulayın.|
| [`set_formula(self, formula, value)`](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-any) | Formülü ve formülün değerini (hesaplanan sonucu) ayarlayın.|
| [`set_formula(self, formula, options)`](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Formülü ve formülün değerini (hesaplanan sonucu) ayarlayın.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-bool-bool-any) | Formülü ve formülün değerini ayarlayın.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/tr/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Formülü ve formülün değerini (hesaplanan sonucu) ayarlayın.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int) | Bir dizi formülünü (MS Excel'de CTRL+SHIFT+ENTER ile girilen eski dizi formülü) bir hücre aralığına ayarlar.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/tr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Bir dizi formülünü bir hücre aralığına ayarlar.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Bir formülü bir hücre aralığına ayarlar.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/tr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Paylaşılan formülleri bir hücre aralığına ayarlar.|
| [`get_leafs(self)`](/cells/python-net/tr/aspose.cells/cell/get_leafs/#) | Bu hücreye doğrudan referans veren ve bu hücre değiştirildiğinde güncellenmesi gereken tüm hücreleri al.|
| [`get_leafs(self, recursive)`](/cells/python-net/tr/aspose.cells/cell/get_leafs/#bool) | Bu hücre değiştirildiğinde güncellenecek tüm hücreleri al.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/tr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/tr/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.|
| [`get_characters(self)`](/cells/python-net/tr/aspose.cells/cell/get_characters/#) | Tüm Karakter nesnelerini döndürür<br/> hücre metni içindeki karakter aralığını temsil eder.|
| [`get_characters(self, flag)`](/cells/python-net/tr/aspose.cells/cell/get_characters/#bool) | Tüm Karakter nesnelerini döndürür<br/> hücre metni içindeki karakter aralığını temsil eder.|
| [`calculate(self, options)`](/cells/python-net/tr/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Hücrenin formülünü hesaplar.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/tr/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Belirli biçimlendirilmiş stratejiye göre dize değerini alır.|
| [`get_width_of_value(self)`](/cells/python-net/tr/aspose.cells/cell/get_width_of_value/#) | Değerin genişliğini piksel cinsinden alır.|
| [`get_height_of_value(self)`](/cells/python-net/tr/aspose.cells/cell/get_height_of_value/#) | Değerin yüksekliğini piksel cinsinden alır.|
| [`get_format_conditions(self)`](/cells/python-net/tr/aspose.cells/cell/get_format_conditions/#) | Bu hücreye uygulanan biçim koşullarını alır.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/cell/get_formula/#bool-bool) | Bu hücrenin formülünü alın.|
| [`get_precedents(self)`](/cells/python-net/tr/aspose.cells/cell/get_precedents/#) | Bu hücrenin formülünde görünen tüm referansları alır.|
| [`get_dependents(self, is_all)`](/cells/python-net/tr/aspose.cells/cell/get_dependents/#bool) | Formülü doğrudan bu hücreye referans veren tüm hücreleri al.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/tr/aspose.cells/cell/get_precedents_in_calculation/#) | Bu hücrenin formülü hesaplanırken kullanılan tüm emsalleri (geçerli çalışma kitabındaki hücrelere yapılan referanslar) alır.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation/#bool) | Hesaplanan sonucu bu hücreye bağlı olan tüm hücreleri alır.|
| [`get_array_range(self)`](/cells/python-net/tr/aspose.cells/cell/get_array_range/#) | Hücrenin formülü bir dizi formülü ise dizi aralığını alır.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/tr/aspose.cells/cell/remove_array_formula/#bool) | Dizi formülünü kaldır.|
| [`copy(self, cell)`](/cells/python-net/tr/aspose.cells/cell/copy/#aspose.cells.cell) | Kaynak hücreden veri kopyalar.|
| [`characters(self, start_index, length)`](/cells/python-net/tr/aspose.cells/cell/characters/#int-int) | Hücre metnindeki karakter aralığını temsil eden bir Characters nesnesi döndürür.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/tr/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Hücrenin metnini seçeneklerle değiştirin.|
| [`insert_text(self, index, text)`](/cells/python-net/tr/aspose.cells/cell/insert_text/#int-str) | Hücreye birkaç karakter ekleyin.<br/> Hücre zengin biçimlendirilmişse, bu yöntem orijinal biçimlendirmeyi koruyabilir.|
| [`is_rich_text(self)`](/cells/python-net/tr/aspose.cells/cell/is_rich_text/#) |Bu hücrenin dize değerinin zengin biçimlendirilmiş metin olup olmadığını gösterir.|
| [`set_characters(self, characters)`](/cells/python-net/tr/aspose.cells/cell/set_characters/#list) | Hücrenin zengin metin biçimini ayarlar.|
| [`get_merged_range(self)`](/cells/python-net/tr/aspose.cells/cell/get_merged_range/#) | Birleştirilmiş bir aralığı temsil eden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür.|
| [`get_html_string(self, html5)`](/cells/python-net/tr/aspose.cells/cell/get_html_string/#bool) | Bu hücrede veri ve bazı formatları içeren html dizesini alır.|
| [`to_json(self)`](/cells/python-net/tr/aspose.cells/cell/to_json/#) | [`Cell`](/cells/python-net/tr/aspose.cells/cell) yapı verisini JSON yapı verisine dönüştürün.|
| [`equals(self, cell)`](/cells/python-net/tr/aspose.cells/cell/equals/#aspose.cells.cell) | Bu nesnenin başka bir hücre nesnesiyle aynı hücreye başvurup başvurmadığını kontrol eder.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/tr/aspose.cells/cell/get_conditional_formatting_result/#) | Koşullu biçimlendirmenin sonucunu alın.|
| [`get_validation(self)`](/cells/python-net/tr/aspose.cells/cell/get_validation/#) | Bu hücreye uygulanan doğrulamayı alır.|
| [`get_validation_value(self)`](/cells/python-net/tr/aspose.cells/cell/get_validation_value/#) | Bu hücreye uygulanan doğrulama değerini alır.|
| [`get_table(self)`](/cells/python-net/tr/aspose.cells/cell/get_table/#) | Bu hücreyi içeren tabloyu alır.|
| [`get_rich_value(self)`](/cells/python-net/tr/aspose.cells/cell/get_rich_value/#) | Hücrenin zengin değerini alır.|



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
