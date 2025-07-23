---
title: SvgImageOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 130
url: /tr/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions sınıfı
Svg resmi oluşturma seçenekleri.



**Miras:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions)



SvgImageOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/__init__/#) | Kondüktör.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/save_format) | Çıktı dosyası biçim türünü alır veya ayarlar<br/> Tiff/XPS'i destekleyin|
| [print_with_status_dialog](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | PrintWithStatusDialog = true ise, geçerli yazdırma durumunu gösteren bir iletişim kutusu açılacaktır.<br/> aksi takdirde böyle bir iletişim kutusu gösterilmeyecektir.|
| [horizontal_resolution](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Oluşturulan görüntülerin yatay çözünürlüğünü inç başına nokta cinsinden alır veya ayarlar.|
| [vertical_resolution](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Oluşturulan görüntülerin dikey çözünürlüğünü inç başına nokta cinsinden alır veya ayarlar.|
| [tiff_compression](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/tiff_compression) | Sayfalar yalnızca `Tiff` biçiminde kaydedilirken uygulanacak sıkıştırma türünü alır veya ayarlar.|
| [tiff_color_depth](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Sayfalar yalnızca `Tiff` biçiminde kaydedilirken uygulanacak bit derinliğini alır veya ayarlar.|
| [tiff_binarization_method](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Görüntüleri 1 bpp biçimine dönüştürürken kullanılan yöntemi alır veya ayarlar<br/>[`ImageOrPrintOptions.image_type`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#image_type) Tiff olduğunda ve [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#tiff_compression) Ccitt3 veya Ccitt4'e eşit olduğunda.|
| [printing_page](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/printing_page) | Hangi sayfaların yazdırılmayacağını belirtir.|
| [quality](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/quality) | Oluşturulan görüntülerin kalitesini belirleyen bir değeri alır veya ayarlar<br/> yalnızca sayfalar `Jpeg` biçiminde kaydedilirken uygulanır. Varsayılan değer 100'dür|
| [image_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/image_type) | Oluşturulan görsellerin formatını alır veya ayarlar.<br/> varsayılan değer: PNG.|
| [is_cell_auto_fit](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Hücrelerin genişliğinin ve yüksekliğinin hücre değerine göre otomatik olarak uydurulup uydurulmadığını belirtir.<br/> Varsayılan değer false'tur.|
| [one_page_per_sheet](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | OnePagePerSheet true ise, bir sayfanın tüm içeriği sonuçta yalnızca bir sayfaya çıktı olarak verilir.<br/> Pagesetup'ın kağıt boyutu geçersiz olacak ve pagesetup'ın diğer ayarları<br/> hala geçerliliğini koruyacaktır.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | AllColumnsInOnePagePerSheet true ise, bir sayfanın tüm sütun içeriği sonuçta yalnızca bir sayfaya çıktı olarak verilir.<br/> Pagesetup'ın kağıt boyutunun genişliği geçersiz olacak ve pagesetup'ın diğer ayarları<br/> hala geçerliliğini koruyacaktır.|
| [chart_image_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/chart_image_type) | Dönüştürürken grafik görüntü türünü belirtin.<br/> varsayılan değer: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | SVG'deki gömülü resmin dosya adını belirtin.<br/> Bu, "c:\\xpsEmbedded" gibi bir dizine sahip tam yol olmalıdır.|
| [svg_fit_to_view_port](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | eğer bu özellik doğruysa, oluşturulan svg görüntü portuna sığacaktır.|
| [svg_css_prefix](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |SVG'deki css adının önekini alır ve ayarlar, varsayılan değer boş dizedir.|
| [only_area](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/only_area) | Bu özellik doğruysa, bir Alan çıktısı verilecek ve hiçbir ölçek etkili olmayacaktır.|
| [text_rendering_hint](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Metin oluşturmanın kalitesini belirtir.<br/> Varsayılan değer TextRenderingHint.SystemDefault'dur|
| [smoothing_mode](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Çizgilere, eğrilere ve doldurulmuş alanların kenarlarına yumuşatma (antialiasing) uygulanıp uygulanmayacağını belirtir.<br/> Varsayılan değer SmoothingMode.None'dur|
| [transparent](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/transparent) | Oluşturulan görüntünün arka planının şeffaf olup olmayacağını belirtir.|
| [pixel_format](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/pixel_format) | Oluşturulan görsellerin piksel biçimini alır veya ayarlar.|
| [is_font_substitution_char_granularity](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Hücre yazı tipi karakterle uyumlu olmadığında yalnızca karakterin yazı tipinin değiştirilip değiştirilmeyeceğini belirtir.|
| [page_index](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/page_index) | Kaydedilecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar.|
| [page_count](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/page_count) | Kaydedilecek sayfa sayısını alır veya ayarlar.|
| [is_optimized](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/is_optimized) | Çıkış elemanlarının optimize edilip edilmeyeceğini belirtir.|
| [default_font](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>Pdf, resim içerisinde blok olarak gözükebilir.<br/>Bu karakterleri göstermek için MingLiu veya MS Gothic gibi DefaultFont'u ayarlayın.<br/>Bu özellik ayarlanmazsa, Aspose.Cells bu unicode karakterlerini göstermek için sistemin varsayılan yazı tipini kullanacaktır.|
| [check_workbook_default_font](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>Pdf, resim içerisinde blok olarak gözükebilir.<br/> Bu karakterleri önce göstermek için çalışma kitabının varsayılan yazı tipini kullanmayı denemek üzere bunu doğru olarak ayarlayın.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Yazdırılacak bir şey olmadığında boş bir sayfa çıktısı alınıp alınmayacağını belirtir.|
| [gridline_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/gridline_type) | Izgara tipini alır veya ayarlar.|
| [gridline_color](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/gridline_color) | Izgara renginin alınması veya ayarlanması.|
| [text_cross_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/text_cross_type) | Metin genişliği hücre genişliğinden büyük olduğunda görüntülenecek metin türünü alır veya ayarlar.|
| [emf_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/emf_type) | Metafile'ın biçimini belirten bir EmfType alır veya ayarlar.<br/> Varsayılan değer EmfPlusDual'dır.|
| [default_edit_language](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/default_edit_language) | Varsayılan düzenleme dilini alır veya ayarlar.|
| [sheet_set](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/sheet_set) | İşlenecek sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Kaynak dosyada Emf meta dosyalarının oluşturulması için ayar.|
| [custom_render_settings](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/custom_render_settings) | İşleme sırasında özel ayarları alır veya ayarlar.|
| [fit_to_view_port](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | eğer bu özellik doğruysa, oluşturulan svg görüntü portuna sığacaktır.|
| [css_prefix](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/css_prefix) |SVG'deki css adının önekini alır ve ayarlar, varsayılan değer boş dizedir.|
| [embedded_font_type](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Svg'ye gömülen yazı tipinin türünü alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Görüntünün istenilen genişliğini ve yüksekliğini ayarlar.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Görüntünün istenilen genişliğini ve yüksekliğini ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
* sınıf [`ImageOrPrintOptions`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions)
* sınıf [`SvgImageOptions`](/cells/python-net/tr/aspose.cells.rendering/svgimageoptions)
