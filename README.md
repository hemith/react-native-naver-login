# @hemith/react-native-naver-login

[![npm version](http://img.shields.io/npm/v/@hemith/react-native-naver-login.svg?style=flat-square)](https://npmjs.org/package/@hemith/react-native-naver-login)
[![downloads](http://img.shields.io/npm/dm/@hemith/react-native-naver-login.svg?style=flat-square)](https://npmjs.org/package/@hemith/react-native-naver-login)
[![license](http://img.shields.io/npm/l/@hemith/react-native-naver-login.svg?style=flat-square)](https://npmjs.org/package/@hemith/react-native-naver-login)


아래 에러를 해결하는 android/build.gradle 파일을 포함합니다.

```
FAILURE: Build failed with an exception. 

* What went wrong:
Execution failed for task ':react-native-naver-login:verifyReleaseResources'.
> java.util.concurrent.ExecutionException: com.android.builder.internal.aapt.v2.Aapt2Exception: Android resource linking failed
  /Users/opensrc/git/aty/dillydilly/node_modules/react-native-naver-login/android/build/intermediates/res/merged/release/values-v28/values-v28.xml:7: error: resource android:attr/dialogCornerRadius not found.
  /Users/opensrc/git/aty/dillydilly/node_modules/react-native-naver-login/android/build/intermediates/res/merged/release/values-v28/values-v28.xml:11: error: resource android:attr/dialogCornerRadius not found.
  /Users/opensrc/git/aty/dillydilly/node_modules/react-native-naver-login/android/build/intermediates/res/merged/release/values/values.xml:2714: error: resource android:attr/fontVariationSettings not found.
  /Users/opensrc/git/aty/dillydilly/node_modules/react-native-naver-login/android/build/intermediates/res/merged/release/values/values.xml:2715: error: resource android:attr/ttcIndex not found.
  error: failed linking references.
```
