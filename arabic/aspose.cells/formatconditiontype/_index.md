---
title: FormatConditionType التعداد
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 2170
url: /ar/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType التعداد
نوع قاعدة التنسيق الشرطي.



يكشف النوع FormatConditionType عن الأعضاء التاليين:

###  مجالات
| مجال| وصف|
| :- | :- |
| CELL_VALUE | تقوم قاعدة التنسيق الشرطي هذه بمقارنة قيمة خلية<br/> إلى نتيجة محسوبة للصيغة، باستخدام عامل التشغيل.|
| EXPRESSION | تحتوي قاعدة التنسيق الشرطي هذه على صيغة لـ<br/>يقيم. عندما تكون نتيجة الصيغة صحيحة، تكون الخلية كذلك<br/> أبرز.|
| TOP10 | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا التي<br/>تقع القيم في قوس N العلوي أو السفلي، كما<br/> محدد.|
| UNIQUE_VALUES |تبرز قاعدة التنسيق الشرطي هذه فريدة من نوعها<br/> القيم في النطاق.|
| DUPLICATE_VALUES | تبرز قاعدة التنسيق الشرطي هذه التكرارات<br/> قيم.|
| CONTAINS_TEXT | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا<br/>تحتوي على نص معين. أي ما يعادل استخدام SEARCH ()<br/>دالة الورقة لتحديد ما إذا كانت الخلية تحتوي على أم لا<br/> النص.|
| NOT_CONTAINS_TEXT | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا التي<br/>لا تحتوي على نص معين. أي ما يعادل استخدام SEARCH ()<br/>دالة الورقة لتحديد ما إذا كانت الخلية تحتوي على أم لا<br/> النص أم لا.|
| BEGINS_WITH | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا الموجودة في ملف<br/>النطاق الذي يبدأ بالنص المحدد. أي ما يعادل<br/> باستخدام دالة الورقة LEFT() ومقارنة القيم.|
| ENDS_WITH | تقوم قاعدة التنسيق الشرطي هذه بتمييز نهاية الخلايا<br/>مع النص المحدد. أي ما يعادل استخدام ورقة RIGHT()<br/> وظيفة ومقارنة القيم.|
| CONTAINS_BLANKS | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا التي<br/>فارغة تماما. أي ما يعادل استخدام LEN(TRIM()).<br/>وهذا يعني أنه إذا كانت الخلية تحتوي على أحرف فقط<br/>التي ستزيلها TRIM()، فإنها تعتبر فارغة.<br/> تعتبر الخلية الفارغة فارغة أيضًا.|
| NOT_CONTAINS_BLANKS | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا التي<br/>ليست فارغة. أي ما يعادل استخدام LEN(TRIM()). هذا<br/>يعني أنه إذا كانت الخلية تحتوي على أحرف فقط<br/>ستتم إزالة TRIM()، ثم تعتبر فارغة. ان<br/> تعتبر الخلية الفارغة فارغة أيضًا.|
| CONTAINS_ERRORS | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا ذات<br/>أخطاء الصيغة. أي ما يعادل استخدام ورقة ISERROR()<br/> وظيفة لتحديد ما إذا كان هناك خطأ في الصيغة.|
| NOT_CONTAINS_ERRORS | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا<br/>بدون أخطاء في الصيغة. أي ما يعادل استخدام ISERROR()<br/> دالة الورقة لتحديد ما إذا كان هناك خطأ في الصيغة.|
| TIME_PERIOD | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا<br/>تحتوي على تواريخ في الفترة الزمنية المحددة. ال<br/>يتم تقييم القيمة الأساسية للخلية، وبالتالي<br/>لا تحتاج الخلية إلى تنسيقها كتاريخ<br/>تقييمها. على سبيل المثال، مع خلية تحتوي على<br/>القيمة 38913 يجب تطبيق التنسيق الشرطي إذا<br/> تتطلب القاعدة قيمة 14/7/2006.|
| ABOVE_AVERAGE | تقوم قاعدة التنسيق الشرطي هذه بتمييز الخلايا التي<br/>أعلى أو أقل من المتوسط لجميع القيم في<br/> يتراوح.|
| COLOR_SCALE | تقوم قاعدة التنسيق الشرطي هذه بإنشاء تنسيق متدرج<br/> مقياس اللون على الخلايا.|
| DATA_BAR | تعرض قاعدة التنسيق الشرطي هذه درجة متدرجة<br/> شريط البيانات في نطاق الخلايا.|
| ICON_SET | تطبق قاعدة التنسيق الشرطي هذه الرموز على الخلايا<br/> وفقا لقيمهم.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
