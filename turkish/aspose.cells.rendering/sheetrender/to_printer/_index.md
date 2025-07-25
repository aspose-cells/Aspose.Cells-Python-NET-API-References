---
title: to_printer yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
Çalışma sayfasını yazıcıya aktar



```python

def to_printer(self, printer_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
Çalışma sayfasını yazıcıya aktar



```python

def to_printer(self, printer_settings):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | yazıcının ayarları, örneğin YazıcıAdı, Dubleks|


##  to_printer(self, printer_name, job_name) {#str-str}
Çalışma sayfasını yazıcıya aktar



```python

def to_printer(self, printer_name, job_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|
| job_name | str | yazdırma işi adını ayarla|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
Çalışma sayfasını yazıcıya aktar



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | yazıcının ayarları, örneğin YazıcıAdı, Dubleks|
| job_name | str | yazdırma işi adını ayarla|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
Çalışma sayfasını yazıcıya aktar



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| printer_name | str | yazıcının adı, örneğin: "Microsoft Office Belge Görüntü Yazıcısı"|
| print_page_index | int | yazdırılacak ilk sayfanın 0 tabanlı dizini, [0, SheetRender.PageCount-1] Aralığında olmalıdır|
| print_page_count | int | yazdırılacak sayfa sayısı sıfırdan büyük olmalıdır|
###  Notlar

NOT: Bu yöntem artık geçerliliğini yitirmiştir.
Bunun yerine, ilk sayfayı ve yazdırılacak sayfa sayısını ayarlamak için ToPrinter(string PrinterName) ve ImageOrPrintOptions.PageIndex, PageCount kullanın.
 Bu özellik Aralık 2021'den itibaren 12 ay sonra kaldırılacaktır.
Aspose yaşadığınız olumsuzluktan dolayı özür diler.


###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`SheetRender`](/cells/python-net/tr/aspose.cells.rendering/sheetrender)
