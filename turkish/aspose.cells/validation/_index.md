---
title: Validation sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1520
url: /tr/aspose.cells/validation/
is_root: false
---
##  Validation sınıfı
Veri doğrulama ayarlarını temsil eder.



Validation türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [operator](/cells/python-net/tr/aspose.cells/validation/operator) | Veri doğrulama operatörünü temsil eder.|
| [alert_style](/cells/python-net/tr/aspose.cells/validation/alert_style) | Doğrulama uyarı stilini temsil eder.|
| [type](/cells/python-net/tr/aspose.cells/validation/type) | Veri doğrulama türünü temsil eder.|
| [input_message](/cells/python-net/tr/aspose.cells/validation/input_message) | Veri doğrulama giriş mesajını temsil eder.|
| [input_title](/cells/python-net/tr/aspose.cells/validation/input_title) | Veri doğrulama giriş iletişim kutusunun başlığını temsil eder.|
| [error_message](/cells/python-net/tr/aspose.cells/validation/error_message) | Veri doğrulama hata mesajını temsil eder.|
| [error_title](/cells/python-net/tr/aspose.cells/validation/error_title) | Veri doğrulama hatası iletişim kutusunun başlığını temsil eder.|
| [show_input](/cells/python-net/tr/aspose.cells/validation/show_input) | Kullanıcının veri doğrulama aralığındaki bir hücreyi seçtiğinde veri doğrulama giriş mesajının görüntülenip görüntülenmeyeceğini belirtir.|
| [show_error](/cells/python-net/tr/aspose.cells/validation/show_error) | Kullanıcı geçersiz veri girdiğinde veri doğrulama hatası mesajının görüntülenip görüntülenmeyeceğini belirtir.|
| [ignore_blank](/cells/python-net/tr/aspose.cells/validation/ignore_blank) |Aralık veri doğrulamasının boş değerlere izin verip vermediğini belirtir.|
| [formula1](/cells/python-net/tr/aspose.cells/validation/formula1) | Veri doğrulamasıyla ilişkili değeri veya ifadeyi temsil eder.|
| [formula2](/cells/python-net/tr/aspose.cells/validation/formula2) | Veri doğrulamasıyla ilişkili değeri veya ifadeyi temsil eder.|
| [value1](/cells/python-net/tr/aspose.cells/validation/value1) | Veri doğrulamasıyla ilişkili ilk değeri temsil eder.|
| [value2](/cells/python-net/tr/aspose.cells/validation/value2) | Veri doğrulamasıyla ilişkili ikinci değeri temsil eder.|
| [in_cell_drop_down](/cells/python-net/tr/aspose.cells/validation/in_cell_drop_down) | Veri doğrulamasının kabul edilebilir değerleri içeren bir açılır liste görüntüleyip görüntülemediğini belirtir.|
| [areas](/cells/python-net/tr/aspose.cells/validation/areas) | Veri doğrulama ayarlarını içeren tüm [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)'leri alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/validation/get_formula1/#bool-bool) | Bu doğrulamayla ilişkili değeri veya ifadeyi alır.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/tr/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Belirli bir hücre için bu doğrulamayla ilişkili değeri veya ifadeyi alır.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/validation/get_formula2/#bool-bool) | Bu doğrulamayla ilişkili değeri veya ifadeyi alır.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/tr/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Belirli bir hücre için bu doğrulamayla ilişkili değeri veya ifadeyi alır.|
| [`add_area(self, cell_area)`](/cells/python-net/tr/aspose.cells/validation/add_area/#aspose.cells.cellarea) | Doğrulamayı alana uygular.|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/tr/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) | Doğrulamayı alana uygular.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/validation/set_formula1/#str-bool-bool) | Bu doğrulamayla ilişkili değeri veya ifadeyi ayarlar.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/validation/set_formula2/#str-bool-bool) | Bu doğrulamayla ilişkili değeri veya ifadeyi ayarlar.|
| [`get_list_value(self, row, column)`](/cells/python-net/tr/aspose.cells/validation/get_list_value/#int-int) | Belirtilen hücre için doğrulama listesinin değerini al.|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/tr/aspose.cells/validation/get_value/#int-int-bool) | Belirli hücredeki doğrulama değerini al.|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/tr/aspose.cells/validation/add_areas/#list-bool-bool) | Doğrulamayı verilen alanlara uygular.|
| [`remove_area(self, cell_area)`](/cells/python-net/tr/aspose.cells/validation/remove_area/#aspose.cells.cellarea) | Aralıktaki doğrulama ayarlarını kaldırın.|
| [`remove_areas(self, areas)`](/cells/python-net/tr/aspose.cells/validation/remove_areas/#list) |Bu doğrulamayı belirtilen alanlardan kaldırır.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/tr/aspose.cells/validation/remove_a_cell/#int-int) | Hücredeki doğrulama ayarlarını kaldırın.|
| [`copy(self, source, copy_option)`](/cells/python-net/tr/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) | Kopya doğrulaması.|



###  Örnek

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)
