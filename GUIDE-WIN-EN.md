# AR/VR for IL-2 Sturmovik: 1946 on Windows
Windows 11 was the first OS tested for the experiment. This is the preferred path for AR/VR due to its extensive list of supported software, etc.

It should also work well on Windows 10. Windows 8 and older versions may be too outdated.

## Before We Begin
Implementing AR/VR on Windows will not cause any issues with your important files, but feel free to back up your IL-2 Sturmovik directory before proceeding further.

AR/VR should work with mods thanks to various technical solutions.

## Adapting AR for IL-2
The most suitable path for those just wanting to try it out. Here we present two options: completely free and low-budget.

### Budget AR
> *This chapter has not been tested by the author. You can help by submitting reports.*

There are many AR devices available in stores and marketplaces in your country. You shouldn't have any trouble adapting the IL-2 to any of them. There are no recommendations for which one to choose; it's up to you.

#### What do we need?
1. OpenTrack ([GitHub](https://github.com/opentrack/opentrack)) or specialized AR object tracking software. *The first option is preferred for greater flexibility*

#### Setup
1. Prepare your AR device (as described in the product manual)
2. Open OpenTrack. Select a convenient data source (PointTracker usually works)
3. Launch IL-2. If successful, the in-game camera will follow your head

4. Enjoy!

### Free AR
It's based on head tracking using the AI ​​built into OpenTrack. You can use your smartphone *or webcam*.

#### What do we need?
1. Opentrack ([GitHub](https://github.com/opentrack/opentrack))
2. Any app for turning your smartphone into a PC camera. *You can try Camo Studio to get started*
3. For low latency, we recommend using a USB cable or stable 5G Wi-Fi

#### Setup
1. Prepare your smartphone. Its primary/selected camera should correctly record your head, taking into account lighting, to avoid tracking inaccuracies
2. Open the camera software on both your PC and smartphone
3. Open OpenTrack. Select NeuralNet as the output interface. Go to the output settings, select the camera, and calibrate
4. Launch IL-2. If successful, the in-game camera will follow your head

5. Enjoy!

## VR Adaptation for IL-2
To achieve the best image quality, you need to invest in specialized software. Here we'll use VorpX to convert 2D to 3D VR. We'll describe how to work with and without SteamVR.

> *You can commit if you know of any unused features. It would be greatly appreciated.*

### Tested VR Headsets
* Meta Quest, Valve Index, and other major VR headsets — should work
* Pico 4 — ✓
* Other less popular VR headsets — *please submit reports to expand this list*

### SteamVR
The most stable method for most VR headsets. It should work correctly if your VR headset doesn't have its own conversion software.

#### What do we need?
1. [SteamVR](https://store.steampowered.com/app/250820/SteamVR/)
2. Software for converting output from a PC to a VR monitor. *This can be any program you're familiar with, such as Virtual Desktop*
3. VorpX. *You can try testing it with [4PDA](https://4pda.to/stat/go?u=https%3A%2F%2Fdisk.yandex.ru%2Fd%2F6iYhJOBe3ZtYAg&e=110018648&f=https%3A%2F%2F4pda.to%2Fforum%2Findex.php%3Fshowtopic%3D1034301%26st%3D5260%23entry118062338)*

Additionally: IL-2 profile created by the community on the [IL-2 forum](https://forum.il2sturmovik.com/topic/69192-for-rift-s-il2_1946_bat-v385_vorpx_opentrack_logitech-x52_settings_v01/)

#### Setup
1. Open VorpX. Select the configuration page ("vorpX Config"). Under "General," select "SteamVR (Index, Vive, Pimax)"
2. Under "Cloud/Local Profiles," download or install the community-created IL-2 profile online
3. Open the translation program (usually on both the PC and the VR headset)
4. Open SteamVR
5. Launch IL-2. If successful, you'll see the VorpX image conversion and a tutorial

6. Enjoy!

*Make sure VorpX works with SteamVR. If not, try a different "Device Selection" in "General"*

### Without SteamVR
> *This chapter has not been tested by the author. You can help by submitting reports.*

This path is designed to improve performance by directly translating IL-2 to the VR headset.

#### What do we need?
1. A program for translating the output from the PC to the VR monitor. *This can be any program you know, such as Virtual Desktop*
2. VorpX. *You can try testing it with [4PDA](https://4pda.to/stat/go?u=https%3A%2F%2Fdisk.yandex.ru%2Fd%2F6iYhJOBe3ZtYAg&e=110018648&f=https%3A%2F%2F4pda.to%2Fforum%2Findex.php%3Fshowtopic%3D1034301%26st%3D5260%23entry118062338)*

Additionally: IL-2 profile created by the community on the [IL-2 forum](https://forum.il2sturmovik.com/topic/69192-for-rift-s-il2_1946_bat-v385_vorpx_opentrack_logitech-x52_settings_v01/)

#### Setup
1. Open VorpX. Select the configuration page ("vorpX Config"). In the "General" section, select the appropriate option in "Device Selection" depending on your VR headset. Exclude SteamVR. If nothing works, try the last two options
2. In the "Cloud/Local Profiles" section, download or install a community-created profile for IL-2
3. Open the broadcasting program (usually on both your PC and your VR headset)
4. Launch IL-2. If successful, you will see VorpX image conversion and a tutorial

5. Enjoy!

*Make sure VorpX is running in the background. If not, try a different "Device Selection" in "General"*
