---
title: طريقة insert_image
second_title: Aspose.Cells.GridJs for Python via .NET API المراجع
description:
type: docs
weight: 130
url: /ar/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

إدراج صورة في ورقة العمل من دفق الملف أو عنوان URL، (يجب توفير دفق الملف أو عنوان URL)
 أو
إدراج شكل، عندما يكون p.type أحد AutoShapeType


###  عائدات


سلسلة التنسيق JSON للصورة المدرجة


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| uid | str | المعرف الفريد لذاكرة التخزين المؤقت للملف|
| p | str | سلسلة التنسيق JSON للعملية التي تحدد موقع الخلية واسم ورقة العمل والصف الأيسر العلوي والعمود الأيسر العلوي للصورة، إلخ {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | دفق الملف لملف الصورة|
| image_url | str | عنوان URL لملف الصورة|



###  أنظر أيضا
* الوحدة [`aspose.cellsgridjs`](../../)
* فئة [`GridJsWorkbook`](/cells/python-net/ar/aspose.cellsgridjs/gridjsworkbook)
