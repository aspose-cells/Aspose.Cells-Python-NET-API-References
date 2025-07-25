---
title: ShapePath صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 540
url: /ar/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath صف
يمثل مسار إنشاء يتكون من سلسلة من الحركات والخطوط والمنحنيات التي عند دمجها ستشكل شكلًا هندسيًا.



يكشف النوع ShapePath عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/__init__/#) | يقوم بتهيئة مثيل جديد للفئة [`ShapePath`](/cells/python-net/ar/aspose.cells.drawing/shapepath).|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [path_segement_list](/cells/python-net/ar/aspose.cells.drawing/shapepath/path_segement_list) | يحصل على قائمة [`ShapeSegmentPathCollection`](/cells/python-net/ar/aspose.cells.drawing/shapesegmentpathcollection)|
| [width_pixel](/cells/python-net/ar/aspose.cells.drawing/shapepath/width_pixel) | يحصل على عرض هذا المسار بوحدة البكسل.|
| [height_pixel](/cells/python-net/ar/aspose.cells.drawing/shapepath/height_pixel) | يحصل على ارتفاع هذا المسار بوحدة البكسل.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/move_to/#float-float) |يبدأ شكلًا جديدًا من النقطة المحددة دون إغلاق الشكل الحالي. تُضاف جميع النقاط اللاحقة المضافة إلى المسار إلى هذا الشكل الجديد.|
| [`line_to(self, x, y)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/line_to/#float-float) | إضافة جزء خط إلى الشكل الحالي.<br/> نقطة البداية هي نقطة النهاية للشكل الحالي.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | يُضيف منحنى بيزييه مكعبًا إلى الشكل الحالي. نقطة البداية هي نقطة نهاية الشكل الحالي.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | يُضيف قوسًا بيضاويًا إلى الشكل الحالي. نقطة البداية هي نقطة نهاية الشكل الحالي.|
| [`close(self)`](/cells/python-net/ar/aspose.cells.drawing/shapepath/close/#) | يُغلق الشكل الحالي ويبدأ شكلًا جديدًا. إذا كان الشكل الحالي يحتوي على سلسلة من الخطوط والمنحنيات المتصلة، تُغلق الطريقة الحلقة بتوصيل خط من نقطة النهاية إلى نقطة البداية.|



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
* فئة [`ShapePath`](/cells/python-net/ar/aspose.cells.drawing/shapepath)
* فئة [`ShapeSegmentPathCollection`](/cells/python-net/ar/aspose.cells.drawing/shapesegmentpathcollection)
