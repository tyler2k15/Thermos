# Thermos 
![Thermos](thermos_icon.png)
![Graph](http://i.mcstats.org/Thermos/Global+Statistics@2x.borderless.png)

[![Build Status](https://travis-ci.org/TCPR/Thermos.svg?branch=master)](https://travis-ci.org/TCPR/Thermos)
![Minecraft Forge v10.13.4.1614][forge]
![Minecraft v1.7.10][mc]
![Java JDK v1.8][java]
![Spigot 1.7.10 Snapshot ][spigot]

### What's Thermos?
Thermos is a fork of KCauldron, a craftbukkit forge server for Minecraft 1.7.10. After periods of inactivity on KCauldron's GitLab concerning major issues, Thermos was created to allow active members of the Minecraft coding community to optimize it and provide fixes in a timely manner.

We hope to eliminate all issues with craftbukkit forge servers. In the end, we envision a seamless, low lag Thermos experience.

Advantages over KCauldron:
+ Lag-lowering optimizations
+ Better world protection (Forge stuff doesn't bypass Bukkit plugins!)
+ Many patches that KCauldron didn't get from Spigot


## Installation
Click [here](https://tcpr.github.io/Thermos/install)

## Downloads
You can download the pre-built packages from [here](https://github.com/TCPR/Thermos/releases). 

**These unofficial builds are in beta, they may cause issues with your server. You have been warned!**

P.S. **PLEASE** look at the release notes before downloading! :smile:

##Installing WarmRoast
[Tutorial Video](https://youtu.be/c0ffjooX7Jw)

## Chat

Feel free to drop in on the TCPR Discord chat [here](https://discord.gg/0VmBoNh2sE2XaJ4m)

## Donate/Support

You can pledge to support Robotia and his work through a monthly [Patreon](https://www.patreon.com/robotia) donation or a one-time [PayPal](http://paypal.me/robotia) donation.

## Issues

**FIRST: Test if the mod has the same error in Vanilla Forge**. If it does, then Thermos is *not at fault* and we cannot help you here.

If a mod does not work with Thermos *specifically*, please check [here](https://github.com/TCPR/Fixes) before posting an issue.

**We will NOT provide support for Reikas mods under ANY circumstances.**

**If your issue meets the criteria listed above, please post your issue in the following format:**

**Mod Crash**

title: `[Crash] <Mod Name> - <First line of the exception>`

description:
`I am having a problem with <Mod Name> and Thermos. Crash log: <link>. What happens is <...>.`

**Thermos-specific Crash**

title: `[Crash] Thermos<build #> - <First line of the exception>`

description:
`I am having a problem with Thermos Build <#>. Crash log: <link>. What happens is <...>.`

**Thermos-specific Feature Proposal**

title: `[Proposal] Thermos Feature - <Feature Name>`

description:
`<What this will do>. <Why I want/need it>. <Ideas on how it might be implemented>. <Any helpful links>.`

*This fork is put together by the community.  Yive is NOT your personal server issue fixer. He does not know Java nor does he want to learn it.*

## Contributing

Please read the [guide](https://github.com/TCPR/Thermos/blob/master/CONTRIBUTING.md) on how to contribute - TCPR/Thermos always needs improvements :smile: 




## Build Requirements
* Java 8 JDK
* `JAVA_HOME` defined on your OS

## Building TCPR/Thermos
* Checkout project
  * You can use IDE or clone from console:
  `git clone https://github.com/TCPR/Thermos.git`
* Setup
  * Auto: `setup.sh`
  * Manual:
  `git submodule update --init --recursive`
* Build
  * This process downloads minecraft and apply patches
  * If you have gradle integration in IDE - you can still use gui
  * Auto: `build.sh`
  * Manual:
  `./gradlew setupCauldron jar`

All builds will be in `build/distributions`
  
## Updating sources
* Update sources
  * `git pull origin master`
* Re apply patches & build binaries
  * `./gradlew clean setupCauldron jar`

[forge]: https://img.shields.io/badge/Minecraft%20Forge-v10.13.4.1614-green.svg "Minecraft Forge v10.13.4.1614"
[mc]: https://img.shields.io/badge/Minecraft-v1.7.10-green.svg "Minecraft 1.7.10"
[java]: https://img.shields.io/badge/Java%20JDK-v1.8-blue.svg "Java JDK 8"
[spigot]: https://img.shields.io/badge/Spigot-v1.7.10--R0.1--SNAPSHOT-lightgrey.svg "Spigot R0.1 Snapshot"
