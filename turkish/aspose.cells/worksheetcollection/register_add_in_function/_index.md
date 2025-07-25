---
title: register_add_in_function yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 180
url: /tr/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
Çalışma kitabına eklenti işlevi ekler


###  İadeler

Eklenti fonksiyonlarını içeren eklenti dosyasının URL'si


```python

def register_add_in_function(self, id, function_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| id | int |Eklenti fonksiyonlarını içeren verinin kimliği,<br/> Aynı eklenti dosyası için [`WorksheetCollection.register_add_in_function`](/cells/python-net/tr/aspose.cells/worksheetcollection/register_add_in_function)'in ilk çağrısıyla elde edilebilir.|
| function_name | str | eklenti fonksiyon adı|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
Çalışma kitabına eklenti işlevi ekler


###  İadeler

Verilen eklenti fonksiyonunu içeren verinin kimliği


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| add_in_file | str | dosya eklenti işlevlerini içerir|
| function_name | str | eklenti fonksiyon adı|
| lib | bool | Verilen eklenti dosyasının Workbook Eklentisi kütüphanesinin dizininde mi yoksa alt dizininde mi olduğu.<br/>Bu bayrak, addInFile'ın bağıl yolda olması durumunda etkili olur ve fark yaratır:<br/> true, yolun Eklenti kitaplığına göreli olduğunu belirtir ve false, yolun bu Çalışma Kitabına göreli olduğunu belirtir.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`WorksheetCollection`](/cells/python-net/tr/aspose.cells/worksheetcollection)
