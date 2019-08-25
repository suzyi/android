# android
## android development
### installation
Before installation
+ You need to have "java jdk" and "android sdk" install on your computer.
+ You have to ensure your computer is connected to 'dl.google.com' by `ping dl.google.com`. If you're unable to connect to this website, two method you can try: method 1 - Add one line "203.208.39.232 dl.google.com" at the ubuntu hosts file. Method 2 - You need vpn to download some components from "dl.google.com" during the process of installation. Basicly, I've tried both two method and the former one is much more reliable.

After installation
+ You may find tab completion errors: "bash: cannot create temp file for here-document: No space left on device". To fix this, by `du -sh /usr/* |grep G` to show all files that is greater than 1GB, `du -sh /usr/android-studio/* |grep G` and then delete un-important files.
+ If installation failed, please completely uninstall android studio from ubuntu, method including [uninstall AS](http://simplecode.xyz/?p=87) or google for other method.

+ If there're any bugs that you find very difficult to fix, go to "taobao.com" for help with some extra fee.

General installation steps:
+ install java JDK
+ install android SDK
+ install android studio
+ [android studio](https://developer.android.com/studio/) - [build your first app](https://developer.android.com/training/basics/firstapp/)

## project
+ How to release/export a project as apk file? Refer to [csdn-woaichimahua](https://blog.csdn.net/woaichimahua/article/details/54427528)
### My first App
This app only show "Hello world!" on my Huawei phone.
+ The procedure of implemention is [building your first app](https://developer.android.com/training/basics/firstapp/)
### calculator
Ｔｈｉｓ app 
+
### camera
### object counting/detection
+ task decription - You need to finish an APP, which can use camera to proceeding object-detection tasks, such counting and face recognition.
