---
title: طريقة to_printer
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer {#str}
تقديم ورقة العمل إلى الطابعة



```python
def to_printer(self, printer_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
تقديم ورقة العمل إلى الطابعة



```python
def to_printer(self, printer_settings):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | إعدادات الطابعة، على سبيل المثال اسم الطابعة، والطباعة على الوجهين|


##  to_printer {#str-str}
تقديم ورقة العمل إلى الطابعة



```python
def to_printer(self, printer_name, job_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|
| job_name | str | قم بتعيين اسم مهمة الطباعة|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
تقديم ورقة العمل إلى الطابعة



```python
def to_printer(self, printer_settings, job_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | إعدادات الطابعة، على سبيل المثال اسم الطابعة، والطباعة على الوجهين|
| job_name | str | قم بتعيين اسم مهمة الطباعة|


##  to_printer {#str-int-int}
تقديم ورقة العمل إلى الطابعة



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|
| print_page_index | int | الفهرس المستند إلى 0 للصفحة الأولى المراد طباعتها، يجب أن يكون في النطاق [0، SheetRender.PageCount-1]|
| print_page_count | int | عدد الصفحات المراد طباعتها، يجب أن يكون أكبر من الصفر|
###  ملاحظات

ملاحظة: هذه الطريقة أصبحت الآن قديمة.
بدلاً من ذلك، الرجاء استخدام ToPrinter(string PrinterName) وImageOrPrintOptions.PageIndex وPageCount لتعيين الصفحة الأولى وعدد الصفحات المراد طباعتها.
 ستتم إزالة هذه الخاصية بعد 12 شهرًا منذ ديسمبر 2021.
Aspose نعتذر عن أي إزعاج قد تعرضت له.


###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`SheetRender`](/cells/python-net/ar/aspose.cells.rendering/sheetrender)
