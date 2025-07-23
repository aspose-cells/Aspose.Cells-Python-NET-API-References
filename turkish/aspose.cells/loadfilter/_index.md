---
title: LoadFilter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 940
url: /tr/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter sınıfı
Çalışma kitabını şablondan yüklerken veri yükleme seçenekleri sağlayan filtreyi temsil eder.



LoadFilter türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#) | Varsayılan filtre seçenekleri LoadDataFilterOptions.All ile bir LoadFilter oluşturur.|
| [`__init__(self, opts)`](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | Verilen filtre seçenekleriyle bir LoadFilter oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_data_filter_options](/cells/python-net/tr/aspose.cells/loadfilter/load_data_filter_options) |Hangi verilerin yükleneceğini belirtmek için kullanılan filtre seçenekleri.|
| [sheets_in_loading_order](/cells/python-net/tr/aspose.cells/loadfilter/sheets_in_loading_order) | Yüklenecek sayfaları(indeksleri) ve sırayı belirtir.<br/>Varsayılan değer null'dır, bu şablon dosyasında tüm sayfaların varsayılan sırayla yüklenmesini belirtir.<br/> Eğer null değilse ve bir sayfanın indeksi döndürülen dizide değilse, o zaman sayfa yüklenmeyecektir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/tr/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | Verilen çalışma sayfasını yüklemeden önce filtre seçeneklerini hazırlar.<br/>Kullanıcının LoadFilter uygulaması, LoadDataFilterOptions'ı burada değiştirebilir<br/> Bu çalışma sayfasına verinin nasıl yükleneceğini belirtmek için.|



###  Notlar

Kullanıcı, filtre seçeneklerini belirleyebilir veya verilerin nasıl yükleneceğini belirtmek için kendi LoadFilter'ini uygulayabilir.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
