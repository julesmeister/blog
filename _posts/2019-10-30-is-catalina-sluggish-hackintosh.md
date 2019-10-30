---
date: 2019-10-30 12:32:56 +00:00
title: Is Catalina Sluggish? (Hackintosh)
categories:
- Review
tags:
- SwiftUI
- 'DWA-123 11n '
- IO80211Family.kext
- kext
- wifi
- realtek
- sluggish
- os
- mac
- catalina
- hackintosh
image: assets/images/macos-catalina-1.jpg

---
As a developer, technically, not yet, but I'm trying to become an iOS developer. I have been giving SwiftUI some thought. I want to try it because the declarative way of developing apps is trending and the canvas besides the code is tantalizing. Maybe it'll be a lot faster than using a storyboard.

Let me give you an idea about my specs:

* Dell Optiplex 9020 micro
* 2 GHz Intel Core i5
* Ram: 12 GB 1600 MHz DDR3
* Quadcore
* WiFi Dongle: DWA-123 11n Adapter

I'm running a Mojave on this Hackintosh, and I have split my partition into two to try out Catalina. I used dosdude1's patcher to install Catalina because it failed when I try to update using App Store or the connection gets interrupted when downloading. So far installation went fine. It took some time and I thought I was stuck in a loop of spinning wheel. Glad it went on after a while.

After importing all files and settings from Mojave, it said something like it can't copy Realtek driver or something. Too bad I didn't take a photo of it so I could search for whatever was happening. I just skipped it and my desktop was then shown.

To my disappointment, I couldn't get the internet to work. I tried installing the driver from [https://www.dlink.com.ph/dwa-123-d1/](https://www.dlink.com.ph/dwa-123-d1/ "DWA-123"), and I also tried installing IO80211Family.kext. All with no luck. I'm giving up at this point because somehow my audio output doesn't work anymore as well. Although Initially, right after installation, I can listen to songs with iTunes.

### What You Came Here For

No, it isn't sluggish as I've read randomly from YouTube commenters on reviews regarding Mac OS Catalina. Or maybe it is, but it was negligible. I tried using Xcode 11.1 to test if it were to slow down. It didn't really slow down. I can still use it with ease the way it is in Mojave.