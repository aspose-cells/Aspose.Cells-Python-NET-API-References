---
title: preprocess_exported_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
Dışa aktarılacak geçerli hücrenin değerini önceden işleyin.


###  İadeler

Mevcut hücrenin farklı bir tür ve/veya değerle değiştirilip değiştirilmediği.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_row | int | geçerli hücrenin satır dizini|
| cell_column | int | hücrenin sütun dizini|
| value | [`CellValue`](/cells/python-net/tr/aspose.cells/cellvalue) | geçerli hücrenin değeri ve türü|
###  Notlar

Satır ve sütun dizini, çalışma sayfasındaki hücrenin mutlak dizinidir, dışa aktarılan tablodaki dizin değildir.
Kullanıcı bu yöntemin geçersiz kılma uygulamasında geçerli hücrenin değerini kontrol edebilir,
mevcut hücrenin başka tür ve değerle değiştirilmesi gerekiyorsa,
Burada uygulama, CellValue nesnesine beklenen türü ve değeri ayarlamalı ve true döndürmelidir.
Varsayılan olarak bu yöntem hiçbir şey yapmaz ve false döndürür.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ExportTableOptions`](/cells/python-net/tr/aspose.cells/exporttableoptions)
