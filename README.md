# cordova-ios-fullscreen

`cordova plugin add https://github.com/innowatio/cordova-ios-fullscreen.git`

It will add the following part to the `*-Info.plist` file during build process:

```xml
<key>UIRequiresFullScreen</key>
<true />
<key>UIStatusBarHidden</key>
<true />
<key>UIViewControllerBasedStatusBarAppearance</key>
<false />
```
