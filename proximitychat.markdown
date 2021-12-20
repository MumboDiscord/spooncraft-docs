---
title: "Installing proximity chat"
description: "Here’s the tutorial to help get you set up with the proximity chat mod for the Spooncraft server. This is completely optional and you can still join the server with a vanilla client, but the option is there for people that want it :D"
permalink: /proximitychat/
layout: single
sidebar:
  title: "Pages"
  nav: sidebar
last_modified_at: 2021-10-21
toc: true
---

![voicechat]({{ site.url }}{{ site.baseurl }}/assets/images/voicechat.png){: .align-center}

Here’s the tutorial to help get you set up with the proximity chat mod for the Spooncraft server. This is **completely optional** and you can still join the server with a vanilla client, but the option is there for people that want it :D

I’m only going to be talking about the default minecraft launcher here as that’s what most people will be familiar with, but if you want to use another launcher like MultiMC or GDLauncher feel free to adapt these steps for your needs. 

If you’re having any problems with this, you can let us know in **#in-game-help** on discord and we’ll try to help you out :P
{: .notice}

## Instructions

1. Go to [the fabric website](https://fabricmc.net/use/), and click **Download installer (Universal/.JAR).**
2. Run the fabric installer by double clicking the jar file you just downloaded (close the minecraft launcher while doing this). If it doesn’t open and instead asks you what to open it with, you need to [install java](https://www.java.com/).
3. Make sure Minecraft Version is set to **1.17.1**, and leave everything else as default, then click install.
4. Open the Minecraft Launcher, select the **fabric-loader-1.17.1** profile and then launch the game. Once the game loads, make sure it says **Minecraft 1.17.1/Fabric** on the bottom left in the main menu, then close the game again.
5. Go to [Plasmo Voice Client](https://www.curseforge.com/minecraft/mc-mods/plasmo-voice-client/files) and download the latest **1.17.1 fabric** version of the voice client.
6. **On windows:** Press windows key + r and type `%appdata%` and press OK. Then open the `.minecraft` folder and then open the `mods` folder. \
**On mac:** Open spotlight search and type: `~/Library/Application Support/minecraft`, then hit enter and open up the `mods` folder. \
**On linux:** I can’t give you detailed steps here since it’ll vary from distro to distro, but you’ll need to browse to `~/.minecraft`. You can use google for more detailed steps. Once you’re in the .minecraft folder, open up the `mods` folder.
7. Once you’re in the mods folder, copy the `plasmovoice-fabric-1.17.1-x.x.x.jar` you downloaded into it.

8. **(Optional)** If you want to run OptiFine at the same time as proximity chat, grab the latest 1.17.1 [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric/files) and copy it into the mods folder. Then, download the latest version of [OptiFine](https://optifine.net/downloads) and copy the file into the `mods` folder. If you want to, you can also download other fabric mods and place them in the `mods` folder.

9. Open the Minecraft Launcher again, select the **fabric-loader-1.17.1** profile and launch the game. Proximity chat should now be installed and you can try connecting to Spooncraft.

## Important info

To configure the chat settings, press **V** and you’ll be able to adjust volume, microphone settings and a few other things. If you use push to talk, **Left Alt** is the default button. Controls can be changed in the standard minecraft controls menu.
{: .notice}

If you want to use **voice activation** instead of push to talk, go to audio in the settings (press V) and change the activation type. **You will need to change the voice activation threshold to be lower, otherwise it will not work.**
{: .notice}

On the main **survival server**, the voice distance is set to **16** by default and can be changed between 8, 16 and 24. On the **creative server**, the voice distance is set to **128** by default and can be changed between 8, 16, 24 and 128.
{: .notice}