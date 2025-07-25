---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/xmlmapcollection/add/
is_root: false
---
##  add(self, url) {#str}
أضف [`XmlMap`](/cells/python-net/ar/aspose.cells/xmlmap) بواسطة عنوان URL/المسار لملف xml/xsd.


###  عائدات

[`XmlMap`](/cells/python-net/ar/aspose.cells/xmlmap) فهرس الكائن.


```python

def add(self, url):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| url | str | عنوان URL/مسار ملف xml/xsd.|

###  مثال

يقوم الكود التالي بإضافة اثنين من XmlMaps بواسطة ملف xsd وملف xml.

```python
from aspose.cells import Workbook

wb = Workbook()
xmlMapCollection = wb.worksheets.xml_maps
# Add a XmlMap by a xsd file.
xmlMapCollection.add("schema.xsd")
# Add a XmlMap by a xml file.
xmlMapCollection.add("xml.xml")
wb.save("twoXmlMaps.xlsx")

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`XmlMap`](/cells/python-net/ar/aspose.cells/xmlmap)
* فئة [`XmlMapCollection`](/cells/python-net/ar/aspose.cells/xmlmapcollection)
