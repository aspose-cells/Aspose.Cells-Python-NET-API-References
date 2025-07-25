---
title: طريقة put_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 290
url: /ar/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
وضع قيمة منطقية في الخلية.



```python

def put_value(self, bool_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
وضع قيمة عددية في الخلية.



```python

def put_value(self, int_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| int_value | int | قيمة الإدخال|


##  put_value(self, double_value) {#float}
وضع قيمة مضاعفة في الخلية.



```python

def put_value(self, double_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| double_value | float | قيمة الإدخال|


##  put_value(self, string_value) {#str}
يضع قيمة سلسلة في الخلية.



```python

def put_value(self, string_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة الإدخال|


##  put_value(self, date_time) {#DateTime}
يضع قيمة DateTime في الخلية.



```python

def put_value(self, date_time):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| date_time | DateTime | قيمة الإدخال|
###  ملاحظات

إن تعيين قيمة DateTime لخلية لا يعني أن الخلية سيتم تنسيقها كتاريخ ووقت تلقائيًا.
تم الاحتفاظ بقيمة DateTime كقيمة عددية في نموذج البيانات لكل من ms excel و Aspose.Cells.
ما إذا كانت القيمة الرقمية سيتم اعتبارها القيمة الرقمية نفسها أو التاريخ والوقت
يعتمد ذلك على تنسيق الأرقام المُطبّق على هذه الخلية. إذا لم يتم تنسيق هذه الخلية كتاريخ ووقت،
سيتم عرضه كقيمة عددية حتى لو كان ما أدخلته هو DateTime.
###  مثال

يوضح هذا المثال كيفية تعيين قيمة DateTime إلى خلية وجعلها تظهر كتاريخ ووقت.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value(self, object_value) {#any}
وضع قيمة الكائن في الخلية.



```python

def put_value(self, object_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| object_value | any | قيمة الإدخال|


##  put_value(self, string_value, is_converted) {#str-bool}
يضع قيمة سلسلة في الخلية ويحول القيمة إلى نوع بيانات آخر إذا لزم الأمر.



```python

def put_value(self, string_value, is_converted):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة الإدخال|
| is_converted | bool | صحيح: يتم تحويله إلى نوع بيانات آخر إذا كان ذلك مناسبًا.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
يضع قيمة في الخلية، وإذا كان ذلك مناسبًا، فسيتم تحويل القيمة إلى نوع بيانات آخر وسيتم إعادة تعيين تنسيق رقم الخلية.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة الإدخال|
| is_converted | bool | صحيح: يتم تحويله إلى نوع بيانات آخر إذا كان ذلك مناسبًا.|
| set_style | bool | صحيح: اضبط تنسيق الأرقام على نمط الخلية عند التحويل إلى نوع بيانات آخر|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
