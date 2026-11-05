# mihrabak-assets

ملفات يحمّلها تطبيق «محرابك» عند الحاجة بدل أن تُضمَّن فيه لكبر حجمها.
Files the Mihrabak app downloads on demand instead of bundling them.

لا يُعدَّل أي ملف هنا. كل ملف منقول كما هو من مصدره، وبصمته (SHA-256) في `quran/fonts/SHA256SUMS`.
Nothing here is modified: every file is a byte-for-byte copy of its source; checksums are in `quran/fonts/SHA256SUMS`.

## quran/fonts/v2 — خطوط صفحات المصحف

| | |
|---|---|
| ما هي | خطوط صفحات مصحف المدينة النبوية من مجمع الملك فهد لطباعة المصحف الشريف، الإصدار الثاني: `QCF2001.ttf` … `QCF2604.ttf` (خط لكل صفحة) و`QCF2BSML.ttf` (البسملة) |
| المصدر | نسخة من ملفات المجمع في github.com/nuqayah/qpc-fonts، المجلد `mushaf-v2`، الإصدار `8a4f39d563ea69c994416a1692827e38156c548d` |
| العدد | 605 ملفات |

## quran/fonts/v1 — إطارات أسماء السور

| | |
|---|---|
| ما هي | `QCF_BSML.TTF` من الإصدار الأول لخطوط المجمع: إطار اسم السورة وأسماء السور |
| المصدر | github.com/quran/quran.com-images، المجلد `res/fonts`، الإصدار `dbda5689691defc7e3b28314cc2d035ff027795c` |

## الحقوق / Rights

الخطوط ملك مجمع الملك فهد لطباعة المصحف الشريف. خطوط الصفحات (QCF2) لا تحمل نص ترخيص بداخلها، وخط QCF_BSML مكتوب فيه «All rights reserved». تُستخدم هنا في تطبيق مجاني دون بيع أو تعديل، وسيُطلب إذن مكتوب من المجمع قبل نشر التطبيق في المتجرين.

The fonts are the property of the King Fahd Glorious Quran Printing Complex. They are used unmodified in a free app; written permission will be requested from the Complex before store release.

## كيف يستخدمها التطبيق / How the app uses them

التطبيق يحمّل كل ملف من رابط مثبّت على إصدار محدد من هذا المستودع، مثل:
`https://raw.githubusercontent.com/mihrabakapp/mihrabak-assets/<commit>/quran/fonts/v2/QCF2001.ttf`
فلا يتغير ما يعرضه التطبيق حتى لو عُدّل المستودع لاحقاً.
