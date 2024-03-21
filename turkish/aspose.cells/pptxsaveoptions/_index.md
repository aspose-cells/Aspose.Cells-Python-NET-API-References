---
title: PptxSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1230
url: /tr/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions sınıfı
Pptx kaydetme seçeneklerini temsil eder.



**Miras:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



PptxSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/pptxsaveoptions/__init__/#) | Pptx kaydetme seçeneklerini temsil eder.|
| [__init__](/cells/python-net/tr/aspose.cells/pptxsaveoptions/__init__/#bool) | .pptx dosyasını kaydetme seçeneklerini temsil eder.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells/pptxsaveoptions/save_format) | Kaydetme dosyası formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells/pptxsaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boşaltın.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells/pptxsaveoptions/cached_file_folder) | Önbelleğe alınmış dosya klasörü bazı büyük verileri depolamak için kullanılır.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells/pptxsaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells/pptxsaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells/pptxsaveoptions/create_directory) | Doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells/pptxsaveoptions/sort_names) | Dosyayı kaydetmeden önce tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells/pptxsaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells/pptxsaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [warning_callback](/cells/python-net/tr/aspose.cells/pptxsaveoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [update_smart_art](/cells/python-net/tr/aspose.cells/pptxsaveoptions/update_smart_art) | Smart art ayarının güncellenip güncellenmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [default_font](/cells/python-net/tr/aspose.cells/pptxsaveoptions/default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/>Bu karakterleri göstermek için MingLiu veya MS Gotik gibi Varsayılan Yazı Tipini ayarlayın.<br/> Bu özellik ayarlanmazsa, Aspose.Cells bu unicode karakterleri göstermek için sistem varsayılan yazı tipini kullanır.|
| [check_workbook_default_font](/cells/python-net/tr/aspose.cells/pptxsaveoptions/check_workbook_default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/> Önce bu karakterleri göstermek amacıyla çalışma kitabının varsayılan yazı tipini kullanmayı denemek için bunu true olarak ayarlayın.|
| [check_font_compatibility](/cells/python-net/tr/aspose.cells/pptxsaveoptions/check_font_compatibility) | Metindeki her karakter için yazı tipi uyumluluğunun kontrol edilip edilmeyeceğini belirtir.|
| [is_font_substitution_char_granularity](/cells/python-net/tr/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |Yalnızca hücre yazı tipi uyumlu olmadığında karakterin yazı tipinin değiştirilip değiştirilmeyeceğini belirtir.|
| [one_page_per_sheet](/cells/python-net/tr/aspose.cells/pptxsaveoptions/one_page_per_sheet) | OnePagePerSheet true olursa, sonuçta bir sayfanın tüm içeriği yalnızca bir sayfaya yazdırılır.<br/> Pagesetup'ın kağıt boyutu ve diğer pagesetup ayarları geçersiz olacaktır.<br/> hâlâ geçerli olacaktır.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/tr/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | AllColumnsInOnePagePerSheet true ise, sonuçta bir sayfanın tüm sütun içeriğinin çıktısı yalnızca bir sayfaya çıkar.<br/> Pagesetup'ın kağıt boyutunun genişliği göz ardı edilecek ve diğer pagesetup ayarları göz ardı edilecektir.<br/> hâlâ geçerli olacaktır.|
| [ignore_error](/cells/python-net/tr/aspose.cells/pptxsaveoptions/ignore_error) | Oluşturma sırasında hatayı gizlemeniz gerekip gerekmediğini belirtir.<br/> Hata; şekil, resim, grafik oluşturma vb. hatalar olabilir.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/tr/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | Yazdırılacak bir şey olmadığında boş sayfa çıktısının alınıp alınmayacağını belirtir.|
| [page_index](/cells/python-net/tr/aspose.cells/pptxsaveoptions/page_index) | Kaydedilecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar.|
| [page_count](/cells/python-net/tr/aspose.cells/pptxsaveoptions/page_count) | Kaydedilecek sayfa sayısını alır veya ayarlar.|
| [printing_page_type](/cells/python-net/tr/aspose.cells/pptxsaveoptions/printing_page_type) | Hangi sayfaların yazdırılmayacağını belirtir.|
| [gridline_type](/cells/python-net/tr/aspose.cells/pptxsaveoptions/gridline_type) | Kılavuz çizgisi türünü alır veya ayarlar.|
| [text_cross_type](/cells/python-net/tr/aspose.cells/pptxsaveoptions/text_cross_type) | Metin genişliği hücre genişliğinden büyük olduğunda görüntülenen metin türünü alır veya ayarlar.|
| [default_edit_language](/cells/python-net/tr/aspose.cells/pptxsaveoptions/default_edit_language) | Varsayılan düzenleme dilini alır veya ayarlar.|
| [sheet_set](/cells/python-net/tr/aspose.cells/pptxsaveoptions/sheet_set) |Oluşturulacak sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/tr/aspose.cells/pptxsaveoptions/draw_object_event_handler) | İşleme sırasında DrawObject ve Bound'u almak için bu arayüzü uygular.|
| [page_saving_callback](/cells/python-net/tr/aspose.cells/pptxsaveoptions/page_saving_callback) | Sayfa kaydetme işleminin ilerlemesini kontrol edin/gösterin.|
| [emf_render_setting](/cells/python-net/tr/aspose.cells/pptxsaveoptions/emf_render_setting) | Emf meta dosyasını işlemeye yönelik ayar.|
| [ignore_hidden_rows](/cells/python-net/tr/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | Excel'i PowerPoint'e dönüştürürken gizli satırların göz ardı edilip edilmeyeceğini belirtir.|
| [adjust_font_size_for_row_type](/cells/python-net/tr/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | Satır yüksekliği küçükse, yazı tipi boyutunun ayarlanması gereken satır türünü temsil eder.|
| [export_view_type](/cells/python-net/tr/aspose.cells/pptxsaveoptions/export_view_type) | PowerPoint'e dışa aktarırken görüntü türünü alır ve ayarlar.<br/> Varsayılan dışa aktarma türü yazdırma olarak çalışmaktadır.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`PaginatedSaveOptions`](/cells/python-net/tr/aspose.cells/paginatedsaveoptions)
* sınıf [`PptxSaveOptions`](/cells/python-net/tr/aspose.cells/pptxsaveoptions)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
