# RoLinux
Roblox on Linux
--------------------

So, one day in August, I wanted to play Roblox on my Pi 5. So I had 2 options:
1. Using Wine
2. Using Sober
So I tried installing Wine on [Pi-Apps, an app store for Raspberry Pi OS](pi-apps.io), but it would not install, so I decided to file an issue on GitHub, come check out my issue [here](https://github.com/Botspot/pi-apps/issues/2824) (but it's probably closed). [I couldn't find anything](problem1.png) So I checked [the Wine FAQ](winehq.org).
### So I tried [Sober](sober.png)
Sober is Roblox on Linux. So I went to [Sober's official website](https://sober.vinegarhq.org/) and then installed Flatpak and Flathub with this command.
```bash
sudo apt install flatpak
```
And everything installed. But here is where the problem would start.
To install Sober, I had to run this command:
```bash
flatpak install flathub org.vinegarhq.Sober
```
But an error message came.
```
error: Nothing matches org.vinegarhq.Sober in remote flathub
```
I tried searching [the Sober FAQ](https://vinegarhq.org/Sober/FAQ/index.html) until I gave up.
So I decided: Why not make my own solution?

That's how this came to exist explained in less than 20 lines of text.

Written by: @akishore15
How to use coming soon!
