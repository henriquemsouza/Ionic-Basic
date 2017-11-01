# Ionic-Basic
***
***


## Install Ionic on Windows

 1. download and install the Node:

 [Download Link](https://nodejs.org/en/download/)

2. install ionic:
```
npm install -g ionic cordova
```

3. Java JDK | Install the most recent Java JDK
```
Next, create an environment variable for JAVA_HOME pointing to the root folder where the Java JDK was installed. So, if you installed the JDK into C:\Program Files\Java\jdk7, set JAVA_HOME to be this path. After that, add the JDK's bin directory to the PATH variable as well. Following the previous assumption, this should be either %JAVA_HOME%\bin or the full path C:\Program Files\Java\jdk7\bin
```
4. Install Apache Ant:
```
To install Ant, download a zip from here, extract it, move the first folder in the zip to a safe place, and update your PATH to include the bin folder in that folder. For example, if you moved the Ant folder to c:/, you'd want to add this to your PATH: C:\apache-ant-1.9.2\bin.
```
5. InstallAndroid SDK:
```
Installing the Android SDK is also necessary. The Android SDK provides you the API libraries and developer tools necessary to build, test, and debug apps for Android.

Cordova requires the ANDROID_HOME environment variable to be set. This should point to the [ANDROID_SDK_DIR]\android-sdk directory (for example c:\android\android-sdk).

Next, update your PATH to include the tools/ and platform-tools/ folder in that folder. So, using ANDROID_HOME, you would add both %ANDROID_HOME%\tools and %ANDROID_HOME%\platform-tools.
  ```
  
6.  Install bower 
 ```
npm install -g bower
 ```
 7. Create the project:
  ```
 ionic start TestApp tabs
  ```
 ###  Configure Platforms
   ```
ionic platform add android  or  ionic cordova platform add android
  ```
  ### Build
    ```
ionic build
  ```
  ## Test The project
    ```
ionic serve
  ```



Error: Cannot find module '@ionic/app-scripts' 
npm i @ionic/app-scripts  

