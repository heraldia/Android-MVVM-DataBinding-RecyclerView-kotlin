# Android-MVVM-DataBinding-RecyclerView-kotlin

Android kotlin : implementation of RecyclerView with Jetpack using MVVM and Data-binding

When using MVVM architecture Android Data Binding is the best way to propagate changes to the UI.

# worklog
2023_0509_1344

# 2023_0509_1356 
Manifest merger failed : android:exported needs to be explicitly specified for element <activity#com.androidmvvmdatabindingrecyclerviewkotlin.MainActivity>. Apps targeting Android 12 and higher are required to specify an explicit value for `android:exported` when the corresponding component has an intent filter defined. See https://developer.android.com/guide/topics/manifest/activity-element#exported for details.

# 2023_0509_1408 
> 'compileDebugJavaWithJavac' task (current target is 1.8) and 'kaptGenerateStubsDebugKotlin' task (current target is 17) jvm target compatibility should be set to the same Java version.

# 2023_0509_1418 give up 

# 2023_0509_1602 
com.androidmvvmdatabindingrecyclerviewkotlin.app-mergeDebugResources-30:/layout/activity_main.xml:28: error: resource dimen/_8sdp (aka com.androidmvvmdatabindingrecyclerviewkotlin:dimen/_8sdp) not found.

# 2023_0509_1604 
> 'compileDebugJavaWithJavac' task (current target is 1.8) and 'kaptGenerateStubsDebugKotlin' task (current target is 17) jvm target compatibility should be set to the same Java version.
  Consider using JVM toolchain: https://kotl.in/gradle/jvm/toolchain

