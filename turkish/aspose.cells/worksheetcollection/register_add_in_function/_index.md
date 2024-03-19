---
title: register_add_in_function yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 180
url: /tr/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
Çalışma kitabına eklenti işlevi ekler


###  İadeler

Eklenti işlevlerini içeren eklenti dosyasının URL'si


```python
def register_add_in_function(self, id, function_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| id | int | Eklenti fonksiyonlarını içeren verilerin kimliği,<br/> aynı eklenti dosyası için [`WorksheetCollection.register_add_in_function`](/cells/python-net/tr/aspose.cells/worksheetcollection/register_add_in_function)'in ilk çağrısıyla ulaşılabilir.|
| function_name | str | eklenti işlev adı|


##  register_add_in_function {#str-str-bool}
Çalışma kitabına eklenti işlevi ekler


###  İadeler

Verilen eklenti fonksiyonunu içeren verilerin kimliği


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| add_in_file | str | dosya eklenti işlevlerini içerir|
| function_name | str | eklenti işlev adı|
| lib | bool | verilen eklenti dosyasının Çalışma Kitabı Eklenti kitaplığının dizininde mi yoksa alt dizininde mi olduğu.<br/>Bu bayrak etkili olur ve addInFile'ın göreceli yolda olması durumunda fark yaratır:<br/> true, yolun Eklenti kitaplığına göre olduğunu, false ise yolun bu Çalışma Kitabına göre olduğunu belirtir.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`WorksheetCollection`](/cells/python-net/tr/aspose.cells/worksheetcollection)
