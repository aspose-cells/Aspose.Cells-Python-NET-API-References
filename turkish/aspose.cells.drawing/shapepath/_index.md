---
title: ShapePath sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 540
url: /tr/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath sınıfı
Birbirleriyle bir geometrik şekil oluşturacak bir dizi hareket, çizgi ve eğriden oluşan bir yaratım yolunu temsil eder.



ShapePath türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/__init__/#) | [`ShapePath`](/cells/python-net/tr/aspose.cells.drawing/shapepath) sınıfının yeni bir örneğini başlatır.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [path_segement_list](/cells/python-net/tr/aspose.cells.drawing/shapepath/path_segement_list) | [`ShapeSegmentPathCollection`](/cells/python-net/tr/aspose.cells.drawing/shapesegmentpathcollection) listesini alır|
| [width_pixel](/cells/python-net/tr/aspose.cells.drawing/shapepath/width_pixel) | Bu yolun genişliğini piksel cinsinden alır.|
| [height_pixel](/cells/python-net/tr/aspose.cells.drawing/shapepath/height_pixel) | Bu yolun yüksekliğini piksel cinsinden alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/move_to/#float-float) |Mevcut şekli kapatmadan belirtilen noktadan yeni bir şekil başlatır. Yola eklenen tüm sonraki noktalar bu yeni şekle eklenir.|
| [`line_to(self, x, y)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/line_to/#float-float) | Mevcut şekle bir çizgi parçası ekler.<br/> Başlangıç noktası mevcut şeklin bitiş noktasıdır.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Mevcut şekle kübik bir Bézier eğrisi ekler. Başlangıç noktası, mevcut şeklin bitiş noktasıdır.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Mevcut şekle eliptik bir yay ekler. Başlangıç noktası, mevcut şeklin bitiş noktasıdır.|
| [`close(self)`](/cells/python-net/tr/aspose.cells.drawing/shapepath/close/#) | Mevcut şekli kapatır ve yeni bir şekil başlatır. Mevcut şekil, birbirine bağlı çizgi ve eğrilerden oluşan bir dizi içeriyorsa, yöntem, bitiş noktasından başlangıç noktasına bir çizgi bağlayarak döngüyü kapatır.|



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](..)
* sınıf [`ShapePath`](/cells/python-net/tr/aspose.cells.drawing/shapepath)
* sınıf [`ShapeSegmentPathCollection`](/cells/python-net/tr/aspose.cells.drawing/shapesegmentpathcollection)
