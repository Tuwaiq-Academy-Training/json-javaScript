
محتوى الملف:
- ماهو json
- مميزات json
- لماذا نستخدم JSON ؟
- أنواع بيانات JSON 



##  ماهو json

الJSON هو اختصار لـ JavaScript Object Notation، وهو تنسيق قياسي مفتوح، وهو خفيف الوزن وقائم على النص، مصمم صراحة لتبادل البيانات التي يمكن قراءتها من قبل الإنسان. ويعتبر تنسيق بيانات مستقل عن اللغة. ويدعم كل أنواع اللغة والإطار والمكتبات تقريبًا.
JSON هو معيار مفتوح لتبادل البيانات على الويب. يدعم هياكل البيانات مثل الكائنات والمصفوفات. لذلك، من السهل كتابة وقراءة البيانات من JSON.
  يتم تمثيل البيانات في أزواج قيمة المفتاح، وتحمل الأقواس المجعدة الكائنات، حيث يتم اتباع colon  بعد كل اسم. يتم استخدام الفاصلة لفصل أزواج قيمة المفتاح. تُستخدم الأقواس المعكوفة لحمل المصفوفات، حيث تكون كل قيمة منفصلة عن الفاصلة.
   
  1- يرمز JSON إلى JavaScript Object Notation.
  
  2- الJSON هو تنسيق قياسي مفتوح لتبادل البيانات.
  
  3-  خفيف الوزن ويصف نفسه بنفسه
  
  4- نشأ JSON من JavaScript.
  
  5- الJSON سهل القراءة والكتابة.
  
  6-  هي لغة مستقلة.
  
  7- يدعم JSON هياكل البيانات مثل المصفوفات والأشياء.
  
  
  ## لماذا نستخدم JSON 
  
  نظرًا لأن JSON هو تنسيق تبادل بيانات لغة سهل الاستخدام وخفيف الوزن مقارنة بالخيارات المتاحة الأخرى، فيمكن استخدامه لتكامل واجهة برمجة التطبيقات. فيما يلي مزايا JSON:
  
- الLess Verbose: على عكس XML، تتبع JSON أسلوبًا مضغوطًا لتحسين إمكانية قراءة مستخدميها. أثناء العمل مع نظام معقد، تميل JSON إلى إجراء تحسينات كبيرة.
- أسرع: عملية تحليل JSON أسرع من عملية XML لأن مكتبة التلاعب DOM في XML تتطلب ذاكرة إضافية للتعامل مع ملفات XML الكبيرة. ومع ذلك، تتطلب JSON بيانات أقل تؤدي في النهاية إلى تقليل التكلفة وزيادة سرعة التحليل.
- يمكن قراءته: يمكن قراءة هيكل JSON بسهولة ومباشرة. بغض النظر عن لغة البرمجة التي تستخدمها، يمكنك بسهولة رسم خريطة لكائنات المجال.
- البيانات المهيكلة: في JSON، يتم استخدام هيكل بيانات الخريطة، بينما يتبع XML هيكل الشجرة. تحد أزواج القيمة الرئيسية من المهمة ولكنها تسهل النموذج التنبؤي والذي يمكن فهمه بسهولة.

## أنواع بيانات JSON

| نوع البيانات  | الوصف | مثال |
|:---:|:------:|:------:|
|  String  |تُكتب السلسلة دائمًا باقتباسات مزدوجة. قد تتكون من أرقام وأبجدية وحروف خاصة. |"student", "name", "1234", "Ver_1" |
|  Number  |يمثل الحروف الرقمية.|	121, 899 |
|  Boolean   | يمكن أن يكون إما صحيحًا أو خاطئًا| true |
|  Null   |  قيمة فارغة|  | 
