---
title: LightCellsDataProvider sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1040
url: /tr/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider sınıfı
Büyük elektronik tablo dosyalarını hafif modda kaydetmek için Veri sağlayıcıyı temsil eder.



LightCellsDataProvider türü aşağıdaki üyeleri ortaya çıkarır:

###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [start_sheet](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Bir çalışma sayfasını kaydetmeye başlar.|
| [next_row](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/next_row/#) | Kaydedilecek sonraki satırı alır.|
| [start_row](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Bir satırın verilerini kaydetmeye başlar.|
| [next_cell](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/next_cell/#) | Kaydedilecek sonraki hücreyi alır.|
| [start_cell](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Bir hücrenin verilerini kaydetmeye başlar.|
| [is_gather_string](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Hücrenin geçerli dize değerinin genel bir havuzda toplanması gerekip gerekmediğini kontrol eder.|



###  Notlar

Bir çalışma kitabını bu modda kaydederken, çalışma kitabındaki her çalışma sayfasını kaydederken [`LightCellsDataProvider.start_sheet`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_sheet) işaretlenecektir.
Bir sayfa için, [`LightCellsDataProvider.start_sheet`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_sheet) doğru değeri verirse, bu sayfanın satırları/hücreleri için tüm veriler ve özellikler kaydedilecektir.
bu arayüzün uygulanması ile sağlanacaktır.
İlk etapta kaydedilecek bir sonraki satır indeksini almak için [`LightCellsDataProvider.next_row`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/next_row) çağrılacaktır.
Geçerli bir satır dizini döndürülürse (satırların kaydedilebilmesi için satır dizini artan sırada olmalıdır),
daha sonra uygulamanın özelliklerini ayarlaması için bu satırı temsil eden bir Row nesnesi [`LightCellsDataProvider.start_row`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_row) tarafından sağlanacaktır.
Bir satır için öncelikle [`LightCellsDataProvider.next_cell`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/next_cell) kontrol edilecektir.
Geçerli bir sütun dizini döndürülürse (sütun dizini geçerli satırın tüm hücreleri için artan sırada olmalıdır),
daha sonra bu hücreyi temsil eden bir Cell nesnesi, verilerini ve özelliklerini ayarlamak üzere uygulama için [`LightCellsDataProvider.start_cell`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_cell) tarafından sağlanacaktır.
[`LightCellsDataProvider.start_cell`](/cells/python-net/tr/aspose.cells/lightcellsdataprovider/start_cell)'den sonra hücre doğrudan sonuçtaki elektronik tablo dosyasına kaydedilecektir.
Daha sonra bir sonraki hücre kontrol edilecek ve işlenecektir.


Kullanıcının yalnızca ilgili yöntemle sağlanan geçerli Row/Cell nesnesinin değerlerini ve özelliklerini güncellemesi gerektiğini lütfen unutmayın.
Hücre verileri sonuç dosyasına akış şeklinde yazıldığı için diğer nesnelerin çoğu da yazılmış olabilir.
ortaya çıkan dosyaya aktarılmış veya bunlar için bazı genel veriler toplanmış ve yazılmıştır. Yani kullanıcı diğer nesneleri güncellerken
Hücre verilerini kaydederken bu işlemler kaydedilen verileri etkilemeyebilir. Daha da kötüsü, bu operasyonlar
tutarsız verilerin ortaya çıkan dosyaya kaydedilmesine ve sonunda dosyanın bozulmasına neden olur.
Yani şekiller, sütun genişliği ve stilleri, koşullu biçimlendirmeler vb. gibi diğer tüm nesneler için,
lütfen bunları bu uygulamanın herhangi bir yönteminde çalıştırmayın.
Bunun yerine lütfen bunları yönetin ve Çalışma Kitabının "Kaydet" yöntemini çağırmadan önce bunları son durumuna ayarlayın.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
