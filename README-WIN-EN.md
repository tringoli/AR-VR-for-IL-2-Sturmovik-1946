# AR/VR for IL-2 Sturmovik: 1946 on Windows
Windows 11 was the first tested OS for an experiment. It's the most preferable path for AR/VR because of it's vast list of software etc. 

It should work well also on Windows 10. Windows 8 and older versions could be too outdated.

*Linux path is described here.*

## Before we start
AR/VR implementation on Windows wouldn't cause problems with any of your important files, but feel free to back up IL-2 Sturmovik directory before next steps.

AR/VR should work with mods due to different techical implementations.

## AR adaptation for IL-2
The most suitable path for ones, who want to just try this out. Here we will introduce two possibilities: absolutely free and with a small budget.

### Budget AR
*This chapter wasn't tested by the author. You can help with an information by sending reports*

There are a lot of AR devices on any of shops/marketplaces you have available in your country. You shouldn't have problems with any of them with adaptation for IL-2. There wouldn't be a recommendation to buy list, it's on your own.

#### What do we need?
1. opentrack (GitHub) or device-specified software for AR tracking. *Prefer the first one for flexibility*

#### Set up
1. Install opentrack
2. Prepare your AR-device (as it described in your manual)
3. Open opentrack. Select ...
4. Launch IL-2. If successful, the in-game camera will follow your head.
5. Enjoy!

### Free AR
It based on head-tracking with AI output, which has been built into opentrack. You can use your smartphone *or web-camera as well.*

#### What do we need?
1. opentrack (GitHub)
2. Any app for turning our smartphone into PC camera. *You can try Camo Studio at first*
3. For low latency it's recommended to have USB-cable or stable Wi-Fi 5G

#### Set up
1. Install opentrack
2. Prepare your smartphone. His main/selected camera should record your head properly with lighting to avoid inaccuracy tracking
3. Open camera-based software both on PC and smartphone
4. Open opentrack. Select ...
5. Launch IL-2. If successful, the in-game camera will follow your head.
6. Enjoy!

## VR adaptation for IL-2
The best possible experience, but it requires financial investment for specified software. Here we will use VorpX to transform 2D into 3D VR. We will describe SteamVR and non-SteamVR paths.

*You can do a commit, if you know free possibilities. It will be appreciated*

### Tested VR headsets
1. Meta Quest, Valve Index, other major VR headsets — should work
3. Pico 4 — ✓
4. Other minor VR headsets — *maybe, send reports to expand this list*

### SteamVR
The most stable way for the majority of VR headsets here. It should work properly, if your VR headset don't have it's own translating software.

#### What do we need?
1. SteamVR
2. Software to translate PC output onto VR monitor. *It could be any programm you know, such as Virtual Desktop*
3. VorpX. *You can try for a probe this version from 4PDA*

Optional: community-driven profile for IL-2 from SAS forum

#### Set up
1. Open VorpX. You need to select configuration page. In ... select ..., depending on your VR headset. If nothing works, try the last two options
2. Download online or install community-driven profile for IL-2
3. Open translating software (usually both on PC and VR headset)
4. Open SteamVR
5. Launch IL-2. If successful, you will see VorpX picture transforming and tutorial.
6. Enjoy!

*Make sure that VorpX is working with SteamVR. If not, try other options in ...*

### Non-SteamVR
*This chapter wasn't tested by the author. You can help with an information by sending reports*

This path is to increase performance by translating IL-2 directly to VR headset.

#### What do we need?
1. Software to translate PC output onto VR monitor. *It could be any programm you know, such as Virtual Desktop*
2. VorpX. *You can try for a probe this version from 4PDA*

#### Set up
1. Open VorpX. You need to select configuration page. In ... select ..., depending on your VR headset. Exclude SteamVR here. If nothing works, try the last two options
2. Download online or install community-driven profile for Il-2
3. Open translating software (usually both on PC and VR headset)
4. Launch Il-2. If successful, you will see VorpX picture transforming and tutorial.
5. Enjoy!
