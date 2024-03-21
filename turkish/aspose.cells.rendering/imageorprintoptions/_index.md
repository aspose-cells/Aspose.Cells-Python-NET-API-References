---
title: ImageOrPrintOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions sınıfı
Çalışma sayfasını görüntülere dönüştürürken, çalışma sayfasını yazdırırken veya grafiği görüntüye dönüştürürken seçenekleri belirtmenize olanak tanır.



ImageOrPrintOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/__init__/#) | ImageOrPrintOptions'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/save_format) | Çıktı dosyası formatı türünü alır veya ayarlar<br/> Destek Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | PrintWithStatusDialog = true ise geçerli yazdırma durumunu gösteren bir iletişim kutusu olacaktır.<br/>aksi takdirde böyle bir diyalog gösterilmez.|
| [horizontal_resolution](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Oluşturulan görüntüler için yatay çözünürlüğü inç başına nokta cinsinden alır veya ayarlar.<br/> Emf formatındaki görüntüler dışında görüntü oluşturma yöntemini uygular.|
| [vertical_resolution](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Oluşturulan görüntüler için dikey çözünürlüğü inç başına nokta cinsinden alır veya ayarlar.<br/> Emf formatındaki görüntü dışında görüntü oluşturma yöntemini uygular.|
| [tiff_compression](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Yalnızca sayfaları `Tiff` biçiminde kaydederken uygulanacak sıkıştırma türünü alır veya ayarlar.|
| [tiff_color_depth](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Yalnızca sayfaları `Tiff` biçiminde kaydederken uygulanacak bit derinliğini alır veya ayarlar.|
| [tiff_binarization_method](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Görüntüleri 1 bpp biçimine dönüştürürken kullanılan yöntemi alır veya ayarlar<br/> [`ImageOrPrintOptions.image_type`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#image_type), Tiff olduğunda ve [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#tiff_compression), Ccitt3 veya Ccitt4'e eşit olduğunda.|
| [printing_page](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/printing_page) | Hangi sayfaların yazdırılmayacağını belirtir.|
| [quality](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/quality) | Oluşturulan görüntülerin kalitesini belirleyen bir değer alır veya ayarlar<br/> yalnızca sayfaları `Jpeg` biçiminde kaydederken uygulamak için. Varsayılan değer 100'dür|
| [image_type](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/image_type) | Oluşturulan görüntülerin formatını alır veya ayarlar.<br/> varsayılan değer: PNG.|
| [is_cell_auto_fit](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Hücrelerin genişliğinin ve yüksekliğinin hücre değerine göre otomatik olarak sığdırılıp sığdırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [one_page_per_sheet](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | OnePagePerSheet true olursa, sonuçta bir sayfanın tüm içeriği yalnızca bir sayfaya yazdırılır.<br/> Pagesetup'ın kağıt boyutu ve diğer pagesetup ayarları geçersiz olacaktır.<br/> hâlâ geçerli olacaktır.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | AllColumnsInOnePagePerSheet true ise, sonuçta bir sayfanın tüm sütun içeriğinin çıktısı yalnızca bir sayfaya çıkar.<br/>Pagesetup'ın kağıt boyutunun genişliği geçersiz olacak ve pagesetup'ın diğer ayarları geçersiz olacaktır.<br/> hâlâ geçerli olacaktır.|
| [draw_object_event_handler](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) | İşleme sırasında DrawObject ve Bound'u almak için bu arayüzü uygular.|
| [chart_image_type](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Dönüştürme sırasında grafik görüntü türünü belirtin.<br/> varsayılan değer: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Gömülü görüntünün dosya adını svg'de belirtin.<br/> Bu, "c:\\xpsEmbedded" gibi bir dizine sahip tam yol olmalıdır|
| [svg_fit_to_view_port](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | bu özellik doğruysa oluşturulan svg, görüntüleme bağlantı noktasına sığacaktır.|
| [only_area](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/only_area) | Bu özellik true ise, bir Alan çıktısı alınacak ve hiçbir ölçek etkili olmayacaktır.|
| [text_rendering_hint](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Metin oluşturmanın kalitesini belirtir.<br/> Varsayılan değer TextRenderingHint.SystemDefault'dur|
| [smoothing_mode](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Çizgilere, eğrilere ve doldurulmuş alanların kenarlarına yumuşatma (kenar yumuşatma) uygulanıp uygulanmayacağını belirtir.<br/> Varsayılan değer: SmoothingMode.None|
| [transparent](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/transparent) | Oluşturulan görüntünün arka planının şeffaf olup olmayacağını belirtir.|
| [pixel_format](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/pixel_format) | Oluşturulan görüntüler için piksel biçimini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [page_saving_callback](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/page_saving_callback) | Sayfa kaydetme işleminin ilerlemesini kontrol edin/gösterin.|
| [is_font_substitution_char_granularity](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |Yalnızca hücre yazı tipi uyumlu olmadığında karakterin yazı tipinin değiştirilip değiştirilmeyeceğini belirtir.|
| [page_index](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/page_index) | Kaydedilecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar.|
| [page_count](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/page_count) | Kaydedilecek sayfa sayısını alır veya ayarlar.|
| [is_optimized](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/is_optimized) | Çıkış öğelerinin optimize edilip edilmeyeceğini belirtir.|
| [default_font](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/>Bu karakterleri göstermek için MingLiu veya MS Gotik gibi Varsayılan Yazı Tipini ayarlayın.<br/> Bu özellik ayarlanmazsa, Aspose.Cells bu unicode karakterleri göstermek için sistem varsayılan yazı tipini kullanır.|
| [check_workbook_default_font](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/> Önce bu karakterleri göstermek amacıyla çalışma kitabının varsayılan yazı tipini kullanmayı denemek için bunu true olarak ayarlayın.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Yazdırılacak bir şey olmadığında boş sayfa çıktısının alınıp alınmayacağını belirtir.|
| [gridline_type](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/gridline_type) | Kılavuz çizgisi türünü alır veya ayarlar.|
| [text_cross_type](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Metin genişliği hücre genişliğinden büyük olduğunda görüntülenen metin türünü alır veya ayarlar.|
| [emf_type](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/emf_type) | Meta dosyasının biçimini belirten bir EmfType alır veya ayarlar.<br/>Varsayılan değer EmfPlusDual'dır.|
| [default_edit_language](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Varsayılan düzenleme dilini alır veya ayarlar.|
| [sheet_set](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/sheet_set) |Oluşturulacak sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Emf meta dosyasını işlemeye yönelik ayar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_desired_size](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Görüntünün istenen genişliğini ve yüksekliğini ayarlar.|
| [set_desired_size](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Görüntünün istenen genişliğini ve yüksekliğini ayarlar.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
