---
title: set_desired_size yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.rendering/imageorprintoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Görüntünün istenilen genişliğini ve yüksekliğini ayarlar.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| desired_width | int | istenilen piksel genişliği|
| desired_height | int | piksel cinsinden istenen yükseklik|
###  Notlar

NOT: Bu üye artık geçerliliğini yitirmiştir. Bunun yerine,
Lütfen keepAspectRatio parametresini false olarak ayarlayarak [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/set_desired_size)'i kullanın.
 Bu özellik Mayıs 2023'ten itibaren 12 ay sonra kaldırılacaktır.
Aspose yaşadığınız olumsuzluktan dolayı özür diler.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Görüntünün istenilen genişliğini ve yüksekliğini ayarlar.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| desired_width | int | istenilen piksel genişliği|
| desired_height | int | piksel cinsinden istenen yükseklik|
| keep_aspect_ratio | bool | orijinal görüntünün en boy oranının korunup korunmayacağı|
###  Notlar

Çıkış görüntüsünün piksel cinsinden genişliği ve yüksekliği yalnızca aşağıdakilere dayalı olacaktır:
istenilen genişlik ve yüksekliği ayarlayın.


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) ve [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
Bu durumda çıktı görüntüsünün genişliğini ve yüksekliğini etkilemeyecektir.


###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`ImageOrPrintOptions`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions)
