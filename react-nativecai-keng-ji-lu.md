1. 用`react-native init`创建完项目后，运行`react-native run-android`会提示安卓SDK不存在，因为没配置SDK。官方教程也没说到这一点，奇怪。

   ```
   A problem occurred configuring project ':app'.
   > SDK location not found. Define location with sdk.dir in the local.properties file or with an ANDROID_HOME environment variable.
   ```

   解决办法：在项目的android目录下添加local.properties文件，文件内容为sdk目录，格式如下：  
   `sdk.dir=C\:\\Users\\SUGAR\\AppData\\Local\\Android\\sdk`

2. 然后再运行`react-native run-android` 又会发现问题：`unable to load script from assets index.android.bundle`fafas  
   解决办法：  
   `(in project directory) mkdir android/app/src/main/assets`

   `react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res`

   `react-native run-android`

3. 安卓真机开启Hot Loading方法：摇一摇。。。

4. `Could not expand ZIP .....node_modules\XXXX  
   `解决办法：`cd android && gradlew clean && cd .. && react-native run-android`

5. 鉴于React Native还不完善，先弃坑。。。

6. 


