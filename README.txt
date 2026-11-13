# Beat Box APK build (GitHub Actions)

## GitHub par kya upload karna hai
1. `beat-box-android.zip` ko repository ke main page par upload karo.
2. Repository mein `.github/workflows/build-apk.yml` naam ka workflow file banao aur is bundle ke andar diya gaya `build-apk.yml` content paste karo.
3. Commit changes karo. Actions tab mein `Build Beat Box APK` workflow run hoga.
4. Run successful hone par workflow ke neeche Artifacts mein `Beat-Box-APK` download karo. ZIP ke andar `app-debug.apk` milega.

Note: Yeh debug APK testing ke liye hai. Play Store par publish karne ke liye signed release build alag se banana hoga.
