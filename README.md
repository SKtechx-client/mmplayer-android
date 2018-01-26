# MusicMate Media Player Library



* project build.gradle file
```diff
apply plugin: 'com.android.application'

+  repositories {
+      maven { url 'https://sktechx-client.github.io/mmplayer-android' }
+  }

android {
  ...
}

dependencies {
+     compile 'com.sktechx:musicmallweb:1.0.0'
}
```
