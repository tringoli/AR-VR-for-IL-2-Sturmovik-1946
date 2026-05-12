# AR/VR for IL-2 Sturmovik: 1946 on Linux
> **:warning: This section has been largely untested by the author and is more of a theoretical usage guide. You can help by submitting reports**

Due to the decentralized nature of Linux distributions, it is virtually impossible to guarantee full compatibility with VR devices. In this regard, Windows is the most practical option. On the other hand, AR doesn't present any particular challenges for setup.

## Before You Begin
Implementing AR/VR on Linux won't cause any issues with your important files, but feel free to backup your IL-2 Sturmovik directory before proceeding.

AR/VR should work with mods thanks to various technical solutions.

## Adapting AR for IL-2
This is the most suitable route for those who just want to try it out. Here we present two options: a completely free one and one for a small budget.

### Budget AR

There are many AR devices available in stores/marketplaces in your country. **Please note:** IL-2 may have issues adapting due to a lack of software and/or device compatibility. A list of recommended devices for purchase is not provided; the choice is yours.

#### What do we need?

1. OpenTrack ([GitHub](https://github.com/opentrack/opentrack)) or specialized AR tracking software. *The first option is preferred for greater flexibility*

#### Setup
1. Prepare your AR device (as described in the product manual)
2. Open OpenTrack. Select…
3. Launch IL-2. If successful, the in-game camera will follow your head

4. Enjoy!

### Free AR
The most affordable option on Linux. It is based on head tracking using the AI ​​built into OpenTrack. You can use your smartphone *or webcam*.

#### What do we need?

1. OpenTrack ([GitHub](https://github.com/opentrack/opentrack))
2. Any app for turning your smartphone into a PC camera. *We'll describe the VDO.Ninja method here, as it's surprisingly the easiest to set up.*
3. OBS Browser (**browser support required** for VDO.Ninja)
4. For low latency, we recommend using a USB cable or stable 5G Wi-Fi.

#### Setup
1. Prepare your smartphone. Its primary/selected camera should accurately record your head, taking into account lighting, to avoid tracking inaccuracies
2. Open the camera software on both your PC and smartphone
   * Open VDO.Ninja on your smartphone. Start a room and create a link for OBS
   * Create a scene in OBS, select the "Browser" option. Paste the link into the scene settings
   * Specify the correct camera stream resolution *(You can also find this in VDO.Ninja)*
3. Open OpenTrack. Select your camera in the input settings
4. Launch IL-2. If successful, the in-game camera will follow your head

5. Enjoy!

## VR adaptation for IL-2
The best possible experience, but it appears that **there is no equivalent to VorpX yet, making full-fledged virtual reality impossible.**

A workaround is possible by linking the window to the player's view. In theory, this could be achieved through a combination of SteamVR and OpenTrack (for converting VR to AR this way. OpenTrack has SteamVR in its input settings).

In any case, for flat full-screen mode, there is a fork between ALVR and WiVRn.

### Tested VR headsets
* Meta Quest, Valve Index, and other major VR headsets — should work
* Pico 4 — only ALVR works, WiVRn doesn't display an image (but has sound)
* Other less popular VR headsets — possible

### ALVR
The most stable method for most VR headsets. It should work correctly if your VR headset doesn't have its own conversion software.

#### What do we need?

1. [SteamVR](https://store.steampowered.com/app/250820/SteamVR/)
2. ALVR ([GitHub](https://github.com/alvr-org/ALVR))

#### Setup
1. Open ALVR (both on your PC and your VR headset) and go through the setup
2. Open SteamVR
3. Launch IL-2. If successful, you'll get an image

4. Enjoy!

### WiVRn

This path is designed to improve performance by directly streaming IL-2 to your VR headset.

#### What do we need?

1. WiVRn ([GitHub](https://github.com/WiVRn/WiVRn))

#### Setup
1. Open WiVRn (both on your PC and your VR headset) and go through the setup
2. Launch IL-2. If successful, you'll get an image

3. Enjoy!
