---
title: set_embedded_object yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 200
url: /tr/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
Gömülü nesne verilerini ayarlar.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| link_to_file | bool | Nesnenin dosyaya bağlanıp bağlanmadığını belirtir. Doğru ise, objectData parametresi yok sayılır.|
| object_data | bytes | Gömülü nesne verileri.|
| source_file_name | str | Dosya adı.|
| display_as_icon | bool | Nesnenin simge olarak görüntülenip görüntülenmeyeceğini belirtir.<br/> Doğruysa orijinal görüntü verileri ikon tarafından örtülecektir.|
| label | str | Simge etiketi. Sadece displayAsIcon true olduğunda çalışır.|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
Gömülü nesne verilerini ayarlar.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| link_to_file | bool | Nesnenin dosyaya bağlanıp bağlanmadığını belirtir. Doğru ise, objectData parametresi yok sayılır.|
| object_data | bytes | Gömülü nesne verileri.|
| source_file_name | str | Dosya adı.|
| display_as_icon | bool | Nesnenin simge olarak görüntülenip görüntülenmeyeceğini belirtir.<br/> Doğruysa orijinal görüntü verileri ikon tarafından örtülecektir.|
| label | str | Simge etiketi. Sadece displayAsIcon true olduğunda çalışır.|
| update_icon | bool |Simgenin otomatik olarak güncellenip güncellenmediğini gösterir.|
###  Notlar

Aspose tüm dosya simgelerini güncelleyebildiğinden, `update_icon`'i false olarak ayarlayarak doğru simgeyi eklemeniz daha iyi olur.


###  Ayrıca bakınız

* modül [`aspose.cells.drawing`](../../)
* sınıf [`OleObject`](/cells/python-net/tr/aspose.cells.drawing/oleobject)
