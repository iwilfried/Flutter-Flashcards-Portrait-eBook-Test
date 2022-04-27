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
<img src="./img/SDK.png"/>
</div>


C:\flutter> flutter doctor

With the execution of this command, it will check your environment and display the Flutter installation status. Find out the below results for any additional applications you are required to install or further tasks to complement.

[-] Android toolchain - develop for Android devices

Android SDK at C:\Android\sdk

? Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
Try re-installing or updating your Android SDK,
visit https://flutter.dev/setup/#android-setup for detailed instructions.
