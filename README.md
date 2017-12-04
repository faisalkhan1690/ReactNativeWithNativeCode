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
![screenshot from 2017-12-04 20-16-09](https://user-images.githubusercontent.com/7554816/33558651-72d56672-d930-11e7-8f43-52d19b948c56.png)

5. Now go in cmd and run follwoing commond 
```cmd 
~ $ cd AwesomeProject
~/AwesomeProject $ npm start
```
And now run project in Android studio. This is it. 

![screenshot_1512396890](https://user-images.githubusercontent.com/7554816/33557618-c16b83f0-d92d-11e7-9f45-ea41240222aa.png)
![screenshot_1512396893](https://user-images.githubusercontent.com/7554816/33557616-c0612e9c-d92d-11e7-823f-671356263218.png)



