---
title: NaryEquationNode sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode sınıfı
Bu sınıf, n-li operatör, bir taban (veya işlenen) ve isteğe bağlı üst ve alt sınırlardan oluşan n-li operatör denklemini belirtir.



**Miras:** [`NaryEquationNode`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode)



NaryEquationNode türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [type](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Alt sınırın görüntülenip görüntülenmeyeceği|
| [is_hide_superscript](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Üst sınırın görüntülenip görüntülenmeyeceği|
| [limit_location](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/limit_location) | Bu öznitelik, n-li operatörlerdeki limitlerin konumunu belirtir. Limitler, n-li operatörün üstünde ve altında ortalanabilir veya operatörün hemen sağına yerleştirilebilir.|
| [nary_operator](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/nary_operator) | n-li bir operatör.örneğin "∑".<br/>n-ary operatörünü ayarlamak için NaryOperatorType niteliğinin kullanılması şiddetle önerilir.<br/> Bilinen bir türde ihtiyacınız olan karakteri bulamazsanız bu özellik ayarını kullanın.|
| [nary_operator_type](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | n-ary operatörü.örneğin "∑"|
| [nary_grow](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Bu öznitelik, belge düzeyinde n-li operatörlerin büyüme özelliğini belirtir. Kapalıyken, integraller ve toplamlar gibi n-li operatörler, işlenen yüksekliklerinin boyutuna uyacak şekilde büyümez. Açıkken, n-li operatör işlenen yüksekliğine uyacak şekilde dikey olarak büyür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Ayrıca bakınız
* modül [`aspose.cells.drawing.equations`](..)
* sınıf [`NaryEquationNode`](/cells/python-net/tr/aspose.cells.drawing.equations/naryequationnode)
