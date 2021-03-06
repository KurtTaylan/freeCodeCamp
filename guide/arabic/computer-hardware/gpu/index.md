---
title: GPU
localeTitle: GPU
---
## GPU

GPU لتقف على وحدة معالجة الرسومات. تستخدم غالبية أجهزة الكمبيوتر هذه لتقديم مقاطع الفيديو أو تشغيل ألعاب الفيديو.

وحدة معالجة الرسوميات تشبه وحدة المعالجة المركزية ولكن لها نقاط قوة ونقاط ضعف مختلفة. وحدات المعالجة المركزية (CPU) جيدة جداً في تشغيل بعض المهام بسرعة كبيرة. GPUs أفضل بكثير في تشغيل العديد من المهام في نفس الوقت ، ولكن أبطأ. يمكن لوحدة GPU النموذجية تشغيل أكثر من 10000 مهمة ، ولكن لتشغيل العديد من المهام في نفس الوقت يجب أن تشارك الذاكرة والموارد الأخرى. GPUs عادة ما تقوم بمهام متكررة للغاية مرارا وتكرارا لحفظ وحدة المعالجة المركزية من إهدار الوقت. تحتوي بعض وحدات المعالجة المركزية (CPUs) على وحدات معالجة رسومية (GPU) مدمجة ، ولكن وجود وحدة معالجة رسومات منفصلة يكون دائمًا أكثر قوة.

يمكن استخدام وحدات معالجة الرسوم الرسومية (GPU) في الحساب وكذلك عرض الفيديو. تتضمن الطرق الشائعة للقيام بذلك OpenACC و CUDA و OpenCL و OpenGL. تتضمن بعض التطبيقات تطبيقات GPU لتقليل مقدار الوقت الذي يستغرقه التطبيق للتشغيل.

تم استخدام وحدة معالجة الرسوميات في الأصل بشكل أساسي لعرض لعبة ثلاثية الأبعاد لتحسين الدقة والتحكم. ولكن الآن يتم تسخير هذه القدرات على نطاق أوسع لتحسين أحمال العمل الحسابية في العديد من المجالات ؛ على سبيل المثال النمذجة المالية والبحث العلمي المتطور واستكشاف النفط والغاز. تستخدم GPU أيضًا كمصدر لتعدين البيتكوين ، حيث إنها قادرة على تشغيل المهام المتكررة بسهولة دون إجهاد موارد وحدة المعالجة المركزية ، والتي تسمح لك بتشغيل نظام التشغيل على الكمبيوتر باستخدام وحدة معالجة مركزية منخفضة في حين لا تزال قادرة على bitcoin mine باستخدام GPU

هناك نوعان من العلامات التجارية الرئيسية التي تنتج GPUs: NVidia و AMD. وغالبًا ما يشار إليهم بـ "الفريق الأخضر" و "الفريق الأحمر" الذي يشير إلى اللون الرئيسي لشعارهم.

وتشمل أبرز صانعي GPU: Nvidia و AMD / ATI.

## أصل GPU

يمكن تعيين الخلفية الأكثر بدائية من GPU إلى عصر وحدات تحكم VGA (Virtual Graphics Array). لكن هذه لم تكن في الواقع وحدة معالجة كاملة ، ولكنها عملت كوحدات داعمة لوظائف العرض. وحدة تحكم VGA هي وحدة تحكم بسيطة في الذاكرة متصلة بذاكرة الوصول العشوائي الديناميكية ومولد العرض. تتمثل الوظيفة الرئيسية لـ VGA في تلقي بيانات الصورة وترتيبها بشكل صحيح وإرسالها إلى جهاز فيديو ، والذي كان بشكل أساسي شاشة كمبيوتر أو شاشة تلفزيون متصلة بوحدة تحكم للألعاب للعرض.

تم تطوير وتسويق أول وحدة معالجة متكاملة من أجل التسارع التصويري بواسطة NVIDIA في عام 1999 ، "GeForce 256". كان على المسرعات الأقدم 3D الاعتماد على وحدة المعالجة المركزية (CPU) لتنفيذ العمليات الحسابية الرسومية. مع "GeForce 256" الجديد كمعالج مشترك للمعالج ، تحسن معدل الإطارات بأكثر من 50٪ وخفض التكلفة الإجمالية ، وبالتالي توسعت في السوق الاستهلاكية.

## GPU مقابل وحدة المعالجة المركزية

تم تحسين وحدة المعالجة المركزية للحد الأدنى من زمن الوصول ، أي "لتتمكن من تنفيذ أكبر قدر ممكن من التعليمات التي تنتمي إلى سلسلة محادثات فردية ، في نافذة زمنية محددة". يجب أن يتمكن المعالج من التبديل بسرعة بين العمليات. من أجل الحصول على الكثير من زمن الوصول على وحدة المعالجة المركزية ، هناك الكثير من البنية التحتية في وحدة المعالجة المركزية مثل مخابئ كبيرة للبيانات لتكون متاحة بسهولة للتنفيذ ، والكثير من وحدات التحكم لتنفيذ عمليات الإعدام خارج نطاق ، وعدد قليل من النوى ALU. تم تصميم ISA للمعالج بطريقة أكثر عمومية ويمكنه تنفيذ نطاق واسع من العمليات. بينما تم تصميم وحدة المعالجة المركزية للحسابات والإرشادات العامة ، تطورت GPU للحسابات الرسومية. يجب إجراء نفس الحساب على مئات وآلاف وحدات البكسل من أجل تقديم الرسومات ثنائية / ثلاثية الأبعاد. وبالتالي ، تم تحسين وحدات معالجة الرسومات (GPU) بشكل أساسي لتحقيق أقصى قدر من الإنتاجية. يتم تنفيذ هذا باستخدام أطنان من ALUs في بنية واحدة. يتم تقليص ذاكرة التخزين المؤقت L2 لأنه حتى يتم جلب البيانات من DRAM ، فإن نواة GPU لديها الكثير من العمليات الحسابية ، مما يؤدي إلى تداخل وقت وحدة المعالجة المركزية بالتوازي الهائل. هذا هو المعروف باسم الاختباء الاختباء.

## تطور العمارة GPU

صممت وحدات معالجة الرسومات في الأصل على مفهوم خط أنابيب الرسومات. خط أنابيب الرسومات هو نموذج نظري ، يشتمل على مستويات كيفية إرسال بيانات الرسومات من خلال وتنفيذها باستخدام GPU والبرامج (مثل OpenGL و DirectX). يقوم خط الأنابيب بشكل أساسي بتحويل الإحداثيات المكانية ثلاثية الأبعاد إلى بيانات ثنائية الأبعاد للجهاز ليتم عرضها. ما يلي هو توضيح "خط أنابيب الرسومات ذات الوظيفة الثابتة التقليدية" ، خط أنابيب مقبول بشكل عام حتى اليوم.

### الجيل 0th

لوحة "Reality Engine" من شركة Silicon Graphics Inc. (SGI) وضعت علامة على بداية أجهزة GPU وخطوط الرسومات. لكن التكنولوجيا كانت لا تزال تعتمد على وحدة المعالجة المركزية للنصف الأول. أيضا ، كانت السرعة تقتصر على تنفيذ بكسل واحد في دورة الساعة. يستخدم المحرك برنامج OpenGL ، وهو برنامج تطبيق ثنائي الأبعاد وثلاثي الأبعاد يستخدم على نطاق واسع.

### 1stGeneration

تطورت لعبة "3dfx Voodoo" (1996) كأحد أول مسرع ثلاثي الأبعاد حقيقي للألعاب. لقد تعاملت مع رسم الملمس ، والتنقيط ، والتخزين المؤقت z ولكن كان لا يزال على وحدة المعالجة المركزية القيام بتحويلات قمة الرأس.

### 2ndGeneration

هذه هي النقطة التي تم فيها إطلاق أول معالج جرافيكس حقيقي من نوع NVIDIA "GeForce 256" في السوق المشتركة. قدمت وحدات معالجة الرسومات (GPU) الخاصة بمنفذ الرسومات المسرَّعة هذا الجيل (AGP) وظائف جديدة مثل التعدد ، وتحويل هندسة الأجهزة ، والخرائط الخفيفة ، والإضاءة. ويعرف خط الأنابيب التقليدي بأنه خط أنابيب "وظيفة ثابتة" ، لأنه بمجرد أن يرسل المطور بيانات الرسومات إلى خط أنابيب GPU ، لا يمكن تغيير البيانات.

### الجيل الثالث

مع هذا الجيل من وحدات المعالجة المركزية ، ظهرت خطوط الأنابيب القابلة للبرمجة. الآن يمكن برمجة الأجزاء غير القابلة للبرمجة من قبل المبرمجين. في عام 2001 ، أصدرت NVIDIA GeForce3.

### الجيل الرابع

مع بداية القرن 21 ، وصلت أول "بطاقات الرسومات القابلة للبرمجة بالكامل" للمستهلكين. كان NVIDIA GeForce FX و ATI Radeon 9700 من بين الأوائل. يمكن لوحدات معالجة الرسومات هذه إجراء عمليات لكل بكسل إلى جانب تظليل وحدات البكسل وبرأس قابل للبرمجة. ولكن ، هناك حاجة إلى أجهزة منفصلة مخصصة لتظليل قمة الرأس ومعالجة تظليل بكسل.

### الجيل الخامس

كانت وحدات معالجة الرسوميات تتطور وتتقدم بمعدل الذروة ، وكانت وحدات معالجة الرسوميات من الجيل هذه أول من استخدم ناقل PCI-express. تم تقديم المخازن المؤقتة للعرض المتعدد ، ودعم 64 بت ، وإمكانية الوصول إلى النسيج ، إلى جانب الزيادة في ذاكرة وحدة معالجة الرسومات.

### الجيل السادس

في عام 2006 ، أحدث إصدار GPU Series 8 من NVIDIA ثورة في صناعة GPU والوصول إليها ، من خلال إدخال GPU كمعالجات متوازية بشكل كبير. كان أول من يمتلك تظليل "موحد" و "قابل للبرمجة" ، أو بمعنى آخر ، معالج موحد قابل للبرمجة. الوحدة الموحدة تعني تنفيذ جميع عمليات خطوط الرسومات على معالج واحد وليس هناك حاجة إلى وحدة خارجية لأي مرحلة. المكونات الأساسية لمعالجات GPU الموحدة موضحة أدناه.

منذ إطلاق سلسلة NVIDIA GPUs 9XX ، ازداد أداء الأداء بين الأجيال فقط. من 980Ti إلى 1080Ti و 208Tis الذي تم إطلاقه حديثًا ، ازداد الأداء إلى أكثر من الضعف. كما بدأت AMD في إنتاج وحدات معالجة رسومية أفضل مثل RX 580 و Vega 64 ، على الرغم من أن هذا لا يزال في أي مكان بالقرب من مستوى Nvidia. في الآونة الأخيرة ، أطلقت Nvidia خطًا جديدًا من GPUs بعنوان RTX الذي يتضمن البطاقات الأعلى مثل 2080Ti و 2080 و 2070. يقف RTX لـ "Ray Tracing" ، وهي تقنية عرض تستخدم في توليد الصور على الرغم من تتبع مسار الضوء في مشهد.

## المكونات الأساسية لمعالجات GPU الموحدة

تستند أبنية GPU الموحدة على مجموعة متوازية من العديد من المعالجات القابلة للبرمجة ، حيث جميع مراحل خطوط إنتاج الرسومات ، أي ، قمة الرأس ، والهندسة ، والتنقيط ، ومعالجة تظليل البكسل والحسابات المتوازية على نفس القلب ، على النقيض من وحدات معالجة الرسومات السابقة. تتكامل مجموعة المعالجات بشكل كبير مع معالجات المهام الثابتة للضغط وإزالة الضغط ، والتنقيط ، والعمليات النقطية ، وتصفية الملمس ، ومكافحة الصقل ، وفك تشفير الفيديو ، ومعالجة الفيديو عالي الدقة.

تركز البنية التالية التي نوقشت على تنفيذ العديد من الخيوط المتوازية بكفاءة في العديد من نوى المعالج.

### صفيف المعالج

يتكون صفيف المعالج من العديد من مراكز المعالجة. يحتوي صفيف معالج GPU الموحد على بنية منظمة نموذجية متعددة المعالجات متعددة الخيوط. لتنفيذ كل خيط ، هناك معالج متعدد المعالجات ، وفي كل معالج متعدد المعالجات (GPUs multi-processor) ، المعروف أيضاً باسم Streaming Multiprocessors (SM) ، هناك العديد من معالجات Streaming ، مرتبة في قائمة انتظار. تتصل جميع المعالجات بأقسام DRAM عبر شبكة ربط الاتصال البيني.

### متعددة الخيوط

كما ذكرنا سابقًا ، تم تحسين استخدام وحدة معالجة الرسومات لزيادة الإنتاجية والوقت المختبئي. تعمل خاصية تعدد المؤشرات على نطاق واسع على تقليص وقت استجابة أحمال الذاكرة من DRAM. بينما يكون مؤشر الترابط في المماطلة بسبب إتمام التحميل أو الإحضار ، يمكن للمعالج تنفيذ مؤشر ترابط آخر. أيضا ، بسبب multithreading على نطاق واسع ، GPU يدعم نماذج برمجية تظليل متوازي الرسومات الحبيبية الدقيقة ونماذج برمجة حواسيب متوازية دقيقة.

### العمارة متعددة المعالجات

إلى جانب العديد من نوى المعالج في SM ، هناك وحدات وظيفية خاصة ، ووحدة تعليمات ذات مؤشرات ترابط متعددة ، وتعليمات ومخابئ ثابتة ، وذاكرة مشتركة. كما أن كل نواة تتكون من ملف تسجيل كبير متعدد الخيوط (RF). يتكون كل معالج معالج التدفق من وحدات حسابية صحيحة ونقطة عائمة ، والتي يمكنها معا التعامل مع معظم العمليات.

### SIMT

يستخدم multi-processor الدفق هندسة "multi-threads multi-thread (SIMT)". يتم تنفيذ التعليمات في مجموعة من المواضيع المتوازية المعروفة باسم الاعوجاج. يكون كل مؤشر ترابط متوازي من النوع نفسه ويبدأ معًا في نفس عنوان البرنامج. تشبه بنية معالج SIMT بنية SIMD تمامًا. في SIMT ، يتم تنفيذ تعليمة معينة في سلاسل متوازية متعددة بشكل مستقل ، بينما في SIMD ، يتم تنفيذ نفس التعليمات في ممرات بيانات متعددة في مجموعات متزامنة.

### معالج الجري

ينفذ جميع عمليات FP الأساسية بالإضافة إلى تعليمات حسابية ومقارنة وتحويل وتعليمات منطقية. وحدة وظيفية خاصة يتم تنفيذ بعض تعليمات مؤشر الترابط في SFUs في وقت واحد مع تعليمات مؤشر ترابط أخرى يتم تنفيذها على SPs.

#### معلومات اكثر:

*   [ويكيبيديا](https://en.wikipedia.org/wiki/Graphics_processing_unit)
*   [OpenACC](https://www.openacc.org/)
*   [CUDA](https://developer.nvidia.com/cuda-zone)
*   [OpenCL](https://www.khronos.org/opencl/)
*   [برنامج OpenGL](https://www.opengl.org/)
*   [مدونة nVidia](https://blogs.nvidia.com/blog/2009/12/16/whats-the-difference-between-a-cpu-and-a-gpu/)
*   [نفيديا](https://www.nvidia.com/)
*   [AMD](http://www.amd.com/en-us/products/graphics)