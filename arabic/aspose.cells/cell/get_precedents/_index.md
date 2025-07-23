---
title: طريقة get_precedents
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 180
url: /ar/aspose.cells/cell/get_precedents/
is_root: false
---
##  get_precedents(self) {#}
يحصل على جميع المراجع التي تظهر في صيغة هذه الخلية.


###  عائدات

مجموعة من كل المراجع التي تظهر في صيغة هذه الخلية.


```python

def get_precedents(self):
    ...
```


###  ملاحظات

* يتم إرجاع قيمة null إذا لم تكن هذه خلية صيغة. سيتم إرجاع جميع المراجع التي تظهر في صيغة هذه الخلية بغض النظر عن الإشارة إليها أم لا أثناء الحساب.

على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا يزال يتم اعتباره بمثابة سوابق للصيغة. للحصول على تلك المراجع التي تؤثر على الحساب فقط، يرجى استخدام [`Cell.get_precedents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_precedents_in_calculation).

* يتم إرجاع قيمة null إذا لم تكن هذه خلية صيغة. سيتم إرجاع جميع المراجع التي تظهر في صيغة هذه الخلية بغض النظر عن الإشارة إليها أم لا أثناء الحساب.
على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا يزال يتم اعتباره بمثابة سوابق للصيغة. للحصول على تلك المراجع التي تؤثر على الحساب فقط، يرجى استخدام [`Cell.get_precedents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_precedents_in_calculation).

* يتم إرجاع قيمة null إذا لم تكن هذه خلية صيغة. سيتم إرجاع جميع المراجع التي تظهر في صيغة هذه الخلية بغض النظر عن الإشارة إليها أم لا أثناء الحساب.
على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا يزال يتم اعتباره بمثابة سوابق للصيغة. للحصول على تلك المراجع التي تؤثر على الحساب فقط، يرجى استخدام [`Cell.get_precedents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_precedents_in_calculation).
###  مثال

```python
from aspose.cells import CellsHelper, Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!A1"
areas = cells.get("A1").get_precedents()
for i in range(len(areas)):
    area = areas[i]
    stringBuilder = []
    if area.is_external_link:
        stringBuilder.append("[")
        stringBuilder.append(area.external_file_name)
        stringBuilder.append("]")
    stringBuilder.append(area.sheet_name)
    stringBuilder.append("!")
    stringBuilder.append(CellsHelper.cell_index_to_name(area.start_row, area.start_column))
    if area.is_area:
        stringBuilder.append(":")
        stringBuilder.append(CellsHelper.cell_index_to_name(area.end_row, area.end_column))
    print("".join(stringBuilder))

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
