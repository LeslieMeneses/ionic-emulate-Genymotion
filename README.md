# Emulate with Genymotion

1. Dowunload Genymotion - http://ionicframework.com/docs/guide/publishing.html

2. make the .apk file. 
    
        $ ionic build android
   
3. install the application in genymotion drive. 

        $  adb install -r platforms/android/build/outputs/apk/android-debug-unaligned.apk

4. For install in your phone
Only you need put the file platforms/android/build/outputs/apk/android-debug-unaligned.apk in your phone and install.
