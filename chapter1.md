بسم الله الرحمن الرحيم
===================

اللهم اجعل هذا العمل خالصا لوجهك الكريم

مقدمه عامه

- ضرورة الترجمة
- انا لا نضيع اجر من احسن عملا 
- عن العلماء العرب والحضاره الاسلامية 

إهداء
===========


الى كل عشاق المصادر المفتوحه ... الى كن من يرغب في التعلم التطبيقات الحره .... الى كل المتطوعين ... الى كل من يرغب في تطوير
واثراء المحتوى العربي .

الى كل من شجعني في البدء في هذا المشروع ...

اليكم جميعا الى كل المتطوعين والمؤثرين في المجتمع


تقديم
=============



ستتعلم في هذا الكتاب مايلي
===============
- كيف يعمل الحاسب الآلي
- كيف تستيطع تجزئة المشاكل المعقده الى مجموعه من الوظائف التي يسهل ادارتها
- كيف تبني برمجيات سوفت وير وهاردوير ذات نطاق عالي
- كما ستجد مقترحات في نهاية كل فصل للراغبين في التطوير 
هذا سوف يبدأ الكتاب من البداية اساسيات الكمبيوتر حتى تستطيع بناء التطبيقات الخاصة بك ... بداية من مستوى المبتدئين. ايضا
سوف تتعلم كيف تبني حاسب الى متكامل من الالف للياء ... وما سوف تكتسبه فيما ستعلمه اكثر اهميه بكثير من الكمبيوتر نفسه الذي
سوف تبنيه ..


يتكون الكتاب من جزئين جزء خاص بالهارد وير (hardware)
والجزء الاخر خاص بالبرمجيات (software)
- مقدمه عامه
- الجبر المنطقي (Boolean Logic)
- الجبر الحسابي (Boolean Arithmetic)
- التصميم المنطقي (Sequential Logic)
- لغة الآله (Machine Language)
- عماره الحاسب (Computer Architecture)
- لغة التجميع (Assembler)
- الخوارزميات (Algorithms)
- الجهاز الافتراضي - المكدسه الحسابيه (VM I: Stack Arithmetic)
- التحكم بالبرنامج (VM II: Program Control)
- اللغات العالية المستوى (High-Level Language)
- المترجم - التحليل اللغوي (Compiler I: Syntax Analysis)
- المترجم - توليد الكود (Compiler II: Code Generation)
- انظمه التشغيل (Operating System)
- ابدأ بنفسك واطلق تطبيقاتك


ستتعلم في هذا الفصل 
-----------

نظرة حول لغات البرمجة
=====================
اذا كانت لديك اي خلفية مسبقة باي من لغات البرمجة .. اذا فربما تكون قد واجهت برنامج مثل هذا البرنامج في اي من الفصول
التعليمية ... هذا البرنامج مكتوب بلغة الجافا


```
class HelloWorldApp {
    public static void main(String[] args) {
        System.out.println("بسم الله"); // Display the string.
    }
}
```

البرامج البدائية مثل (hello world)
في غاية البساطه .. ولكن هل فكرت ماذا يحدث لكي تقوم هذه العملية وتظهر كلمة بسم الله على الشاشه
لننظر بعمق اكثر .. هذا البرنامج ليس مجرد الا مجموعه من الحروف مخزنه على ملف بصيغه (txt)
اذا فأول شئ ينبغي علينا فعله ان نقوم بمعالجه (parse)
هذا الملف لكي يفهم محتوى الملف (semantics)
ثم اعادة صيغة هذا الملف باللغات المستوى المنخفض مثل لغة الاله او لغة التجميع
لكي يقوم الكمبيوتر بفهم محتوى هذا الملف .
تسمى هذه العمليه بالتصنيف (compilation)
ينتج عنها ملف نصي اخر ولكن هذه المرة بلغة الآله



عن اختراع رقم الصفر
==================
يعد الصّفر أوّل الأعداد وأكثرها تبسيطا وأشدها شهرة ودهشة واستعمالا وأهميّة وروعة الصفر ذلك الرمز الذي يشير إلى اللاشيء ويعبر عنه باستخدام العلامة (.), هل تتخيل كم عانت البشرية قبل اكتشافه؟
وقد يظن الإنسان للوهلة الأولى أن الصفر الذي يعبر عن اللا قيمة هو أيضاً عديم القيمة وهذا خطأ كبير ولكي نتعرف كم يساوي الصفر في حياة البشرية يجب أولاً أن نستعرض رحلة البشرية نحو اكتشاف الصفر.
ويعتبر الخوارزمي (780 – 850)م. ، من أبرز علماء العرب والعالم في الرياضيات ، وقيل إنه هو الذي ابتكر الصّفر وجعله عددا مهما في العمليات الحسابية . واستعمل العرب النقطة لتدلّ إلى الصّفر ، وبيّنوا دوره في العمليات الحسابية ، وأهميّته في تحديد مراتب العشرات والمئات والألوف .
نظام العد الثنائي (بالإنجليزية: binary numeral system) هو نظام عد ذو رقم أساس 2، يستخدم لتمثيل قيم عددية باستخدام رمزين ،عادة ما يكونان، 0 و 1. كما يمكن استخدام أي رمزين أو حالتين مثل 0 و1 أوصح وخطأ أوتشغيل وإطفاء. بسبب سهولة تنفيذه مباشرةً في البوابات المنطقية والإلكترونيات الرقمية فإن نظام العد الثنائي مستخدم عملياً في كل الحواسب الحديثة.



لغة الآلة
==================
كما هو ملاحظ فأن لغة الآله مبنيه على النظام الثنائي الذي يتكون بطبعه من الرقمين الصفر والواحد  .. ومع النظر الى هيكله 
الحاسب الآلي ستجد انه يتكون من مجموعه من المكونات الاساسيه :-
- المسجلات (registers)
- وحدة الحساب والمنطق (ALU)
- بالاضافة الى وحدات الادخال والاخراج
- 

وبالنظر بصورة اكثر دقه لكل مكون من مكونات الحاسب الآلي سنجد انها تتكون من مجموعه من البوابات المنطقيه (Logic Gates)
مثل ال NAND - NOR - OR 
وبالاستمرار بنظرة تحليله سنجد ان كل واحده تتكون من مجموعه من المبدلات (switching devices)
والقلابات flip flop
التي بدورها تتكون من مجموعه من الترانزستورات (transistors)
وسنكتفي بهذا الحد لان الى هنا تنتهي علوم الحاسب حيث يبدأ دور الفيزائيون ولكن للاطلاع اكثر عن تكوين الترانزستور يمكنك
زيارة الرابط التالي من الموسوعه الحره ويكيبيديا
http://ar.wikipedia.org/wiki/%D9%85%D9%82%D8%AD%D9%84


اذا لماذا كل هذا التعب  والكمبيوتر يقوم بكل شئ
==============================================
ربما عليك التفكير اذا لماذا نقوم بكل شئ من البداية ...وكل ماعلي فعله في الحاسب ان اضغط على مجموعه من الملفات
والكمبيوتر  يقوم بكل شئ  عن طريق مجموعه من الاوامر  (commands)
في الحقيقه اجهزة الكمبيوتر الحديثه ماهي الا عباره عن مجموعه من جبال الجليد الضخمه  نحن لا نشاهد الا القمم فقط
ولا نستيطع رؤية اي شئ اخر بخلاف القمم ... لذلك فاننا نجد ان معرفتنا بانظمه الحاسب الالي سطحيه جدا 
اذا اردت ان تتعمق اكثر لتكتشف معنا هذا الجبل الجليدي ستجد ان هناك عالم آخر اكثر روعه مما يمكنك ان تتخيل 
بالفهم العميق لهذه العلوم هذا مايميز المبرمج العادي عن المبرمج المتميز وسوف تساعدك على تخيل كيفيه بناء تطبيقات معقده
ومبتكره وكيف يعمل الكمبيوتر من البداية وحركه كل الكترون داخل الكمبيوتر 



البدء من لاشئ
==================
ربما يتسائل البعض كيف يمكننا تصميم كمبيوتر من الالف للياء من اللاشئ...  
سوف نقوم بتجزيئ الكمبيوتر لتبسيط تركييبه المعقد الى مجموعه من الدوائر الالكترونية والبوابات المنطقية البسيطه 
وسوف يتم شرح كل مكون من مكونات الكمبيوتر في فصل منفصل

ربما يتسائل البعض كيف يمكن عزل كل مكون من هذه المكونات وشرحه في فصل على حدى ..
هناك طريقه دايما يستخدمها المصممون وهي ان تجزء التصميم الى مجموعه من المكونات وان تعمل على كل وحدة على حدى وان تتجاهل 
تماما بقية التصميم ....  كما يمكنك بناء هذه المكونات باي ترتيب تريده

هناك مصطلح دائما نشير اليه في هذا الصدد (abstractions)
يستخدم هذا المصطلح في كثير من العلوم والتكنولوجيا ودائما مايستخدم للتبسيط
يستخدم مصطلح التجريد في علوم الحاسب بصفه دائما لاننا عادة مانسئل ...وظيفه هذه الاداه ... ولا يهمنا بقية التفاصيل كيف تفعل هذه الوظيفه 

هذا الوصف التوظيفي يجب ان يحدد كل مايجب ان تعرفه لكي تستخدم هذه الاداه بالاضافه الى تحديد وظائفها لكي تستخدمها الاستخدام الامثل بغض النظر عن ال تفاصيل الداخليه بالاداه....  هناك دائما بعض التفاصيل التي يتم اخفائها عن المستخدم للتبسيط عليه في استخدام الاداه لانها ببساطه ليست ذات صلة بطريقه العمل .

دائما في هندسه البرمجيات مانستخدم مصطلح الواجهات (interfaces)
حيث يتكون التطبيق من مجموعه من الطبقات المتتاليه (layers)

صورة layers فوق بعض
فتستخدم الواجهات لبناء طبقات متتاليه او ربما تكون جيده لجعل مجموعه من مهندسي البرمجيات البدء عند مانتهى اليه الاخرين 

تصميم نموذج جيد للتجريد يحتاج موهبه حقيقه   (Abstraction)
في هذا الكتاب سنسعى في كل فصل ان نقوم بفك نموذج مجرد من مكونات الحاسب الآلي على حدى سواء كان في البرمجيات او الالكترونيات مع تصميم نموذج للتطبيق على كل فصل في هذا الكتاب ... بفضل النموذج التجزيئ الذي يعتمد بدوره على التجريد
في كل فصل سيهتم القارئ بالتركيز على 
- فهم الاداة التي تم تجريدها في كل فصل
- كيفيه بناء هذه الاداه
- كيفيه التطوير من هذه الاداة باضافة مميزات مقترحه 


نماذج معالجه المعلومات
=============
من الإستراتيجيات التي تستخدم في معالجة المعلومات وترتيب المعرفة وغالبا ما تتطلب استخدام البرمجيات ونظريات إنسانية وعلمية ويمكن النظر إلى هاتين الطريقتين عمليا كنظامي تفكير وتعليم. تستخدم طريقة التصميم من أعلى إلى أسفل في كثير من الحالات كمرادف لمصطلح التحليل أو تقسيم المشكلة إلى وحدات صغيرة بينما تستخدم طريقة التصميم من أسفل إلى أعلى كمرادف لمفهوم التخليق أو الاصطناع.


يوجد طريقتان لعرض كيفيه تصميم الحاسب الآلى
- من الاعلى للاسفل (top-down)
- من الاسفل للأعلى (bottom-up)


إن طريقة التصميم من أعلى لأسفل (وتعرف أيضا بالتصميم المتدرج) هي أساسا عبارة عن تحليل النظام بهدف اكتساب المعرفة بالنظم الفرعية التركيبية الخاصة به. تصاغ النظرة العامة للنظام في طريقة التصميم من أعلى لأسفل بحيث تحدد ولا تفصل أي أنظمة فرعية من المستوى الأول. تتم بعد ذلك تنقية النظام الفرعي بتفصيل أكبر وأحيانا في مستويات فرعية إضافية إلى أن يتم تقليص كامل المواصفات إلى العناصر الأساسية. غالبا ما يتم تحديد مواصفات نموذج التصميم من أعلى إلى أسفل بمساعدة "الصناديق السوداء" مما يساعد في تسهيل معالجتها. ومع ذلك قد يفشل اختبار الصناديق السوداء في توضيح الآليات الأساسية لعمل هذه الطريقة أو في أن يكون مفصلا كفاية لتقييم صحة النموذج بشكل واقعي.

أما طريقة التصميم من أسفل لأعلى فهي عبارة عن دمج أجزاء الأنظمة معا لإنشاء نظم أكثر ضخامة وبذا يتكون نظام ناشئ هو عبارة عن تجميع للأنظمة الفرعية الخاصة بالأنظمة الأصلية. يتم في هذا التصميم تحديد العناصر الأساسية المنفردة للنظام أولا في تفصيل كبير، من ثم ربطها معا لتكون أنظمة فرعية أكبر حجما يتم ربطها بدورها مع بعضها على مستويات عدة أحيانا إلى أن يتم تشكيل نظام مكتمل عالي المستوى في النهاية. تشبه هذه الطريقة غالبا نموذج "بذرة" حيث تكون البدايات صغيرة ولكنها تنمو في النهاية لتكون أكثر تعقيدا واكتمالا. على أي حال فقد تتمخض هذه "الإستراتيجيات العضوية" عن تشابك العناصر والأنظمة الفرعية التي يتم تطويرها بشكل معزول لتصير موضوعا للتحسين المحلي مقابل العمل على التوافق مع غرض عالمي للنظام.


في هذا الكتاب سوف نستخدم طريقه من الاسفل لاعلى حيث سنبدأ بابسط مكونات الحاسب الالي بداية من البوابات المنطقية ثم سنرتفع بالمستوى الى ان نصل الى تصميم كمبيوتر متعدد الاغراض


اللغات العالية المستوى (High-Level Language)
==========================================
هي لغة برمجة لا تعرض المبرمج إلي تفاصيل تطبيق أوامر اللغة على مستوى عتاد الحاسوب. يعتبر هذا النوع من اللغات أسهل في استخدامه لأنه يستخدم في مفرداته كلمات قريبة للفهم، وجمله تكون أقرب للغات الطبيعية منها إلى لغة التجميع بعكس لغات البرمجة منخفضة المستوى. من أمثلة لغات البرمجة عالية المستوى: جافا وسي شارب


اذا اردنا مثال على ذلك 
```
 Output.printString(‘‘Hello World’’)
 ```
 
 هذا الكود يقوم باستدعاء مكتبة لطباعه او إظهار كلمة بسم الله على الشاشه من مكتبة في مكان ما ... في الحقيقه هناك الكثير من العمليات تحدث داخل نظام التشيغل لكي يحدث هذا الأمر 
 سنتعرف اكثر مايحدث داخل نظام التشغيل وهذه المكتبات لاحقا ... كما سنتعرف على كيفيه كتابه اوامر لغات البرمجة في الفصول القادمه باذن الله 



نظرة الى عالم الالكترونيات والهاردوير
===================================
قبل ان  يعمل اي برنامج وان يقوم باي عمليات حسابيه او تتم معالجته يجب تحويل اوامر هذا البرنامج الى لغة الآلة ... هذه العملية يمكن تقسيمها الى عدة مراحل :-
- المترجم (Compiler)
- الآله الافتراضية (virtual machine)
- المجمع (Assembler)

تتم عملية الترجمه على مرحلتين اساسيتين 
- تحليل الجمل (syntax analysis)
- توليد الكود (code generation)

في المرحله الاولى يتم تحليل النصوص الى جمل يستطيع الحاسب الالي فهمها والتعامل معها ويتم هيكلتها على صورة  شجريه (parse tree) 
لاحقا سيتم شرح كيف يمكن عن طريق هذه الصورة الشجريه الوصول الى لغات برمجة متوسطة المستوى ... الكود الناتج من المترجم يمكن نفسيره بانه مجموعه من الخطوات تستطيع فهمه الألى الافتراضية لكي يقوم بتنفيذ وظيفه ما ... وبما ان الناتج من الآله الافتراضية يكون بلغه التجميع  يتم ترجمته لاحقا الى لغة الالة بالنظام الثنائي


الى قاع الالكترونيات 
====================
والان وصلنا من لغة الالة الى الالة نفسها  ... النقطه التي يلتقي عندها البرمجيات والخوارزميات بالالكترونيات .... النقطه التي عندها نكون انتهينا من تصميم جهاز الحاسب متعدد الاغراض ... لغة الالة سيتم شرحها في الفصول القادمه بالاضافة الى تصميم النموذج الاولي للحاسب يجب مرعاه المكونات الالية للحاسب من الذاكره العشوائية و المسجلات ووحدة الحساب والمنطق سيتم شرح كل وحدة منهم على حده في الفصول القادمه


ماسوف نفعله الآن باذن الله
1- سنبدأ بتصميم الدوائر المنطقيه (Logic Gates)
2- ثم تصميم الدوائر المتتابعه والتوافقيه  (combinational and sequential chips)
3- ثم سننتقل الى عماره الحاسب والمكونات المميزة للحاسب الآلي (Computer Architecture)
وبهذا نكون انتهينا من الالكترونيات ونبدا رحله جديده في عالم البرمجيات
1- معنى البرمجيات
2- الخوارزميات
3- المترجم
4- بناء لغة برمجة
5- بناء نظام التشغيل


ثم بناء التطبيقات الخاصه بك




المصادر مع كل جزئية

نهاية المقدمه

ماجد الجزار
