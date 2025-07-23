---
title: LowCodeSaveOptionsProviderOfPlaceHolders sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 120
url: /tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders sınıfı
Bölünmüş parçaları dosyalara kaydeden kaydetme seçenekleri sağlamak için uygulama
ve sonuçtaki dosyanın yolu yer tutucularla tanımlanır.



**Miras:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



LowCodeSaveOptionsProviderOfPlaceHolders türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Belirtilen şablonlara göre kaydetme seçenekleri sağlamak için bir örneği örnekleştirir.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [sheet_index_offset](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Dosya yolunda kullanılan ile sayfanın indeksinin ofseti<br/> ve gerçek değeri ([`SplitPartInfo.sheet_index`](/cells/python-net/tr/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Dosya yolunda kullanılan ile bölünmüş parçanın dizininin ofseti<br/> ve gerçek değeri ([`SplitPartInfo.part_index`](/cells/python-net/tr/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Dosya yoluna her zaman sayfa indeksi veya isim ekleyin.<br/>Varsayılan değer false'tur, yani yalnızca bir sayfa olduğunda,<br/>sayfa dizini ve adı ve karşılık gelen önek ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> dosya yoluna eklenmeyecektir.|
| [build_path_with_split_part_always](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Dosya yoluna her zaman bölünmüş parça indeksi eklensin mi?<br/>Varsayılan değer false'tur, yani yalnızca bir bölünmüş parça olduğunda,<br/>bölünmüş parça dizini ve karşılık gelen önek ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> dosya yoluna eklenmeyecektir.|
| [sheet_name_prefix](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Çalışma sayfasının dizininin öneki.|
| [sheet_index_prefix](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Çalışma sayfasının dizininin öneki.|
| [split_part_prefix](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Bölünmüş parçanın indeksi için önek.|
| [save_options_template](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options)'de kaydetme seçeneklerinin örneğini oluşturma şablonu.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Şu anda bölünmüş parça için çıktı ayarlarının alınacağı kaydetme seçeneklerini alır.|
| [`finish(self, part)`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](..)
* sınıf [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
