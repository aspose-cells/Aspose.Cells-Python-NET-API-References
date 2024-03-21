---
title: SheetRender sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 120
url: /tr/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender sınıfı
Çalışma sayfasını (BMP, PNG, JPEG, TIFF..) gibi çeşitli görüntülere işleyebilen bir çalışma sayfası oluşturma işlemini temsil eder.
Bu sınıfın yapıcısı, sayfa düzeni, hücre stili değiştirildikten sonra kullanılmalıdır.



SheetRender türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | SheetRender'ın yapısı, parametre olarak çalışma sayfasına ve ImageOrPrintOptions'a ihtiyaç duyar|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [page_count](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_count) | Geçerli çalışma sayfasının toplam sayfa sayısını alır.|
| [page_scale](/cells/python-net/tr/aspose.cells.rendering/sheetrender/page_scale) | Sayfanın hesaplanan sayfa ölçeğini alır.<br/> [`PageSetup.zoom`](/cells/python-net/tr/aspose.cells/pagesetup#zoom) ayarlanmışsa ayarlanan ölçeği döndürür. Aksi halde [`PageSetup.fit_to_pages_wide`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_wide) ve [`PageSetup.fit_to_pages_tall`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_tall)'e göre hesaplanan ölçeği döndürür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [to_image](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-str) |Belirli bir sayfayı bir dosyaya dönüştürün.|
| [to_image](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Belirli bir sayfayı bir akışa dönüştürün.|
| [to_tiff](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Akış için tüm çalışma sayfasını Tiff Image olarak işleyin.|
| [to_tiff](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_tiff/#str) | Çalışma sayfasının tamamını Tiff Görüntüsü olarak bir dosyaya dönüştürün.|
| [to_printer](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str) | Çalışma sayfasını Yazıcıya aktar|
| [to_printer](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Çalışma sayfasını Yazıcıya aktar|
| [to_printer](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Çalışma sayfasını Yazıcıya aktar|
| [to_printer](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Çalışma sayfasını Yazıcıya aktar|
| [to_printer](/cells/python-net/tr/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Çalışma sayfasını Yazıcıya aktar|
| [get_page_size_inch](/cells/python-net/tr/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Çıktı görüntüsünün inç cinsinden sayfa boyutunu alın.|
| [custom_print](/cells/python-net/tr/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Müşteri bu işlevi kullanarak her sayfayı yazdırırken yazıcının sayfa ayarını kontrol edebilir.|
| [dispose](/cells/python-net/tr/aspose.cells.rendering/sheetrender/dispose/#) | Oluşturma için oluşturulan ve kullanılan kaynakları serbest bırakır.|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
