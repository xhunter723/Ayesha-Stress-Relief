AYESHA STRESS RELIEF — OFFLINE ANDROID PROJECT

This project is configured for an offline Android game. It does not request internet permission.

BUILD WITHOUT ANDROID STUDIO (GitHub Actions)
1. On GitHub.com, create a new repository (you can keep it Private).
2. Upload the contents of this project folder to the repository's main branch.
   Include the hidden .github/workflows/build-apk.yml file.
3. Open the repository's Actions tab.
4. Select "Build Ayesha Stress Relief APK" and click "Run workflow".
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run and download the artifact named
   "Ayesha-Stress-Relief-APK". It contains app-debug.apk.
7. Transfer app-debug.apk to your Android phone and install it. Android may ask
   you to allow installing apps from that browser/file manager.

No Android Studio or local Android SDK is required. GitHub builds it online.

Note: The APK is a debug-signed APK suitable for personal testing/installing.
