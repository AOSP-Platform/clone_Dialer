## Clone AOSP platform_packages_apps_Dialer

This is the build script to build AOSP Dialer app outside the AOSP source tree using gradle.



## Notes

* I'm not sure if this application will actually run without crashes, I don't want to replace my system dialer with this app. Need to fork AOSP Dialer and change package names etc.. to make it installable as a separate app.
* Other AOSP based Dialer apps might compile with these build scripts too with minimal modifications.
* Bundled lib packages are needed to build the app. `aosp-android.jar` is the `android.jar` for api 28 with hidden apis bundled, it's extracted from a LineageOS build tree. `sdk.jar` is taken from `android_prebuilts`
