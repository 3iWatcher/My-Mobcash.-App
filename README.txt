MY MOBCASH ANDROID PROJECT

This project wraps the supplied HTML screen in an Android WebView.
It is built in the cloud with GitHub Actions; Android Studio is not required on your phone.

IMPORTANT:
- This is a front-end prototype only.
- No real bank, payment gateway, deposits, withdrawals, or account data are connected.
- The workflow creates a debug APK for testing, not a Play Store release.

GitHub mobile steps:
1. Create a new repository named My-Mobcash-App.
2. Extract this ZIP on your phone.
3. Upload the CONTENTS of the extracted My_Mobcash_Android_Project folder to the repository root.
4. Confirm .github/workflows/build-apk.yml is present in the repository.
5. Open Actions, select Build My Mobcash APK, tap Run workflow.
6. When completed successfully, open the run and download My-Mobcash-APK under Artifacts.
7. Extract the downloaded artifact ZIP and install app-debug.apk.
