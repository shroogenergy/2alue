# Mini-AGI Playground — HuggingFace Edition

نسخة من Mini‑AGI بنفس الواجهة لكن تعتمد على **HuggingFace Inference API** بدل OpenAI.

## المزايا
- تشغيل بدون مفتاح API (وضع محلي).
- تشغيل مع مفتاح HuggingFace مجاني (يحسّن المخرجات).
- اختيار نموذج من HuggingFace (مثل bloomz-560m أو falcon-7b-instruct).

## التشغيل
- افتح `index.html` في المتصفح مباشرة.
- بدون مفتاح: يعمل الوضع المحلي البسيط.
- مع مفتاح HuggingFace: ضع المفتاح في الحقل وفعّل "استخدام LLM".

## الحصول على مفتاح HuggingFace
1. أنشئ حساب مجاني على https://huggingface.co/
2. من إعدادات الحساب → Access Tokens → إنشاء مفتاح جديد يبدأ بـ `hf_`.

## ملاحظات
- النماذج المجانية قد تكون أبطأ من OpenAI.
- قد تمنع بعض المواقع طلبات fetch (CORS) في الوضع المحلي.

## الترخيص
MIT
