AX EDITZ Android wrapper project

Yeh Android WebView wrapper tumhari existing website ko app ke andar kholta hai:
https://vikram635.github.io/Vik/

IMPORTANT:
- Yeh source project hai, compiled APK/AAB nahi.
- Is environment mein Android SDK/Gradle chala kar APK compile/sign nahi hua.
- GitHub Actions se debug APK build kar sakte ho; Play Store release ke liye signed AAB, signing key, privacy policy, Data safety form, testing aur Play Console account chahiye.
- Yeh wrapper online website ko reuse karta hai. Offline video export automatically add nahi hota; website editor ko separately implement aur test karna hoga.
- File upload picker included. Camera/microphone web permissions default se denied hain.
- App ID: com.axeditz.app. Publish se pehle final package ID confirm karo.

ANDROID MOBILE SE BUILD:
1. ZIP extract karo.
2. Is project ke files ko GitHub repository ke root mein upload karo. Existing website files ko delete/replace mat karna.
3. GitHub repo > Actions > Build AX EDITZ Android APK > Run workflow.
4. Workflow complete hone par run ke Artifacts se AX-EDITZ-debug-apk download karo.
5. Debug APK testing ke liye hai; ise Play Store par upload nahi kar sakte.
