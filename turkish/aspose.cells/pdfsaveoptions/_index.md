---
title: PdfSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1220
url: /tr/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions sınıfı
Pdf dosyasını kaydetme seçeneklerini temsil eder.



**Miras:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



PdfSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/pdfsaveoptions/__init__/#) | Pdf dosyasını kaydetme seçeneklerini oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells/pdfsaveoptions/save_format) | Kaydetme dosyası formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells/pdfsaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boşaltın.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells/pdfsaveoptions/cached_file_folder) | Önbelleğe alınmış dosya klasörü bazı büyük verileri depolamak için kullanılır.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells/pdfsaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells/pdfsaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells/pdfsaveoptions/create_directory) | Doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells/pdfsaveoptions/sort_names) | Dosyayı kaydetmeden önce tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells/pdfsaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells/pdfsaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [warning_callback](/cells/python-net/tr/aspose.cells/pdfsaveoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [update_smart_art](/cells/python-net/tr/aspose.cells/pdfsaveoptions/update_smart_art) | Smart art ayarının güncellenip güncellenmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [default_font](/cells/python-net/tr/aspose.cells/pdfsaveoptions/default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/>Bu karakterleri göstermek için MingLiu veya MS Gotik gibi Varsayılan Yazı Tipini ayarlayın.<br/> Bu özellik ayarlanmazsa, Aspose.Cells bu unicode karakterleri göstermek için sistem varsayılan yazı tipini kullanır.|
| [check_workbook_default_font](/cells/python-net/tr/aspose.cells/pdfsaveoptions/check_workbook_default_font) | Excel'deki karakterler Unicode olduğunda ve hücre stilinde doğru yazı tipiyle ayarlanmadığında,<br/>PDF, resimde blok olarak görünebilirler.<br/> Önce bu karakterleri göstermek amacıyla çalışma kitabının varsayılan yazı tipini kullanmayı denemek için bunu true olarak ayarlayın.|
| [check_font_compatibility](/cells/python-net/tr/aspose.cells/pdfsaveoptions/check_font_compatibility) | Metindeki her karakter için yazı tipi uyumluluğunun kontrol edilip edilmeyeceğini belirtir.|
| [is_font_substitution_char_granularity](/cells/python-net/tr/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |Yalnızca hücre yazı tipi uyumlu olmadığında karakterin yazı tipinin değiştirilip değiştirilmeyeceğini belirtir.|
| [one_page_per_sheet](/cells/python-net/tr/aspose.cells/pdfsaveoptions/one_page_per_sheet) | OnePagePerSheet true olursa, sonuçta bir sayfanın tüm içeriği yalnızca bir sayfaya yazdırılır.<br/> Pagesetup'ın kağıt boyutu ve diğer pagesetup ayarları geçersiz olacaktır.<br/> hâlâ geçerli olacaktır.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/tr/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | AllColumnsInOnePagePerSheet true ise, sonuçta bir sayfanın tüm sütun içeriğinin çıktısı yalnızca bir sayfaya çıkar.<br/> Pagesetup'ın kağıt boyutunun genişliği göz ardı edilecek ve diğer pagesetup ayarları göz ardı edilecektir.<br/> hâlâ geçerli olacaktır.|
| [ignore_error](/cells/python-net/tr/aspose.cells/pdfsaveoptions/ignore_error) | Oluşturma sırasında hatayı gizlemeniz gerekip gerekmediğini belirtir.<br/> Hata; şekil, resim, grafik oluşturma vb. hatalar olabilir.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/tr/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Yazdırılacak bir şey olmadığında boş sayfa çıktısının alınıp alınmayacağını belirtir.|
| [page_index](/cells/python-net/tr/aspose.cells/pdfsaveoptions/page_index) | Kaydedilecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar.|
| [page_count](/cells/python-net/tr/aspose.cells/pdfsaveoptions/page_count) | Kaydedilecek sayfa sayısını alır veya ayarlar.|
| [printing_page_type](/cells/python-net/tr/aspose.cells/pdfsaveoptions/printing_page_type) | Hangi sayfaların yazdırılmayacağını belirtir.|
| [gridline_type](/cells/python-net/tr/aspose.cells/pdfsaveoptions/gridline_type) | Kılavuz çizgisi türünü alır veya ayarlar.|
| [text_cross_type](/cells/python-net/tr/aspose.cells/pdfsaveoptions/text_cross_type) | Metin genişliği hücre genişliğinden büyük olduğunda görüntülenen metin türünü alır veya ayarlar.|
| [default_edit_language](/cells/python-net/tr/aspose.cells/pdfsaveoptions/default_edit_language) | Varsayılan düzenleme dilini alır veya ayarlar.|
| [sheet_set](/cells/python-net/tr/aspose.cells/pdfsaveoptions/sheet_set) |Oluşturulacak sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/tr/aspose.cells/pdfsaveoptions/draw_object_event_handler) | İşleme sırasında DrawObject ve Bound'u almak için bu arayüzü uygular.|
| [page_saving_callback](/cells/python-net/tr/aspose.cells/pdfsaveoptions/page_saving_callback) | Sayfa kaydetme işleminin ilerlemesini kontrol edin/gösterin.|
| [emf_render_setting](/cells/python-net/tr/aspose.cells/pdfsaveoptions/emf_render_setting) | Emf meta dosyasını işlemeye yönelik ayar.|
| [embed_standard_windows_fonts](/cells/python-net/tr/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | True type yazı tiplerini gömmek için True.<br/>Yalnızca 32-127 arası ASCII karakterlerini etkiler.<br/>127'den büyük karakter kodları için yazı tipleri her zaman gömülüdür.<br/>Yazı tipleri her zaman PDF/A-1a, PDF/A-1b standardına göre gömülüdür.<br/> Varsayılan doğrudur.|
| [bookmark](/cells/python-net/tr/aspose.cells/pdfsaveoptions/bookmark) | [`PdfBookmarkEntry`](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry) nesnesini alır ve ayarlar.|
| [compliance](/cells/python-net/tr/aspose.cells/pdfsaveoptions/compliance) | Çıktı belgeleri için PDF standartlarına uygunluk düzeyini alır veya ayarlar.|
| [security_options](/cells/python-net/tr/aspose.cells/pdfsaveoptions/security_options) | Xls2pdf sonucunda güvenliğe ihtiyaç duyulduğunda bu seçeneği ayarlayın.|
| [image_type](/cells/python-net/tr/aspose.cells/pdfsaveoptions/image_type) |Grafiği ve şekli dönüştürürken görüntü türünü temsil eder.|
| [calculate_formula](/cells/python-net/tr/aspose.cells/pdfsaveoptions/calculate_formula) | Formüllerin pdf dosyasını kaydetmeden önce hesaplanıp hesaplanmayacağını belirtir.|
| [pdf_compression](/cells/python-net/tr/aspose.cells/pdfsaveoptions/pdf_compression) | Sıkıştırma algoritmasını belirtin|
| [created_time](/cells/python-net/tr/aspose.cells/pdfsaveoptions/created_time) | PDF belgesinin oluşturulma zamanını alır ve ayarlar.|
| [producer](/cells/python-net/tr/aspose.cells/pdfsaveoptions/producer) | Oluşturulan pdf belgesinin üreticisini alır ve ayarlar.|
| [optimization_type](/cells/python-net/tr/aspose.cells/pdfsaveoptions/optimization_type) | PDF optimizasyon türünü alır ve ayarlar.|
| [custom_properties_export](/cells/python-net/tr/aspose.cells/pdfsaveoptions/custom_properties_export) | [`CustomDocumentPropertyCollection`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection)'in PDF dosyasına aktarılma şeklini belirleyen bir değer alır veya ayarlar. Varsayılan değer Yok'tur.|
| [export_document_structure](/cells/python-net/tr/aspose.cells/pdfsaveoptions/export_document_structure) | Belge yapısının dışa aktarılıp aktarılmayacağını belirtir.|
| [display_doc_title](/cells/python-net/tr/aspose.cells/pdfsaveoptions/display_doc_title) | Pencerenin başlık çubuğunun belge başlığını görüntüleyip görüntülemeyeceğini belirtir.|
| [font_encoding](/cells/python-net/tr/aspose.cells/pdfsaveoptions/font_encoding) | PDF olarak gömülü yazı tipi kodlamasını alır veya ayarlar.|
| [watermark](/cells/python-net/tr/aspose.cells/pdfsaveoptions/watermark) | Çıktıya filigran alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_image_resample](/cells/python-net/tr/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | Yeniden örnekleme görüntülerinin ve jpeg kalitesinin istenen ÜFE'sini (inç başına piksel) ayarlar.<br/> Tüm resimler belirtilen kalite ayarıyla JPEG'e dönüştürülecek,<br/> ve belirtilen ÜFE'den (inç başına piksel) daha büyük görüntüler yeniden örneklenecektir.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`CustomDocumentPropertyCollection`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection)
* sınıf [`PaginatedSaveOptions`](/cells/python-net/tr/aspose.cells/paginatedsaveoptions)
* sınıf [`PdfBookmarkEntry`](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry)
* sınıf [`PdfSaveOptions`](/cells/python-net/tr/aspose.cells/pdfsaveoptions)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
