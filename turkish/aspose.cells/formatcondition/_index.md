---
title: FormatCondition sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 720
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
| [operator](/cells/python-net/tr/aspose.cells/formatcondition/operator) | Koşullu biçim işleç türünü alır ve ayarlar.|
| [stop_if_true](/cells/python-net/tr/aspose.cells/formatcondition/stop_if_true) | Doğru, bu kural doğru olarak değerlendirildiğinde bu kurala daha düşük önceliğe sahip hiçbir kural uygulanamaz.<br/> Yalnızca Excel 2007 için geçerlidir;|
| [priority](/cells/python-net/tr/aspose.cells/formatcondition/priority) | Bu koşullu biçimlendirme kuralının önceliği. Bu değer hangisini belirlemek için kullanılır?<br/>formatı değerlendirilmeli ve işlenmelidir. Daha düşük sayısal değerler, şuna göre daha yüksek önceliğe sahiptir:<br/> '1'in en yüksek öncelik olduğu daha yüksek sayısal değerler.|
| [style](/cells/python-net/tr/aspose.cells/formatcondition/style) | Koşullu biçimlendirilmiş hücre aralıklarının stilini alır veya ayarlar.|
| [type](/cells/python-net/tr/aspose.cells/formatcondition/type) |Koşullu formatın Type olup olmadığını alır ve ayarlar.|
| [icon_set](/cells/python-net/tr/aspose.cells/formatcondition/icon_set) | Koşullu biçimlendirmenin "IconSet" örneğini alın.<br/>Varsayılan örneğin IconSetType'ı TrafficLights31'dir.<br/> Yalnızca type = IconSet için geçerlidir.|
| [data_bar](/cells/python-net/tr/aspose.cells/formatcondition/data_bar) | Koşullu biçimlendirmenin "DataBar" örneğini alın.<br/>Varsayılan örneğin rengi mavidir.<br/> Yalnızca DataBar türü için geçerlidir.|
| [color_scale](/cells/python-net/tr/aspose.cells/formatcondition/color_scale) | Koşullu biçimlendirmenin "ColorScale" örneğini alın.<br/>Varsayılan örnek "yeşil-sarı-kırmızı" 3ColorScale'dir.<br/> Yalnızca tür = ColorScale için geçerlidir.|
| [top10](/cells/python-net/tr/aspose.cells/formatcondition/top10) | Koşullu biçimlendirmenin "Top10" örneğini alın.<br/>Varsayılan örneğin kuralı,<br/>değerler ilk 10 parantez içinde yer almaktadır.<br/> Yalnızca Top10 türü için geçerlidir.|
| [above_average](/cells/python-net/tr/aspose.cells/formatcondition/above_average) | Koşullu biçimlendirmenin "AboveAverage" örneğini alın.<br/> Varsayılan örneğin kuralı, şu hücreleri vurgular:<br/>aralıktaki tüm değerler için ortalamanın üzerinde.<br/>Yalnızca = Ortalamanın Üstündeki türü için geçerlidir.|
| [text](/cells/python-net/tr/aspose.cells/formatcondition/text) | "Metin şunu içerir" koşullu biçimlendirme kuralındaki metin değeri.<br/>Yalnızca type = includeText, notContainsText, beginWith ve endWith için geçerlidir.<br/> Varsayılan değer null'dur.|
| [time_period](/cells/python-net/tr/aspose.cells/formatcondition/time_period) | "Gerçekleşen tarih..." koşullu biçimlendirme kuralındaki geçerli zaman aralığı.<br/>Yalnızca type = timePeriod için geçerlidir.<br/> Varsayılan değer TimePeriodType.Today'dır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [get_formula1](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi alır.|
| [get_formula1](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Hücrenin koşullu biçimlendirmesinin değerini veya ifadesini alır.|
| [get_formula1](/cells/python-net/tr/aspose.cells/formatcondition/get_formula1/#int-int) | Hücrenin koşullu biçimlendirme formülünü alır.|
| [get_formula2](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi alır.|
| [get_formula2](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Hücrenin koşullu biçimlendirmesinin değerini veya ifadesini alır.|
| [get_formula2](/cells/python-net/tr/aspose.cells/formatcondition/get_formula2/#int-int) | Hücrenin koşullu biçimlendirme formülünü alır.|
| [set_formulas](/cells/python-net/tr/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|
| [set_formula1](/cells/python-net/tr/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|
| [set_formula2](/cells/python-net/tr/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Bu biçim koşuluyla ilişkili değeri veya ifadeyi ayarlar.|



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
