# Installation

- manually copy: model.net categories.txt files in /sdcard/neural-nets

- Install Android Studio from: http://developer.android.com/sdk/index.html
- Install latest API through Android Studio. Tutorial: http://developer.android.com/sdk/installing/adding-packages.html
- Open the app folder into Android Studio.
- Compile app.
- Android Studio may or may not give errors. If you see an error, click the "Fix now" link, and then compile again. This may happen a few times.
- Once all the errors have been fixed, then app can be run.


### Note on error omp.h not found: 
Application.mk forces the use of gcc-4.9 (present in NDK 13b), because clang is the default in NDK 13b and it does not support OpenMP; if yo are using another NDK, just modify NDK_TOOLCHAIN_VERSION in Application.mk
