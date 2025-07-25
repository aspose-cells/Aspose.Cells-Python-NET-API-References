---
title: WorkbookRender sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender sınıfı
 Bir Çalışma Kitabı oluşturmayı temsil eder.
Bu sınıfın kurucusu, pagesetup, hücre stili değiştirildikten sonra kullanılmalıdır.



WorkbookRender türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | WorkbookRender'ın yapısı|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [page_count](/cells/python-net/tr/aspose.cells.rendering/workbookrender/page_count) | Çalışma kitabının toplam sayfa sayısını alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Tüm çalışma kitabını Tiff Görüntüsü olarak akışa aktarın.|
| [`to_image(self, filename)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_image/#str) | Tüm çalışma kitabını Tiff Görüntüsü olarak bir dosyaya aktar.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_image/#int-str) | Belirli bir sayfayı bir dosyaya dönüştür.|
| [`to_image(self, page_index, stream)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Belirli bir sayfayı akışa dönüştür.|
| [`to_printer(self, printer_name)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_printer/#str) | Çalışma kitabını Yazıcıya aktar|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Çalışma kitabını Yazıcıya aktar|
| [`to_printer(self, printer_settings)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Çalışma kitabını Yazıcıya aktar|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Çalışma kitabını Yazıcıya aktar|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Çalışma kitabını Yazıcıya aktar|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Çıktı görüntüsünün sayfa boyutunu inç cinsinden alın.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Bu fonksiyonu kullanarak istemci her sayfayı yazdırırken yazıcının sayfa ayarlarını kontrol edebilir.|
| [`dispose(self)`](/cells/python-net/tr/aspose.cells.rendering/workbookrender/dispose/#) | Oluşturulan ve işleme için kullanılan kaynakları serbest bırakır.|



###  Notlar



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
