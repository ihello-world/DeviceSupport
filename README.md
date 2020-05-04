# How to Fix "This iPhone xx is running iOS 13.3.1 (17D50), which may not be supported by this version of Xcode."


```
13.3.1 = iOS version number
(17D50) = build number
```

# Solutions:
* **Step 1**: Download iOS version [13.3.1 (17D50)](https://github.com/ihello-world/DeviceSupport/tree/master/iPhoneOS/13.3.1%20(17d50)) from github
* **Step 2**: Unzip downloaded file
* **Step 3**: Close Xcode
* **Step 4**: Go to Application Folder and Find Xcode;
* **Step 5**: Right click on Xcode and click on "Show Package Content";
* **Step 6**: Then, go to Contents -> Developer -> Platforms -> iPhoneOS.platforms -> DeviceSupport
* **Step 7**: Now, drag and drop the updates device support file to the old Xcode Device support folder and restart the Xcode. 
This should have fixed the error


# Device Support files for Xcode
   * [iPhoneOS](https://github.com/ihello-world/DeviceSupport/tree/master/iPhoneOS)
   * [AppleTVOS](https://github.com/ihello-world/DeviceSupport/tree/master/AppleTVOS) 
   * [WatchOS](https://github.com/ihello-world/DeviceSupport/tree/master/WatchOS)
   
