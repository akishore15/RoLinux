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

But how do you use it?

It uses Docker, the underlying technlogy behind tons of things that you use. You can run Windows on a Mac using Docker. So you need Docker installed on your computer. Learn how to install it [here](https://docs.docker.com/engine/install/). You will need to use [this image](https://hub.docker.com/r/cimg/android) and build a container. If you don't know how to do that, learn it [here](https://www.youtube.com/watch?v=eGz9DS-aIeY) I'm too lazy and sleepy (I'm writing this at 12AM here in Seattle) to actually explain to you. Anyway, now that you have the Android, you can go to the Play Store and install Roblox (and probably grind on it for hours)
And for those people asking why I am not using iOS, it's easier to get a copy of Android for free, but a copy of iOS? I'll have to pay majority of my college fund (yes, I am a kid writing this) just for an iOS copy. And if you want iOS, I'll have to change this from open-source, to $2000 USD for one copy of this. This was made to be a completely free alternative to Wine and Sober if you don't feel comfortable working with them or it does not work with your computer.

Written by: @akishore15
