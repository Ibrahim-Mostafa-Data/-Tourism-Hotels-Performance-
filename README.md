# 🏨 Hotel Booking & Performance Analytics Hub

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=microsoft&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0176D3?style=for-the-badge&logo=salesforce&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Star_Schema-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

### 👤 Created By:
**Ebrahim Mustafa** — *Data Analyst & BI Analyst*

---

## 📌 نبذة عن المشروع (Project Overview)
يهدف هذا المشروع إلى تقديم تحليل استراتيجي متكامل لأداء سلسلة الفنادق (**Hotel Analysis Report**)، لمتابعة الإيرادات الكلية (**\$675.18K**)، سلوك الحجوزات (**293 Bookings**)، معدلات الإلغاء مرتفعة الخطورة (**295 Cancellations**)، قياس تقييمات وجدة رضا العملاء (**5.4 AVG Satisfaction**)، ومتوسط الليالي المحجوزة (**7.89 Nights**).

تم بناء التقرير واختيار الهوية البصرية بنظام الصفحات المتعددة التفاعلية (Multi-Page Interactive Dashboard) لتوفير تجربة مستخدم (UI/UX) مرنة وسلسة للقيادات التنفيذية ومسؤولي إدارة الفنادق.

---

## 🛠️ أدوات وتقنيات العمل (Tech Stack & Methodology)

- **Power Query (ETL Process):**
  * استيراد بيانات الحجوزات الخام ومعالجة مشاكل جودة البيانات.
  * تنظيف البيانات، معالجة القيم المفقودة، تصحيح التنسيقات، وإنشاء الأعمدة المحسوبة (Calculated Columns).
  * تقسيم البيانات وتوليد جداول الأبعاد وجداول الحقائق لتجهيزها لعملية النمذجة.

- **Data Modeling & DAX Measures:**
  * بناء نموذج بيانات متكامل (**Star Schema**) يربط بين جدول الحقائق وجداول الأبعاد بعلاقات (1-to-Many).
  * صياغة مقاييس حسابية ديناميكية باستخدام **DAX** لحساب إجمالي الإيرادات، معدلات الإلغاء، متوسط مدة الإقامة، وتقييمات الرضا.

- **Figma & UI/UX Design:**
  * تصميم واجهات ومكونات الخلفية والأزرار والقوائم الجانبية الاحترافية وتناسق درجات البنفسجي المودرن.

- **Power BI Interactive Reporting:**
  * بناء وتطوير لوحات المؤشرات التفاعلية وربط عناصر التقرير بالسلايسرز والفلاتر الزمنية والجغرافية.

---

## 🏗️ هندسة البيانات والنمذجة (Data Pipeline & Modeling)

### 1️⃣ البيانات الخام (Raw Data)
نظرة على شكل البيانات الأصلية غير المعالجة قبل البدء في عمليات التنظيف وهندسة البيانات.

![Raw Data](raw-data.png)

---

### 2️⃣ معالجة وتنظيف البيانات (Power Query Cleaning)
استيراد البيانات الخام داخل **Power Query Editor** لتشخيص المشاكل التشغيلية، تنظيف القيم المتضاربة، ضبط أنماط البيانات (Data Types)، وحذف التكرارات والتأكد من سلامة الجودة قبل الضخ في النموذج.

![Power Query Cleaning](power_query_cleaning.png)

---

### 3️⃣ فصل وجرد جداول الأبعاد (Power Query Dimensions Extraction)
تمت إعادة هيكلة البيانات عبر تطبيق أفضل الممارسات في الـ Data Transformation بفصل الكيانات المتعددة لتوليد جداول الأبعاد المخصصة (مثل `Dim_Customers`, `Dim_Hotels`, `Dim_Rooms`, `Dim_Date`) لضمان مرونة وسرعة الاستعلام.

![Power Query Dimensions](power-query-dimensions.png)

---

### 4️⃣ نمذجة البيانات الهيكلية (Star Schema Data Modeling)
داخل **Power BI Desktop**، تم ربط جداول الأبعاد بجدول الحقائق الرئيسي لبناء **Star Schema** احترافي يضمن العلاقات السليمة (1-to-Many)، لسهولة كتابة الـ DAX وتصفية البيانات بمرونة عبر جميع الواجهات.

![Data Modeling](Data%20Modeling.png)

---

## 🚀 صفحات التقرير (Dashboard Pages)

### 1️⃣ الصفحة الرئيسية (Home Page)
صفحة ترحيبية وتوجيهية تعرض مؤشرات الأداء الرئيسية (KPI Cards) مع خيارات التنقل السريع بين أقسام التقرير المختلفة.
![Home Page](Home.png)

---

### 2️⃣ صفحة النظرة العامة (Overview)
متابعة اتجاهات الإيرادات الحجمية عبر الشهور (Revenue Trend by Month)، اتجاه الحجوزات حسب الأعوام (Bookings Trend by Month)، إيرادات الفروع، وتوزيع الإيرادات حسب نوع الغرف (Single, Penthouse, Suite, Double).
![Overview Dashboard](Overview.png)

---

### 3️⃣ صفحة تحليل العملاء (Customer Analysis)
تحليل سلوك النزلاء حسب الفئات العمرية (Age Groups)، التوزيع حسب الموقع الجغرافي (Las Vegas, Miami, Orlando..)، نسبة أعضاء برنامج الولاء (Loyalty Members)، والنمط التكراري للزيارة (Repeat Guests).
![Customer Analysis Dashboard](Customer.png)

---

### 4️⃣ صفحة أداء الفنادق (Hotel Performance)
مقارنة شاملة بين فروع السلسلة (`Beachfront`, `Airport`, `Downtown`) من حيث إجمالي الإيرادات، توزيع الحجوزات، معدلات الرضا، ومتوسط الإقامة.
![Hotel Performance Dashboard](Performance.png)

---

### 5️⃣ صفحة تحليل الغرف (Room Analysis)
تقييم تفصيلي لأداء كل نوع من أنواع الغرف (Single, Penthouse, Suite, Double) من حيث الإيرادات المباشرة، عدد الحجوزات، متوسط رضا النزلاء، ومتوسط الليالي المقضاة لكل غرفة.
![Room Analysis Dashboard](Room.png)

---

## 💡 الرؤى الاستراتيجية والتوصيات (Business Insights & Recommendations)

1. **معالجة ارتفاع معدل الإلغاء (High Cancellation Rate Problem):**
   * **الرؤية:** عدد طلبات الإلغاء (**295 إلغاء**) يتجاوز إجمالي الحجوزات المؤكدة (**293 حجز**)، مما يمثل استنزافاً كبيراً للإيرادات الممكنة وفرص الإشغال.
   * **التوصية:** تطبيق سياسات إلغاء مرنة ولكن بشروط (Non-refundable deposits)، وإرسال تأكيدات تلقائية عبر البريد الإلكتروني مع تقديم حوافز للالتزام بالحجز.

2. **تحسين أداء الفروع والتركيز على الفرع الأكثر ربحية:**
   * **الرؤية:** فرع الشاطئ **Sunset Haven - Beachfront** يسيطر على أعلى نسبة إيرادات (**\$0.26M** أرباح ومتوسط إقامة **8.9 ليالي**)، بينما يسجل فرع وسط المدينة **Downtown** أدنى إيرادات (**\$0.20M**).
   * **التوصية:** تعزيز الحملات الترويجية لفرع الشاطئ، وإعادة النظر في تسعير وخدمات فرع وسط المدينة لرفع جاذبيته لرجال الأعمال والمسافرين.

3. **تطوير برنامج الولاء والنزلاء المكررين (Loyalty & Repeat Guests):**
   * **الرؤية:** الإيرادات القادمة من غير الأعضاء ببرنامج الولاء تبلغ **\$410.45K (60.79%)**، والنزلاء غير المكررين يمثلون الجانب الأكبر من الإيرادات (**\$0.50M**).
   * **التوصية:** تقديم خصومات حصرية وتسهيلات تسجيل دخول (Check-in) للنزلاء لتحويل الجدد إلى أعضاء دائمين في برنامج الولاء لزيادة القيمة الممتدة للعميل (LTV).

4. **رفع تقييم رضا العملاء (Customer Satisfaction Enhancement):**
   * **الرؤية:** متوسط رضا العملاء يقف عند **5.4 من 10** وهو معدل متوسط يحتاج لتدخل سريع، مع ملاحظة أن أطول فترة إقامة تكون في الغرف الفردية **Single Rooms** بمتوسط **8.6 ليالي**.
   * **التوصية:** تحسين خدمات الغرف والصيانة الدورية بناءً على استبيانات النزلاء، وتقديم خدمات مضافة لغرف الـ Penthouse و Suites لرفع معدل التقييم العام.

---

### ✍️ Created By:
**Ebrahim Mustafa — Data Analyst & BI Analyst**
