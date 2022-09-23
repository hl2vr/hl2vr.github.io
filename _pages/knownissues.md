---
permalink: /knownissues/
title: "Known Issues (and some solutions)"
---

### Hi all,

We are aware of several different bugs (or non-bug *reasons*) some users are having trouble installing the game via Steam, or the game not launching once installed, or other game-breaking issues. If you are one of those users, please see the following list for the current status and/or any recommendations.

### **Not all of these issues have solutions or workarounds yet.**  
We will keep this updated as we learn more.

### This is intentionally an incomplete list.  
It's being updated over time, and only covers the biggest *game-breaking* issues we've come across.
It does not include smaller bugs or feedback on the game. (Please see [the Help page](help/#reporting-bugs) and bug tracker for those!)

<br />

| Table of Contents  |
| ------------- |
| [Step 1](#step-1-for-every-issue)  |
| [Downloading or Installing issues](#downloading--installing-issues  )  |
| [Launching or crash issues](#crashes-or-other-game-breaking-issues)  |
| [Ingame issues](#ingame-issues)   |

<br />

---

# Step 1 for every issue

---

I know nobody likes to hear *just turn it off and on again*, but you're going to turn it off and on again and you're going to like it!

Please try the basics, listed below, before anything else. We've seen these solve problems for half the users who report issues.

- Update Windows, Steam, and SteamVR to the latest versions.  
- Update your graphics drivers.  
  Don't skip this step! I know you're thinking *I'm just gonna skip this step because I know all about my updates already*, but that would be a mistake!  
  For NVIDIA users in particular, try the [517.22 Vulkan Beta drivers](https://developer.nvidia.com/vulkan-beta-51722-windows).
- Close Steam and SteamVR, and reboot your device.

<br />

---

# Downloading / Installing issues

---

### Unable to claim or download the game in the Steam Store

This is often caused by the user not owning the standard Half-Life 2 on Steam. Having access to HL2 via Steam Family Sharing is not enough -- your account needs to own HL2.

We've also seen cases where it takes a bit of time after purchasing Half-Life 2 for Steam to notice that you should now be allowed to grab HL2VR. So if you've *just now* bought it, please give it a bit of time and try again later.

<br />

---

# Crashes or other game-breaking issues

---

### Game does not start, crashes immediately or hangs

Known issue that probably has a number of different causes. We have not found a definitive fix, yet, but there are a number of things you can try that have helped some of those affected:

- Update your graphics driver. For NVIDIA users in particular, try the [517.22 Vulkan Beta drivers](https://developer.nvidia.com/vulkan-beta-51722-windows).
- Try different versions of SteamVR by either switching to the stable branch or to the beta branch.
- If you are using a laptop, see if your laptop has an option to disable the integrated GPU, either via the laptop manufacturer's control software or in the BIOS. If no such option exists, try forcing both HL2VR and SteamVR to use the dedicated GPU.  
  For instructions, [see here](https://www.windowsdigitals.com/force-chrome-firefox-game-to-use-nvidia-gpu-integrated-graphics/).
- If you are using a laptop with an AMD Ryzen processor, a very particular fix that has helped a number of people is to go to the Windows Device Manager, then disable and re-enable the integrated Radeon graphics.

### Game launches on the desktop, but doesn't display in the VR headset

###### Update your graphics drivers

This is known to have fixed the issue for people in the past. (See the Nvidia drivers linked above, as well.)

###### Bad launch parameters
If you were trying to launch the game with *-dev* or *-console* parameters, then this behaviour is actually normal. The menu will not load in the headset, and you will have to load a save game or start a new game before you will actually see something in the headset.

For that reason, we recommend not using these launch parameters. The console can actually be opened via a button from the options menu, and if you need cheat access, you may find the launch parameter *-vrdev* more convenient. It will add a "Developer" panel to the Options menu.


### Error: "Engine Error - Failed to initialize OpenVR", or "Could not load library client"

This is typically caused by SteamVR not being installed or not running. Please install it via Steam: [SteamVR](https://store.steampowered.com/app/250820/SteamVR/) and start it before launching HL2VR.


### Game gets stuck in an infinite menu loop where you can't close the menu

In most instances, this is caused by using the OculusKiller app for Oculus devices. You can either disable Oculus Killer, or you can try launching the new *hl2vr.exe* directly from the game folder.


### Getting error: "Setup file 'gameinfo.txt' doesn't exist in subdirectory 'hl2'."

Somehow your Windows install has been modified so the default action for Batch files is Edit instead of Open. For now, simply open the hlvr.bat file *(in the [your Steam directory]/Half-Life 2 VR/ folder)* with right-click and selecting Open.

You may also try launching directly using the new *hl2vr.exe* directly from the game folder.

### ...Some other issue!

We'll be adding more info over time.

<br />

---

# In-game issues

---

### I am falling half-way into the ground / I am a dwarf?

Chances are you accidentally toggled Crouch. This is bound to your main hand's joystick "down" direction. Simply pull the joystick down again to un-crouch.


### I cannot get out of the water!

Make sure you're holding forward and jump towards a nearby ledge, and if it's low enough you'll likely hop your way out of the water within a couple seconds.

Alternatively, you may have accidentally crouched, which prevents you from properly jumping out of the water. Try to uncrouch using your main hand's joystick "down" to toggle it.