---
title: WebQueryConnection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells.externalconnections/webqueryconnection/
is_root: false
---
##  WebQueryConnection sınıfı
 Bir web sorgu kaynağının özelliklerini belirtir. Bir web sorgusu, HTML tablolarından veri alacaktır,
 ve ayrıca web sunucusu tarafından HTML'i oluştururken işlenecek HTTP "Get" parametrelerini sağlayabilir.
parametreler ve parametre öğeleri dahil.



**Miras:** [WebQueryConnection](/cells/python-net/aspose.cells.externalconnections/webqueryconnection) → 
[ExternalConnection](/cells/python-net/tr/aspose.cells.externalconnections/externalconnection)



WebQueryConnection türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [id](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/id) | Bağlantının kimliğini alır.|
| [power_query_formula](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/power_query_formula) | Güçlü sorgu formülünün tanımını alır.|
| [type](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/type) | Dış bağlantı DataSource türünü alır veya ayarlar.|
| [source_file](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/source_file) | Harici veri kaynağı dosya tabanlı olduğunda kullanılır. Böyle bir veriye bağlantı kurulduğunda<br/> kaynak başarısız olursa, elektronik tablo uygulaması doğrudan bu dosyaya bağlanmaya çalışır. Belki<br/> URI veya sisteme özel dosya yolu notasyonu ile ifade edilir.|
| [sso_id](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/sso_id) | Bir aracı arasında kimlik doğrulama için kullanılan Çoklu Oturum Açma (SSO) tanımlayıcısı<br/> elektronik tabloML sunucusu ve harici veri kaynağı.|
| [save_password](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/save_password) | Parola bağlantı dizesinin bir parçası olarak kaydedilecekse doğrudur; Aksi takdirde, Yanlış.|
| [save_data](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/save_data) | Bir tabloyu doldurmak için bağlantı üzerinden getirilen harici veriler kaydedilecekse doğrudur.<br/> çalışma kitabı ile; Aksi takdirde, yanlış.|
| [refresh_on_load](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/refresh_on_load) | Dosya açılırken bu bağlantının yenilenmesi gerekiyorsa doğrudur; Aksi takdirde, yanlış.|
| [reconnection_method_type](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/reconnection_method_type) | Bir bağlantı başarısız olduğunda elektronik tablo uygulamasının ne yapması gerektiğini belirtir.<br/>Varsayılan değer ReConnectionMethodType.Required şeklindedir.|
| [reconnection_method](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/reconnection_method) | Bir bağlantı başarısız olduğunda elektronik tablo uygulamasının ne yapması gerektiğini belirtir.<br/>Varsayılan değer ReConnectionMethodType.Required şeklindedir.|
| [only_use_connection_file](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/only_use_connection_file) | Elektronik tablo uygulamasının her zaman ve yalnızca<br/> odcFile özniteliği tarafından belirtilen harici bağlantı dosyasındaki bağlantı bilgileri<br/> bağlantı yenilendiğinde. Yanlışsa, elektronik tablo uygulaması<br/> reconnectionMethod özniteliği tarafından belirtilen prosedürü izlemelidir|
| [odc_file](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/odc_file) | Bu bağlantının yapıldığı harici bağlantı dosyasının tam yolunu belirtir.<br/> oluşturuldu. Verileri yenileme girişimi sırasında bir bağlantı başarısız olursa ve reconnectionMethod=1,<br/> ardından elektronik tablo uygulaması, harici bağlantı dosyasındaki bilgileri kullanarak tekrar deneyecektir.<br/> çalışma kitabına katıştırılmış bağlantı nesnesi yerine.|
| [is_new](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_new) | Bağlantı ilk kez yenilenmediyse doğrudur; Aksi takdirde, yanlış.<br/> Bu durum, bir sorgunun döndürülmesi tamamlanmadan önce kullanıcı dosyayı kaydettiğinde gerçekleşebilir.|
| [name](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/name) | Bağlantının adını belirtir. Her bağlantının benzersiz bir adı olmalıdır.|
| [keep_alive](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/keep_alive) | Elektronik tablo uygulamasının bağlantıyı sürdürmek için çaba göstermesi gerektiğinde doğrudur<br/>açık. Yanlış olduğunda, uygulama, bağlantıyı aldıktan sonra bağlantıyı kapatmalıdır.<br/> bilgi.|
| [refresh_internal](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/refresh_internal) | Bağlantının otomatik yenilemeleri arasındaki dakika sayısını belirtir.|
| [connection_id](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/connection_id) | Bu bağlantının benzersiz tanımlayıcısını belirtir.|
| [connection_description](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/connection_description) | Bu bağlantı için kullanıcı açıklamasını belirtir|
| [is_deleted](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_deleted) |İlişkili çalışma kitabı bağlantısının silinip silinmediğini gösterir. doğru ise<br/> bağlantı silindi; Aksi takdirde, yanlış.|
| [credentials_method_type](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/credentials_method_type) | Bağlantı kurulurken (veya yeniden kurulurken) kullanılacak kimlik doğrulama yöntemini belirtir.|
| [credentials](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/credentials) | Bağlantı kurulurken (veya yeniden kurulurken) kullanılacak kimlik doğrulama yöntemini belirtir.|
| [background_refresh](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/background_refresh) | Bağlantının arka planda (eşzamansız olarak) yenilenip yenilenemeyeceğini belirtir.<br/>true bağlantının tercih edilen kullanımı arka planda eşzamansız olarak yenilemekse;<br/> false bağlantının tercih edilen kullanımı ön planda eşzamanlı olarak yenilemekse.|
| [parameters](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/parameters) | ODBC veya web sorgusu için [ConnectionParameterCollection](/cells/python-net/tr/aspose.cells.externalconnections/connectionparametercollection) alır.|
| [is_xml](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_xml) | web sorgu kaynağı XML ise true (HTML'e karşı), aksi takdirde false.|
| [is_xl97](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_xl97) |Bu işaret, daha eski elektronik tablo dosyalarıyla geriye dönük uyumluluk için mevcuttur ve ayarlanmıştır<br/>Bu web sorgusu Microsoft Excel 97'de oluşturulduysa true olur.<br/> Bu, göz ardı edilebilecek isteğe bağlı bir özelliktir.|
| [is_xl2000](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_xl2000) |Bu işaret, daha eski elektronik tablo dosyalarıyla geriye dönük uyumluluk için mevcuttur ve ayarlanmıştır<br/>bu web sorgusu şundan daha yeni veya eşit bir elektronik tablo uygulamasında yenilendiyse true olur<br/>Microsoft Excel 2000'e.<br/> Bu, göz ardı edilebilecek isteğe bağlı bir özelliktir.|
| [url](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/url) | Harici verileri yenilemek için kullanılacak URL.|
| [is_text_dates](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_text_dates) | Çalışma sayfasındaki hücrelere tarihlerin tarih yerine metin olarak aktarılması gerekip gerekmediğini gösteren bayrak.|
| [is_xml_source_data](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_xml_source_data) | HTML tablosunun kendisi yerine XML kaynak verilerinin içe aktarılması gerektiğini belirten işaret.|
| [post](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/post) | Bir web sunucusuna veri girişinin post yöntemiyle kullanılan dizeyi döndürür veya ayarlar<br/> bir web sorgusundan veri döndürmek için.|
| [is_parse_pre](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_parse_pre) | Web sayfasındaki HTML PRE etiketlerinde yer alan verilerin olup olmadığını gösteren bayrak<br/> sayfayı bir sorgu tablosuna aktardığınızda sütunlara ayrıştırılır.|
| [is_html_tables](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_html_tables) | Web sorgularının yalnızca HTML tablolarında çalışıp çalışmayacağını gösteren bayrak.|
| [html_format](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/html_format) | Web sorgu verilerini HTML kaynağından biçimlendirme nasıl yapılır?<br/> çalışma kağıdı. sourceData True olduğunda geçerlidir.|
| [is_same_settings](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_same_settings) |Bir PRE bloğu içindeki tüm tabloların aynı genişlik ayarlarıyla ayrıştırılıp ayrıştırılmayacağını gösteren bayrak<br/> ilk sıra olarak.|
| [edit_web_page](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/edit_web_page) | Web sorgusu verilerini gösteren, kullanıcıya yönelik web sayfasının URL'si. Bu URL kalıcı<br/>sourceData="true" ve url'nin bir XML dosyasına başvurmak üzere yeniden yönlendirilmesi durumunda.<br/>Ardından, kullanıcıya bakan sayfa kullanıcı arayüzünde gösterilebilir ve XML verileri alınabilir.<br/> kamera ARKASI.|
| [edit_page](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/edit_page) | Web sorgusu verilerini gösteren, kullanıcıya yönelik web sayfasının URL'si. Bu URL kalıcı<br/>sourceData="true" ve url'nin bir XML dosyasına başvurmak üzere yeniden yönlendirilmesi durumunda.<br/>Ardından, kullanıcıya bakan sayfa kullanıcı arayüzünde gösterilebilir ve XML verileri alınabilir.<br/> kamera ARKASI.|
| [is_consecutive](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection/is_consecutive) | Ardışık sınırlayıcıların yalnızca bir sınırlayıcı olarak ele alınması gerekip gerekmediğini gösteren bayrak.|



###  Ayrıca bakınız
* modül [aspose.cells.externalconnections](..)
* sınıf [ConnectionParameterCollection](/cells/python-net/tr/aspose.cells.externalconnections/connectionparametercollection)
* sınıf [ExternalConnection](/cells/python-net/tr/aspose.cells.externalconnections/externalconnection)
* sınıf [WebQueryConnection](/cells/python-net/tr/aspose.cells.externalconnections/webqueryconnection)
