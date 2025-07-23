---
title: trim_leading_blank_row_and_column mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 230
url: /tr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column mülk

Öndeki boş satır ve sütunların, MS Excel'in yaptığı gibi kırpılıp kırpılmayacağını belirtir.
Varsayılan değer doğrudur.

###  Notlar

Aynısı ms excel'deki kuralda da var, özel bir stile sahip bir satır/sütun boş olarak alınmayacaktır.
Hücresel veri içermese bile.
LightCells moduyla kaydederken bu seçeneğin hiçbir etkisi olmaz.
Kullanıcı, [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/tr/aspose.cells/txtsaveoptions) uygulamasıyla çıkış aralığını kontrol etmelidir
veya [`TxtSaveOptions.export_area`](/cells/python-net/tr/aspose.cells/txtsaveoptions#export_area)'i belirterek
###  Tanım:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`TxtSaveOptions`](/cells/python-net/tr/aspose.cells/txtsaveoptions)
