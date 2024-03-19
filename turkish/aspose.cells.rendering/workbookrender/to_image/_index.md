---
title: to_image yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 50
url: /tr/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Akış için tüm çalışma kitabını Tiff Görüntüsü olarak işleyin.



```python
def to_image(self, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | çıktı görüntüsünün akışı|


##  to_image {#str}
Çalışma kitabının tamamını Tiff Görüntüsü olarak bir dosyaya dönüştürün.



```python
def to_image(self, filename):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| filename | str | çıktı görüntüsünün dosya adı|


##  to_image {#int-str}
Belirli bir sayfayı bir dosyaya dönüştürün.



```python
def to_image(self, page_index, file_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| page_index | int | hangi sayfanın dönüştürüleceğini belirtin|
| file_name | str | çıktı görüntüsünün dosya adı|


##  to_image {#int-io.RawIOBase}
Belirli bir sayfayı bir akışa dönüştürün.



```python
def to_image(self, page_index, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| page_index | int | hangi sayfanın dönüştürüleceğini belirtin|
| stream | io.RawIOBase | çıktı görüntüsünün akışı|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`WorkbookRender`](/cells/python-net/tr/aspose.cells.rendering/workbookrender)
