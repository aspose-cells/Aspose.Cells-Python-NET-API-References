---
title: get_dependents yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Formülü doğrudan bu hücreye referans veren tüm hücreleri al.



```python

def get_dependents(self, is_all):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_all | bool |Diğer çalışma sayfalarındaki formüllerin kontrol edilip edilmeyeceğini belirtir|
###  Notlar

* Bu hücreyi içeren bir başvuru bir hücrenin formülünde yer alırsa, o hücre şu şekilde alınacaktır:

Bu hücrenin bağımlısı, hesaplama sırasında referans veya bu hücrenin kullanılıp kullanılmadığına bakılmaksızın.
Örneğin, "=EĞER(DOĞRU;A1;A2)" formülündeki A2 hücresi hesaplama sırasında kullanılmasa da,
Bu formül hala A2'ye bağlı olarak alınabilir.
Hesaplanan sonuçları bu hücreye bağlı olan formülleri elde etmek için lütfen [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanın. Bir hücre için bağımlıları izlerken, çalışma kitabındaki veya çalışma sayfasındaki tüm formüller analiz edilecek ve kontrol edilecektir.
Bu nedenle zaman alıcı bir işlemdir. Kullanıcının çok sayıda hücre için bağımlı kişileri izlemesi gerekiyorsa, bu yöntemi kullanmak
Performans düşüklüğüne neden olur. Performans değerlendirmesi için kullanıcı [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanmalıdır.
Veya kullanıcı öncelikle [`Cell.get_precedents`](/cells/python-net/tr/aspose.cells/cell/get_precedents)'e göre tüm hücrelerin emsal haritasını toplayabilir,
ve daha sonra emsal haritaya göre bağımlı haritasını oluşturun.

* Bu hücreyi içeren bir başvuru bir hücrenin formülünde yer alırsa, o hücre şu şekilde alınacaktır:
Bu hücrenin bağımlısı, hesaplama sırasında referans veya bu hücrenin kullanılıp kullanılmadığına bakılmaksızın.
Örneğin, "=EĞER(DOĞRU;A1;A2)" formülündeki A2 hücresi hesaplama sırasında kullanılmasa da,
Bu formül hala A2'ye bağlı olarak alınabilir.
Hesaplanan sonuçları bu hücreye bağlı olan formülleri elde etmek için lütfen [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanın. Bir hücre için bağımlıları izlerken, çalışma kitabındaki veya çalışma sayfasındaki tüm formüller analiz edilecek ve kontrol edilecektir.
Bu nedenle zaman alıcı bir işlemdir. Kullanıcının çok sayıda hücre için bağımlı kişileri izlemesi gerekiyorsa, bu yöntemi kullanmak
Performans düşüklüğüne neden olur. Performans değerlendirmesi için kullanıcı [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanmalıdır.
Veya kullanıcı öncelikle [`Cell.get_precedents`](/cells/python-net/tr/aspose.cells/cell/get_precedents)'e göre tüm hücrelerin emsal haritasını toplayabilir,
ve daha sonra emsal haritaya göre bağımlı haritasını oluşturun.

* Bu hücreyi içeren bir başvuru bir hücrenin formülünde yer alırsa, o hücre şu şekilde alınacaktır:
Bu hücrenin bağımlısı, hesaplama sırasında referans veya bu hücrenin kullanılıp kullanılmadığına bakılmaksızın.
Örneğin, "=EĞER(DOĞRU;A1;A2)" formülündeki A2 hücresi hesaplama sırasında kullanılmasa da,
Bu formül hala A2'ye bağlı olarak alınabilir.
Hesaplanan sonuçları bu hücreye bağlı olan formülleri elde etmek için lütfen [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanın. Bir hücre için bağımlıları izlerken, çalışma kitabındaki veya çalışma sayfasındaki tüm formüller analiz edilecek ve kontrol edilecektir.
Bu nedenle zaman alıcı bir işlemdir. Kullanıcının çok sayıda hücre için bağımlı kişileri izlemesi gerekiyorsa, bu yöntemi kullanmak
Performans düşüklüğüne neden olur. Performans değerlendirmesi için kullanıcı [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'i kullanmalıdır.
Veya kullanıcı öncelikle [`Cell.get_precedents`](/cells/python-net/tr/aspose.cells/cell/get_precedents)'e göre tüm hücrelerin emsal haritasını toplayabilir,
ve daha sonra emsal haritaya göre bağımlı haritasını oluşturun.
###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
