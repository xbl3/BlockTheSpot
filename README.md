[![Build status](https://ci.appveyor.com/api/projects/status/31l6ynm0a1fhr2vs/branch/master?svg=true)](https://ci.appveyor.com/project/mrpond/blockthespot/branch/master)

<center>
  <h1 align="center">BlockTheSpot</h1>
  <h4 align="center">A multi-purpose adblocker and skip bypass for the <strong>Windows</strong> Spotify Desktop Application.</h4>
  <h5 align="center">Please support Spotify by purchasing premium</h5>
  <p align="center">
    <strong>Last updated:</strong> 1 March 2020<br>
    <strong>Last tested version:</strong> 1.1.31.703.g256add22
  </p>
  <h4 align="center">Important!!</h4>
 * Do Windows Update/Patch<br>
 * Make sure you antivirus working and had latest virus signature<br>
 * "chrome_elf.dll" gets replaced by Spotify Installer each time it updates, make sure to replace it again.<br>
</center>

#### IMPORTANT FOR OLD USER:
1. Goto "windows security" -> "Virus & Threat protection"
2. Click "Allowed threats" -> Remove all allowed threats

### Features:
* Blocks all banner/video/audio ads within the app
* Retains friend, vertical video and radio functionality
* Unlocks the skip function for any track

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows, **not the Microsoft Store version**.

#### Installation/Update:
* Just run BlockTheSpot.bat
or
1. Browse to Spotify installation folder `%APPDATA%\Spotify`
2. Download chrome_elf.zip from [releases](https://github.com/mrpond/BlockTheSpot/releases)
3. Replace chrome_elf.dll, config.ini from chrome_elf.zip to that folder. 

#### Uninstall:
* Just run uninstall.bat
or
* reinstall spotify

#### Note:
* Ads banner maybe appear if you network use 'Web Proxy Auto-Discovery Protocol'
https://en.wikipedia.org/wiki/Web_Proxy_Auto-Discovery_Protocol
set Skip_wpad in config.ini to 1 may help.
* if automatic install/uninstall .bat not working please contact (https://github.com/rednek46)