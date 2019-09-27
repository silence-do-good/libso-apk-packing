# libso-apk-packing
This repo is an Android Studio example on how to pack a shared object (.so) library into an APK.

The .so has to be uncompressed for this to work

The android manifest has the `extractNativeLibs=false` for this reason.

Place the .so file in the actual target abi folder under `src/main/jniLibs/<target-abi>/`
