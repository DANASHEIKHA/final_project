# الـ Prompts الأساسية — عون (Awn AI)

## 1\. Prompts الذكاء الاصطناعي داخل النظام



الصور :Context:

أنت مصمم جرافيك محترف متخصص في تعريب التصاميم التسويقية التقنية. التصميم المرفق خاص بمنصة عون Awn AI لمطابقة المتطوعين بالفرص المناسبة باستخدام الذكاء الاصطناعي.



Task:

عدّل الصورة المرفقة نفسها بتحويل النصوص الإنجليزية إلى العربية، مع الحفاظ على الشخصيات الثلاث، والأجهزة اللوحية، والشبكة الذكية المضيئة، والأسهم، والتكوين العام.



Constraints:

\- حافظ على الهوية اللونية: #1a647d و#deebf4 و#ffffff.

\- حافظ على الطابع الزجاجي والإضاءة السماوية الناعمة.

\- استخدم خطًا عربيًا عصريًا وواضحًا واتجاه كتابة صحيحًا من اليمين إلى اليسار.

\- حافظ على شعار Awn AI في الأعلى دون تغيير.

\- لا تضف نصوصًا أخرى أو شعارات وهمية.

\- استخدم هذه النصوص بدقة:

العنوان: انضم إلى ثورة عون للذكاء الاصطناعي!

الوصف: اكتشف قدراتك واصنع أثرًا حقيقيًا في مجتمعك، مع المطابقة الذكية للفرص التطوعية.

الزر: ابدأ رحلتك الآن

السطر السفلي: لديك حساب بالفعل؟ سجّل دخولك



Output:

صورة 3:1 جاهزة للنشر، بنفس التصميم المرجعي، بجميع النصوص العربية واضحة ومتوازنة.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Context:

Act as a senior visual designer specializing in Arabic AI technology campaigns for nonprofit organizations. Create a premium institutional social media visual for Awn AI, an intelligent volunteer-to-opportunity matching system using semantic retrieval and RAG, with human oversight.



Task:

Create an Arabic RTL visual centered on the message: كيف تختار المتطوع المناسب للمهمة المناسبة بدقة متناهية؟ Show the transformation from scattered volunteer profiles and mismatched opportunities into an organized, intelligent matching process. Include three concise feature labels: بحث دلالي ذكي، تقارير توافق مفسّرة، القرار النهائي للمنسق.



Constraints:

Use only deep teal blue #1a647d, icy light blue #deebf4, and white #ffffff. Employ a premium minimal vector and editorial infographic aesthetic, elegant Arabic typography, generous whitespace, subtle network lines, profile cards, and clean matching connections. Arabic RTL layout. Avoid dense paragraphs, exaggerated accuracy claims, fabricated percentages, unrelated imagery, and decorative clutter. The AI recommends; a human coordinator decides.



Output:

One polished social media key visual with clear headline hierarchy, a central volunteer-to-opportunity matching illustration, three short feature highlights, Awn AI branding, and legible Arabic text. Adapt final dimensions to the selected publishing platform.





\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



### Context:

### أنت مصمم جرافيك متخصص في تصميم منشورات تقنية احترافية للمؤسسات والجمعيات الخيرية. المشروع هو عون (Awn AI)، نظام ذكي يساعد على مطابقة مهارات المتطوعين مع الفرص التطوعية باستخدام RAG، مع بقاء القرار النهائي للمنسق.

### 

### Task:

### صمم منشورًا بصريًا باللغة العربية يوضح مشكلة التوزيع العشوائي للمتطوعين والحل الذكي الذي يقدمه عون. استخدم العنوان: كيف تختار المتطوع المناسب للمهمة المناسبة بدقة متناهية؟

### 

### Constraints:

### \- استخدم حصريًا الألوان #1a647d و#deebf4 و#ffffff.

### \- تصميم مؤسسي عصري وواضح، بخط عربي مقروء.

### \- تجنب ازدحام النصوص.

### \- أبرز البحث الدلالي، تقارير التوافق، والمراجعة البشرية.

### \- لا تدّع دقة مضمونة أو نسب توافق فعلية غير موثقة.

### \- حافظ على اتجاه القراءة من اليمين إلى اليسار.

### 

### Output:

تصميم منشور واحد متوازن يتضمن عنوانًا رئيسيًا، تصورًا بصريًا للمطابقة الذكية، ثلاث ميزات مختصرة، واسم Awn AI، مع مساحة مناسبة للهوية البصرية.

\---

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### 

### 

1. برومبت lavable  لإنشاء الصفحة الرئيسية :

\---

Build "Awn AI" (عون), an Arabic-first (RTL) web app that matches volunteers to

volunteer opportunities and gives coordinators an AI chat assistant.

Tagline: "تنظيم ذكي لطاقات المجتمع.. لنجعل كل متطوع في المكان الأنسب تماماً"

Use React + Tailwind + Supabase (I already connected Supabase).



\## VISUAL IDENTITY (follow strictly; match the attached images)

\- Direction: dir="rtl", lang="ar". Font: Cairo (Google Fonts), fallback Tahoma.

\- Palette (define as CSS variables / Tailwind theme):

&#x20; deep teal #17566e, brand teal #1f6a89, navy #0f172a, royal blue #1e3a8a,

&#x20; sky blue #3b82f6, pale blue #dce9f3, page background #eef5fb (soft light-blue

&#x20; gradient), white #ffffff. Semantic: AI accent orange #e88c26 (use ONLY where

&#x20; AI is involved: match score badge, assistant chat header), success green

&#x20; #2e8f57 (approved), RAG/knowledge teal-green #1f8a70 on #d6efe8.

\- Hero section: solid teal background (#135a74 → #17566e), white Cairo bold

&#x20; headline "ابدأ رحلتك التطوعية مع عون", subline "اكتشف قدراتك واصنع أثراً

&#x20; حقيقياً في مجتمعك، مع المطابقة الذكية للفرص التطوعية.", and a pale-blue pill

&#x20; button "ابدأ رحلتك الآن" (navy text, circular arrow icon) linking to the

&#x20; registration form. Use the uploaded illustrations/logo; if missing, use a

&#x20; simple flat-illustration style (volunteers with lanyards and tablets, a glowing

&#x20; network-sphere in the middle).

\- Logo: a stylized letter "A" built from connected nodes in cyan, next to the

&#x20; text "Awn AI" (and "عون الذكي" in Arabic). Show in the header.

\- Content pages (dashboard, chat): light background, white cards with 12px

&#x20; radius, thin #c8d9e6 borders, navy headings, teal primary buttons, rounded

&#x20; pill CTAs. Calm, professional, human-friendly tone; generous spacing; no neon.

\- Light and dark mode supported; keyboard focus visible; mobile responsive.



\## PAGES

1\. "/" Landing: hero (above), a 3-step "كيف يعمل عون؟" section

&#x20;  (1 سجّل مهاراتك → 2 مطابقة ذكية بتقرير توافق → 3 مراجعة المنسق)

&#x20;  with the line "مطابقة ذكية بلمسة بشرية." and a small note about privacy

&#x20;  and human review.

2\. "/register" Volunteer form: full name, phone (optional, never shown

&#x20;  to anyone later), city (select: شمال غزة، جنوب غزة، الوسطى), available days

&#x20;  (checkboxes الأحد..السبت), "مهاراتك بكلماتك" (textarea, placeholder

&#x20;  "مثال: أصمم بوسترات على كانفا وأحب التنظيم"), interests (optional).

&#x20;  Button "سجّل واعرض الترشيحات". On submit POST JSON to the n8n webhook URL in

&#x20;  env VITE\_N8N\_REGISTER\_URL with fields: full\_name, phone, city, days (array),

&#x20;  skills\_text, interests\_text. If that env var is empty, insert directly into

&#x20;  the Supabase table `volunteers` instead so the demo still works. Show a

&#x20;  success message: "تم استلام طلبك. سيراجع المنسق الترشيحات قبل أي إسناد."

3\. "/login" Coordinator login with Supabase Auth (email + password).

4\. "/dashboard" (protected, coordinators only): list of matches from the

&#x20;  Supabase view `matches\\\\\\\_view`, newest/highest score first, with filters by

&#x20;  opportunity and status. Each card: volunteer name, opportunity title, big

&#x20;  percentage badge (orange, labelled "نسبة التوافق"), reasons, recommendation,

&#x20;  status tag (قيد المراجعة / معتمد / مرفوض) and two buttons "اعتماد" and "رفض"

&#x20;  that update `matches.status` ('approved' / 'rejected'). Poll or use Supabase

&#x20;  realtime so new matches appear. Never display phone numbers anywhere.

&#x20;  Footer note: "ترشيحات الذكاء الاصطناعي أدوات مساعدة؛ القرار النهائي للمنسق."

5\. "/assistant" (protected): coordinator chat UI. Orange header "مساعد المنسق".

&#x20;  Message bubbles, suggested question chips: "ما شروط الانضمام؟",

&#x20;  "ما التدريب المطلوب لتوزيع الطرود؟", "ما شروط الدعم التعليمي للأطفال؟",

&#x20;  "رشّح لي متطوعين لحملة التشجير". Send each message (+ a stable sessionId) to

&#x20;  the n8n chat webhook in env VITE\_N8N\_CHAT\_URL as JSON

&#x20;  { chatInput, sessionId } and render the "output" field of the response.

&#x20;  Render source names (the assistant cites document names) in small muted text

&#x20;  under the answer. Show a typing indicator and a friendly error state:

&#x20;  "تعذّر الوصول إلى المساعد، حاول مرة أخرى."

6\. "/opportunities" (protected): simple table to view/add/toggle opportunities.



\## SUPABASE (create via migrations)

Tables (RLS enabled on all):

\- volunteers(id uuid pk default gen\_random\_uuid(), full\_name text not null,

&#x20; city text not null, days text\[] not null default '{}', skills\_text text not

&#x20; null, interests\_text text, phone text, created\_at timestamptz default now())

\- opportunities(id uuid pk, title text not null, org\_name text, city text not

&#x20; null, days text\[], required\_skills text\[], description text, active boolean

&#x20; default true)

\- matches(id uuid pk, volunteer\_id uuid references volunteers on delete

&#x20; cascade, opportunity\_id uuid references opportunities on delete cascade,

&#x20; score int check (score between 0 and 100), reasons text, recommendation text,

&#x20; status text default 'pending' check (status in ('pending','approved','rejected')),

&#x20; created\_at timestamptz default now())

\- chat\_logs(id bigserial pk, session\_id text, question text, answer text,

&#x20; sources jsonb, created\_at timestamptz default now())

View `matches\\\\\\\_view` (matches joined with volunteer full\_name, city and

opportunity title; NO phone) created with security\_invoker = on.

RLS: anon may INSERT into volunteers only; anon may SELECT active

opportunities; authenticated users whose JWT app\_metadata.role = 'coordinator'

can read/manage volunteers, opportunities, matches, chat\_logs.

Seed 6 sample opportunities (org "جمعية نماء (تجريبية)"):

حملة تشجير الحي (شمال غزة، السبت، تنظيم ميداني+تصوير),

كتابة تقارير الأثر (شمال غزة، الثلاثاء+الخميس، كتابة تقارير),

تطوير موقع الجمعية (جنوب غزة، الأحد-الخميس، برمجة),

دعم تعليمي للأطفال (جنوب غزة، الأحد+الاثنين، تدريس),

هوية بصرية لمعرض خيري (الوسطى، الأحد+الثلاثاء، تصميم),

توزيع الطرود الغذائية (الوسطى، الجمعة+السبت، تنظيم ميداني).

I will separately add a `documents` table with pgvector and the n8n workflows;

do not create them and do not call any AI API from the frontend.

\## BILINGUAL SUPPORT (Arabic + English)

\- Full i18n with two languages: ar (default, RTL) and en (LTR). Language

&#x20; toggle button in the header ("English" / "العربية"). Switching sets

&#x20; <html lang> and dir, flips layout, and is remembered per browser.

&#x20; Keep all UI strings in a translations file; no hardcoded text in components.

\- Cairo font supports both scripts; keep the same palette and components in both.

\- Registration form: save the current language into volunteers.lang ('ar'|'en')

&#x20; and send it as `lang` in the n8n payload.

\- Show opportunity titles/descriptions by language: title/description in ar,

&#x20; title\_en/description\_en in en (fallback to ar if empty). Add title\_en and

&#x20; description\_en inputs to the opportunities page. Add column `lang text not

&#x20; null default 'ar'`to volunteers and`title\_en`, `description\_en` to

&#x20; opportunities; matches\_view also exposes opportunity\_en.

\- Dashboard shows volunteer-facing text (reasons, recommendation) exactly as

&#x20; stored; do not translate it in the frontend.

\- Chat assistant: send { chatInput, sessionId, lang } to the n8n chat webhook;

&#x20; render answers with dir="auto" so Arabic and English answers each align

&#x20; correctly; suggested-question chips change with the UI language.

\- City values stay Arabic keys in the database (شمال غزة، جنوب غزة، الوسطى) and

&#x20; display as North Gaza / South Gaza / Central Gaza in English.

\## RULES

\- All UI text in Arabic, sentence case, plain verbs; errors say what happened

&#x20; and how to fix it.

\- Put the two n8n URLs in .env (VITE\_N8N\_REGISTER\_URL, VITE\_N8N\_CHAT\_URL), never

&#x20; hardcode keys or secrets.

\- Use only sample/fake data. Add a short "الخصوصية والمراجعة البشرية" page or

&#x20; modal explaining: phones are never shared, AI suggestions need coordinator

&#x20; approval



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_





برمبت تصحيح الأخطاء في lovable



Bug: after a successful sign-in, the app redirects back to the login page.



Please fix the route guard for /dashboard, /assistant and /opportunities:



Wait for the auth session to finish loading (use onAuthStateChange and a



"loading" state) before deciding to redirect; show a spinner meanwhile.



Treat the user as coordinator if



session.user.app\_metadata?.role === "coordinator".



If signed in but NOT a coordinator, do not redirect to login: show a clear



Arabic message "حسابك غير مصرّح له بدخول لوحة المنسق" with a sign-out button.



Add a console.log of the user email and app\_metadata after sign-in so I can



see what the guard reads.



Do not change anything else.





\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

