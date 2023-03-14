---
title: LoadFilter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1010
url: /tr/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter sınıfı
Çalışma kitabını şablondan yüklerken veri yüklemek için seçenekler sağlayan filtreyi temsil eder.



LoadFilter türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [LoadFilter()](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#) | LoadDataFilterOptions.All varsayılan filtre seçenekleriyle bir LoadFilter oluşturur.|
| [LoadFilter(opts)](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#LoadDataFilterOptions) | Verilen filtre seçenekleriyle bir LoadFilter oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_data_filter_options](/cells/python-net/tr/aspose.cells/loadfilter/load_data_filter_options) | Hangi verilerin yüklenmesi gerektiğini gösteren filtre seçenekleri.|
| [sheets_in_loading_order](/cells/python-net/tr/aspose.cells/loadfilter/sheets_in_loading_order) | Sayfaları (endeksleri) ve yüklenecek sırayı belirtir.<br/>Varsayılan boştur, bu, şablon dosyasındaki tüm sayfaların varsayılan sırayla yüklenmesini belirtir.<br/> Null değilse ve bazı sayfaların dizini döndürülen dizide değilse, sayfa yüklenmez.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [start_sheet(sheet)](/cells/python-net/tr/aspose.cells/loadfilter/start_sheet/#Worksheet) | Verilen çalışma sayfasını yüklemeden önce filtre seçeneklerini hazırlar.<br/>Kullanıcının LoadFilter uygulaması, LoadDataFilterOptions'ı burada değiştirebilir<br/> Bu çalışma sayfası için verilerin nasıl yükleneceğini belirtmek için.|



###  Notlar

Kullanıcı, verilerin nasıl yükleneceğini belirtmek için filtre seçeneklerini belirleyebilir veya kendi LoadFilter'ini uygulayabilir.

###  Ayrıca bakınız
* modül [aspose.cells](..)
