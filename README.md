# ios-cardboard-in-space
My first go at working with Unity and the Google Cardboard SDK.

## Steps To Run App
If you wish to download this and run it on iOS you'll need to do a few things first. 
1. Download and unzip project
2. Download and run [Unity][unity]
3. Open `ios-cardboard-in-space` project in Unity
4. Click `File > Build` and save where you can access it
5. Open the project in Xcode
6. In Xcode, click the project in the left pane and go to `Build Settings`
7. Search `Enable Bitcode` and change it to NO
8. Go to Build `Build Phases > Link Binary With Library > Add` and add `Security.framework`
9. Build and run on device

## Screen Shots
<img src="https://raw.github.com/khaptonstall/ios-cardboard-in-space/master/Screens/Screen1.png" width="360" />


<img src="https://raw.github.com/khaptonstall/ios-cardboard-in-space/master/Screens/Screen2.png" width="360" />




[unity]:  https://unity3d.com/get-unity
