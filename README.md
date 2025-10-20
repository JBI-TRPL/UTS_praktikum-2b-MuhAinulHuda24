 # Ujian Praktikum Flutter POS SQLite
 **Nama Mahasiswa:** Muhammad Ainul Huda
 **NIM:** 362458302075
 **Kelompok:** Kelompok - 1
 ##  Deskripsi Fitur yang Ditambahkan
 Tuliskan fitur baru atau modifikasi yang Anda kerjakan.

 * Disini Saya membuat Drawer Menu
 * isi dari drawer menu yaitu home, transactions, settings, Log Out
 ## File yang Dimodifikasi
 Tuliskan nama file dan deskripsi singkat:
 * lib/pages/menu_pages.dart : menambahkan list drawer
 * lib/home/home_screen.dart : menghubungkan drawer di menu di pages
 ## Cara Menjalankan Aplikasi
 1. Jalankan ‘flutter pub get‘
 2. Jalankan ‘flutter run‘
 3. Uji fitur yang telah tambahkan
 ## Screenshot
 screnshoot tutorial :
<img width="1919" height="881" alt="Cuplikan layar 2025-10-20 150044" src="https://github.com/user-attachments/assets/31740aad-893b-4b02-884c-38f55b1ece10" />

<img width="280" height="620" alt="Cuplikan layar 2025-10-20 151230" src="https://github.com/user-attachments/assets/9ebf184f-61b6-46f5-b0ed-1b9ba6e04f9a" />
ketika sudah dirubah 
<img width="354" height="792" alt="Cuplikan layar 2025-10-20 154300" src="https://github.com/user-attachments/assets/8e07de17-2f66-44e5-bf78-dc5a78408da0" />


 ## Catatan Tambahan
Belum mangerti dalam hal routing, sehingga masih kebingunan untuk menghubungkan beberapa file dan juga method atau fungsi yang lain, saya disini melihat tutorial yang ada di web flutter : https://docs.flutter.dev/cookbook/design/drawer
saya juga memakai AI Gemini untuk mecari tahu errornya ketika bagaimana simulator tidak bisa dijalankan dengan promt :
Warning: Flutter support for your project's Gradle version (8.4.0) will soon be dropped. Please upgrade your Gradle version to a version of at least 8.7.0 soon.
Alternatively, use the flag "--android-skip-build-dependency-validation" to bypass this check.

Potential fix: Your project's gradle version is typically defined in the gradle wrapper file. By default, this can be found at D:\API\praktikum-uts-2b-MuhAinulHuda24\android/gradle/wrapper/gradle-wrapper.properties.
For more information, see https://docs.gradle.org/current/userguide/gradle_wrapper.html.

Warning: Flutter support for your project's Android Gradle Plugin version (Android Gradle Plugin version 8.2.0) will soon be dropped. Please upgrade your Android Gradle Plugin version to a version of at least Android Gradle Plugin version 8.6.0 soon.
Alternatively, use the flag "--android-skip-build-dependency-validation" to bypass this check.

Potential fix: Your project's AGP version is typically defined in the plugins block of the `settings.gradle` file (D:\API\praktikum-uts-2b-MuhAinulHuda24\android/settings.gradle), by a plugin with the id of com.android.application.
If you don't see a plugins block, your project was likely created with an older template version. In this case it is most likely defined in the top-level build.gradle file (D:\API\praktikum-uts-2b-MuhAinulHuda24\android/build.gradle) by the following line in the dependencies block of the buildscript: "classpath 'com.android.tools.build:gradle:<version>'".

Warning: Flutter support for your project's Kotlin version (1.9.20) will soon be dropped. Please upgrade your Kotlin version to a version of at least 2.1.0 soon.
Alternatively, use the flag "--android-skip-build-dependency-validation" to bypass this check.

Potential fix: Your project's KGP version is typically defined in the plugins block of the `settings.gradle` file (D:\API\praktikum-uts-2b-MuhAinulHuda24\android/settings.gradle), by a plugin with the id of org.jetbrains.kotlin.android.
If you don't see a plugins block, your project was likely created with an older template version, in which case it is most likely defined in the top-level build.gradle file (D:\API\praktikum-uts-2b-MuhAinulHuda24\android/build.gradle) by the ext.kotlin_version property.

Checking the license for package NDK (Side by side) 25.1.8937393 in C:\Users\hp\AppData\Local\Android\sdk\licenses
License for package NDK (Side by side) 25.1.8937393 accepted.
Preparing "Install NDK (Side by side) 25.1.8937393 v.25.1.8937393".
"Install NDK (Side by side) 25.1.8937393 v.25.1.8937393" ready.
Installing NDK (Side by side) 25.1.8937393 in C:\Users\hp\AppData\Local\Android\sdk\ndk\25.1.8937393
"Install NDK (Side by side) 25.1.8937393 v.25.1.8937393" complete.
"Install NDK (Side by side) 25.1.8937393 v.25.1.8937393" finished.
Checking the license for package Android SDK Build-Tools 34 in C:\Users\hp\AppData\Local\Android\sdk\licenses
License for package Android SDK Build-Tools 34 accepted.
Preparing "Install Android SDK Build-Tools 34 v.34.0.0".
"Install Android SDK Build-Tools 34 v.34.0.0" ready.
Installing Android SDK Build-Tools 34 in C:\Users\hp\AppData\Local\Android\sdk\build-tools\34.0.0
"Install Android SDK Build-Tools 34 v.34.0.0" complete.
"Install Android SDK Build-Tools 34 v.34.0.0" finished.
Checking the license for package Android SDK Platform 34 in C:\Users\hp\AppData\Local\Android\sdk\licenses
License for package Android SDK Platform 34 accepted.
Preparing "Install Android SDK Platform 34 (revision 3)".
"Install Android SDK Platform 34 (revision 3)" ready.
Installing Android SDK Platform 34 in C:\Users\hp\AppData\Local\Android\sdk\platforms\android-34
"Install Android SDK Platform 34 (revision 3)" complete.
"Install Android SDK Platform 34 (revision 3)" finished.

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':path_provider_android:compileDebugJavaWithJavac'.
> Could not resolve all files for configuration ':path_provider_android:androidJdkImage'.
   > Failed to transform core-for-system-modules.jar to match attributes {artifactType=_internal_android_jdk_image, org.gradle.libraryelements=jar, org.gradle.usage=java-runtime}.
      > Execution failed for JdkImageTransform: C:\Users\hp\AppData\Local\Android\sdk\platforms\android-34\core-for-system-modules.jar.
         > Error while executing process D:\Android\jbr\bin\jlink.exe with arguments {--module-path C:\Users\hp\.gradle\caches\transforms-3\bc144398e63080bbf549a8a3e80aa3f1\transformed\output\temp\jmod --add-modules java.base --output C:\Users\hp\.gradle\caches\transforms-3\bc144398e63080bbf549a8a3e80aa3f1\transformed\output\jdkImage --disable-plugin system-modules}

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
> Get more help at https://help.gradle.org.

BUILD FAILED in 7m 10s
Running Gradle task 'assembleDebug'...                            432,0s

┌─ Flutter Fix ─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ [!] This is likely due to a known bug in Android Gradle Plugin (AGP) versions less than 8.2.1, when                                   │
│   1. setting a value for SourceCompatibility and                                                                                      │
│   2. using Java 21 or above.                                                                                                          │
│ To fix this error, please upgrade your AGP version to at least 8.2.1. The version of AGP that your project uses is likely defined in: │
│ D:\API\praktikum-uts-2b-MuhAinulHuda24\android\settings.gradle,                                                                       │
│ in the 'plugins' closure (by the number following "com.android.application").                                                         │
│  Alternatively, if your project was created with an older version of the templates, it is likely                                      │
│ in the buildscript.dependencies closure of the top-level build.gradle:                                                                │
│ D:\API\praktikum-uts-2b-MuhAinulHuda24\android\build.gradle,                                                                          │
│ as the number following "com.android.tools.build:gradle:".                                                                            │
│                                                                                                                                       │
│ For more information, see:                                                                                                            │
│ https://issuetracker.google.com/issues/294137077                                                                                      │
│ https://github.com/flutter/flutter/issues/156304                                                                                      │
└───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┘
Error: Gradle task assembleDebug failed with exit code 1

bagaimana arti dari error ini dan solusinya bagaimana ?

setelah itu aku mecoba membenahinya dan alhamdulillah bisa, tetapi memang belum selesai semua

