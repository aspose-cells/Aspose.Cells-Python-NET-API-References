---
title: set_embedded_object yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 190
url: /tr/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object {#bool-bytes-str-bool-str}
Gömülü nesne verilerini ayarlar.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| link_to_file | bool | Nesnenin dosyaya bağlanıp bağlanmadığını belirtir. Doğruysa, objectData parametresi yoksayılır.|
| object_data | bytes | Gömülü nesne verileri.|
| source_file_name | str | Dosya adı.|
| display_as_icon | bool | Nesnenin simge olarak görüntülenip görüntülenmediğini belirtir.<br/> Doğruysa orijinal görüntü verileri simgeyle kaplanacaktır.|
| label | str | Simge etiketi. Yalnızca AsIcon'u true olarak gösterdiğinde çalışır.|


##  set_embedded_object {#bool-bytes-str-bool-str-bool}
Gömülü nesne verilerini ayarlar.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| link_to_file | bool | Nesnenin dosyaya bağlanıp bağlanmadığını belirtir. Doğruysa, objectData parametresi yoksayılır.|
| object_data | bytes | Gömülü nesne verileri.|
| source_file_name | str | Dosya adı.|
| display_as_icon | bool | Nesnenin simge olarak görüntülenip görüntülenmediğini belirtir.<br/> Doğruysa orijinal görüntü verileri simgeyle kaplanacaktır.|
| label | str | Simge etiketi. Yalnızca AsIcon'u true olarak gösterdiğinde çalışır.|
| update_icon | bool |Simgenin otomatik olarak güncellenip güncellenmeyeceğini belirtir.|
###  Notlar

Aspose tüm dosya simgelerini yerleştirmeyi güncelleyebildiğinden, `update_icon` ile doğru simgeyi yanlış olarak eklemeniz daha iyidir.


###  Ayrıca bakınız

* modül [`aspose.cells.drawing`](../../)
* sınıf [`OleObject`](/cells/python-net/tr/aspose.cells.drawing/oleobject)
