# capacitor-tutorial

1. create an angular application
ng new angular-app

2. Install Capacitor in your project
npm install --save @capacitor/core @capacitor/cli

After successfully installed the capacitor you see in the pckage.json file.

3. Change Output Path to “www”
Then open the “angular.json” file and change “outputPath”: “dist/AngularApp” to “outputPath”: “www”.

4. Build Product
ng build --configuration production

5. Initialise Capacitor in your project
npx cap init

6. Install android for capacitor
npm install @capacitor/android

7. Add Android platform
npx cap add android

After that, If you change anything in the web-based code, you can use the below code to copy those things to the native app.

8. Then run the below code to open the application in Android Studio.
npx cap open android

After the run “npx cap open android“, android studio automatically open and then you can run the app on the emulator or your phone using USB debugging. Then you can see the output like below in your phone or emulator.
