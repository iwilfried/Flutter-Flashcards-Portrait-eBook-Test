## Set-Up 

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
**C:\>**Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

If you don't see any errors, you are ready to use Chocolatey!</p>

```
C:\>choco
```

<pre><i>Chocolatey v1.1.0    
Please run 'choco -?' or 'choco <command> -?' for help menu.</i></pre></br>  

`With Chocolatey on your machine, you simply have to run:`

```
C:\> choco install flutter
```


<div align=center>
<img width="450" src="./img/SDK.png"/>
</div>
