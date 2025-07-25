---
title: get_cell_display_style yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 320
url: /tr/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Verilen hücrenin görüntülenme stilini al.


###  İadeler

Verilen hücrenin görüntüleme stili.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | verilen hücrenin satır dizini|
| column | int | verilen hücrenin sütunu|
###  Notlar

[`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style) ile aynı,
ve [`BorderType.SIDE_BORDERS`](/cells/python-net/tr/aspose.cells/bordertype#SIDE_BORDERS)'i kullanırken de aynı şey geçerli
[`Cells.get_cell_display_style`](/cells/python-net/tr/aspose.cells/cells/get_cell_display_style) için.

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Verilen hücrenin görüntülenme stilini al.


###  İadeler

Verilen hücrenin görüntüleme stili.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | verilen hücrenin satır dizini|
| column | int | verilen hücrenin sütunu|
| adjacent_borders | [`BorderType`](/cells/python-net/tr/aspose.cells/bordertype) | Komşu hücrelerin sınırlarına göre hangi sınırların kontrol edilmesi ve ayarlanması gerektiğini belirtir.<br/>Lütfen aynı parametrenin açıklamasına bakın<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Notlar

Hücre koşullu biçimlendirme, liste nesneleri vb. gibi diğer ayarlardan da etkileniyorsa,
o zaman görüntüleme stili [`Cells.get_cell_style`](/cells/python-net/tr/aspose.cells/cells/get_cell_style)'den farklı olabilir.
Ve bu ayarlar boş (mevcut olmayan) hücrelere de uygulanabileceğinden,
Bu yöntemi kullanarak boş hücrelerin örneklenmesi önlenebilir
bu nedenle performans, Cells örneğinden Cell örneğini almaktan daha iyi olacaktır
ve ardından [`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style)'i arayın.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
