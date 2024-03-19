---
title: LoadFilter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1050
url: /tr/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter sınıfı
Çalışma kitabını şablondan yüklerken veri yükleme seçenekleri sağlayan filtreyi temsil eder.



LoadFilter türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#) | Varsayılan filtre seçenekleriyle bir LoadFilter oluşturur LoadDataFilterOptions.All.|
| [__init__](/cells/python-net/tr/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) | Verilen filtre seçenekleriyle bir LoadFilter oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_data_filter_options](/cells/python-net/tr/aspose.cells/loadfilter/load_data_filter_options) | Hangi verilerin yüklenmesi gerektiğini belirten filtre seçenekleri.|
| [sheets_in_loading_order](/cells/python-net/tr/aspose.cells/loadfilter/sheets_in_loading_order) | Yüklenecek sayfaları (indeksleri) ve sırayı belirtir.<br/>Varsayılan değer null'dur; bu, tüm sayfaların şablon dosyasındaki varsayılan sıraya göre yükleneceğini belirtir.<br/> Boş değilse ve bazı sayfaların dizini döndürülen dizide değilse, sayfa yüklenmeyecektir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [start_sheet](/cells/python-net/tr/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) | Verilen çalışma sayfasını yüklemeden önce filtre seçeneklerini hazırlar.<br/>Kullanıcının LoadFilter uygulaması burada LoadDataFilterOptions'ı değiştirebilir<br/> Bu çalışma sayfasına ilişkin verilerin nasıl yükleneceğini belirtmek için.|



###  Notlar

Kullanıcı, verilerin nasıl yükleneceğini belirtmek için filtre seçeneklerini belirleyebilir veya kendi LoadFilter'ini uygulayabilir.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
