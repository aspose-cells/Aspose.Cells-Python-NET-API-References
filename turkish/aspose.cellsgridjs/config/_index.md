---
title: Config sınıfı
second_title: Aspose.Cells.GridJs for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cellsgridjs/config/
is_root: false
---
##  Config sınıfı

GridJ'ler için tüm ayarları temsil eder



Config türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cellsgridjs/config/__init__/#) | Config'in yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_html_as_zip](/cells/python-net/tr/aspose.cellsgridjs/config/save_html_as_zip) | Html dosyasının zip arşivi olarak kaydedilip kaydedilmeyeceğini ayarlar/alır, varsayılan değer false'tur.|
| [same_image_detecting](/cells/python-net/tr/aspose.cellsgridjs/config/same_image_detecting) | Resmin aynı kaynağa sahip olup olmadığının kontrol edilip edilmeyeceğini ayarlar/alır, varsayılan değer doğrudur<br/> varsayılan değer doğrudur.|
| [auto_optimize_for_large_cells](/cells/python-net/tr/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Büyük hücreli çalışma sayfası için yükleme performansının otomatik olarak optimize edilip edilmeyeceğini ayarlar/alır<br/> Yükleme süresini azaltmak için bazı stilleri/kenarlıkları göz ardı edin<br/> varsayılan değer doğrudur.|
| [islimit_shape_or_image](/cells/python-net/tr/aspose.cellsgridjs/config/islimit_shape_or_image) |Doğru olarak ayarlanırsa, bir çalışma sayfasındaki toplam ekran şekli/görüntü sayısının sınırlanıp sınırlanmayacağını ayarlar/alır,<br/> GridJ'ler, bir çalışma sayfasındaki toplam ekran şekli/görüntü boyutunu MaxShapeOrImageCount ile sınırlayacak<br/> varsayılan değer doğrudur.|
| [max_shape_or_image_count](/cells/python-net/tr/aspose.cellsgridjs/config/max_shape_or_image_count) | Aktif sayfanın içindeki toplam ekran şekli/görüntü sayısını ayarlar/alır, IslimitShapes=true olduğunda etkili olacaktır.<br/> varsayılan değer 100'dür.|
| [max_total_shape_or_image_count](/cells/python-net/tr/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Tüm çalışma kitabı içindeki toplam ekran şekli/görüntü sayısını ayarlar/alır, IslimitShapes=true olduğunda etkili olur.<br/> varsayılan değer 300'dür.|
| [max_shape_or_image_width_or_height](/cells/python-net/tr/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Bir şekil/görüntü için maksimum genişliği veya yüksekliği ayarlar/alır, GridJ'ler bundan daha büyük genişlik veya yüksekliğe sahip şekli/görüntüyü yok sayar, IslimitShapes=true olduğunda etkilenecektir.<br/> varsayılan değer 10000'dir.|
| [max_pdf_save_seconds](/cells/python-net/tr/aspose.cellsgridjs/config/max_pdf_save_seconds) | PDF olarak kaydederken zaman aşımına uğrayan maksimum saniyeyi ayarlar/alır.<br/> varsayılan değer 10'dur.|
| [ignore_empty_content](/cells/python-net/tr/aspose.cellsgridjs/config/ignore_empty_content) | Verileri, stili, birleştirilmiş hücreleri ve şekilleri içeren maksimum aralığın gösterilip gösterilmeyeceğini ayarlar/alır.<br/> son satır veya sütunda değeri ve formülü olmayan ancak özel stile sahip hücreler varsa<br/>o zaman bu vlaue doğru olduğunda bu satırı/sütunu göstermeyeceğiz.<br/> varsayılan değer true'dur.|
| [use_print_area](/cells/python-net/tr/aspose.cellsgridjs/config/use_print_area) |Çalışma sayfasında PrintArea için PageSetup ayarı olduğunda, kullanıcı arayüzü görüntüleme aralığı için PageSetup.PrintArea'nın kullanılıp kullanılmayacağını ayarlar/alır.<br/> varsayılan değer false'tur.|
| [load_time_out](/cells/python-net/tr/aspose.cellsgridjs/config/load_time_out) | Dosya yüklemenin maliyet süresi beklenenden daha uzun olduğunda, dosya yüklemede milisaniye cinsinden bir zaman aşımı kesintisi ayarlar/alır, istisna oluşturacaktır.<br/> varsayılan değer -1'dir; bu, zaman aşımı kesintisinin ayarlanmadığı anlamına gelir.|
| [show_chart_sheet](/cells/python-net/tr/aspose.cellsgridjs/config/show_chart_sheet) | Grafik çalışma sayfasının gösterilip gösterilmeyeceğini ayarlar/alır.<br/> varsayılan değer false'tur.|
| [page_size](/cells/python-net/tr/aspose.cellsgridjs/config/page_size) | Sayfalandırma yapılıp yapılmayacağını ayarlar/alır<br/> GridJ'ler, PageSize'a göre satır boyutunu sınırlandırır, PageSize -1 ise sayfalandırma yapmaz<br/> varsayılan değer -1'dir|
| [empty_sheet_max_row](/cells/python-net/tr/aspose.cellsgridjs/config/empty_sheet_max_row) | Boş bir çalışma sayfası için varsayılan maksimum satırı ayarlar/alır.<br/> varsayılan değer 12'dir.|
| [empty_sheet_max_col](/cells/python-net/tr/aspose.cellsgridjs/config/empty_sheet_max_col) | Boş bir çalışma sayfası için varsayılan maksimum sütunu ayarlar/alır.<br/> varsayılan değer 15'tir.|
| [picture_cache_directory](/cells/python-net/tr/aspose.cellsgridjs/config/picture_cache_directory) | Resimler için önbellek dizinini ayarlar/alır. (Bu, GridJsWorkbook.CacheImp null olduğunda etkili olacaktır)<br/> varsayılan yol FileCacheDirectory içindeki "_piccache" olacaktır.|
| [file_cache_directory](/cells/python-net/tr/aspose.cellsgridjs/config/file_cache_directory) |Elektronik tablo dosyası için önbellek dizinini ayarlar/alır.<br/> GridJ'leri kullanmadan önce onu belirli bir yola ayarlamamız gerekiyor.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_license](/cells/python-net/tr/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/tr/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Bileşeni lisanslar.|
| [set_font_folder](/cells/python-net/tr/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Yazı tipleri klasörünü ayarlar|
| [set_font_folders](/cells/python-net/tr/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Yazı tipi klasörlerini ayarlar|



###  Ayrıca bakınız
* modül [`aspose.cellsgridjs`](..)
