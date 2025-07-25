---
title: LowCodeSaveOptionsProviderOfAssembling sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling sınıfı
Bölünmüş parçaları dosyalara kaydeden kaydetme seçenekleri sağlamak için uygulama
ve ortaya çıkan dosyanın yolu şu şekilde adlandırılır (dizinleri içerebilir):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+SheetIndex(veya SheetName)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Miras:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



LowCodeSaveOptionsProviderOfAssembling türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | LowCodeSaveOptionsProviderOfAssembling'in yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [path_header](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Dosya yolunun başlık kısmı (sayfanın içeriği eklenmeden ve bölünmüş kısımdan önce).|
| [path_tail](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Dosya yolunun sıra numaralarından sonraki kısmı.<br/> Dosya adının uzantısını içermesi gerekir.|
| [use_sheet_name](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Dosya yolunu sayfa dizini yerine sayfa adıyla mı oluşturur? Varsayılan değer false'tur.|
| [sheet_prefix](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Çalışma sayfasının dizininin öneki.|
| [split_part_prefix](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Bölünmüş parçanın indeksi için önek.|
| [sheet_index_offset](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Dosya yolunda kullanılan ile sayfanın indeksinin ofseti<br/> ve gerçek değeri ([`SplitPartInfo.sheet_index`](/cells/python-net/tr/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Dosya yolunda kullanılan ile bölünmüş parçanın dizininin ofseti<br/> ve gerçek değeri ([`SplitPartInfo.part_index`](/cells/python-net/tr/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Dosya yoluna her zaman sayfa indeksi veya isim ekleyin.<br/>Varsayılan değer false'tur, yani yalnızca bir sayfa olduğunda,<br/> Sayfa dizini (veya adı) ve karşılık gelen önek dosya yoluna eklenmeyecektir.|
| [build_path_with_split_part_always](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Dosya yoluna her zaman bölünmüş parça indeksi eklensin mi?<br/>Varsayılan değer false'tur, yani yalnızca bir bölünmüş parça olduğunda,<br/> bölünmüş parça dizini ve karşılık gelen önek dosya yoluna eklenmeyecektir.|
| [save_options_template](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options)'de kaydetme seçeneklerinin örneğini oluşturma şablonu.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Şu anda bölünmüş parça için çıktı ayarlarının alınacağı kaydetme seçeneklerini alır.|
| [`finish(self, part)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](..)
* sınıf [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
