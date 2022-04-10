# Flutter QR Code

## STEPS(for Android)
1. Add `<uses-permission android:name="android.permission.CAMERA" />` to **"project/android/app/src/debug/AndroidManifest.xml"**
2. In **"project/android/app/build.gradle"**
  - Change minSdkVersion `minSdkVersion 18`
  - Add `implementation 'com.android.support:multidex:1.0.3'` in dependencies
  - Add `multiDexEnabled true` in defaultConfig

