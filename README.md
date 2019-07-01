Based on [cordova-plugin-background-mode.git](https://github.com/katzer/cordova-plugin-background-mode.git) 0.7.2 with following changes:

0.7.3

- Fix crash on iOS 12

  0.7.4

- Fix crash on Android 9

  0.7.5

- Remove Windows Platform

## iOS Pitfalls

On iOS this plugin is extremly ugly: It uses a very short `.wav` file and plays it with volume 0 in an endless loop. So in order to get this to work under iOS you need the "Background Audio"-capability. Also it will mute any sound-output that your app might have, as soon as you go to background.
