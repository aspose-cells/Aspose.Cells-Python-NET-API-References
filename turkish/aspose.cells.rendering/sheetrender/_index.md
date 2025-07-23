---
title: SheetRender sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender sınıfı
(BMP, PNG, JPEG, TIFF..) gibi çeşitli resimlere çalışma sayfası oluşturabilen bir çalışma sayfası oluşturma aracını temsil eder.
Bu sınıfın kurucusu, pagesetup, hücre stili değiştirildikten sonra kullanılmalıdır.



SheetRender türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | SheetRender'ın yapısı, çalışma sayfası ve ImageOrPrintOptions parametrelerine ihtiyaç duyar|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [page_count](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_count) | Geçerli çalışma sayfasının toplam sayfa sayısını alır.|
| [page_scale](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_scale) | Sayfanın hesaplanan sayfa ölçeğini alır.<br/> [`PageSetup.zoom`](/cells/python-net/tr/aspose.cells/pagesetup#zoom) ayarlanmışsa ayarlanan ölçeği döndürür. Aksi takdirde [`PageSetup.fit_to_pages_wide`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_wide) ve [`PageSetup.fit_to_pages_tall`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_tall)'e göre hesaplanan ölçeği döndürür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-str) | Belirli bir sayfayı bir dosyaya dönüştür.|
| [`to_image(self, page_index, stream)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Belirli bir sayfayı akışa dönüştür.|
| [`to_tiff(self, stream)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Tüm çalışma sayfasını Tiff Görüntüsü olarak yayına dönüştürün.|
| [`to_tiff(self, filename)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#str) | Tüm çalışma sayfasını Tiff Görüntüsü olarak bir dosyaya aktarın.|
| [`to_printer(self, printer_name)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str) | Çalışma sayfasını yazıcıya aktar|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Çalışma sayfasını yazıcıya aktar|
| [`to_printer(self, printer_settings)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Çalışma sayfasını yazıcıya aktar|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Çalışma sayfasını yazıcıya aktar|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Çalışma sayfasını yazıcıya aktar|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Çıktı görüntüsünün sayfa boyutunu inç cinsinden alın.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Bu fonksiyonu kullanarak istemci her sayfayı yazdırırken yazıcının sayfa ayarlarını kontrol edebilir.|
| [`dispose(self)`](/cells/python-net/tr/aspose.cells.rendering/sheetrender/dispose/#) | Oluşturulan ve işleme için kullanılan kaynakları serbest bırakır.|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
