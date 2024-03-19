---
title: to_printer yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.rendering/workbookrender/to_printer/
is_root: false
---
##  to_printer {#str}
Çalışma kitabını Yazıcıya aktar



```python
def to_printer(self, printer_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
Çalışma kitabını Yazıcıya aktar



```python
def to_printer(self, printer_settings):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | yazıcının ayarları, örneğin YazıcıAdı, Dubleks|


##  to_printer {#str-str}
Çalışma kitabını Yazıcıya aktar



```python
def to_printer(self, printer_name, job_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|
| job_name | str | yazdırma işi adını ayarlayın|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
Çalışma kitabını Yazıcıya aktar



```python
def to_printer(self, printer_settings, job_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | yazıcının ayarları, örneğin YazıcıAdı, Dubleks|
| job_name | str | yazdırma işi adını ayarlayın|


##  to_printer {#str-int-int}
Çalışma kitabını Yazıcıya aktar



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|
| print_page_index | int | Yazdırılacak ilk sayfanın 0 tabanlı dizini, [0, WorkbookRender.PageCount-1] aralığında olmalıdır.|
| print_page_count | int | yazdırılacak sayfa sayısı sıfırdan büyük olmalıdır|
###  Notlar

NOT: Bu yöntem artık geçerliliğini yitirmiştir.
Bunun yerine, ilk sayfayı ve yazdırılacak sayfa sayısını ayarlamak için lütfen ToPrinter(string PrinterName) ve ImageOrPrintOptions.PageIndex, PageCount'u kullanın.
 Bu mülk, Aralık 2021'den itibaren 12 ay sonra kaldırılacaktır.
Aspose, yaşamış olabileceğiniz rahatsızlıklardan dolayı özür diler.


###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`WorkbookRender`](/cells/python-net/tr/aspose.cells.rendering/workbookrender)
