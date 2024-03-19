---
title: preprocess_exported_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
Dışa aktarılacak mevcut hücrenin değerini önceden işleyin.


###  İadeler

Geçerli hücrenin farklı tür ve/veya değerle değiştirilip değiştirilmediği.


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

Satır ve sütun dizini, dışa aktarılan tablodaki dizin değil, çalışma sayfasındaki hücrenin mutlak dizinidir.
Kullanıcı bu yöntemin geçersiz kılma uygulamasında mevcut hücrenin değerini kontrol edebilir,
mevcut hücrenin başka tür ve değerle değiştirilmesi gerekiyorsa,
burada uygulama beklenen türü ve değeri CellValue nesnesine ayarlamalı ve true değerini döndürmelidir.
Varsayılan olarak bu yöntem hiçbir şey yapmaz ve false değerini döndürür.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ExportTableOptions`](/cells/python-net/tr/aspose.cells/exporttableoptions)
