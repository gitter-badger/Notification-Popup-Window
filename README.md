# Notification Popup Window
### A notification window that appears on the lower right part of the screen for .NET

   [![Nuget](https://img.shields.io/nuget/dt/LiorBanai.NotificationWindow)](https://www.nuget.org/packages/LiorBanai.NotificationWindow/) [![Build Status](https://liorbanai.visualstudio.com/Notification-Window/_apis/build/status/LiorBanai.Notification-Popup-Window?branchName=master)](https://liorbanai.visualstudio.com/Notification-Window/_build/latest?definitionId=5&branchName=master)
<a href="https://github.com/LiorBanai/Notification-Popup-Window/issues">
    <img src="https://img.shields.io/github/issues/LiorBanai/Notification-Popup-Window"  alt="Issues"/>
</a>
<a href="https://github.com/LiorBanai/Notification-Popup-Window/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/LiorBanai/Notification-Popup-Window"  alt="License"/>
</a>
   [![Nuget](https://img.shields.io/nuget/v/LiorBanai.NotificationWindow)](https://www.nuget.org/packages/LiorBanaI.NotificationWindow/)
<a href="https://github.com/LiorBanai/Notification-Popup-Window/releases"> 
    <img src="https://img.shields.io/github/v/release/LiorBanai/Notification-Popup-Window"  alt="Latest Release"/>
</a> 
 <a href="https://github.com/LiorBanai/Notification-Popup-Window/compare/V1.0.0...master">
    <img src="https://img.shields.io/github/commits-since/LiorBanai/Notification-Popup-Window/latest"  alt="Commits Since Latest Release"/>
</a>
       



![Screenshot](Screenshots/example1.png)

This project is based on a [Notification Window](http://www.codeproject.com/Articles/277584/Notification-Window) created in 2011 by Simon Baer. It is also base in [Office 2003-like popup notifier](http://www.codeproject.com/Articles/13547/An-Office-like-popup-notifier) created in 2006 by Nicolas Wälti.

### Features:
- Scroll and/or fade window in and out
- Configure the animation speed and the time the window is displayed
- Display a custom icon
- Set title and content text, font, size, and color
- Set all paddings around icon, title and content
- Sptionally display a close button
- Optionally display a button which opens a context menu
- Supports right to left languages like Persian and Arabic

![Screenshot](Screenshots/example2.png)

### How to use it
Download from the release section and use it this way:
```cs
var popupNotifier = new PopupNotifier();
popupNotifier.TitleText = "Title of popup";
popupNotifier.ContentText  = "Content text";
popupNotifier.IsRightToLeft = false;
popupNotifier.Popup();


```
This repository contains a Visual Studio Test Project if you want a working example.
