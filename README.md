# انشرها

تطبيق Android باستخدام Jetpack Compose.

## البناء على GitHub Actions
Workflow: `.github/workflows/build-apk.yml`

البناء يتم مباشرة من مشروع Gradle ولا يحتاج إلى ZIP داخل المستودع.

## حل Compose
تم تثبيت `ui-tooling-preview` على الإصدار `1.7.6` المتوافق مع Compose BOM `2024.12.01` لتجنب خطأ:
`Could not find androidx.compose.ui:ui-tooling-preview:.`
