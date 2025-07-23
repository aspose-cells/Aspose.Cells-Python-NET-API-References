---
title: CalculationData sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData sınıfı
Bir işlevi hesaplarken, işlev adı, parametreler vb. gibi gerekli verileri temsil eder.



CalculationData türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [calculated_value](/cells/python-net/tr/aspose.cells/calculationdata/calculated_value) | Bu fonksiyon için hesaplanan değeri alır veya ayarlar.|
| [workbook](/cells/python-net/tr/aspose.cells/calculationdata/workbook) | Fonksiyonun bulunduğu Çalışma Kitabı nesnesini alır.|
| [worksheet](/cells/python-net/tr/aspose.cells/calculationdata/worksheet) | Fonksiyonun bulunduğu Worksheet nesnesini alır.|
| [cell_row](/cells/python-net/tr/aspose.cells/calculationdata/cell_row) | Fonksiyonun bulunduğu hücrenin satır dizinini alır.|
| [cell_column](/cells/python-net/tr/aspose.cells/calculationdata/cell_column) | Fonksiyonun bulunduğu hücrenin sütun indeksini alır.|
| [cell](/cells/python-net/tr/aspose.cells/calculationdata/cell) |Fonksiyonun bulunduğu Cell nesnesini alır.|
| [function_name](/cells/python-net/tr/aspose.cells/calculationdata/function_name) | Hesaplanacak fonksiyon adını alır.|
| [param_count](/cells/python-net/tr/aspose.cells/calculationdata/param_count) | Parametrelerin sayısını alır|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_param_value(self, index)`](/cells/python-net/tr/aspose.cells/calculationdata/get_param_value/#int) |Verilen dizindeki parametrenin temsil edilen değer nesnesini alır.|
| [`get_param_value_in_array_mode(self, index, max_row_count, max_column_count)`](/cells/python-net/tr/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Verilen indeksteki parametrenin değerini alır.<br/>Parametre hesaplanması gereken bir tür ifade ise,<br/> daha sonra dizi modunda hesaplanacaktır.|
| [`get_param_text(self, index)`](/cells/python-net/tr/aspose.cells/calculationdata/get_param_text/#int) | Verilen dizindeki parametrenin gerçek metnini alır.|



###  Notlar

Bu sınıf tarafından sağlanan tüm nesneler yalnızca "okuma" amaçlıdır.
Kullanıcı, formül hesaplama işlemi sırasında Çalışma Kitabındaki herhangi bir veriyi değiştirmemelidir,
Aksi takdirde beklenmeyen bir sonuç veya İstisna meydana gelebilir.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
