---
title: detect_file_format yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, akış){#io.RawIOBase}
Bir akışta saklanan bir Excel dosyası formatı hakkında bilgiyi algılar ve döndürür.


###  İadeler

Tespit edilen bilgileri içeren [`FileFormatInfo`](/cells/python-net/tr/aspose.cells/fileformatinfo) nesnesi.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, dosya_yolu){#str}
Bir dosyada saklanan Excel formatı hakkında bilgiyi algılar ve döndürür.


###  İadeler

Tespit edilen bilgileri içeren [`FileFormatInfo`](/cells/python-net/tr/aspose.cells/fileformatinfo) nesnesi.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file_path | str | Dosya yolu.|


##  detect_file_format(, akış, şifre){#io.RawIOBase-str}
Bir akışta saklanan bir Excel dosyası formatı hakkında bilgiyi algılar ve döndürür.


###  İadeler

Tespit edilen bilgileri içeren [`FileFormatInfo`](/cells/python-net/tr/aspose.cells/fileformatinfo) nesnesi.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | Şifrelenmiş ooxml dosyalarının şifresi.|


##  detect_file_format(, dosya_yolu, parola){#str-str}
Bir dosyada saklanan Excel formatı hakkında bilgiyi algılar ve döndürür.


###  İadeler

Tespit edilen bilgileri içeren [`FileFormatInfo`](/cells/python-net/tr/aspose.cells/fileformatinfo) nesnesi.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file_path | str | Dosya yolu.|
| password | str | Şifrelenmiş ooxml dosyalarının şifresi.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FileFormatInfo`](/cells/python-net/tr/aspose.cells/fileformatinfo)
* sınıf [`FileFormatUtil`](/cells/python-net/tr/aspose.cells/fileformatutil)
