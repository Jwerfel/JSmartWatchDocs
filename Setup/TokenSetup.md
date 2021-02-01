---
title: Token Setup
tags: setup
---

# Token Setup
This application requires a SmartThings Personal Access Token. The token then must be entered in the iPhone app and communicated to the Watch app. The steps below will walk you through this process
1. On your iPhone, open the **JSmartWatch** app
<br />
![JSmartWatch App Icon](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/AppIcon.png)
2. Tap on the button labeled **Open Page** to open a browser to the SmartThings token generation page (or open a browser to https://account.smartthings.com/tokens)
<br/>
![Personal Access Token Page](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/PersonalAccessTokens.png)
3. Enter your SmartThings username and password and click **GENERATE NEW TOKEN**
4. Give the token a descriptive name
<br/>
![New Access Token Name](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/NewAccessTokenName.png)
5. This application requires the following authorized scopes:
> - Devices: List all devices, See all devices, control all devices
<br/>
![Devices Scopes](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/DeviceScopes.png)
> - Locations: See all locations
<br/>
![Locations Scopes](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/LocationsScopes.png)
> - Scenes: See all scenes, Control this scene
<br/>
![Scenes Scopes](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/ScenesScopes.png)
6. Click **GENERATE TOKEN**
7. Copy the token to the clipboard
8. Return to the JSmartWatch app and paste the token in the box labeled **Personal Access Token**
9. Open the JSmartWatch app on your watch and tap **Settings**
10. In the iPhone app, tap **Send Token to Watch**
<br/>
![Send token to watch](https://raw.githubusercontent.com/jwerfel/JSmartWatchDocs/DataSource/Images/SendTokenToWatchButton.png)
11. If the token appears on the watch, tap **Save**
12. Setup is complete you can return to the main menu on the watch and you should be able to access your smart home!