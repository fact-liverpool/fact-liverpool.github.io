---
layout: post
title: Cloudmaker
permalink: documentation-test
img: featured/Cloudmaker.png
category: [NSTAG, SHS]
---
## [FACT](http://fact.co.uk) minecraft server and resources for Teaching and Engagement through social design and game culture frameworks

<iframe src="https://player.vimeo.com/video/92258008?portrait=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

### From [Ross Dalziel github](https://github.com/cheapjack/CloudMaker)

For Minecraft PC client version `1.7.9`

![CloudMaker](/images/featured/Cloudmaker.png)

### Quickstart

We've made a minecraft server for version `1.7.9` that you can send python commands to, build, explore and play with Minecraft. It's also got a version of [ScriptCraft](http://scriptcraftjs.org/) setup.

Alternatively you can run your own server with CanaryMod and Canary Raspberry Juice Plugin. You could use the server we made with [@radamar](https://twitter.com/@radamar) [here](https://github.com/radames/Minecraft-Solar-Explorations/tree/atomic)

And you can also run the game and code locally on [Raspberry Pi](http://pi.minecraft.net/) and follow the guides [here](https://www.raspberrypi.org/learning/getting-started-with-minecraft-pi/)

#### Using the FACT CloudMaker server

Go to `Add Server` and enter a name for the server like `CloudMaker` the address `mc.fact.co.uk:25568`

**Make sure you are running client in version `1.7.9`**

On spawn you will be part of the `Default` user group outside a map of [FACT](http://fact.co.uk/). You can build pretty much anything in Creative mode as you explore the worlds via the FACT gallery entrances but PVP, lava fire, TNT ignition are banned I'm afraid. You cannot build or destroy blocks in the building but outside and in other un-protected areas build what you want. `World` is the main experimental world where all the Raspberry Juice magic happens and you can get there through the gallery 1 opening on the left..

Enter lifts to teleport to other floors (be careful not to walk back into them by mistake reversing out helps), get a drink in the bar and enter the gallery spaces to jump to other worlds.

You can look at the [server `dynmap` here](http://mc.fact.co.uk:8124)

You can use the `/warp` command to explore areas of the server and list all available warps with `/listwarps`.

Features the bukkit [Raspberry Juice](https://github.com/martinohanlon/CanaryRaspberryJuice) plugin that lets you send python commands using the [Minecraft: Pi Edition](http://pi.minecraft.net/) `mcpi` API described [here](https://github.com/martinohanlon/Minecraft-Pi-API)  plus Walter Higgins' [ScriptCraft](https://github.com/walterhiggins/ScriptCraft)

### Background

CloudMaker and [The Minecraft Of Things](http://minecraftofthings.tumblr.com) sprang from research with [FACT](http://fact.co.uk/), [Dr Mark Wright](https://twitter.com/dr_mark_wright), [Adrian McEwen](http://www.mcqn.com/) and Paul Harter of [PrintCraft](http://www.printcraft.org/) funded by [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) for the [CloudMaker](http://www.fact.co.uk/projects/cloudmaker-making-minecraft-real.aspx) project

Find out more in the [project video here](https://vimeo.com/92258008)

## Research Outputs and Spin-Outs

![rfcraftpi](https://cloud.githubusercontent.com/assets/128456/11501525/b5ac718a-982c-11e5-957e-e393b6b7c2ae.png)

CloudMaker has resulted in numerous outputs documented [here](https://github.com/cheapjack/CloudMaker/blob/master/EverythingMinecraft.md) resulting in a range of research projects that use the CloudMaker server and build and extend the ITaaU research.

 * [RF-Craft](https://github.com/cheapjack/RF-Craft)
  * Open source Radio messaging system using the [RFM69HW tranceiver chip](https://lowpowerlab.com/shop/rfm69hw) and the radio frequency 868MHz designed by technician in residence at [DoESLiverpool](http://doesliverpool.com) [DefProc](http://www.deferredprocrastination.co.uk/) RF-Craft is a prototype Raspberry Pi [HAT](https://github.com/raspberrypi/hats) (Hardware Attached on Top) and arduino clone to send `mcpi` API  commands to a minecraft server. It features an onboard button and light, digital input for a Dallas DS18B20 one-wire temperature sensor and 5 analog inputs. It can act as a powered HAT or an arduino radio receiver or transmitter.
 * [StasisCraft](https://github.com/cheapjack/StasisCraft)
  * CloudMaker resources for Teaching and Engaging with KS4 HomeoStasis through Minecraft & Python
 * [MemoryCraft](https://github.com/cheapjack/MemoryCraft)
  * Exploring Memory through the Internet Of Things, scale maps and MineCraft
 * [ShrimpCraft](https://github.com/cheapjack/ShrimpCraft)
  * Breadboard based Minecraft/Shrimping.It/Python sensor kits for the Internet of Things
 * [Minecraft Of Things](https://github.com/cheapjack/MoT)
  * Resources for Exploring The Internet of Things (IoT) with Minecraft
 * [cocklecraft-of-things](https://github.com/mcqn/cocklecraft-of-things)
  * A breadboard temperature sensor with WiFi using the [Sparkfun ESP8266 Thing](https://www.sparkfun.com/products/13231) for pushing temperature data to the cloud using [ThingSpeak](https://thingspeak.com/). Also features a a pop up [Flask](http://flask.pocoo.org/) server to post data locally.   
 * [MindCraft](https://github.com/cheapjack/MindCraft)
  * [Gemma May Latham's](http://gemmamaylatham.co.uk/) Resources for connecting Minecraft with EEG headset raw data, using the NeuroSky Mindwave Mobile Headset
 * [Minecraft-Solar-Explorations](https://github.com/radames/Minecraft-Solar-Explorations)
  * Resources for exploring scale with a custom CanaryMod server made by [@cheapjack](https://twitter.com/cheapjack) & [@radamar](https://twitter.com/cheapjack)

### Wiki

Read the [CloudMakerWiki](https://github.com/cheapjack/CloudMaker/wiki) here

### Plugins & Features

You need Builder or Admin permissions to use most of the tools like WorldEdit etc. and generally you only get this if you're part of a FACT project at the moment. Leave messages on signs for `Ops` if you want to do something in particular and want to use CloudMaker to do it or raise an issue on github.

 * `mcpi` is an API for Minecraft Pi Edition, released under an MIT License and is maintained by Martin O'Hanlon's [Stuff About Code](http://www.stuffaboutcode.com/p/minecraft.html) project.
 * RaspberryJuice 1.3.2 enables the use of the `mcpi` API with an additional `server.py` moduleincluded.
 * Dynmap  [View the map](http://mc.fact.co.uk:8124)
 * Essentials [wiki](wiki.mc-ess.net)
 * WorldEdit
 * Multi-Verse [wiki](https://github.com/Multiverse/Multiverse-Core/wiki/basics)
 * Printcraft [Bukkit Plugin Page](http://dev.bukkit.org/bukkit-plugins/printbot/)
 * ScriptCraft [wiki](https://github.com/walterhiggins/ScriptCraft/blob/master/docs/YoungPersonsGuideToProgrammingMinecraft.md)

### Staying Safe

<img src="https://www.nspcc.org.uk/globalassets/blocks/about-us/our-partners/o2/o2-partnership/minecraft-cta-v4.png" width="400">

The NSPCC have this great [online guide](https://www.nspcc.org.uk/preventing-abuse/keeping-children-safe/online-safety/minecraft-a-parents-guide) for parents and carers and players if you have any concerns about online safety.

The internal WhitCraft server is white-listed while the public one is not, but all server logs are recorded. If you have any concerns please contact Steven Roper at the Whitworth Art Gallery or any staff member.

We cannot accept any liabilty for what may happen on these servers but will endeavour to block any inappropriate behaviour where possible and can ban players where necessary.


### Is This Open Source?

The project is essentially about data, code and hardware literacy in the context of social design and gaming. It's released under a permissive MIT License but not necessarily recursively; some elements are released under certain different terms and you will need follow back to source to see this.

CloudMaker follows the `spirit` of open source although some elements used may not **strictly** be `open-source`:

 * Minecraft is not open source but has a large and healthy modding culture. In many ways this culture IS the game. You have to buy the game basically to play on servers. This project however is based on the use of [Minecraft Pi Edition](http://pi.minecraft.net/?page_id=14) which is free to download and use and initiated by Mojang but maintained by the Minecraft and [Raspberry Pi](http://elinux.org/RPi_Hub) community
 * `mcpi` is released under an MIT License and is maintained by Martin O'Hanlon's [Stuff About Code](http://www.stuffaboutcode.com/p/minecraft.html) project.

### Is Minecraft a learning platform

Using Minecraft to learn is an exciting area but after a year of research and activity we believe it's not a platform. A platform implies stability and comprehensiveness and minecraft and the components you can use to play with it is a constantly changing beast.

What we've tried to do is to make a curated portal into the world of learning  with minecraft, pointing at the great work being done in the community. We have tried to show a diverse approach and share what we've learnt.

One thing I think is essential is people; you need people to learn: you dont just learn after downloading the game, it takes the performance of a teacher or student or player to make the imaginitive stuff happen.

What we've tried to do is make some resources for exploring the Internet of Things and some hardware designs that could help. We believe experimenting with the game is like a gateway to the sort of skills and literacy needed to work and use IoT.
