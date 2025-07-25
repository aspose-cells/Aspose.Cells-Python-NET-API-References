---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.drawing.equations/
is_root: false
---
 ال**Aspose.Cells.Drawing.Equations** توفر مساحة الاسم فئات لإنشاء أشكال معادلات مختلفة (مثل المعادلات الكسرية، ومعادلات القوة، وما إلى ذلك) من خلال عقد المعادلات.

###  الطبقات
| فصل| وصف|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/accentequationnode) | تحدد هذه الفئة معادلة لهجة تتكون من مكون أساسي وعلامة تشكيل مركبة.|
| [`ArrayEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/arrayequationnode) | يحدد وظيفة Equation-Array، وهو كائن يتكون من معادلة واحدة أو أكثر.|
| [`BarEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/barequationnode) |تحدد هذه الفئة معادلة الشريط، التي تتكون من وسيطة أساسية وشريط علوي أو شريط سفلي.|
| [`BorderBoxEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/borderboxequationnode) | تحدد هذه الفئة وظيفة Border Box، والتي تتكون من حدود مرسومة حول معادلة.|
| [`BoxEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/boxequationnode) | تحدد هذه الفئة وظيفة الصندوق، التي تستخدم لتجميع مكونات المعادلة.|
| [`DelimiterEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/delimiterequationnode) | تحدد هذه الفئة معادلة الفاصل، التي تتكون من فواصل الفتح والإغلاق (مثل الأقواس، والأقواس المعقوفة، والأقواس المربعة، والأشرطة الرأسية)، ومكون موجود بداخلها.<br/> يمكن أن يحتوي الفاصل على أكثر من مكون، مع وجود حرف فاصل مخصص بين كل مكون.|
| [`EquationComponentNode`](/cells/python-net/ar/aspose.cells.drawing.equations/equationcomponentnode) | تحدد هذه الفئة مكونات المعادلة أو التعبير الرياضي.<br/>أنواع مختلفة من المكونات مجتمعة في معادلات مختلفة.<br/>على سبيل المثال، يتكون الكسر من جزأين، جزء البسط وجزء المقام.<br/> لمعرفة المزيد عن أنواع المكونات، يرجى الرجوع إلى 'EquationNodeType'.|
| [`EquationNodeParagraph`](/cells/python-net/ar/aspose.cells.drawing.equations/equationnodeparagraph) | تحدد هذه الفئة فقرة رياضية تحتوي على عنصر MathEquationNode(OMath) واحد أو أكثر.|
| [`FractionEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/fractionequationnode) |تحدد هذه الفئة معادلة الكسور، التي تتكون من بسط ومقام، يفصل بينهما شريط كسور. يمكن أن يكون شريط الكسور أفقيًا أو قطريًا، حسب خصائص الكسور. تُستخدم معادلة الكسور أيضًا لتمثيل دالة المكدس، التي تضع عنصرًا فوق آخر، بدون شريط كسور.|
| [`FunctionEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/functionequationnode) | تحدد هذه الفئة معادلة تطبيق الوظيفة، والتي تتكون من اسم الوظيفة والحجة التي يتم العمل عليها.<br/> أنواع مكونات الاسم والحجة هي 'EquationNodeType.FunctionName' و'EquationNodeType.Base' على التوالي.|
| [`GroupCharacterEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/groupcharacterequationnode) | تحدد هذه الفئة وظيفة Group-Character، التي تتكون من حرف مرسوم أعلى أو أسفل النص، غالبًا بغرض تجميع العناصر بصريًا.|
| [`LimLowUppEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/limlowuppequationnode) | تحدد هذه الفئة دالة الحد.|
| [`MathematicalEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/mathematicalequationnode) | تُحدد هذه الفئة معادلةً أو تعبيرًا رياضيًا. تحتوي هذه الفئة على جميع النصوص الرياضية للمعادلات أو التعبيرات الرياضية.|
| [`MatrixEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/matrixequationnode) |تحدد هذه الفئة معادلة المصفوفة، التي تتكون من عنصر واحد أو أكثر موزعة في صف واحد أو أكثر وعمود واحد أو أكثر.|
| [`NaryEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/naryequationnode) | تحدد هذه الفئة معادلة عامل n-ary تتكون من عامل n-ary، وقاعدة (أو متغير)، وحدود علوية وسفلية اختيارية.|
| [`RadicalEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/radicalequationnode) | تحدد هذه الفئة المعادلة الجذرية، المكونة من درجة اختيارية deg(EquationNodeType.Degree) وقاعدة.|
| [`SubSupEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/subsupequationnode) | تحدد هذه الفئة معادلة يمكن أن تكون اختياريا علوية أو سفلية.<br/> هناك أربعة أشكال رئيسية لهذه المعادلة، العلوي والسفلي، العلوي والسفلي الموضوعين على يسار القاعدة، العلوي والسفلي الموضوعين على يمين القاعدة.|
| [`TextRunEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/textrunequationnode) | يتم استخدام هذه الفئة في عقدة المعادلة لتخزين المحتوى الفعلي (سلسلة من النص الرياضي) للمعادلة.<br/> عادة ما يكون كائن عقدة لكل حرف.|
| [`UnknowEquationNode`](/cells/python-net/ar/aspose.cells.drawing.equations/unknowequationnode) | فئة عقدة المعادلة من النوع غير المعروف|


###  التعدادات
| تعداد| وصف|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationcharacterpositiontype) | يحدد موضع كائن فرعي معين داخل الكائن الرئيسي الخاص به|
| [`EquationCombiningCharacterType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationcombiningcharactertype) | نوع من الجمع بين الشخصيات.|
| [`EquationDelimiterShapeType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationdelimitershapetype) |يحدد هذا شكل الفواصل في كائن الفاصل.|
| [`EquationFractionType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationfractiontype) | يحدد هذا نمط عرض شريط الكسر.|
| [`EquationHorizontalJustificationType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | يحدد هذا المحاذاة الأفقية الافتراضية للمعادلات في المستند.|
| [`EquationLimitLocationType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationlimitlocationtype) | يحدد موقع الحد على المشغل.|
| [`EquationMathematicalOperatorType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationmathematicaloperatortype) | نوع المعاملات الرياضية|
| [`EquationNodeType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationnodetype) | نوع عقدة المعادلة.<br/>يلاحظ:<br/>(1)[1-99] يوجد حاليًا عقدة واحدة فقط في النطاق، وقيمة العد الخاصة بها هي 1. يتم استخدام العقدة التي تحددها لتخزين النص الرياضي.<br/>(2)[100-199] يشير إلى أن العقدة هي أحد مكونات بعض عقد الوظائف الخاصة.<br/> (3)[200-] يشير إلى أن العقدة لديها بعض الوظائف الخاصة.|
| [`EquationVerticalJustificationType`](/cells/python-net/ar/aspose.cells.drawing.equations/equationverticaljustificationtype) | يحدد هذا المحاذاة الرأسية الافتراضية للمعادلات في المستند.|


