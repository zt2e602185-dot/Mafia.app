بناء APK (بدون تثبيت أي شيء على جهازك):
1) أنشئ حساباً على github.com ثم مستودعاً جديداً (New repository).
2) ارفع كل محتويات هذا المجلد (بما فيها مجلد .github) إلى المستودع.
3) افتح تبويب Actions ← Build APK ← انتظر ~5 دقائق.
4) من صفحة التشغيل نزّل Artifact باسم mafia-app-apk ← فك الضغط ← app-debug.apk
5) انقله للهاتف وثبّته (فعّل "التثبيت من مصادر غير معروفة").

أو محلياً: Node 20 + JDK 17 + Android Studio:
npm install && npx cap add android && npx cap sync android && cd android && ./gradlew assembleDebug
