## Set-Up 

?> What’s Flutter?  

<p>Developed by Google, Flutter is a mobile app SDK, which allows developers to develop high-quality native interfaces for iOS, Android, Web, macOS, and Linux devices using a single codebase. It allows developers to write a code once and use it on different software devices.</p> 

Flutter is a free and open-source framework. The amazing features of Flutter enhance the mobile app development experiences.

Therefore, Flutter is the best choice for every startup.


### Minimum Requirements

- Operating Systems: Windows 7 SP1 or later (64-bit)
- Disk Space: At least 400 MB.
- Tools: Flutter depends on these tools being available in your environment.
- Windows PowerShell 5.0 or newer (this is pre-installed with Windows 10)
- Git For Windows

### Installing Chocolatey

?> On windows, the easiest way to install Flutter is via the package manager <strong>Chocolatey</strong>.  
<p>With PowerShell, you must ensure Get-ExecutionPolicy is not Restricted.</br>
Run the following command in Windows Powershell</p>

```
C:\>Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

<p>If you don't see any errors, you are ready to use Chocolatey!</p>

> C:\> **choco**

<pre><i>Chocolatey v1.1.0    
Please run 'choco -?' or 'choco <command> -?' for help menu.</i></pre></br> 

`With Chocolatey on your machine, you simply have to run:`


> C:\> **choco install flutter**

<br>

<div align=center>
<img src="./img/Flutter.png"/>
</div>


> C:\> **flutter doctor**  

<p>With the execution of this command, it will check your environment and display the Flutter installation status. Find out the below results for any additional applications you are required to install or further tasks to complement.</p>

### Android toolchain - develop for Android devices  

Android SDK at C:\Android\sdk  

? Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
Try re-installing or updating your Android SDK,
visit https://flutter.dev/setup/#android-setup for detailed instructions.  

### How to Install Flutter on Android?
Download the Android Studio and install it.
Open Android Studio > Android Studio Setup Wizard . This installs the latest version of Android SDK, Android SDK Platform-Tools, and Android SDK Build-Tools, which are essential while developing a Flutter app for the Android system.

### Set Up Your Android Device
Before going further, make sure that your Android device runs on the Android 4.1 version (API level 16) or higher.

Enable Developer Options and USB debugging on your device. You can read further on Android documentation.
Install Google USB Driver for Windows-only.
Now plug your Android device into the computer using a USB cable. Give access to your device through the computer.
Now run the flutter devices command to verify that Flutter accesses your connected Android device
Actually, Flutter uses the default version of the Android SDK where your adb tool is located.

If you want to use a different version of Android SDK for Flutter, then set the ANDROID_HOME environment variable to that installation directory.

### Set Up Android Emulator
Enable VM acceleration on your device.
Open Android Studio > Tools > Android > AVD Manager and select Create Virtual Device .
Set Up Android Emulator

Select a device definition and click Next .
Select Virtual Devices

Select a system image and click Next .
Click Finish .
Install the Flutter and Dart Plugins – Android Studio
Install the Flutter and Dart Plugins

1. Open Android Studio .

2. Open plugin preferences ( File > Settings > Plugins ).

3. Select Browser repositories , select the Flutter plugin and click Install .

4. Click Yes when prompted to install the Dart plugin.

5. Click Restart when prompted.

Tadda! Now, you are one step closer to becoming a Flutter developer.

Flutter and Dart are the right choices if you wish to develop feature-rich mobile and web interfaces in a given time.

Since you are on the verge of developing an app using Flutter app development services, we chose to guide you through this tutorial of Flutter installation on your system.

Now you know how to install Flutter on different systems – Android, iOS, and Windows. So, install the Flutter on your existing system and walk on the path of a developer. I hope this guide helps you with the installation process. If you still face any issues with the installation process, you can consult the top-notch Flutter app development company, Radixweb.

Good luck in your development journey!
