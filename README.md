# GoogleSignInAndroid
# Integrating Google Sign-In Android App

First we need to download the google play services in Android SDK manager.

Open the SDK manager from **Tools -> Android -> SDK Manager** and install or update the play services.

**Generating Google-Services.json**
Requires google-services.json file to be add in app folder. you can get this using the below steps.

You should have sha key for getting google-services.json. If you are using android studio use simple step for getting **sha1 key**.
* Run your project
* Click on Gradle menu on right side
* Expand Gradle Tasks tree
* Double click on android -> signingReport and see the magic
* It will tell you everything on the Run tab

After that goto android <a href="https://developers.google.com/identity/sign-in/android/start-integrating" target="_blank" rel="nofollow noopener">quick start guide</a> and click on <a href="https://developers.google.com/mobile/add?platform=android&amp;cntapi=signin&amp;cnturl=https:%2F%2Fdevelopers.google.com%2Fidentity%2Fsign-in%2Fandroid%2Fsign-in%3Fconfigured%3Dtrue&amp;cntlbl=Continue%20Adding%20Sign-In" target="_blank" rel="nofollow noopener">Get A Configuration File</a> button. Here you can choose the project and add your application package name

Enter <strong>SHA1 key</strong> which you saved from Android studio <strong>Run tab</strong> on top
Now Click on <strong>enable google Sign-In</strong> button and click on <strong>Generate Configuration</strong> Files button.

After downloading, copy the google-services.json to the <strong>app/</strong> or <strong>mobile/ module directory</strong> in your Android project.

[Read More...](http://tutorialstack.in/integrating-google-sign-in-android-app/)