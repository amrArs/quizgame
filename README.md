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
