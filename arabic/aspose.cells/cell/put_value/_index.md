---
title: طريقة put_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells/cell/put_value/
is_root: false
---
##  put_value {#bool}
يضع قيمة منطقية في الخلية.



```python
def put_value(self, bool_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value {#int}
يضع قيمة عددية في الخلية.



```python
def put_value(self, int_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| int_value | int | قيمة المدخلات|


##  put_value {#float}
يضع قيمة مزدوجة في الخلية.



```python
def put_value(self, double_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| double_value | float | قيمة المدخلات|


##  put_value {#str}
يضع قيمة سلسلة في الخلية.



```python
def put_value(self, string_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة المدخلات|


##  put_value {#DateTime}
يضع قيمة DateTime في الخلية.



```python
def put_value(self, date_time):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| date_time | DateTime | قيمة المدخلات|
###  ملاحظات

لا يعني تعيين قيمة DateTime لجرعة الخلية أنه سيتم تنسيق الخلية كتاريخ ووقت تلقائيًا.
تم الحفاظ على قيمة DateTime كقيمة رقمية في نموذج البيانات لكل من MS Excel وAspose.Cells.
ما إذا كان سيتم اعتبار القيمة الرقمية كقيمة رقمية نفسها أو كتاريخ ووقت
يعتمد على تنسيق الأرقام المطبق على هذه الخلية. إذا لم يتم تنسيق هذه الخلية كتاريخ ووقت،
سيتم عرضه كقيمة رقمية على الرغم من أن ما تقوم بإدخاله هو DateTime.
###  مثال

يوضح هذا المثال كيفية تعيين قيمة DateTime لخلية وجعلها معروضة كتاريخ ووقت.

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


##  put_value {#any}
يضع قيمة كائن في الخلية.



```python
def put_value(self, object_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| object_value | any | قيمة المدخلات|


##  put_value {#str-bool}
يضع قيمة سلسلة في الخلية ويحول القيمة إلى نوع بيانات آخر إذا كان ذلك مناسبًا.



```python
def put_value(self, string_value, is_converted):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة المدخلات|
| is_converted | bool | صحيح: تم تحويله إلى نوع بيانات آخر إذا كان ذلك مناسبًا.|


##  put_value {#str-bool-bool}
يضع قيمة في الخلية، وإذا كان ذلك مناسبًا، فسيتم تحويل القيمة إلى نوع بيانات آخر وسيتم إعادة تعيين تنسيق أرقام الخلية.



```python
def put_value(self, string_value, is_converted, set_style):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| string_value | str | قيمة المدخلات|
| is_converted | bool | صحيح: تم تحويله إلى نوع بيانات آخر إذا كان ذلك مناسبًا.|
| set_style | bool | صحيح: قم بتعيين تنسيق الأرقام على نمط الخلية عند التحويل إلى نوع بيانات آخر|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
