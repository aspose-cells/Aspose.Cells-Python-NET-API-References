---
title: EbookSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions sınıfı
E-kitap dosyasını kaydetme seçeneklerini temsil eder.



**Miras:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



EbookSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/__init__/#) | E-kitap dosyasını kaydetmek için seçenekler oluşturur.|
| [`__init__(self, save_format)`](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/__init__/#aspose.cells.saveformat) | E-kitap dosyasını kaydetmek için seçenekler oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/save_format) | Kaydetme dosyasının formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boş hale getirin.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | Veri önbelleği olarak kullanılabilecek geçici dosyalar için klasör.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/create_directory) | Eğer doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/sort_names) |Dosyayı kaydetmeden önce tanımlanmış isimlerin sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici olarak tanımlanmış adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/> 32K'dan uzun bir değer girdiğinizde, bu değer kesilecektir.|
| [update_smart_art](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Akıllı sanat ayarının güncellenip güncellenmediğini gösterir.<br/> Varsayılan değer false'tur.|
| [encrypt_document_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/encrypt_document_properties) | .xls dosyası olarak kaydederken belge özelliklerinin şifrelenip şifrelenmeyeceğini belirtir.<br/> Varsayılan değer doğrudur.|
| [ignore_invisible_shapes](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Görünmeyen şekillerin dışa aktarılıp aktarılmayacağını belirtin|
| [page_title](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/page_title) | HTML sayfasının başlığı.<br/> Sadece html akışına kaydetmek için.|
| [attached_files_directory](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | Eklenen dosyaların kaydedileceği dizin.<br/> Sadece html akışına kaydetmek için.|
| [attached_files_url_prefix](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | HTML dosyasındaki resim gibi ekli dosyaların URL önekini belirtin.<br/> Sadece html akışına kaydetmek için.|
| [default_font_name](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/default_font_name) | HTML'yi dışa aktarmak için varsayılan yazı tipi adını belirtin, yazı tipi stili mevcut olmadığında varsayılan yazı tipi kullanılacaktır,<br/>Bu özellik boşsa, Aspose.Cells orijinal yazı tipiyle aynı aileye sahip evrensel yazı tipini kullanacaktır.<br/> varsayılan değer null'dır.|
| [add_generic_font](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/add_generic_font) |CSS font-family'e genel bir yazı tipi eklenip eklenmeyeceğini belirtir.<br/> Varsayılan değer doğrudur|
| [worksheet_scalable](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Dosyayı HTML olarak kaydederken çalışma sayfası yakınlaştırma düzeyine göre HTML'yi yakınlaştırıp uzaklaştırmayı belirtir, varsayılan değer false'tur.|
| [is_export_comments](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_export_comments) | Dosyayı html'e kaydederken yorumların dışa aktarılıp aktarılmayacağını belirtir, varsayılan değer false'tur.|
| [export_comments_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Yorumların html dosyalarına aktarılma türünü temsil eder.|
| [disable_downlevel_revealed_comments](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Dosyayı HTML'ye aktarırken Downlevel-revealed koşullu yorumların devre dışı bırakılıp bırakılmayacağını belirtir, varsayılan değer false'tur.|
| [is_exp_image_to_temp_dir](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Resim dosyalarının geçici dizine aktarılıp aktarılmayacağını belirtir.<br/> Sadece html akışına kaydetmek için.|
| [image_scalable](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/image_scalable) | Görüntü genişliğini tanımlamak için ölçeklenebilir bir birim kullanılıp kullanılmayacağını belirtir<br/>Sütun genişliğini tanımlamak için ölçeklenebilir birim kullanıldığında.<br/> Varsayılan değer doğrudur.|
| [width_scalable](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/width_scalable) | Sütun genişliğinin ölçek biriminde HTML'e aktarılıp aktarılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [export_single_tab](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Dosyada yalnızca bir çalışma sayfası olduğunda tek sekmenin dışa aktarılıp aktarılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [export_images_as_base64](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Görüntülerin Base64 formatında HTML, MHTML veya EPUB olarak kaydedilip kaydedilmeyeceğini belirtir.|
| [export_active_worksheet_only](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Yalnızca etkin çalışma sayfasının HTML dosyasına aktarılacağını belirtir.<br/>Eğer doğruysa, yalnızca etkin çalışma sayfası html dosyasına aktarılacaktır;<br/>Eğer false ise tüm çalışma kitabı html dosyasına aktarılacaktır.<br/> Varsayılan değer false'tur.|
| [export_print_area_only](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_print_area_only) |Yalnızca yazdırma alanının HTML dosyasına aktarılacağını belirtir. Varsayılan değer false'tur.|
| [export_area](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_area) | Geçerli etkin Çalışma Sayfasının dışa aktarılan Hücre Alanını alır veya ayarlar.<br/>Bu özniteliği ayarlarsanız, geçerli etkin Çalışma Sayfasının yazdırma alanı atlanacaktır.<br/> Dosyayı html olarak kaydederken sadece belirtilen alan dışarı aktarılacaktır.|
| [parse_html_tag_in_cell](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) | Hücredeki html etiketinin (örneğin `<div></div>`) hücre değeri olarak ayrıştırılıp ayrıştırılmayacağını veya olduğu gibi korunacağını belirtir.<br/> Varsayılan değer doğrudur.|
| [html_cross_string_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Bir Excel dosyasını HTML formatında kaydederken, çapraz hücre dizesinin MS Excel ile aynı şekilde görüntülenip görüntülenmeyeceğini belirtir.<br/>Varsayılan olarak değer Varsayılan'dır, bu nedenle hücreler arası dizeler için Aspose.Cells ile MS Excel tarafından oluşturulan html dosyaları arasında çok az fark vardır.<br/> Ancak büyük html dosyaları oluşturma performansı için değeri Cross olarak ayarlamak, Default veya Fit2Cell olarak ayarlamaktan birkaç kat daha hızlı olacaktır.|
| [hidden_col_display_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Excel'de gizli sütun (bu sütunun genişliği 0'dır), bunu html formatına kaydetmeden önce,<br/>HtmlHiddenColDisplayType "Kaldır" ise, gizli sütun çıktı olarak verilmez,<br/> eğer değer "Gizli" ise, sütun çıktı olarak verilir, ancak gizlidir, varsayılan değer "Gizli"dir|
| [hidden_row_display_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Excel'de gizli satır (bu satırın yüksekliği 0'dır), bunu html formatına kaydetmeden önce,<br/>HtmlHiddenRowDisplayType "Kaldır" ise, gizli satır çıktı olarak verilmez,<br/>eğer değer "Gizli" ise, satır çıktı olarak verilir, ancak gizlidir, varsayılan değer "Gizli"dir|
| [encoding](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/encoding) | Ayarlanmamışsa, varsayılan kodlama türü olarak Encoding.UTF8'i kullanın.|
| [image_options](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/image_options) | Dışa aktarmadan önce ImageOrPrintOptions nesnesini alın|
| [save_as_single_file](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Html'nin tek dosya olarak kaydedilip kaydedilmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [show_all_sheets](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Tek bir HTML dosyası olarak kaydedildiğinde tüm sayfaların gösterilip gösterilmeyeceğini belirtir.|
| [export_page_headers](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Sayfa başlıklarının dışa aktarılıp aktarılmayacağını belirtir.|
| [export_page_footers](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Sayfa başlıklarının dışa aktarılıp aktarılmayacağını belirtir.|
| [export_hidden_worksheet](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Gizli çalışma sayfası içeriğinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer doğrudur.|
| [presentation_preference](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Sunum tercihinin html veya mht dosyası olduğunu belirtir.<br/>Varsayılan değer false'tur.<br/> Daha güzel bir sunum elde etmek istiyorsanız lütfen değeri true olarak ayarlayın.|
| [cell_css_prefix](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Css isminin ön ekini alır ve ayarlar, varsayılan değer "" dir.|
| [table_css_id](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/table_css_id) | tr,col,td vb. gibi CSS tipinin önekini alır ve ayarlar, bunlar tablo öğesinde bulunur<br/> Belirli TableCssId özniteliğine sahip. Varsayılan değer ""'dir.|
| [is_full_path_link](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_full_path_link) |sheet00x.htm,filelist.xml ve tabstrip.htm'de tam yol bağlantısının kullanılıp kullanılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [export_worksheet_css_separately](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) | Çalışma sayfasının css'sini ayrı ayrı dışarı aktarmak isteyip istemediğinizi belirtir. Varsayılan değer false'tur.|
| [export_similar_border_style](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Tarayıcılar tarafından desteklenmeyen kenarlık stilinin dışa aktarılıp aktarılmayacağını belirtir.<br/>Eğer html veya mht dosyasını excel'e aktarmak istiyorsanız lütfen varsayılan değeri koruyun.<br/> Varsayılan değer false'tur.|
| [merge_empty_td_forcely](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Dosyayı HTML'e aktarırken boş TD öğesinin zorunlu olarak birleştirilip birleştirilmeyeceğini belirtir.<br/> Değeri true olarak ayarlandığında HTML dosyasının boyutu önemli ölçüde azalacaktır. Varsayılan değer false'tur.<br/> Html dosyasını Excel'e aktarmak veya dosyayı HTML'e kaydederken mükemmel ızgara çizgileri dışa aktarmak istiyorsanız,<br/> Lütfen varsayılan değeri koruyun.|
| [merge_empty_td_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Bitişik boş hücreleri (boş td öğeleri) birleştirme seçeneği<br/> Varsayılan değer MergeEmptyTdType.Default'dur.|
| [export_cell_coordinate](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Dosyayı HTML'e kaydederken boş olmayan hücrelerin Excel koordinatlarının dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer false'tur.<br/> Çıktı html'ini Excel'e aktarmak istiyorsanız lütfen varsayılan değeri koruyun.|
| [export_extra_headings](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Metnin uzunluğu maksimum görüntüleme sütunundan uzun olduğunda ekstra başlıkların dışa aktarılıp aktarılmayacağını belirtir.<br/> Varsayılan değer false'tur. HTML dosyasını Excel'e aktarmak istiyorsanız, lütfen varsayılan değeri koruyun.|
| [export_headings](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_headings) |HTML dosyalarına kaydedilirken sayfanın satır ve sütun başlıklarının dışa aktarılıp aktarılmayacağını belirtir.|
| [export_row_column_headings](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |HTML dosyalarına kaydedilirken sayfanın satır ve sütun başlıklarının dışa aktarılıp aktarılmayacağını belirtir.|
| [export_formula](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_formula) | Dosyayı HTML'e kaydederken formülün dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer true'dur.<br/> Çıktı html'ini Excel'e aktarmak istiyorsanız lütfen varsayılan değeri koruyun.|
| [add_tooltip_text](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Veriler tam olarak görüntülenemediğinde araç ipucu metninin eklenip eklenmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [export_grid_lines](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Izgara çizgilerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer false'tur.|
| [export_bogus_row_data](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Sahte alt satır verilerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer true'dur. HTML veya mht dosyasını içe aktarmak istiyorsanız<br/> Excel'de başarılı olmak için lütfen varsayılan değeri koruyun.|
| [exclude_unused_styles](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Kullanılmayan stillerin hariç tutulup tutulmayacağını belirtir.<br/>Oluşturulan HTML dosyaları için kullanılmayan stilleri hariç tutmak dosya boyutunu küçültebilir<br/>Görsel efektleri etkilemeden. Bu nedenle bu özelliğin varsayılan değeri true'dur.<br/>Kullanıcının, oluşturulan HTML için çalışma kitabındaki tüm stilleri tutması gerekiyorsa (örneğin, kullanıcının<br/> (daha sonra oluşturulan HTML'den çalışma kitabını geri yüklemesi gerekir), lütfen bu özelliği false olarak ayarlayın.|
| [export_document_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer doğrudur. İçe aktarmak istiyorsanız<br/> html veya mht dosyasını excel'e aktarırken lütfen varsayılan değeri koruyun.|
| [export_worksheet_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Çalışma sayfası özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer doğrudur. İçe aktarmak istiyorsanız<br/> html veya mht dosyasını excel'e aktarırken lütfen varsayılan değeri koruyun.|
| [export_workbook_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Çalışma kitabı özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer doğrudur. İçe aktarmak istiyorsanız<br/> html veya mht dosyasını excel'e aktarırken lütfen varsayılan değeri koruyun.|
| [export_frame_scripts_and_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Çerçeve betiklerinin ve belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer true'dur. HTML veya mht dosyasını içe aktarmak istiyorsanız<br/> Excel'de başarılı olmak için lütfen varsayılan değeri koruyun.|
| [export_data_options](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/export_data_options) | Html dosya verilerinin dışa aktarılması kuralını belirtir. Varsayılan değer All'dur.|
| [link_target_type](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/link_target_type) | `<a>` bağlantısındaki hedef niteliğinin türünü belirtir. Varsayılan değer HtmlLinkTargetType.Parent'tır.|
| [is_ie_compatible](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | HTML çıktısının IE tarayıcısıyla uyumlu olup olmadığını belirtir.<br/> Varsayılan değer yanlıştır|
| [format_data_ignore_column_width](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Sütun taştığında hücrenin tüm biçimlendirilmiş verilerinin gösterilip gösterilmeyeceğini belirtir.<br/>Eğer doğruysa sütun genişliğini yoksayarsınız ve hücrenin tüm verileri dışarı aktarılır.<br/>Eğer false ise veriler Excel'deki gibi dışarı aktarılacaktır.<br/> Varsayılan değer false'tur.|
| [calculate_formula](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Html dosyasını kaydetmeden önce formüllerin hesaplanıp hesaplanmayacağını belirtir.|
| [is_js_browser_compatible](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | JavaScript'in JavaScript'i desteklemeyen tarayıcılarla uyumlu olup olmadığını gösterir.<br/> Varsayılan değer doğrudur.|
| [is_mobile_compatible](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | HTML çıktısının mobil cihazlarla uyumlu olup olmadığını gösterir.<br/> Varsayılan değer false'tur.|
| [css_styles](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/css_styles) | Biçimlendirici için ek CSS stillerini alır veya ayarlar.<br/>Sadece [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/tr/aspose.cells/htmlsaveoptions#save_as_single_file) True olduğunda çalışır.<br/><br/> CssStyles="body { dolgu: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/hide_overflow_wrapped_text) |Hücre biçimi metni kaydırmaya ayarlandığında taşan metnin gizlenip gizlenmeyeceğini belirtir.<br/> Varsayılan değer false'tur|
| [is_border_collapsed](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/is_border_collapsed) | Tablo kenarlıklarının daraltılıp daraltılmadığını gösterir.<br/> Varsayılan değer doğrudur.|
| [encode_entity_as_code](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/encode_entity_as_code) | HTML karakter varlıklarının ondalık kodla değiştirilip değiştirilmeyeceğini belirtir.<br/>(örneğin "&nbsp;" "&#160;" ile değiştirilir).<br/> Varsayılan değer false'tur.|
| [office_math_output_mode](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/office_math_output_mode) | OfficeMath nesnelerinin HTML'e nasıl aktarılacağını belirtir. Varsayılan değer Görüntü'dür.|
| [cell_name_attribute](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/cell_name_attribute) | Yazılacak CellName'i belirten özniteliği belirtir.<br/>(Örneğin eğer değer "id" ise, o zaman "A1" hücresi için çıktı şu şekilde olacaktır:<td id='A1'>).<br/> Varsayılan değer null'dır.|
| [disable_css](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/disable_css) | CSS'ye dayanmadan yalnızca satır içi stillerin uygulanıp uygulanmadığını belirtir.<br/> Varsayılan değer false'tur.|
| [enable_css_custom_properties](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/enable_css_custom_properties) | CSS özel özelliklerini kullanarak HTML çıktısını optimize edin. Örneğin, bir base64 görselinin birden fazla kez görüntülendiği bir senaryoda, özel özellik kullanıldığında görsel verilerinin yalnızca bir kez kaydedilmesi yeterlidir; böylece elde edilen HTML'nin performansı artırılabilir.<br/> Varsayılan değer false'tur.|
| [html_version](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/html_version) | HTML formatını kaydederken kullanılması gereken HTML standardının sürümünü belirtir.<br/> Varsayılan değer HtmlVersion.Default'dur.|
| [sheet_set](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions/sheet_set) | İşlenecek sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).|



###  Ayrıca bakınız
* modül [`aspose.cells.saving`](..)
* sınıf [`EbookSaveOptions`](/cells/python-net/tr/aspose.cells.saving/ebooksaveoptions)
* sınıf [`HtmlSaveOptions`](/cells/python-net/tr/aspose.cells/htmlsaveoptions)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
