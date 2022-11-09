# My App

A template project for Flutter apps


To use flutter_native_splash :

- choose an image for the splashscreen
- name it logo_splash.png
- put it in 'assets/icons'
- use flutter pub run flutter_native_splash:create


To use flutter_launcher_icons :

- choose an image for the splashscreen
- name it logo.png
- put it in 'assets/icons'
- use flutter pub run flutter_launcher_icons:main


If <span style="color:red">**Cannot not find minSdk**</span> error :
- in android/local.properties add :
  - flutter.minSdkVersion=16
  - flutter.targetSdkVersion=31
