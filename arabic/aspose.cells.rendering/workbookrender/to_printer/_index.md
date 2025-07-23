---
title: طريقة to_printer
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells.rendering/workbookrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
عرض المصنف على الطابعة



```python

def to_printer(self, printer_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
عرض المصنف على الطابعة



```python

def to_printer(self, printer_settings):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | إعدادات الطابعة، على سبيل المثال PrinterName وDuplex|


##  to_printer(self, printer_name, job_name) {#str-str}
عرض المصنف على الطابعة



```python

def to_printer(self, printer_name, job_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|
| job_name | str | تعيين اسم مهمة الطباعة|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
عرض المصنف على الطابعة



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | إعدادات الطابعة، على سبيل المثال PrinterName وDuplex|
| job_name | str | تعيين اسم مهمة الطباعة|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
عرض المصنف على الطابعة



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| printer_name | str | اسم الطابعة، على سبيل المثال: "Microsoft Office Document Image Writer"|
| print_page_index | int | الفهرس المستند إلى 0 للصفحة الأولى المراد طباعتها، يجب أن يكون في النطاق [0، WorkbookRender.PageCount-1]|
| print_page_count | int | عدد الصفحات المراد طباعتها يجب أن يكون أكبر من الصفر|
###  ملاحظات

ملحوظة: هذه الطريقة أصبحت قديمة الآن.
بدلاً من ذلك، يرجى استخدام ToPrinter(string PrinterName) وImageOrPrintOptions.PageIndex، PageCount لتعيين الصفحة الأولى وعدد الصفحات التي سيتم طباعتها.
 سيتم إزالة هذه الخاصية بعد مرور 12 شهرًا منذ ديسمبر 2021.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.


###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`WorkbookRender`](/cells/python-net/ar/aspose.cells.rendering/workbookrender)
