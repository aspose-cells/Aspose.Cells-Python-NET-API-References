---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.drawing.equations/
is_root: false
---
**Aspose.Cells.Drawing.Equations** Пространство имен предоставляет классы для создания различных форм уравнений (таких как дробные уравнения, степенные уравнения и т. д.) с помощью узлов уравнений.

###  Классы
| Сорт| Описание|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/accentequationnode) | Этот класс определяет уравнение ударения, состоящее из базового компонента и соединительного диакритического знака.|
| [`ArrayEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/arrayequationnode) | Задает функцию Equation-Array, объект, состоящий из одного или нескольких уравнений.|
| [`BarEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/barequationnode) |Этот класс определяет уравнение черты, состоящее из базового аргумента и черты сверху или снизу.|
| [`BorderBoxEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/borderboxequationnode) | Этот класс определяет функцию Border Box, представляющую собой рамку, нарисованную вокруг уравнения.|
| [`BoxEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/boxequationnode) | Этот класс определяет функцию ящика, которая используется для группировки компонентов уравнения.|
| [`DelimiterEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/delimiterequationnode) | Этот класс определяет уравнение разделителя, состоящее из открывающих и закрывающих разделителей (таких как круглые скобки, фигурные скобки, квадратные скобки и вертикальные черты), а также компонента, содержащегося внутри.<br/> Разделитель может иметь более одного компонента, между каждым компонентом должен быть назначен символ-разделитель.|
| [`EquationComponentNode`](/cells/python-net/ru/aspose.cells.drawing.equations/equationcomponentnode) | Этот класс определяет компоненты уравнения или математического выражения.<br/>Различные типы компонентов объединены в различные уравнения.<br/>Например, дробь состоит из двух частей: числителя и знаменателя.<br/> Дополнительные типы компонентов см. в разделе «EquationNodeType».|
| [`EquationNodeParagraph`](/cells/python-net/ru/aspose.cells.drawing.equations/equationnodeparagraph) | Этот класс определяет математический абзац, содержащий один или несколько элементов MathEquationNode(OMath).|
| [`FractionEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/fractionequationnode) |Этот класс определяет уравнение дроби, состоящее из числителя и знаменателя, разделённых дробной чертой. Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Уравнение дроби также используется для представления стековой функции, которая размещает один элемент над другим без дробной черты.|
| [`FunctionEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/functionequationnode) | Этот класс определяет уравнение «функция-применение», которое состоит из имени функции и аргумента, над которым выполняется действие.<br/> Типы компонентов имени и аргумента — «EquationNodeType.FunctionName» и «EquationNodeType.Base» соответственно.|
| [`GroupCharacterEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/groupcharacterequationnode) | Этот класс определяет функцию Group-Character, состоящую из символа, нарисованного над или под текстом, часто с целью визуальной группировки элементов.|
| [`LimLowUppEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/limlowuppequationnode) | Этот класс определяет предельную функцию.|
| [`MathematicalEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/mathematicalequationnode) | Этот класс определяет уравнение или математическое выражение. Весь математический текст уравнений или математических выражений содержится в этом классе.|
| [`MatrixEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/matrixequationnode) |Этот класс определяет матричное уравнение, состоящее из одного или нескольких элементов, расположенных в одной или нескольких строках и одном или нескольких столбцах.|
| [`NaryEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode) | Этот класс определяет уравнение n-арного оператора, состоящее из n-арного оператора, основания (или операнда) и необязательных верхней и нижней границ.|
| [`RadicalEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/radicalequationnode) | Этот класс определяет радикальное уравнение, состоящее из необязательной степени deg(EquationNodeType.Degree) и основания.|
| [`SubSupEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/subsupequationnode) | Этот класс определяет уравнение, которое может быть как надстрочным, так и подстрочным.<br/> Существует четыре основных формы этого уравнения: надстрочный индекс, подстрочный индекс, надстрочный и подстрочный индекс, размещенные слева от основания, надстрочный и подстрочный индекс, размещенные справа от основания.|
| [`TextRunEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/textrunequationnode) | Этот класс в узле уравнения используется для хранения фактического содержимого (последовательности математического текста) уравнения.<br/> Обычно на каждого персонажа приходится один узловой объект.|
| [`UnknowEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/unknowequationnode) | Класс узла уравнения неизвестного типа|


###  Перечисления
| Перечисление| Описание|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationcharacterpositiontype) | Указывает положение конкретного подобъекта внутри его родительского объекта.|
| [`EquationCombiningCharacterType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationcombiningcharactertype) | Тип объединения символов.|
| [`EquationDelimiterShapeType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationdelimitershapetype) |Это определяет форму разделителей в объекте разделителя.|
| [`EquationFractionType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationfractiontype) | Это определяет стиль отображения дробной черты.|
| [`EquationHorizontalJustificationType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Это определяет горизонтальное выравнивание уравнений в документе по умолчанию.|
| [`EquationLimitLocationType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationlimitlocationtype) | Указывает предельное местоположение оператора.|
| [`EquationMathematicalOperatorType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Тип математических операторов|
| [`EquationNodeType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationnodetype) | Тип узла уравнения.<br/>Уведомление:<br/>(1)[1-99] В настоящее время в области действия имеется только один узел, и его значение перечисления равно 1. Указанный им узел используется для хранения математического текста.<br/>(2)[100-199] Указывает, что узел является компонентом некоторых специальных функциональных узлов.<br/> (3)[200-] Указывает, что узел имеет некоторые специальные функции.|
| [`EquationVerticalJustificationType`](/cells/python-net/ru/aspose.cells.drawing.equations/equationverticaljustificationtype) | Это определяет вертикальное выравнивание уравнений в документе по умолчанию.|


