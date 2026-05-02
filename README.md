تفضلي يا ليان، هذا هو النص الكامل والمرتب بدون النجوم (البولد) وبدون مراجع الـ cite البرمجية، ليكون جاهزاً للنسخ واللصق مباشرة في ملف README.md الخاص بكِ:
Smart Invoice & Receipt Logger (n8n + AI) 🚀

مشروع أتمتة متكامل لاستقبال ومعالجة الفواتير والوصولات تلقائياً باستخدام منصة n8n وتقنيات الذكاء الاصطناعي، بهدف إلغاء الإدخال اليدوي للبيانات وتقليل الأخطاء البشرية.
نظرة عامة على الإنجاز

تم تصميم وبناء الـ Workflow بالكامل على منصة n8n لضمان مسار بيانات سلس وآمن، يبدأ من لحظة رفع المستند وينتهي بأرشفته وتسجيل بياناته وإخطار المعنيين.
الشغل الذي تم إنجازه تقنياً:

    نقطة البداية (Form Submission): إنشاء نموذج لاستقبال البيانات والملفات المرفوعة مباشرة.

    إدارة الملفات: ربط مسار رفع الملفات (Google Drive) لضمان أرشفة المستندات برمجياً.

    الذكاء الاصطناعي (AI/OCR): تجهيز منطق استخراج البيانات الهيكلية من الصور والملفات بدقة باستخدام AI Vision.

    معالجة البيانات (Code Node): كتابة كود JavaScript لتنظيف المخرجات وتحويلها لصيغة JSON مرتبة قابلة للتخزين.

    دمج البيانات (Merge): دمج بيانات الملف الأصلية مع البيانات المستخرجة من الذكاء الاصطناعي في تدفق واحد.

    توجيه المسارات (Switch Node): بناء منطق يفرق تلقائياً بين نوع المستند (Invoice أو Receipt) لتوجيهه للمسار الصحيح.

    التسجيل المحاسبي (Google Sheets): تجهيز خطوات إضافة البيانات إلى الجداول المخصصة (AR/AP).

    الأتمتة البريدية (Gmail): إعداد مسار إرسال إيميلات تلقائية للفواتير وتحديث حالة الإرسال في الجداول.

التكنولوجيا المستخدمة (Stack)

    n8n: محرك الأتمتة الأساسي.

    Google Gemini / AI Vision: لاستخراج البيانات نصياً وصورياً.

    Google Sheets & Drive: لتخزين البيانات والأرشفة السحابية.

    Gmail: للتواصل التلقائي مع العملاء.

متطلبات التشغيل والربط النهائي

بما أن التصميم والمنطق جاهز 100%، يحتاج النظام فقط لربط الحسابات الرسمية للشركة (Credentials) ليدخل حيز التنفيذ:

    استيراد الـ Workflow: رفع ملف الـ JSON المرفق إلى n8n.

    ربط Google Drive: في نود رفع الملفات لتحديد مجلد الحفظ.

    ربط Google Sheets: في نودز الإضافة والتحديث (Append/Update).

    ربط Gmail: في نود الإرسال لتحديد بريد الشركة المرسل.

    تفعيل خدمة AI: إضافة الـ API Key الخاص بالشركة لتفعيل الاستخراج التلقائي.

Smart Invoice & Receipt Logger (n8n + AI) 🚀

A comprehensive automation project designed to receive and process invoices and receipts automatically using the n8n platform and AI technologies, aiming to eliminate manual data entry and reduce human error.
Project Overview

The Workflow was fully designed and built on the n8n platform to ensure a seamless and secure data path, starting from document upload to archiving, data logging, and stakeholder notification.
Technical Achievements:

    Form Submission: Created a form to receive data and uploaded files directly.

    File Management: Integrated the file upload path (Google Drive) for programmatic document archiving.

    AI Vision / OCR: Configured logic to accurately extract structured data from images and documents.

    Data Processing (Code Node): Wrote JavaScript code to clean outputs and convert them into a structured JSON format.

    Data Merging (Merge): Merged original file data with AI-extracted data into a single flow.

    Route Logic (Switch Node): Built logic to automatically distinguish between document types (Invoice or Receipt) for correct routing.

    Accounting Logging (Google Sheets): Prepared steps to append data to specific sheets (AR for Invoices, AP for Expenses).

    Email Automation (Gmail): Configured automated email notifications for invoices and updated the delivery status in the sheets.

Tech Stack

    n8n: The primary workflow automation engine.

    Google Gemini / AI Vision: For text and visual data extraction.

    Google Sheets & Drive: For data logging and cloud archiving.

    Gmail: For automated client communication.

Setup & Configuration

The logic and design are 100% complete; the system only requires connecting the company's official credentials to go live:

    Import Workflow: Upload the attached JSON file to n8n.

    Connect Google Drive: In the upload node to specify the storage folder.

    Connect Google Sheets: In the append/update nodes.

    Connect Gmail: In the send message node to define the sender's email.

    Activate AI Service: Add the company's API Key for automated data extraction
