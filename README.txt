CIVIL ENGINEER ASSISTANT — ANDROID PROJECT
Included:
- Offline searchable civil engineering Q&A reference
- Concrete volume, steel weight, brick estimate and area conversion calculators
- Pre-concrete-pour checklist
- Android WebView wrapper project

BUILD APK:
1. Install Android Studio (current stable) on a computer.
2. Open this project folder in Android Studio.
3. Allow Gradle sync and install the required Android SDK (compileSdk 35).
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the debug APK at app/build/outputs/apk/debug/app-debug.apk.
6. Transfer it to your Android phone and install. You may need to allow installation from that source.

LIMITATIONS:
- This starter app works offline and contains a curated starter set of common questions.
- It is not connected to a live AI service, does not read DWG/Revit files and does not perform structural design.
- Live AI answers would require a secure backend and an API key; never embed a private API key in the APK.
- All engineering values and designs must be verified against current applicable IS codes, project specifications and qualified engineer approval.
