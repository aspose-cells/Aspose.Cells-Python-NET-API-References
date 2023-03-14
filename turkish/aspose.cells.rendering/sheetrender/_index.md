---
title: SheetRender sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender sınıfı
Çalışma sayfasını (BMP, PNG, JPEG, TIFF..) gibi çeşitli görüntülere işleyebilen bir çalışma sayfası oluşturmayı temsil eder.
Bu sınıfın yapıcısı, sayfa düzeni, hücre stili değiştirildikten sonra kullanılmalıdır.



SheetRender türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [SheetRender(worksheet, options)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/__init__/#Worksheet-ImageOrPrintOptions) | SheetRender yapısı, param olarak çalışma sayfası ve ImageOrPrintOptions'a ihtiyaç duyar|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [page_count](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_count) | Geçerli çalışma sayfasının toplam sayfa sayısını alır.|
| [page_scale](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_scale) | Sayfanın hesaplanan sayfa ölçeğini alır.<br/> [PageSetup.zoom](/cells/python-net/tr/aspose.cells/pagesetup#zoom) ayarlanmışsa ayarlanan ölçeği döndürür. Aksi takdirde, [PageSetup.fit_to_pages_wide](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_wide) ve [PageSetup.fit_to_pages_tall](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_tall)'e göre hesaplanan ölçeği döndürür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [to_image(page_index, file_name)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-str) | Belirli bir sayfayı bir dosyaya dönüştürün.|
| [to_image(page_index, stream)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Belirli bir sayfayı bir akışa dönüştürün.|
| [to_tiff(stream)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Akış için tüm çalışma sayfasını Tiff Görüntüsü olarak işleyin.|
| [to_tiff(filename)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#str) | Tüm çalışma sayfasını bir dosyaya Tiff Görüntüsü olarak işleyin.|
| [to_printer(printer_name)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str) | Çalışma sayfasını Yazıcıya işle|
| [to_printer(printer_name, job_name)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Çalışma sayfasını Yazıcıya işle|
| [to_printer(printer_settings)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Çalışma sayfasını Yazıcıya işle|
| [to_printer(printer_settings, job_name)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Çalışma sayfasını Yazıcıya işle|
| [to_printer(printer_name, print_page_index, print_page_count)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Çalışma sayfasını Yazıcıya işle|
| [get_page_size_inch(page_index)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) |Çıktı görüntüsünün inç cinsinden sayfa boyutunu alın.|
| [custom_print(next_page_after_print, print_page_event_args)](/cells/python-net/tr/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | İstemci, bu işlevi kullanarak her sayfayı yazdırırken yazıcının sayfa ayarını kontrol edebilir.|



###  Ayrıca bakınız
* modül [aspose.cells.rendering](..)
