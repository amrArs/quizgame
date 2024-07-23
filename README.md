sk-proj-ldwio6uVotkgIiJ2YUIhT3BlbkFJDgykxMSm5JbUvLwXZz1h
asistant_id = "asst_WZ86SnI0US9qaqNIXNLivMd9"
# thread_id = "thread_VBYAyhQCxScPWv1Q8xXaqOlZ"

$graphik-arabic-font-path: '../../fonts/graphik-arabic';

@mixin graphik-arabic-font($type, $weight, $style) {
    @font-face {
        font-family: 'GraphikArabic';
        src: url('#{$graphik-arabic-font-path}/GraphikArabic-#{$type}.eot');
        src: url('#{$graphik-arabic-font-path}/GraphikArabic-#{$type}.eot?#iefix') format('embedded-opentype'),
        url('#{$graphik-arabic-font-path}/GraphikArabic-#{$type}.woff2') format('woff2');
        font-weight: $weight;
        font-style: $style;
    }
}

@mixin graphik-arabic-font-pair($type, $weight) {
    @include graphik-arabic-font('#{$type}', $weight, normal);
}


@include graphik-arabic-font-pair('Thin', 100);
@include graphik-arabic-font-pair('Extralight', 200);
@include graphik-arabic-font-pair('Light', 300);
@include graphik-arabic-font-pair('Regular', 400);
@include graphik-arabic-font-pair('Medium', 500);
@include graphik-arabic-font-pair('Semibold', 600);
@include graphik-arabic-font-pair('Bold', 700);
@include graphik-arabic-font-pair('Super', 800);
@include graphik-arabic-font-pair('Black', 900);

$font-family-sans-serif: 'GraphikArabic', fantasy !default;

الرئيسية
مجتمع خمسات
طلبات الخدمات غير الموجودة
خبير لإستخدام instagram messaging api
تغلق الطلبات تلقائيًا بعد أسبوع من فتحها، رجاء فتح موضوع جديد في القسم إن لم تجد عرضًا مناسبًا لطلبك بعد.
السلام عليكم.

محتاج شخص يسوي ال instagram messaging api علشان يكون حساب الإنستا عندة قدرة الرد على الرسائل في الخاص.

المطلوب:

المطلوب إنه أقدر أسوي حساب إنستجرام واخلي عنده القدرة يرد على رسائل الخاص في الانستجرام

بعدين الحساب هذا اي شخص يقدر يضيفه عنده عشان يرد الرسائل بالنيابة عن الحساب الاصلي... مثال:

ممكن انا شخص احتاج حد يرد على رسائلي (بوت باستخدام ال api)... فراح اروح اضيف البوت (حساب الانستجرام الي يستخدم ال api) واضيفه عندي على حسابي الانستاجرام (يعني ك team member) واعطيه صلاحيات انه يرد بدلا عني.

لانه راح يستخدم البوت هذا عدة حسابات فالمطلوب أن صاحب الحساب فقط يضيف البوت ك team member, يعطيه صلاحيات الرسائل, وخلاص البوت الان يقدر يرد على رسائل الحساب الاصلي بدلا عنه.

المطلوب استلامه:

البوت مع الكود

ويشرح لي ع السريع كيف سوا لمن سوا التطبيق الذي سمح له باستخدام ال api على منصة Meta For Developers.

المزانية: 20$
