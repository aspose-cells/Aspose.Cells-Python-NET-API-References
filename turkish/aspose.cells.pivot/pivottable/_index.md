---
title: PivotTable sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 230
url: /tr/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable sınıfı
PivotTable için özet açıklama.



PivotTable türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/tr/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | PivotTable yenilenirken PivotTable'ın Excel2003 ile uyumlu olup olmadığını belirtir.<br/>eğer doğruysa, bir dize 255 karakterden az veya ona eşit olmalıdır, bu nedenle dize 255 karakterden büyükse,<br/>kesilecektir. Eğer false ise, bir dize yukarıda belirtilen kısıtlamaya sahip olmayacaktır.<br/> Varsayılan değer doğrudur.|
| [refreshed_by_who](/cells/python-net/tr/aspose.cells.pivot/pivottable/refreshed_by_who) | Bu PivotTable'ı yenileyen son kullanıcının adını alır|
| [refresh_date](/cells/python-net/tr/aspose.cells.pivot/pivottable/refresh_date) | PivotTable'ın yenilendiği son tarih ve saati alır.|
| [pivot_table_style_name](/cells/python-net/tr/aspose.cells.pivot/pivottable/pivot_table_style_name) | Pivottable stil adını alır ve ayarlar.|
| [pivot_table_style_type](/cells/python-net/tr/aspose.cells.pivot/pivottable/pivot_table_style_type) | Yerleşik pivot tablo stilini alır ve ayarlar.|
| [column_fields](/cells/python-net/tr/aspose.cells.pivot/pivottable/column_fields) | Şu anda sütun alanları olarak gösterilen PivotFields nesnesini döndürür.|
| [row_fields](/cells/python-net/tr/aspose.cells.pivot/pivottable/row_fields) | Şu anda satır alanları olarak gösterilen PivotFields nesnesini döndürür.|
| [page_fields](/cells/python-net/tr/aspose.cells.pivot/pivottable/page_fields) | Şu anda sayfa alanları olarak gösterilen PivotFields nesnesini döndürür.|
| [data_fields](/cells/python-net/tr/aspose.cells.pivot/pivottable/data_fields) | PivotTable'daki tüm veri alanlarını temsil eden bir PivotField nesnesi alır.<br/>Salt okunur. DataPiovtFiels'da iki veya daha fazla veri alanı olduğunda yalnızca init olur.<br/> Sadece PivotTable satır/sütun alanına DataPivotField eklemek için kullanılır. Varsayılan satır alanıdır.|
| [data_field](/cells/python-net/tr/aspose.cells.pivot/pivottable/data_field) |PivotTable'daki tüm veri alanlarını temsil eden [`PivotField`](/cells/python-net/tr/aspose.cells.pivot/pivotfield) nesnesini alır.<br/>Salt okunur.<br/>Yalnızca Veri bölgesinde iki veya daha fazla veri alanı olduğunda oluşturulur.<br/> Varsayılan olarak satır bölgesindedir. PivotTable.AddFieldToArea() metoduyla satır/sütun bölgesine sürükleyebilirsiniz.|
| [base_fields](/cells/python-net/tr/aspose.cells.pivot/pivottable/base_fields) | PivotTable'daki tüm temel pivot alanlarını döndürür.|
| [pivot_filters](/cells/python-net/tr/aspose.cells.pivot/pivottable/pivot_filters) | Pivot tablodaki pivot alanlarının tüm filtrelerini döndürür.|
| [column_range](/cells/python-net/tr/aspose.cells.pivot/pivottable/column_range) | Aralığı temsil eden bir CellArea nesnesi döndürür<br/> PivotTable raporundaki sütun alanını içeren. Salt okunur.|
| [row_range](/cells/python-net/tr/aspose.cells.pivot/pivottable/row_range) | Aralığı temsil eden bir CellArea nesnesi döndürür<br/> PivotTable raporundaki satır alanını içeren. Salt okunur.|
| [data_body_range](/cells/python-net/tr/aspose.cells.pivot/pivottable/data_body_range) | Veri alanını içeren aralığı temsil eden [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) nesnesini döndürür<br/> Başlık satırı ile ekleme satırı arasındaki listede. Salt okunur.|
| [table_range1](/cells/python-net/tr/aspose.cells.pivot/pivottable/table_range1) | PivotTable raporunun tamamını içeren aralığı temsil eden bir CellArea nesnesi döndürür.<br/> ancak sayfa alanlarını içermez. Salt okunur.|
| [table_range2](/cells/python-net/tr/aspose.cells.pivot/pivottable/table_range2) | PivotTable raporunun tamamını içeren aralığı temsil eden bir CellArea nesnesi döndürür.<br/> sayfa alanlarını içerir. Salt okunur.|
| [is_grid_drop_zones](/cells/python-net/tr/aspose.cells.pivot/pivottable/is_grid_drop_zones) | PivotTable raporunun klasik pivottable düzenini görüntüleyip görüntülemediğini belirtir.<br/> (ızgaradaki alanların sürüklenmesini sağlar)|
| [show_column_grand_totals](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_column_grand_totals) |Bu pivot tablonun sütunları için genel toplamların gösterilip gösterilmeyeceğini belirtir.|
| [show_row_grand_totals](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_row_grand_totals) | Pivot tablonun satırları için genel toplamların gösterilip gösterilmeyeceğini belirtir.|
| [column_grand](/cells/python-net/tr/aspose.cells.pivot/pivottable/column_grand) | PivotTable raporunun sütunlar için genel toplamları gösterip göstermediğini belirtir.|
| [row_grand](/cells/python-net/tr/aspose.cells.pivot/pivottable/row_grand) | Bu pivot tablonun satırları için genel toplamların gösterilip gösterilmeyeceğini belirtir.|
| [display_null_string](/cells/python-net/tr/aspose.cells.pivot/pivottable/display_null_string) | Değer boşsa PivotTable raporunun özel bir dize görüntüleyip görüntülemeyeceğini belirtir.|
| [null_string](/cells/python-net/tr/aspose.cells.pivot/pivottable/null_string) | Boş değerler içeren hücrelerde görüntülenen dizeyi alır<br/> DisplayNullString özelliği true olduğunda. Varsayılan değer boş bir dizedir.|
| [display_error_string](/cells/python-net/tr/aspose.cells.pivot/pivottable/display_error_string) | PivotTable raporunun hata içeren hücrelerde özel bir dize görüntüleyip görüntülemediğini belirtir.|
| [data_field_header_name](/cells/python-net/tr/aspose.cells.pivot/pivottable/data_field_header_name) | PivotTable'daki değer alanı başlığının adını alır ve ayarlar.|
| [error_string](/cells/python-net/tr/aspose.cells.pivot/pivottable/error_string) | Hatalar içeren hücrelerde görüntülenen dizeyi alır<br/> DisplayErrorString özelliği true olduğunda. Varsayılan değer boş bir dizedir.|
| [is_auto_format](/cells/python-net/tr/aspose.cells.pivot/pivottable/is_auto_format) | PivotTable raporunun otomatik olarak biçimlendirilip biçimlendirilmeyeceğini belirtir.<br/>Excel 2003 için pivottable seçeneğinde bulunan "tabloyu otomatik biçimlendir" onay kutusu|
| [autofit_column_width_on_update](/cells/python-net/tr/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Güncelleme sırasında sütun genişliğinin otomatik olarak ayarlanıp ayarlanmadığını belirtir|
| [auto_format_type](/cells/python-net/tr/aspose.cells.pivot/pivottable/auto_format_type) | PivotTable'ın otomatik biçimlendirme türünü alır ve ayarlar.|
| [has_blank_rows](/cells/python-net/tr/aspose.cells.pivot/pivottable/has_blank_rows) | Boş satırların eklenip eklenmeyeceğini belirtir.<br/> Bu özellik yalnızca boş satırlar eklemesi gereken PivotTable otomatik biçimlendirme türleri için geçerlidir.|
| [merge_labels](/cells/python-net/tr/aspose.cells.pivot/pivottable/merge_labels) | Belirtilen PivotTable raporunun dış satır öğesi, sütun öğesi, ara toplam ve genel toplam etiketleri birleştirilmiş hücreler kullanıyorsa doğrudur.|
| [preserve_formatting](/cells/python-net/tr/aspose.cells.pivot/pivottable/preserve_formatting) | PivotTable yenilendiğinde veya yeniden hesaplandığında biçimlendirmenin korunup korunmayacağını belirtir.|
| [show_drill](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_drill) | Genişlet/daralt düğmelerinin gösterilip gösterilmeyeceğini alır ve ayarlar.|
| [enable_drilldown](/cells/python-net/tr/aspose.cells.pivot/pivottable/enable_drilldown) | Ayrıntılı incelemenin etkin olup olmadığını alır.|
| [enable_field_dialog](/cells/python-net/tr/aspose.cells.pivot/pivottable/enable_field_dialog) | PivotTable Alanı iletişim kutusunun kullanılabilir olup olmadığını gösterir<br/> Kullanıcı PivotTable alanına çift tıkladığında.|
| [enable_field_list](/cells/python-net/tr/aspose.cells.pivot/pivottable/enable_field_list) | PivotTable için alan listesinin Excel görünümünde kullanılabilir olup olmadığını belirtir.|
| [enable_wizard](/cells/python-net/tr/aspose.cells.pivot/pivottable/enable_wizard) | PivotTable Sihirbazı'nın kullanılabilir olup olmadığını gösterir.|
| [subtotal_hidden_page_items](/cells/python-net/tr/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |PivotTable raporunda gizli sayfa alanı öğelerinin olup olmadığını gösterir<br/>satır ve sütun ara toplamlarına, blok toplamlarına ve genel toplamlara dahil edilir.<br/> Varsayılan değer False'dur.|
| [grand_total_name](/cells/python-net/tr/aspose.cells.pivot/pivottable/grand_total_name) | Genel toplam sütun veya satır başlığında görüntülenen etiketi döndürür.<br/> Varsayılan değer "Genel Toplam" dizesidir.|
| [manual_update](/cells/python-net/tr/aspose.cells.pivot/pivottable/manual_update) | PivotTable raporunun yalnızca kullanıcının isteği üzerine yeniden hesaplanıp hesaplanmayacağını belirtir.|
| [is_multiple_field_filters](/cells/python-net/tr/aspose.cells.pivot/pivottable/is_multiple_field_filters) | PivotTable'ın alanlarına birden fazla filtre uygulanıp uygulanamayacağını belirten bir Boole değeri belirtir.|
| [allow_multiple_filters_per_field](/cells/python-net/tr/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | PivotTable'ın alanlarına birden fazla filtre uygulanıp uygulanamayacağını belirten bir Boole değeri belirtir.|
| [missing_items_limit](/cells/python-net/tr/aspose.cells.pivot/pivottable/missing_items_limit) | PivotTable'ın alanlarına birden fazla filtre uygulanıp uygulanamayacağını belirten bir Boole değeri belirtir.|
| [enable_data_value_editing](/cells/python-net/tr/aspose.cells.pivot/pivottable/enable_data_value_editing) | Pivot tablonun veri alanındaki hücreleri düzenlemeye kullanıcının izin verilip verilmediğini belirten bir Boole değeri belirtir.<br/> Değerler alanında hücre düzenlemeyi etkinleştirin|
| [show_data_tips](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_data_tips) | PivotTable veri hücreleri için araç ipuçlarının görüntülenip görüntülenmeyeceğini belirten bir Boole değeri belirtir.|
| [show_member_property_tips](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_member_property_tips) | Üye özelliği bilgilerinin PivotTable araç ipuçlarından çıkarılıp çıkarılmayacağını belirten bir Boole değeri belirtir.|
| [show_values_row](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_values_row) | Değer satırının gösterilip gösterilmeyeceğini belirtir.|
| [show_empty_col](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_empty_col) | Tabloya boş sütunların dahil edilip edilmeyeceğini belirtir|
| [show_empty_row](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_empty_row) |Tabloya boş satırların dahil edilip edilmeyeceğini belirtir.|
| [field_list_sort_ascending](/cells/python-net/tr/aspose.cells.pivot/pivottable/field_list_sort_ascending) | PivotTable'daki alanların alan listesinde varsayılan olmayan bir sırada sıralanıp sıralanmadığını belirtir.|
| [print_drill](/cells/python-net/tr/aspose.cells.pivot/pivottable/print_drill) | Matkap göstergelerinin yazdırılıp yazdırılmayacağını belirten bir Boole değeri belirtir.<br/> Pivottable'da görüntülendiğinde genişletme/daraltma düğmelerini yazdır.|
| [alt_text_title](/cells/python-net/tr/aspose.cells.pivot/pivottable/alt_text_title) | Değişiklik metninin başlığını alır ve ayarlar.|
| [alt_text_description](/cells/python-net/tr/aspose.cells.pivot/pivottable/alt_text_description) | Alt metnin açıklamasını alır.|
| [name](/cells/python-net/tr/aspose.cells.pivot/pivottable/name) | PivotTable'ın adını alır|
| [column_header_caption](/cells/python-net/tr/aspose.cells.pivot/pivottable/column_header_caption) | PivotTable'ın Sütun Başlığı Başlığını alır.|
| [indent](/cells/python-net/tr/aspose.cells.pivot/pivottable/indent) | Sıkıştırılmış eksen için girinti artışını belirtir ve Rapor Düzenini Sıkıştırılmış Form olarak ayarlamak için kullanılabilir.|
| [row_header_caption](/cells/python-net/tr/aspose.cells.pivot/pivottable/row_header_caption) | PivotTable'ın Satır Başlığı Başlığını alır.|
| [show_row_header_caption](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_row_header_caption) | PivotTable raporunda satır başlığı başlığının gösterilip gösterilmeyeceğini belirtir<br/> Alan başlıklarının ve filtre açılır listelerinin görüntülenip görüntülenmeyeceğini belirtir|
| [custom_list_sort](/cells/python-net/tr/aspose.cells.pivot/pivottable/custom_list_sort) | Verileri sıralarken yerleşik özel listenin dikkate alınıp alınmayacağını belirtir|
| [pivot_format_conditions](/cells/python-net/tr/aspose.cells.pivot/pivottable/pivot_format_conditions) | Pivot tablonun Biçim Koşullarını alır.|
| [conditional_formats](/cells/python-net/tr/aspose.cells.pivot/pivottable/conditional_formats) | Pivot tablonun koşullu biçimlerini alır.|
| [page_field_order](/cells/python-net/tr/aspose.cells.pivot/pivottable/page_field_order) |Sayfa alanlarının PivotTable raporunun düzenine eklenme sırasını alır ve ayarlar.|
| [page_field_wrap_count](/cells/python-net/tr/aspose.cells.pivot/pivottable/page_field_wrap_count) | PivotTable raporundaki her sütun veya satırdaki sayfa alanlarının sayısını alır.|
| [tag](/cells/python-net/tr/aspose.cells.pivot/pivottable/tag) | PivotTable raporuyla kaydedilen bir dizeyi alır.|
| [save_data](/cells/python-net/tr/aspose.cells.pivot/pivottable/save_data) | PivotTable raporuna ait verilerin çalışma kitabıyla birlikte kaydedilip kaydedilmediğini belirtir.|
| [refresh_data_on_opening_file](/cells/python-net/tr/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Dosyayı Açarken Verileri Yenile'yi belirtir.|
| [refresh_data_flag](/cells/python-net/tr/aspose.cells.pivot/pivottable/refresh_data_flag) | Verilerin yenilenip yenilenmeyeceğini belirtir.|
| [source_type](/cells/python-net/tr/aspose.cells.pivot/pivottable/source_type) | Pivot tablonun veri kaynağı türünü alır.|
| [external_connection_data_source](/cells/python-net/tr/aspose.cells.pivot/pivottable/external_connection_data_source) | Dış bağlantı veri kaynağını alır.|
| [data_source](/cells/python-net/tr/aspose.cells.pivot/pivottable/data_source) | Pivot tablonun veri kaynağını alır ve ayarlar.|
| [pivot_formats](/cells/python-net/tr/aspose.cells.pivot/pivottable/pivot_formats) | PivotTable'a uygulanan formatların koleksiyonunu alır.|
| [item_print_titles](/cells/python-net/tr/aspose.cells.pivot/pivottable/item_print_titles) | PivotItem adlarının her yazdırılan sayfanın üst kısmında tekrarlanıp tekrarlanmayacağını belirtir.|
| [repeat_items_on_each_printed_page](/cells/python-net/tr/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Tablo biçimindeki pivot alanlar için, satır alanındaki pivot öğe başlıklarının her yazdırılan sayfada tekrarlanıp tekrarlanmadığını gösterir.|
| [print_titles](/cells/python-net/tr/aspose.cells.pivot/pivottable/print_titles) | Çalışma sayfasının baskı başlıklarının aşağıdakilere göre ayarlanıp ayarlanmadığını gösterir:<br/> PivotTable raporunda. Varsayılan değer false'tur.|
| [display_immediate_items](/cells/python-net/tr/aspose.cells.pivot/pivottable/display_immediate_items) |Satır ve sütun alanlarındaki öğelerin görünür olup olmadığını belirtir<br/> PivotTable'ın veri alanı boş olduğunda. Varsayılan değer true'dur.|
| [is_selected](/cells/python-net/tr/aspose.cells.pivot/pivottable/is_selected) | Bu PivotTable'ın seçili olup olmadığını gösterir.|
| [show_pivot_style_row_header](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Pivot tabloda satır başlığına stil uygulanıp uygulanmayacağını belirtir.|
| [show_pivot_style_column_header](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Pivot tablodaki sütun başlığına stilin uygulanıp uygulanmayacağını belirtir.|
| [show_pivot_style_row_stripes](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Satır şerit biçimlendirmesinin uygulanıp uygulanmadığını belirtir.|
| [show_pivot_style_column_stripes](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Sütun için şerit biçimlendirmesinin uygulanıp uygulanmadığını belirtir.|
| [show_pivot_style_last_column](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Sütun biçimlendirmesinin uygulanıp uygulanmadığını gösterir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Belirli bir alandan bir alanı kaldırır|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Belirli bir alandan bir alanı kaldırır|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Belirli alandan alanı kaldır|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Alanı belirli alana ekler.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Alanı belirli alana ekler.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Alanı belirli alana ekler.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Pivot alanına hesaplanmış bir alan ekler.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Pivot alanına hesaplanan bir alan ekler ve onu veri alanına sürükler.|
| [`move(self, row, column)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/move/#int-int) | PivotTable'ı çalışma sayfasında farklı bir konuma taşır.|
| [`move(self, dest_cell_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/move/#str) | PivotTable'ı çalışma sayfasında farklı bir konuma taşır.|
| [`move_to(self, row, column)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/move_to/#int-int) | PivotTable'ı çalışma sayfasında farklı bir konuma taşır.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/move_to/#str) | PivotTable'ı çalışma sayfasında farklı bir konuma taşır.|
| [`get_source(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_source/#) | Pivottable'ın kaynak verilerini al.|
| [`get_source(self, is_original)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_source/#bool) | Pivottable'ın kaynak verilerini al.|
| [`refresh_data(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/refresh_data/#) |Pivottable'ın verilerini ve ayarlarını veri kaynağından yeniler.|
| [`refresh_data(self, option)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Pivottable'ın verilerini ve ayarlarını veri kaynağından seçeneklerle yeniler.|
| [`calculate_data(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/calculate_data/#) | Pivottable'ın verilerini hücrelere hesaplar.|
| [`calculate_data(self, option)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Pivot tabloların seçeneklerle hesaplanması|
| [`format(self, pivot_area, style)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | PivotTable'ın seçili alanını biçimlendirir.|
| [`format(self, ca, style)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | PivotTable'ın seçili alanını biçimlendirir.|
| [`format(self, row, column, style)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Pivot tablo alanındaki hücreyi biçimlendir|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | PivotTable'a göre otomatik alan grubu ayarlar.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | PivotTable'a göre otomatik alan grubu ayarlar.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | PivotTable'a göre manuel alan grubu ayarlar.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | PivotTable'a göre manuel alan grubu ayarlar.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | PivotTable'a göre manuel alan grubu ayarlar.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | PivotTable'a göre manuel alan grubu ayarlar.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_ungroup/#int) | PivotTable'a göre gruplandırmayı kaldır|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | PivotTable'a göre gruplandırmayı kaldır|
| [`copy_style(self, pivot_table)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Başka bir pivot tablodan adlandırılmış stili kopyalar.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | PivotField'a göre tüm rapor filtre sayfalarını göster, PivotField'ın PageFields'da bulunması gerekir.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | PivotField ismine göre tüm rapor filtre sayfalarını göster, PivotField PageFields'da bulunmalıdır.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | PageFields'daki konum dizinine göre tüm rapor filtre sayfalarını göster|
| [`get_fields(self, field_type)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Bölgeye göre belirli pivot alan listesini alır.|
| [`fields(self, field_type)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Alan türüne göre belirli alanları alır.|
| [`get_source_data_connections(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Dış bağlantı veri kaynaklarını alır.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Dış kaynak veri bağlantılarının adını alır.|
| [`change_data_source(self, source)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/change_data_source/#list) | Pivottable'ın kaynak verilerini ayarlayın.|
| [`clear_data(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/clear_data/#) | PivotTable'ın verilerini ve biçimlendirmesini temizle|
| [`calculate_range(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/calculate_range/#) | Pivottable'ın aralığını hesaplar.|
| [`format_all(self, style)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Pivot tablo alanındaki tüm hücreleri biçimlendir|
| [`format_row(self, row, style)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Pivot tablo alanındaki satır verilerini biçimlendirin|
| [`select_area(self, ca)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Pivot tablo görünümünün bir alanını seçin.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Veri bölgesindeki bir öğenin ayrıntılarını yeni bir Tabloya göster.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Bu pivot tablonun yatay sayfa sonlarını alır.|
| [`get_horizontal_breaks(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Yatay sayfa sonlarının pivot tablo satır dizin listesini alır|
| [`show_in_compact_form(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_in_compact_form/#) | PivotTable'ı kompakt biçimde düzenler.|
| [`show_in_outline_form(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_in_outline_form/#) | PivotTable'ı anahat biçiminde düzenler.|
| [`show_in_tabular_form(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | PivotTable'ı tablo biçiminde düzenler.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | PivotField'ın görüntü adına göre [`Cell`](/cells/python-net/tr/aspose.cells/cell) nesnesini alır.|
| [`get_children(self)`](/cells/python-net/tr/aspose.cells.pivot/pivottable/get_children/#) | Bu PivotTable verilerini veri kaynağı olarak kullanan Çocuk Pivot Tablolarını alır.|



###  Örnek

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
* sınıf [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)
* sınıf [`PivotField`](/cells/python-net/tr/aspose.cells.pivot/pivotfield)
