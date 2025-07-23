---
title: get_display_style yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Bu hücrenin görüntüleme stilini alır.


###  İadeler

bu hücrenin görüntüleme stili


```python

def get_display_style(self):
    ...
```


###  Notlar

[`BorderType.SIDE_BORDERS`](/cells/python-net/tr/aspose.cells/bordertype#SIDE_BORDERS)'i kullanırken de aynı şey geçerli
[`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style) için.
Yani bu yöntem, bu hücrenin üst/alt/sol/sağ kenarlıklarını kontrol edecek ve ayarlayacaktır
bitişik hücrelerinin stiline ([`Cell.get_style`](/cells/python-net/tr/aspose.cells/cell/get_style)) göre,
Ancak birleştirilmiş hücreleri kontrol etmeyin ve bitişik hücrelerin görüntülenme stilini kontrol etmeyin.

##  get_display_style(self, include_merged_borders) {#bool}
Bu hücrenin görüntüleme stilini alır.


###  İadeler

bu hücrenin görüntüleme stili


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| include_merged_borders | bool | Birleştirilmiş hücrelerin sınırlarının kontrol edilip edilmeyeceğini belirtir.|
###  Notlar

Belirtilen bayrak false ise [`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style) ile aynıdır.
Aksi takdirde, kullanımıyla aynıdır
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
[`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style) için.

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Bu hücrenin görüntüleme stilini alır.


###  İadeler

bu hücrenin görüntüleme stili


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/tr/aspose.cells/bordertype) | Hangi sınırların kontrol edilmesi ve ayarlanması gerektiğini belirtir<br/> komşu hücrelerin sınırlarına göre.|
###  Notlar

Bu hücre koşullu biçimlendirme, liste nesneleri vb. gibi diğer ayarlar tarafından da etkileniyorsa,
o zaman görüntüleme stili [`Cell.get_style`](/cells/python-net/tr/aspose.cells/cell/get_style)'den farklı olabilir.

Bitişik hücrelere göre sınırları ayarlama bayrakları için,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
alt/üst/sağ/sol kenarlıklarını kontrol edip birleştirip birleştirmediğinizi belirtin
bu hücrenin yanındaki sol/sağ/üst/alt hücreler.

Performans ve uyumluluk hususunda,
Bazı enumlar bazı özel işlemleri belirtmek için kullanılır:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
Birleştirilmiş hücrelerin alt/sağ kenarlığının bu kenarlıkla birleştirilip birleştirilmeyeceğini belirtir.

[`BorderType.DIAGONAL`](/cells/python-net/tr/aspose.cells/bordertype#DIAGONAL) (yani hem [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/tr/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) hem de
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/tr/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) ayarlandı) sınırları kontrol etmeyi ve birleştirmeyi belirtir
bitişik hücrelerin görüntülenme stilinden.

Lütfen bitişik hücrelerin kenarlıklarını/stillerini, özellikle de görüntüleme stillerini kontrol ettiğinizden emin olun.
zaman alıcı bir işlemdir. Döndürülen stil için kenarlıkları almaya gerek yoksa,
bitişik hücrelerin işlemini devre dışı bırakmak için [`BorderType.NONE`](/cells/python-net/tr/aspose.cells/bordertype#NONE)'i kullanma
daha iyi performans verecektir.
Yalnızca bu hücrelerde tanımlanan stillerden bitişik hücrelerin sınırlarını alırken (ayar yapmadan)
[`BorderType.DIAGONAL`](/cells/python-net/tr/aspose.cells/bordertype#DIAGONAL)), performans da daha iyi olabilir çünkü kontrol
Bir hücrenin görüntülenme biçimi de zaman alıcıdır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
