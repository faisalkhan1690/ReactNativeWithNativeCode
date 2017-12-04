ReactNativeWithNativeCode
===================================
A sample project to understand how to integrate react native code in android native code. 

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.2
- Android studio 
- React Native congiured system (NPM)
- Visula code (You can use other tools also like Atom etc)


Steps to connect native code with React Native code 
--------------
1. Create one sample project using follwing commond 
```cmd 
$ react-native inti AwesomeProject
```
2. Once your the processing is done. Open project folder and you will find structure like this
![screenshot from 2017-12-04 20-08-05](https://user-images.githubusercontent.com/7554816/33558023-e519a394-d92e-11e7-8ff9-f7f53506d8a6.png)

3. Now open this android folder in android studio and create one activity that will be your first activity.Once your create activity you will find one new class in package and one new layout in res/layout folder. As of now in my project i have created one new activity FirstActivity.java and activity_first.xml layout.
![screenshot from 2017-12-04 20-14-57](https://user-images.githubusercontent.com/7554816/33558546-2796bc74-d930-11e7-9253-bff1f6387656.png)
![screenshot from 2017-12-04 20-15-56](https://user-images.githubusercontent.com/7554816/33558547-27d01960-d930-11e7-947e-5aa63aa24980.png)

4. Now go in Manifest.xml and change first activity of application from MainActivty.java to your Activity.
![screenshot from 2017-12-04 20-19-25](https://user-images.githubusercontent.com/7554816/33558657-77483338-d930-11e7-8257-d016e0042c01.png)

5. Now start one intent from 
![screenshot from 2017-12-04 20-16-09](https://user-images.githubusercontent.com/7554816/33559296-534f5626-d932-11e7-8958-9ae407d4f97d.png)

5. Now go in cmd and run follwoing commond 
```cmd 
~ $ cd AwesomeProject
~/AwesomeProject $ npm start
```
And now run project in Android studio. This is it. 
![screenshot_1512396890](https://user-images.githubusercontent.com/7554816/33559212-146a77c4-d932-11e7-9971-9d49e5266a86.png)
![screenshot_1512396893](https://user-images.githubusercontent.com/7554816/33559213-14a77566-d932-11e7-91ac-16bfb0c7da31.png)


References 
--------------
https://facebook.github.io/react-native/docs/getting-started.html
https://developer.android.com/studio/index.html?gclid=Cj0KCQiAgZTRBRDmARIsAJvVWAtu_imrQqm8SIgN1le4ZuVr8S2E_PKLQY1zqRyx--gvdyKx4-alI6caAhCeEALw_wcB


