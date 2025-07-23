---
title: FormatCondition sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 700
url: /tr/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition sınıfı
Koşullu biçimlendirme koşulunu temsil eder.



FormatCondition türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [formula1](/cells/python-net/tr/aspose.cells/formatcondition/formula1) | Koşullu biçimlendirmeyle ilişkili değeri veya ifadeyi alır ve ayarlar.|
| [formula2](/cells/python-net/tr/aspose.cells/formatcondition/formula2) | Koşullu biçimlendirmeyle ilişkili değeri veya ifadeyi alır ve ayarlar.|
| [operator](/cells/python-net/tr/aspose.cells/formatcondition/operator) | Koşullu biçimlendirme operatör türünü alır ve ayarlar.|
| [stop_if_true](/cells/python-net/tr/aspose.cells/formatcondition/stop_if_true) |Doğru, bu kural doğru olarak değerlendirildiğinde, bu kurala daha düşük önceliğe sahip hiçbir kural uygulanamaz.<br/> Sadece Excel 2007 için geçerlidir;|
| [priority](/cells/python-net/tr/aspose.cells/formatcondition/priority) | Bu koşullu biçimlendirme kuralının önceliği. Bu değer, hangisinin<br/>biçimi değerlendirilmeli ve oluşturulmalıdır. Daha düşük sayısal değerler, daha yüksek önceliğe sahiptir.<br/> daha yüksek sayısal değerler, burada '1' en yüksek önceliği ifade eder.|
| [style](/cells/python-net/tr/aspose.cells/formatcondition/style) | Koşullu biçimlendirilmiş hücre aralıklarının stilini alır veya ayarlar.|
| [type](/cells/python-net/tr/aspose.cells/formatcondition/type) | Koşullu biçimlendirme Türünü alır ve ayarlar.|
| [icon_set](/cells/python-net/tr/aspose.cells/formatcondition/icon_set) | Koşullu biçimlendirmenin "IconSet" örneğini alın.<br/>Varsayılan örneğin IconSetType'ı TrafficLights31'dir.<br/> Yalnızca type = IconSet için geçerlidir.|
| [data_bar](/cells/python-net/tr/aspose.cells/formatcondition/data_bar) | Koşullu biçimlendirmenin "DataBar" örneğini alın.<br/>Varsayılan örneğin rengi mavidir.<br/> Sadece DataBar türü için geçerlidir.|
| [color_scale](/cells/python-net/tr/aspose.cells/formatcondition/color_scale) | Koşullu biçimlendirmenin "ColorScale" örneğini alın.<br/>Varsayılan örnek "yeşil-sarı-kırmızı" 3ColorScale'dir.<br/> Yalnızca ColorScale türü için geçerlidir.|
| [top10](/cells/python-net/tr/aspose.cells/formatcondition/top10) | Koşullu biçimlendirmenin "Top10" örneğini alın.<br/>Varsayılan örneğin kuralı, hangi hücreleri vurguladığını belirtir.<br/>değerler ilk 10'a giriyor.<br/> Sadece Top10 türü için geçerlidir.|
| [above_average](/cells/python-net/tr/aspose.cells/formatcondition/above_average) |Koşullu biçimlendirmenin "AboveAverage" örneğini alın.<br/> Varsayılan örneğin kuralı, şu hücreleri vurgular:<br/>aralıktaki tüm değerler için ortalamanın üzerinde.<br/> Yalnızca AboveAverage türü için geçerlidir.|
| [text](/cells/python-net/tr/aspose.cells/formatcondition/text) | "Metin içerir" koşullu biçimlendirme kuralındaki metin değeri.<br/>Yalnızca type = containsText, notContainsText, beginsWith ve endsWith için geçerlidir.<br/> Varsayılan değer null'dır.|
| [time_period](/cells/python-net/tr/aspose.cells/formatcondition/time_period) | "Tarih meydana geliyor…" koşullu biçimlendirme kuralında uygulanabilir zaman aralığı.<br/>Yalnızca type = timePeriod için geçerlidir.<br/> Varsayılan değer TimePeriodType.Today'dir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi alır.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Hücrenin koşullu biçimlendirmesinin değerini veya ifadesini alır.|
| [`get_formula1(self, row, column)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#int-int) | Hücrenin koşullu biçimlendirmesinin formülünü alır.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi alır.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Hücrenin koşullu biçimlendirmesinin değerini veya ifadesini alır.|
| [`get_formula2(self, row, column)`](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#int-int) | Hücrenin koşullu biçimlendirmesinin formülünü alır.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|



###  Örnek

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
