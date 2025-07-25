---
title: طريقة to_image
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells.charts/chart/to_image/
is_root: false
---
##  to_image(self, image_file) {#str}
إنشاء صورة الرسم البياني وحفظها في ملف.
يحدد امتداد اسم الملف تنسيق الصورة.



```python

def to_image(self, image_file):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| image_file | str | اسم ملف الصورة مع المسار الكامل.|
###  ملاحظات

يتم تحديد تنسيق الصورة باستخدام امتداد اسم الملف.
على سبيل المثال، إذا قمت بتحديد "myfile.png"، فسيتم حفظ الصورة
 بالتنسيق PNG. امتدادات الملفات التالية مُعرَّفة:
.bmp، .gif، .png، .jpg، .jpeg، .tiff، .tif، .emf.


إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.

##  to_image(self, image_file, image_type) {#str-aspose.cells.drawing.ImageType}
إنشاء صورة الرسم البياني وحفظها في ملف بنوع الصورة المحدد.



```python

def to_image(self, image_file, image_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| image_file | str | اسم ملف الصورة مع المسار الكامل.|
| image_type | aspose.cells.drawing.ImageType | نوع الصورة التي سيتم حفظ الصورة بها.|
###  ملاحظات

يتم تحديد نوع الصورة باستخدام `imageType`.
 يتم دعم الأنواع التالية:
ImageType.Bmp، ImageType.Gif، ImageType.Png، ImageType.Jpeg، ImageType.Tiff، ImageType.Emf.


إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.

##  to_image(self, image_file, jpeg_quality) {#str-int}
إنشاء صورة الرسم البياني وحفظها في ملف بتنسيق Jpeg.



```python

def to_image(self, image_file, jpeg_quality):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| image_file | str | اسم ملف الصورة مع المسار الكامل.|
| jpeg_quality | int | جودة JPEG.|
###  ملاحظات

إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.
 ملاحظة: هذه الطريقة أصبحت قديمة الآن. بدلاً من ذلك،
يرجى استخدام طريقة ToImage(string,ImageOrPrintOptions) بالجودة المحددة.
 سيتم إزالة هذه الطريقة بعد 12 شهرًا اعتبارًا من مارس 2025.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.

##  to_image(self, stream, jpeg_quality) {#io.RawIOBase-int}
إنشاء صورة الرسم البياني وحفظها في مجرى بتنسيق Jpeg.



```python

def to_image(self, stream, jpeg_quality):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | تيار الإخراج.|
| jpeg_quality | int | جودة JPEG.|
###  ملاحظات

إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.

##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}

إنشاء صورة الرسم البياني وحفظها في مجرى بالتنسيق المحدد.



```python

def to_image(self, stream, image_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | تيار الإخراج.|
| image_type | aspose.cells.drawing.ImageType | نوع الصورة التي سيتم حفظ الصورة بها.|
###  ملاحظات

يتم تحديد نوع الصورة باستخدام `imageType`.
 يتم دعم الأنواع التالية:
ImageType.Bmp، ImageType.Gif، ImageType.Png، ImageType.Jpeg، ImageType.Tiff، ImageType.Emf.


إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.

##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
إنشاء صورة الرسم البياني وحفظها في ملف.
يحدد امتداد اسم الملف تنسيق الصورة.



```python

def to_image(self, image_file, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| image_file | str | اسم ملف الصورة مع المسار الكامل.|
| options | aspose.cells.rendering.ImageOrPrintOptions | خيارات إنشاء الصور الإضافية|
###  ملاحظات

يتم تحديد تنسيق الصورة باستخدام امتداد اسم الملف.
على سبيل المثال، إذا قمت بتحديد "myfile.png"، فسيتم حفظ الصورة
 بالتنسيق PNG. امتدادات الملفات التالية مُعرَّفة:
.bmp، .gif، .png، .jpg، .jpeg، .tiff، .tif، .emf.


إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.
 يرجى الرجوع إلى[قائمة المخططات المدعومة](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) لمزيد من التفاصيل.
###  مثال

يحفظ بصيغة Tiff بدقة 300 نقطة في البوصة وضغط CCITT4.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, TiffCompression

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.tiff_compression = TiffCompression.COMPRESSION_CCITT4
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Tiff", options)

```


يحفظ بصيغة Jpeg بدقة 300 نقطة في البوصة وجودة صورة 80.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.quality = 80
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Jpeg", options)

```


##  to_image(self, stream, options) {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
إنشاء صورة الرسم البياني وحفظها في مجرى بالتنسيق المحدد.



```python

def to_image(self, stream, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | تيار الإخراج.|
| options | aspose.cells.rendering.ImageOrPrintOptions | خيارات إنشاء الصور الإضافية|
###  ملاحظات

يتم تحديد نوع الصورة باستخدام `options.ImageType`.
 يتم دعم التنسيقات التالية:
ImageType.Bmp، ImageType.Gif، ImageType.Png، ImageType.Jpeg، ImageType.Tiff، ImageType.Emf.


إذا كان العرض أو الارتفاع يساوي صفرًا أو لم يكن الرسم البياني مدعومًا وفقًا لقائمة الرسوم البيانية المدعومة، فلن تؤدي هذه الطريقة إلى أي شيء.
 يرجى الرجوع إلى[قائمة المخططات المدعومة](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) لمزيد من التفاصيل.


###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](../../)
* فئة [`Chart`](/cells/python-net/ar/aspose.cells.charts/chart)
