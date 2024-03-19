---
title: on_circular yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Döngüsel referanslara sahip formülleri hesaplarken iş yapmak için bu yöntemi uygulayın.


###  İadeler

Bu çağrıdan sonra formül motorunun bu hücreleri dairesel olarak hesaplaması gerekip gerekmediği.
Formül motorunun onlar için hesaplama yapmaya devam etmesine izin vermek doğru.
Formül motorunun bu hücreleri Hesaplanmış olarak işaretlemesine izin vermek için False.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator, hücreleri temsil eden [`CalculationCell`](/cells/python-net/tr/aspose.cells/calculationcell) öğeye sahip<br/> döngüsel referanslara bağlıdır.|
###  Notlar

Uygulamada kullanıcı beklenen değeri hesaplanan sonuç olarak da ayarlayabilir
bu hücrelerin bir kısmı/tümü için formül motoru bunları yinelemeli olarak hesaplamayacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`AbstractCalculationMonitor`](/cells/python-net/tr/aspose.cells/abstractcalculationmonitor)
* sınıf [`CalculationCell`](/cells/python-net/tr/aspose.cells/calculationcell)
