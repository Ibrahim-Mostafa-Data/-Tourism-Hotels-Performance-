# 🏨 Hotel Booking & Performance Analytics Hub

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
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

## 🛠️ أدوات وتقنيات العمل (Tech Stack & Workflow)
* **Power BI Desktop:** لبناء وتطوير لوحات المؤشرات التفاعلية وربط عناصر التقرير.
* **Power Query (ETL):** لتنظيف وتنظيم بيانات الحجوزات وتحويلها إلى الهيكلة المناسبة للتحليل.
* **DAX & Data Modeling:** لبناء المقاييس الحسابية الديناميكية وعلاقات نموذج البيانات (Star Schema).
* **Figma & UI/UX Design:** لتصميم واجهات ومكونات الخلفية والأزرار والقوائم الجانبية الاحترافية.

---

## 🚀 رحلة صفحات التقرير والتصميم (Dashboard Structure)

### 1️⃣ الصفحة الرئيسية (Home Page)
صفحة ترحيبية وتوجيهية تعرض مؤشرات الأداء الرئيسية (KPI Cards) مع خيارات التنقل السريع بين أقسام التقرير المختلفة.
![Home Page](Screenshot_2026-06-19_083413.png)

---

### 2️⃣ صفحة النظرة العامة (Overview)
متابعة اتجاهات الإيرادات الحجمية عبر الشهور (Revenue Trend by Month)، اتجاه الحجوزات حسب الأعوام (Bookings Trend by Month)، إيرادات الفروع، وتوزيع الإيرادات حسب نوع الغرف (Single, Penthouse, Suite, Double).
![Overview Dashboard](Screenshot_2026-06-19_083520.jpg)

---

### 3️⃣ صفحة تحليل العملاء (Customer Analysis)
تحليل سلوك النزلاء حسب الفئات العمرية (Age Groups)، التوزيع حسب الموقع الجغرافي (Las Vegas, Miami, Orlando..)، نسبة أعضاء برنامج الولاء (Loyalty Members)، والنمط التكراري للزيارة (Repeat Guests).
![Customer Analysis Dashboard](Screenshot_2026-06-19_083727.jpg)

---

### 4️⃣ صفحة أداء الفنادق (Hotel Performance)
مقارنة شاملة بين فروع السلسلة (`Beachfront`, `Airport`, `Downtown`) من حيث إجمالي الإيرادات، توزيع الحجوزات، معدلات الرضا، ومتوسط الإقامة.
![Hotel Performance Dashboard](Screenshot_2026-06-19_083816.jpg)

---

### 5️⃣ صفحة تحليل الغرف (Room Analysis)
تقييم تفصيلي لأداء كل نوع من أنواع الغرف (Single, Penthouse, Suite, Double) من حيث الإيرادات المباشرة، عدد الحجوزات، متوسط رضا النزلاء، ومتوسط الليالي المقضاة لكل غرفة.
![Room Analysis Dashboard](Screenshot_2026-06-19_083839.jpg)

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
