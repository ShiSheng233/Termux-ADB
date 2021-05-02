# Termux-ADB

[![](https://data.jsdelivr.com/v1/package/gh/ShiSheng233/Termux-ADB/badge)](https://www.jsdelivr.com/package/gh/ShiSheng233/Termux-ADB)

> Install ADB & FastBoot Tools in Termux

By use this tool, you can use adb & fastboot in Termux.

For devices with ARM or ARM64 processors only.

Now using Jsdelivr CDN for file transfer.

~~ADB binarie version **may be** updated **later**.~~

Now the ADB binaries updated.

Thanks to the Magisk module project [adb-ndk](https://github.com/Magisk-Modules-Repo/adb-ndk).

_Important: If you want to update the binaries, I think you should uninstall and reinstall it._

## How to install

- <b>Silent installation:</b></br>
Copy and paste the following command in Termux to silently install Tools:<br/>
```apt update > /dev/null 2>&1 && apt --assume-yes install wget > /dev/null 2>&1 && wget https://cdn.jsdelivr.net/gh/ShiSheng233/Termux-ADB@master/InstallTools.sh -q && bash InstallTools.sh```<br/>
- <b>Common installation:</b><br/>
Copy and paste the following command in Termux to install Tools with logs output:<br/>
```apt update && apt install wget && wget https://cdn.jsdelivr.net/gh/ShiSheng233/Termux-ADB@master/InstallTools.sh && bash InstallTools.sh```<br/>

## How to uninstall

- <b>Silent uninstallation:</b></br>
Copy and paste the following command in Termux to silently remove Tools:<br/>
```apt update > /dev/null 2>&1 && apt --assume-yes install wget > /dev/null 2>&1 && wget https://cdn.jsdelivr.net/gh/ShiSheng233/Termux-ADB@master/RemoveTools.sh -q && bash RemoveTools.sh```<br/>
- <b>Common uninstallation:</b><br/>
Copy and paste the following command in Termux to remove Tools with logs output:<br/>
```apt update && apt install wget && wget https://cdn.jsdelivr.net/gh/ShiSheng233/Termux-ADB@master/RemoveTools.sh && bash RemoveTools.sh```<br/>

## Credits

- <a href="https://github.com/MasterDevX">MasterDevX</a> - Scripts development.
- <a href="https://github.com/osm0sis">osm0sis</a> - Binaries compilation & Magisk module project [adb-ndk](https://github.com/Magisk-Modules-Repo/adb-ndk).
- <a href="https://github.com/chameleonbr">chameleonbr</a> - Author of idea.

---

Powered by ShiSheng with Love.